# -Face-Recognition


# Face Recognition with OpenCV and Python

## Overview
This project implements a face recognition system using OpenCV and Python. The system detects faces in real-time using a webcam, compares the detected faces with a database of stored images, and displays the name of the recognized person on the screen.

## Features
- **Face Database Creation**: Add photos of individuals to a designated folder, each labeled with the person's name.
- **Real-Time Face Detection**: Capture live video from a webcam and detect faces in each frame.
- **Face Recognition**: Compare detected faces with stored images using face encodings.
- **Name Annotation**: Display the name of the recognized person on the screen.

## Installation
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Omarkh2021/face-recognition-opencv-python.git
    cd face-recognition-opencv-python
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Prepare the Face Database**:
    - Create a folder named `faces` in the project directory.
    - Add photos of individuals to the `faces` folder. Each photo should be named with the person's name (e.g., `john_doe.jpg`).

2. **Run the Face Recognition Script**:
    ```bash
    python face_recognition.py
    ```

3. **Real-Time Face Recognition**:
    - The script will start the webcam and begin detecting faces.
    - When a face is detected, it will be compared with the images in the `faces` folder.
    - If a match is found, a bounding box will be drawn around the detected face, and the person's name will be displayed.

## Project Structure
- `face_recognition.py`: Main script for running the face recognition system.
- `faces/`: Folder containing the reference images for face recognition.
- `requirements.txt`: List of dependencies required for the project.

## Dependencies
- **OpenCV**: For face detection and image processing.
- **face_recognition**: For encoding and comparing faces.
- **numpy**: For numerical operations.
