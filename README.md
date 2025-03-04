# Robotron P5.js Recreation

A recreation of the classic arcade game Robotron: 2084 using p5.js. This project was created with the assistance of Claude 3.7 Sonnet, an AI assistant by Anthropic.

![Robotron Screenshot](screenshot.png)

## About

This project is a web-based implementation of the classic 1982 arcade game Robotron: 2084, originally developed by Williams Electronics. The game has been recreated using p5.js, a JavaScript library for creative coding.

## Initial Prompt

This project was generated based on the following prompt to Claude:

```
In p5js create the classic arcade game Robotron as closely as possible. I've attached a screenshot for reference. Please try to recreate the artwork as closely as possible. Use WASD for shooting and arrow keys for movement.
```

## How to Run

1. Clone this repository
2. Open `index.html` in any modern web browser
3. Press SPACE to start the game

No server or additional installation required! The game runs entirely in your browser.

## Controls

- **Arrow Keys**: Move your character
- **WASD Keys**: Shoot in corresponding directions
  - W: Shoot up
  - A: Shoot left
  - S: Shoot down
  - D: Shoot right
  - (Diagonal shooting is supported by pressing two keys simultaneously)
- **SPACE**: Start game
- **R**: Restart after game over

## Gameplay

- You control the last human survivor against an army of robots
- Rescue the human family members for bonus points (blue figures)
- Different types of enemies have different behaviors:
  - Grunts (red): Basic enemies that chase the player
  - Hulks (cyan): Tank-like enemies that take multiple hits to destroy
  - Brains (magenta): Chase and convert humans to enemies
  - Enforcers (orange): Move in patterns
  - Tanks (white): Slow but persistent

## Features

- Classic arcade-style grid background
- Multiple enemy types with different behaviors
- Progressive difficulty with increasing levels
- Score tracking and lives system
- Retro-style graphics

## License

This project is available under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- Original game created by Eugene Jarvis and Larry DeMar for Williams Electronics
- Recreation assistance by Claude 3.7 Sonnet, an AI assistant by Anthropic
- Uses the p5.js library for rendering and game logic
