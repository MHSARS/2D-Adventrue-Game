2D Adventure Game

This is a 2D adventure game developed using Java. The game features a tile-based world, various interactive objects, a user interface, and sound effects. 
The game is designed to run smoothly at 60 FPS and provides an engaging experience through dynamic interactions and an intuitive interface.

Features:
- Tile-Based World: A dynamic game world with different tile types (grass, wall, water, etc.) and collision detection.
- Entity Management: Interactable objects (e.g., keys, doors, chests) with specific properties and behaviors.
- User Interface: Displays essential game information, including collected items, game time, and messages.
- Sound Integration: Background music and sound effects enhance the gaming experience.
- Collision Detection: Accurate collision handling between the player, objects, and tiles.

Directory Structure:
- src/main: Contains the main game classes including GamePanel, Main, and Sound.
- src/object: Contains classes for different game objects (e.g., OBJ_Key, OBJ_Door).
- src/tile: Contains tile-related classes (Tile, TileManager).
- resources/sound: Directory for sound files.
- resources/tiles: Directory for tile images.
- resources/objects: Directory for object images.
- maps: Directory for map files (e.g., world01.txt).
  
Code Overview:
- GamePanel: Manages the game’s main rendering and update loop. Handles user input and game state updates.
- KeyHandler: Processes keyboard input for player movement and debugging features.
- UI: Manages the user interface, including displaying game information and messages.
- Sound: Handles background music and sound effects.
- SuperObject and Derived Classes: Define various interactive objects in the game.
- TileManager: Loads and renders tiles, handles tile collisions and map loading.
- Skills and Technologies
- Java: Core programming language used for development.
- Java Swing and AWT: Libraries used for graphics and user interface.
- BufferedReader: For loading map data.
- ImageIO: For loading and processing images.
