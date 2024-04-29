# Circus Game

Welcome to the Circus Game, a single-player game where you control a clown trying to catch falling objects and create combinations to score points!

## Description

In this game, each clown is equipped with two stacks of plates and faces a variety of falling objects. The goal is to catch three consecutive plates of the same color to make them vanish and increase your score. Be careful not to drop too many objects or it's game over!

## Features

- Catch falling objects to create color combinations and earn points.
- Support for different shapes beyond plates, including dynamic loading of shapes at the start of the game.
- Multiple types of falling objects, such as plates, bombs, and more.
- Dynamically load shapes from a specific folder or path chosen by the user.
- Earn points for collecting three consecutive shapes of the same color, regardless of their type.

## Design Patterns Used

This project demonstrates the application of several design patterns:

- **Singleton**: Used for managing game resources or components.
- **Factory or Pool**: Implemented to create and manage instances of falling objects.
- **Observer**: Used to track and update game state based on player actions.
- **Strategy**: Implemented for defining different levels of difficulty with varying game criteria.
- **Iterator**: Used for iterating over game objects or collections.

## Difficulty Levels

The game supports three levels of difficulty, each with unique challenges:

- **Easy**: Slower speed, fewer falling objects, and simpler combinations.
- **Medium**: Moderate speed and complexity with additional features.
- **Hard**: Faster speed, more falling objects, and challenging combinations.

## Game Engine Integration

This game utilizes a custom game engine supporting three types of game objects:

- **Movable**: Objects that can move and interact within the game environment.
- **Constant**: Static objects that provide the game's backdrop and environment.
- **User-controlled**: Objects that respond to player input, such as the clown.

## Interfaces

Two interfaces define interactions with the game engine:

1. **World**: Represents a level of the game containing various objects and challenges.
2. **GameObject**: Represents any object within the game, including shapes, clowns, etc.

## Getting Started

To play the Circus Game:

1. Download and install the game on your local machine.
2. Launch the game executable.
3. Select the desired difficulty level and start playing!

## Contributing

Contributions to the game project are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Implement new features or improvements.
3. Submit a pull request for review and integration.


