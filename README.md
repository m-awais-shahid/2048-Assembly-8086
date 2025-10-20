# 2048 Game in Assembly 8086

A classic 2048 puzzle game implemented in Assembly 8086 language using Irvine32 library.

## 🎮 Game Overview

This project is a complete implementation of the popular 2048 game written in Assembly 8086. The game features a 4x4 grid where players combine numbered tiles to reach the 2048 tile and win the game.

## 🚀 Features

- **Interactive Gameplay**: Use keyboard controls to move tiles
- **Colorful Display**: Different colored tiles for different numbers
- **Score Tracking**: Real-time score display
- **Win/Lose Conditions**: Game ends when you reach 2048 or run out of moves
- **Random Tile Generation**: New tiles (2 or 4) appear after each move

## 🎯 How to Play

### Controls
- **W** - Move tiles up
- **A** - Move tiles left  
- **S** - Move tiles down
- **D** - Move tiles right

### Objective
- Combine tiles with the same number to create higher numbers
- Reach the **2048** tile to win the game
- The game ends when the board is full and no more moves are possible

## 🛠️ Technical Details

### Requirements
- MASM (Microsoft Macro Assembler)
- Irvine32 library
- Windows environment

### File Structure
```
2048-Assembly-8086/
├── F190193-Awais-Project-Final.txt    # Main Assembly source code
└── README.md                          # This file
```

### Key Components

#### Game Board
- 4x4 grid represented as a 16-element array
- Each cell can contain values: 0, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024, 2048

#### Main Procedures
- `drawBoard` - Renders the game board with colored tiles
- `userInput` - Handles keyboard input for movement
- `inputW/inputA/inputS/inputD` - Movement logic for each direction
- `genRandom` - Generates random tiles (2 or 4) in empty spaces
- `windcondition` - Checks for win condition (2048 tile)
- `loseCondition` - Checks for game over condition
- `dispScore` - Displays current score

#### Visual Features
- Color-coded tiles based on their values
- Game title and control instructions
- Score display
- Border around the game board

## 🎨 Color Scheme

The game uses different colors for different tile values:
- **Empty tiles**: Magenta background
- **2**: Red background
- **4**: Blue background  
- **8**: Cyan background
- **16**: Green background
- **32**: Brown background
- **64**: Yellow background
- **Higher values**: Light cyan background

## 🏃‍♂️ How to Run

1. Ensure you have MASM and Irvine32 library installed
2. Compile the source file `F190193-Awais-Project-Final.txt`
3. Run the executable
4. Use W, A, S, D keys to play the game

## 📝 Code Structure

The Assembly code is organized into several key procedures:

- **Initialization**: Sets up the game board and display
- **Game Loop**: Main loop that handles input, updates board, and checks conditions
- **Movement Logic**: Complex algorithms for sliding and merging tiles
- **Display Functions**: Handles all visual output and formatting

## 🎓 Educational Value

This project demonstrates:
- Assembly language programming concepts
- Array manipulation and memory management
- Input/output operations
- Game logic implementation
- User interface design in console applications

## 👨‍💻 Author

**Awais Shahid** (F190193)
- Student ID: F190193
- Project: 2048 Game Implementation in Assembly 8086

## 📄 License

This project is created for educational purposes as part of an academic assignment.

---

*Enjoy playing 2048 in Assembly! 🎮*
