# Python Asteroids Game

A classic Asteroids arcade game implementation using Python and Pygame.


## Features

- Player-controlled ship with rotation and thrust mechanics
- Randomly spawning asteroids that split when hit
- Simple vector-based physics
- Collision detection
- Minimalist white-on-black graphics, like the original arcade game

## Project Structure

- `main.py` - Game initialisation and main loop
- `circleshape.py` - Base class for circular game objects
- `player.py` - Player ship implementation
- `asteroids.py` - Asteroid implementation
- `asteroidField.py` - Asteroid spawning system
- `shot.py` - Projectile implementation
- `constants.py` - Game parameters and configuration

## Requirements

- Python 3.7+
- Pygame 2.0+

## Installation

1. Ensure you have Python installed
2. Install Pygame:
   ```
   pip install pygame
   ```
3. Clone or download this repository
4. Run the game:
   ```
   python main.py
   ```

## Controls

- **W**: Move forward
- **S**: Move backward
- **A**: Rotate left
- **D**: Rotate right
- **Spacebar**: Fire projectiles

## Game Design

This game demonstrates several key programming concepts:

- **Object-Oriented Programming**: Using classes to encapsulate game object behavior
- **Inheritance**: Base functionality shared through a common parent class
- **Game Loop Pattern**: Consistent update, draw, and input handling
- **Delta Time**: Frame-rate independent movement
- **Vector Mathematics**: For movement and collision detection

## Customisation

You can modify game parameters by editing `constants.py`:
- Screen dimensions
- Asteroid sizes and spawn rates
- Player movement and shooting speed

## Future Enhancements

Potential features to add:
- Score system
- Sound effects
- Visual effects (explosions, thruster particles)
- Multiple lives
- Game over screen
- High score tracking

## License

This project is open source and available for educational purposes.

## Acknowledgements

Inspired by the classic Atari Asteroids arcade game from 1979.
