## Technologies Used
- Python 3.9
- OpenCV 4.5.5
- NumPy 1.23.5

## Features
- Face Detection
- Face Recognition
- Real-time Webcam Recognition

## How to Run
1. Install requirements
2. Run the Python file
3. Show face in front of webcam

## Installation

Install the required packages:
```bash
pip install opencv-contrib-python==4.5.5.64
pip install numpy==1.23.5
```
Architecture:       +----------------------+
                    |   Webcam / Camera    |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    |   Capture Image      |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Face Detection       |
                    | (Haar Cascade)       |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Image Preprocessing  |
                    | (Grayscale & Resize) |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | FisherFace           |
                    | Model Training       |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Face Recognition     |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Display Result       |
                    | (Name / Unknown)     |
                    +----------------------+
