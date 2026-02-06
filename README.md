
## Overview

This repository contains a Python application that leverages the `Mediapipe`, `open-cv`, and `pyautogui` libraries to enable gesture-based control for running games. The application showcases the integration of pose detection to control character movements in games using hand and body gestures.


## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Dependencies](#dependencies)

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/AKILSADIK/Running-Games-Using-openCV.git
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:

    ```bash
    python playing_subway_surfers_game_using_pose_detection.py
    ```

## Running the Game

Follow the steps below to run the game:

1. Run the provided Python script by executing the code.
2. Press the 'ESC' key three times to initialize the pose detection.
3. Open the game links in separate tabs:

   - Subway Surfers game link: [Subway Surfers](https://subway-surfers.me/)
   - Temple Run game link: [Temple Run 2](https://poki.com/en/g/temple-run-2)

4. After opening the game links, run the Python script again (4th time).
5. The controls of the game should now work fine.

Please note that this setup requires your webcam to be functional and properly positioned. Additionally, ensure that you have the required libraries (`cv2`, `pyautogui`, `mediapipe`, and `matplotlib`) installed in your Python environment.

## Usage

- Start the application and position yourself in front of the camera.
- Use specific hand and body gestures to control character movements in supported games.
- Follow on-screen instructions to start and interact with the game.

## Features

- Real-time pose detection using `Mediapipe` for accurate tracking of hand and body movements.
- Gesture-based control for popular games using `pyautogui`.
- Dynamic adjustment of game control based on user gestures.

## Dependencies

- [Mediapipe](https://github.com/google/mediapipe)
- [OpenCV](https://github.com/opencv/opencv)
- [pyautogui](https://github.com/asweigart/pyautogui)

Install these dependencies using the provided `requirements.txt` file.

