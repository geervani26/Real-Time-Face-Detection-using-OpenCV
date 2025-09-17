# Real-Time-Face-Detection-using-OpenCV
This project demonstrates real-time face detection using OpenCV and the Haar Cascade Classifier. The program captures live video from your webcam, detects faces, and highlights them with bounding boxes.
# Features
* Uses Haar Cascade Classifier (haarcascade_frontalface_default.xml) for face detection.
* Captures live video from the webcam.
* Converts frames to grayscale for faster detection.
* Draws a green rectangle around detected faces.
* Runs continuously until you press the ESC (27) key to exit.
# Requirements
* Python 3.x
* OpenCV (pip install opencv-python)
* Haar Cascade XML file (included in OpenCV or can be downloaded from OpenCV GitHub)
# Usage
* Clone the repository and navigate to the project folder.
* Ensure haarcascade_frontalface_default.xml is present in the same directory.
  # Run the script:
  * python face_detection.py
  * The webcam will open, and detected faces will be highlighted.
  * Press ESC (27) to close the program.
# Output Preview
When the script runs, you’ll see your webcam feed with green rectangles around detected faces.
