# Machine Vision Pong Game

Welcome to the Machine Vision Pong Game project! This repository contains a Python implementation of the classic Pong game, enhanced with machine vision technology. The game detects the player's hands using a webcam, and each hand controls a paddle to bounce the ball.

## Features

- **Machine Vision**: Utilizes computer vision to detect and track the player's hands.
- **Hand-Controlled Paddles**: Each hand controls a paddle, providing an immersive and interactive gaming experience.
- **Classic Pong Gameplay**: Retains the fun and simplicity of the classic Pong game.

## Getting Started

To get started with this project, follow the steps below:

### Prerequisites

- Python 3.x
- OpenCV
- Pygame
- Mediapipe

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mali-98/Pong-Game.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd machine-vision-pong
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Game

1. **Start the Game**:
   ```bash
   python main.py
   ```

2. **Play the Game**:
   - Ensure your webcam is connected and properly set up.
   - The game will detect your hands and map each hand to a paddle on the screen.
   - Move your hands to control the paddles and bounce the ball.

## Project Structure

- `pong_game.py`: Main script to run the Pong game with machine vision.
- `vision/`: Contains the machine vision logic and hand detection code.
- `requirements.txt`: List of dependencies for the project.

## How It Works

1. **Hand Detection**: The game uses Mediapipe and OpenCV to detect and track the player's hands through the webcam feed.
2. **Paddle Control**: The position of each detected hand is mapped to the corresponding paddle on the screen.
3. **Game Mechanics**: The game follows the classic Pong mechanics, with the ball bouncing off the paddles and walls.

## Contributing

We welcome contributions to enhance this project. Feel free to open issues or submit pull requests with improvements, bug fixes, or new features.
Feel free to customize the content to better fit your project's specifics and your preferences.
