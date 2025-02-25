Minesweeper Game in C++

Overview

This is a simple console-based Minesweeper game implemented in C++. The game generates an 8x8 board with 10 randomly placed mines. The player can reveal cells, and the goal is to uncover all non-mine cells without hitting a mine.

Features

Randomly generated minefield.

Automatic counting of adjacent mines.

Recursive reveal of empty spaces.

Win condition detection.

How to Play

Run the program.

Enter row and column indices (0-based) to reveal a cell.

If you hit a mine, the game is over.

If all non-mine cells are revealed, you win!

Compilation & Execution

To compile and run the program, use:

 g++ -o minesweeper minesweeper.cpp
 ./minesweeper

Requirements

C++ Compiler (GCC, Clang, or MSVC)

Compatible with Windows, macOS, and Linux

Future Improvements

Add a flagging system to mark potential mines.

Implement a graphical user interface (GUI).

Expand board size and difficulty levels.

Enjoy the game! 🚀

