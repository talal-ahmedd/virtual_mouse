# virtual_mouse
An alternative to traditional mouse, controlled through hand gestures, virtual mouse is implemented through opencv, mediapipe and pyautogui to capture video frames, localize 21 hand coordinates, recognize more than 10 hand gestures and associate specific functions of mouse to each of the gestures.

## Libraries and Frameworks used in our Proposed Virtual Mouse
#### 1. OpenCV
We used openCV in our virtual mouse in order to set up the camera, capture video frames and apply video processing functions on those frames such as converting the subpixel layouts, flipping and displaying the frames etc.
#### 2. Mediapipe
Mediapipe Hands was used to detect and track the hands and fingers, and to deduce 21 3D hand coordinates from a single video frame in order to recognize different gestures.
#### 2. PyAutoGUI
PyAutoGUI is a simple, cross-platform GUI automation library that we used to associate the gestures with different functions for controlling the mouse movement, clicks and keyboard strokes through Python scripts.

## Functionality of the Virtual Mouse
1. Mouse movement
2. Right click
3. Left click
4. Double click
5. Drag & Drop
6. Multiple item selection
7. Vertical scroll
8. Horizontal scroll
9. Zoom in & out
10. Brightness control
11. Volume control
