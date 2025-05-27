# color-detection-webcam-opencv
## Real-Time Color Detection using Trackbars and Webcam
This Opencv project allows real-time color detection from your webcam using HSV color space. Trackbars are used to dynamically adjust the range of colors being detected.
## Features 
- Real-time color detection from webcam feed
- Trackbars to set HSV range (Hue, Saturation, Value)
- Instant mask generation based on selected HSV values
- Helps understand how color segmentation works in computer vision
## How It Works
- Converts the webcam frame from BGR to HSV color space
- Applies a mask using 'cv2.inRange()' to isolate desired colors
- Trackbars adjust the lower and upper HSV bounds dynamically
- The result is displayed in a separate window as a binary mask
