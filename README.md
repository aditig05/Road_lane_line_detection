# Road_lane_line_detection Using OpenCV

## Overview

This project utilizes the OpenCV library in Python to detect lane lines in images or videos. Lane detection is a crucial component of various applications, including self-driving cars and advanced driver-assistance systems (ADAS). The system identifies lane boundaries and overlays them on the original image or video, providing a visual representation of the road lanes.

## Features

- **Lane Detection:** Identifies and highlights the lane lines on the road.
- **Region of Interest (ROI):** Defines a region of interest within the image to focus on lane detection.
- **Canny Edge Detection:** Utilizes Canny edge detection to find potential lane edges.
- **Hough Transform:** Applies the Hough line transform to detect lines in the image.
- **Averaging Lines:** Averages and extrapolates detected line segments to obtain full lane lines.
- **Visual Output:** Generates a visual output showing detected lane lines overlaid on the original image or video.

## Usage

1. Ensure you have OpenCV and NumPy installed. You can install them using `pip`:

2. Place your input images or videos in the project directory.

3. Open the Python script (`lane_detection.py`) in your preferred code editor.

4. Modify the `input_path` variable to specify the path to your input video or image.

5. Optionally, adjust parameters such as the region of interest or Canny edge detection thresholds to fine-tune lane detection.

6. Run the script:

7. The program will process the input and display the output with lane lines highlighted.

## Files

- `lane_detection.py`: The main Python script for lane detection.
- `test_image.jpg`: Sample test image for lane detection.
- `test.mp4`: Sample test video for lane detection.

## Dependencies

- Python 3.x
- OpenCV (Open Source Computer Vision Library)
- NumPy (Numerical Python)

## Acknowledgments

- OpenCV: https://opencv.org/
- NumPy: https://numpy.org/

## Contact

If you have any questions or issues, please feel free to contact 
[Aditi Gupta](mailto:aditig0501@gmail.com)





