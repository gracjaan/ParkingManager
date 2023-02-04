# Car Park Space Detection

This project aims to detect free parking spaces in a video feed from a car park. The project consists of two python scripts that perform the following tasks:

Detecting free parking spaces in the video feed and displaying them on screen with a green rectangle for free spaces and a red rectangle for occupied spaces.
Creating a graphical user interface for selecting the parking space regions in an image of the car park.

## Required Libraries

The following libraries are required to run the project:

* OpenCV (cv2)
* Pickle
* Numpy
* Usage

The first script, carParkDetection.py, takes a video feed from a file named carPark.mp4 and displays the parking spaces with color-coded rectangles. The second script, carParkSelector.py, opens an image of the car park and allows the user to select the parking space regions by clicking on the image with the mouse. The selected regions are saved in a file named CarParkPos and used in the first script.

## Steps to Run the Project

Run the carParkSelector.py script to select the parking space regions in an image of the car park.
Run the carParkDetection.py script to detect the free parking spaces in the video feed.

## Note

The scripts have been tested with the provided video feed and image of the car park. If using a different video feed or image, the values for width, height, and the threshold for the adaptive threshold method may need to be adjusted.
