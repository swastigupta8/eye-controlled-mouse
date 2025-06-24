# Eye Controlled Mouse using Python, MediaPipe, and OpenCV

This is a fun and simple Python project that lets you control your mouse cursor using your **eye movements**. It uses your webcam, detects facial landmarks with **MediaPipe**, and moves your mouse in real-time with **OpenCV** and **PyAutoGUI**.

> This project is meant to be a casual experiment — a small but powerful reminder of what a few Python packages and some curiosity can do.

## Features

- Moves the mouse cursor using your eyes (based on iris tracking)
- Clicks automatically when you blink (detected using eye landmark distances)

## Requirements

- Python 3.10
- `opencv-python`
- `mediapipe`
- `pyautogui`

Install the dependencies:

```bash
pip install opencv-python mediapipe pyautogui

Note: MediaPipe supports Python 3.7 to 3.10. This won’t work on Python 3.11+ or 3.13
