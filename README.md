# OOP-Snake-Game-Using-SFML-Libraray
Snake Game in C++ using SFML Library

This project is a Snake Game built using C++ and the [SFML](https://www.sfml-dev.org/) (Simple and Fast Multimedia Library). 
It was developed as an Object-Oriented Programming (OOP) course project and demonstrates key OOP concepts like encapsulation, inheritance, and modular programming.

## 🎮 Features

- Classic Snake gameplay
- Object-Oriented design using classes like `Game`, `SnakeGame`, `GameBoy`, and `Player`
- Sound effects and background music
- Textures and custom fonts
- Save/load high scores
- Profiles management system
- Smooth gameplay experience using SFML


## 📁 Project Structure
├── main.cpp # Entry point
├── SnakeGame.cpp/.h # Core game mechanics
├── GameBoy.cpp/.h # Handles UI & controls
├── Game.cpp/.h # Game loop and logic
├── player.h # Player profile and data
├── *.o # Object files
├── *.png / *.wav / *.ogg # Assets (images, sounds)
├── *.ttf / *.otf # Fonts
├── highscore.txt # Stores high score
├── profiles.txt # Stores user profiles
├── sfml_test.cpp # SFML integration testing
└── snake / sfml_test / SnakeGameApp # Executables

## 🛠️ Requirements
- C++17 or later
- SFML Library (Graphics, Audio, Window, System modules)
