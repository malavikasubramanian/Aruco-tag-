# Aruco-tag
ArUco Tag Position and Distance Measurement
Overview
This repository includes Python scripts for working with ArUco tags, allowing users to detect their positions and measure distances between them in real-time. The project consists of three main scripts:

1. generate_aruco_tag.py:

> Generates a specific ArUco tag with a given ID and type.
> Outputs the generated tag to a specified file.
> detect_aruco_tags.py:

2. Captures video frames from the camera:
   
> Detects ArUco tags in the frames using OpenCV.
> Draws bounding boxes and IDs around the detected tags.

3. measure_distance.py:

> Continuously captures video frames and detects ArUco tags.
> Measures the distance between two specific ArUco tags in centimeters based on a reference length.
> 
Prerequisites
Ensure that you have the following dependencies installed:

> Python (version >= 3.6)
> OpenCV
> NumPy
> imutils

Install the required Python packages using the provided requirements.txt file.

Instructions
Generating ArUco Tag:

> Run the generate_aruco_tag.py script with the desired output file, ArUco ID, and type.

Detecting ArUco Tags:

> Run the detect_aruco_tags.py script to observe real-time detection of ArUco tags.

Measuring Distance:

> Execute the measure_distance.py script to continuously measure the distance between two ArUco tags.
Important Notes
Adjust camera calibration parameters in the scripts if needed.
Ensure that the camera is properly connected and configured.
Press 'q' to exit the real-time detection or distance measurement scripts.
