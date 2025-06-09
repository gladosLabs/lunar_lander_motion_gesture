# Hand Gesture Controlled LunarLander

This project allows you to control the OpenAI Gym **LunarLander-v2** environment using hand gestures detected from your webcam with **MediaPipe Hands** and **OpenCV**.

## Features

- Real-time hand gesture recognition via webcam
- Control LunarLander actions using intuitive finger gestures
- Slowed down gameplay for better control and longer episodes
- Visual feedback of hand landmarks and current action on the webcam feed
- Win/loss notification at the end of the game

## Gesture Controls

| Gesture                      | Action             | Description                 |
|-----------------------------|--------------------|-----------------------------|
| Index + Middle finger up     | Main engine (Action 2) | Fire main engine            |
| Index finger up only         | Left engine (Action 1) | Fire left engine            |
| Thumb up only                | Right engine (Action 3) | Fire right engine           |
| Any other gesture            | Do nothing (Action 0) | No engine fired             |

## Requirements

- Python 3.11+
- OpenCV (`opencv-python`)
- MediaPipe (`mediapipe`)
- Gym (`gym` with Box2D support)
- NumPy (`numpy`)
