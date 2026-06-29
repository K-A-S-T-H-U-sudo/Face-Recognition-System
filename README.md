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
## FACE RECOGNITION SYSTEM
                        │
                        ▼
          Load Haar Cascade Classifier
                        │
                        ▼
        Load Training Dataset (Images)
                        │
                        ▼
      Preprocess Images (Grayscale & Resize)
                        │
                        ▼
      Train FisherFace Recognition Model
                        │
                        ▼
          Save / Load Trained Model
                        │
                        ▼
          Capture Live Webcam Frames
                        │
                        ▼
             Detect Face using OpenCV
                        │
                        ▼
          Preprocess Detected Face
                        │
                        ▼
      Compare Face with Trained Model
                        │
                        ▼
     ┌─────────────────────────────────┐
     │ Match Found?                    │
     └──────────────┬──────────────────┘
                    │
          Yes       │        No
           ▼        │        ▼
 Display Person Name│  Display "Unknown"
 and Confidence     │
                    ▼
             Continue Detection

                
