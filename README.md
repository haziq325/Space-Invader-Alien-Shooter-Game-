# Space Invaders Clone - SFML C++ Game

![Game Screenshot](assets/screenshots/gameplay.png) <!-- Add a screenshot if available -->

A modern C++ implementation of the classic Space Invaders arcade game using the SFML library, featuring advanced OOP architecture, state management, and particle effects.

## Key Features

- **Object-Oriented Design**: Clean architecture with proper separation of concerns
- **State Management**: Menu, gameplay, and transition states
- **Advanced Gameplay**:
  - Progressive difficulty system (3 levels)
  - Boss battles with multiple phases
  - Health power-ups and special abilities
- **Visual Effects**:
  - Sprite animations
  - Screen shake on explosions
  - Particle systems
- **Audio System**: Background music and sound effects
- **Persistence**: High score saving/loading

## Technology Stack

- **Language**: C++17
- **Libraries**:
  - SFML 2.5.1 (Graphics, Audio, Window)
- **Tools**:
  - CMake (build system)
  - Git (version control)

## Installation

### Prerequisites
- SFML library installed
- C++17 compatible compiler
- CMake 3.12+

### Build Instructions
```bash
git clone https://github.com/yourusername/space-invaders-sfml.git
cd space-invaders-sfml
mkdir build && cd build
cmake ..
make
./SpaceInvaders
