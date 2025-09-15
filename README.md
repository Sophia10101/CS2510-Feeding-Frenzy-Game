An interactive fish game built with javalib (funworld and worldimages) and the tester framework: move your fish with the arrow keys, 
eat smaller fish to grow, avoid larger ones, and survive until you’re the biggest. The world updates on ticks, spawns fish over time, 
ends with a winning message when you outgrow every fish or "Game Over" if you’re eaten by a larger fish. 

## Requirements
- Java 8+ (JDK)
- JARs in `lib/`: `javalib.jar` (or funworld+worldimages jars) and `tester.jar`

## How to Run 
1. Import the project (File → Import → Existing Projects into Workspace).
2. Add libraries: Right-click project → Build Path → Configure Build Path → Add JARs → add `lib/javalib.jar` and `lib/tester.jar`.
3. Run via tester:
   - Run → Run Configurations → Java Application → New
   - Project: your project name
   - Main class:
     tester.Main
   - arguments:
     ExamplesMyWorldProgram
   - Run and use arrow key to move your fish left right up or down
