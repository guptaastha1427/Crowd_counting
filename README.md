# Crowd Counting with OpenCV

This code demonstrates crowd counting using OpenCV and a Haar Cascade classifier for face detection. It captures the video feed from the webcam, detects faces in the frame, and counts the number of faces. The count is displayed in real-time on the video feed.

## How it works

1. The Haar Cascade classifier for face detection is loaded.

2. The webcam is initialized to capture video frames.

3. In each frame, the code converts the image to grayscale for face detection.

4. Faces are detected in the grayscale frame using the `detectMultiScale` function.

5. For each detected face, a green rectangle is drawn around it, and the face count is incremented.

6. The frame is displayed with the face count in real-time.

7. To exit the program, press 'q'.

## Requirements

- Python
- OpenCV library

To run the code, make sure you have OpenCV installed. You can install it using `pip`:

```pip install opencv-python```

## How to use

1. Clone this repository.

2. Run the Python script:

```python3 count.py```

3. The webcam will open, and faces will be detected and counted in real-time.

4. To exit the program, press 'q'.

Feel free to modify the code for your specific crowd counting needs or integrate it into your projects.
