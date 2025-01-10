# Color-Detection-using-opencv
Code Explanation
main.py
Capture Video Feed:

Uses OpenCV to capture video feed from the webcam.
Convert to HSV:

Converts the BGR frame to the HSV color space for color detection.
Generate Mask:

Creates a binary mask for the specified color using HSV limits.
Bounding Box:

Uses the mask to detect the region of interest and draws a bounding box.
Exit:

Press q to quit the application.
utils.py
get_limits(color):
Converts the specified RGB color to its HSV equivalent.
Returns lower and upper bounds for HSV thresholding.
