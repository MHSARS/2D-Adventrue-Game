## 2D Adventure Game


A classic top-down 2D adventure game built in Java, featuring tile-based movement, object interaction, and retro-style graphics.

## 🎮 Features
- Tile-based world exploration
- Player movement with collision detection
- Collectable items (keys, boots)
- Interactive objects (doors, chests)
- Background music and sound effects
- Real-time UI displaying inventory and game time
- Debug mode for development

## 🔧 Prerequisites
- Java JDK 17 or higher
- Eclipse IDE (recommended) or any Java IDE

## 🚀 Installation
1. Clone the repository
   git clone https://github.com/yourusername/2d-adventure-game.git
2. Open the project in Eclipse:
   - File -> Import -> Existing Projects into Workspace
   - Select the cloned repository folder
   - Click Finish
3. Run src/main/Main.java

## 🎯 How to Play
- Use WASD keys to move the player
- Collect keys to open doors
- Find boots to increase movement speed
- Reach the treasure chest to win
- Press T to toggle debug mode

## 🗺️ Map Creation
Maps are stored in the res/maps directory as text files. Each number represents a different tile:
0: Grass
1: Wall
2: Water
3: Earth
4: Tree
5: Sand


## 📁 Project Structure

```
src/
├── main/           # Core game systems
├── entity/         # Player and entity classes
├── object/         # Game objects (items, etc.)
├── tile/           # Tile system and map management
└── res/
    ├── player/     # Player sprites
    ├── tiles/      # Tile images
    ├── objects/    # Object sprites
    ├── maps/       # Map files
    └── sound/      # Music and sound effects
```

## 🛠️ Built With
- Java
- AWT/Swing for graphics
- Java Sound API for audio
