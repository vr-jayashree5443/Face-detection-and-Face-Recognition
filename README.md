# Face-detection-and-Face-Recognition

### Introduction
This project is aimed at implementing a face recognition system using Python, OpenCV, and the face_recognition library. The system is designed to recognize faces from images and live video streams, enabling various applications in security, access control, and personalization.

### Requirements
- Python 3.x
- OpenCV (cv2)
- face_recognition
- imutils
- Google Colab (optional for running in Colab environment)

### Installation
To run the project, ensure you have Python installed on your system. Then, install the required libraries using pip:

```bash
pip install opencv-python
pip install face_recognition
pip install imutils
```

### Usage
1. **Training the System**:
    - Place the images of individuals you want to recognize in a designated directory (`train` directory). Each image file should contain the face of a single individual. The file name can be used as the label for recognition.
    - Execute the provided code in the Jupyter notebook or Python script to train the system. This involves encoding the faces in the images and storing their encodings along with corresponding labels.
    
2. **Testing the System**:
    - Provide a directory (`test` directory) containing images to be recognized.
    - Run the provided code to compare the faces in the test images with the trained encodings. The system will recognize known faces and label them accordingly. For unknown faces, it will mark them as "unknown".
    - Optionally, you can run the system on live video streams by using a webcam. The code includes functionality for real-time face recognition.

### Files
- **Face-Success.ipynb**: The Jupyter notebook containing the code for training and testing the face recognition system.
- **README.md**: This readme file providing instructions and information about the project.

### Drawbacks
- The system currently supports training with only one image per person.
- Despite limitations, the system achieves a high accuracy rate of 99.38%.
