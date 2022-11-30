# Virtual-White-Board
Air-Canvas Project -  Computer vision project implemented with OpenCV

The development of quicker PCs, accessibility of cheap and great quality camcorders and requests of computerized video investigation has given prevalence to object tracking strategies. Generally , video investigation system has three significant stages: first and foremost, identifying of the Object, furthermore following its movement from frame to frame and lastly analyzing the behaviour of that object.
# Algorithm

1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it.
3.. Adjust the trackbar values for finding the mask of coloured marker.
4. Preprocess the mask with morphological operations.(Erotion and dilation)
5. Detect the contours, find the centre coordinates of largest contour and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
6. Finally draw the points stored in array on the frames and canvas.

Write mode:
In this express, the framework will follow the fingertip coordinates and stores them.
Colour mode:
The client can change the shade of the text among the different accessible tones
Backspace:
Say in the event that the client turns out badly, we really want a signal to add a backspace

#Requirements: Python3 , NumPy , OpenCV installed on your system.

# How to execute the file:

> Install any Python compiler.

> Open Air-canvas.py and Run the Python File.

> When You execute the File You can see 4 windows (Mask,Tracking,Paint, Color Detectors )

> Color Detector will Show Which Color it will detect

> Mask will Show the Object detection 

> Tracking Will Track the Object Movement 

> Paint will show the Output of the Object Movement 

> Now Take Any Blue Object ( By default the code is for Blue ) and Start Drawing in the Air.

> Now You can see the Output coming in the paint window.
