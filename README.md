# Asteroids Game

A classic arcade-style Asteroids game implemented in Python using Pygame. This project was developed as part of the [Boot.dev](https://boot.dev) Backend Development Course.

## Description

This is a modern take on the classic Asteroids arcade game where players control a spaceship and must avoid or destroy incoming asteroids. The game features:

- Smooth spaceship controls with rotation and thrust
- Colorful asteroids that split when shot
- Random asteroid spawning from screen edges
- Particle effects for shots
- Sound effects for shooting

## Prerequisites

- Python 3.x
- Pygame 2.6.1

## Installation

1. Clone this repository:
```bash
git clone https://github.com/IslamEssam01/asteroids.git
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## How to Play

Run the game using:
```bash
python main.py
```

### Controls

- `W` - Move forward
- `S` - Move backward
- `A` - Rotate left
- `D` - Rotate right
- `SPACE` - Shoot

### Game Rules

- Destroy asteroids by shooting them
- Large asteroids split into smaller ones when hit
- Avoid colliding with asteroids
- Game ends if your ship collides with an asteroid

## Project Structure

- `main.py` - Game entry point and main loop
- `player.py` - Player ship implementation
- `asteroid.py` - Asteroid object implementation
- `asteroidField.py` - Asteroid spawning and management
- `shot.py` - Player projectile implementation
- `circleshape.py` - Base class for circular game objects
- `constants.py` - Game constants and configuration

## Technical Details

The game is built using object-oriented programming principles and uses Pygame's sprite system for game object management. The physics system uses simple vector-based movement and collision detection.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
