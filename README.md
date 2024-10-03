## Workflow
| Serial Number | Workflow                                              |
|---------------|-------------------------------------------------------|
| 1             | Import and Install Dependencies                       |
| 2             | Keypoints using MP Holistic                           |
| 3             | Extract Keypoint Values                               |
| 4             | Setup Folders for Collection                          |
| 5             | Collect Keypoint Values for Training and Testing      |
| 6             | Preprocess Data and Create Labels and Features        |
| 7             | Build and Train LSTM Neural Network                   |
| 8             | Make Predictions                                      |
| 9             | Save Weights                                          |
|10             | Load the pre-trained action recognition model         |
|11             | Create a Streamlit application                        |

# Real-time Sign Language Detection

This project implements a real-time sign language detection system using TensorFlow, Mediapipe, and Streamlit. It detects three basic signs: "Hello," "Thanks," and "I Love You" using a webcam feed and provides real-time predictions with visualization.

## Features
- **Real-time Sign Detection**: Detects and classifies sign language gestures in real-time using a webcam.
- **Mediapipe Integration**: Uses Mediapipe for hand, face, and pose landmark detection.
- **Streamlit Interface**: Provides a simple web-based interface for running the model and visualizing results.
- **Gesture Visualization**: Displays the probability of each gesture being detected with a color-coded bar.
- **Key Points Extraction**: Utilizes landmarks from the body, hands, and face for gesture recognition.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- OpenCV
- TensorFlow
- Mediapipe
- Streamlit
- NumPy

You can install the required dependencies using the following command:

```bash
pip install opencv-python tensorflow mediapipe streamlit numpy
