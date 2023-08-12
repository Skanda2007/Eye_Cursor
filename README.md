# Eye_Cursor
##Overview
This is a program built to help control the cursor of any laptop or desktop using python. it uses **Mediapipe from Google**, **PyAutoGUI** and **OpenCV**. OpenCV is used to enable the camera of the system to take input. Mediapipe is then used to draw landmarks over the face and track the iris and the eyelids. The position of the iris in the frame is used to as a refernce to use PyAutoGUI to move the cursor and blinking is programmed to click.

##Installation
  1. Go To _https://www.python.org/_ and install the latest version of python if not present in the system.
  2. Open the CLU and install Mediapipe `pip install mediapipe`, PyAutoGUI `pip install pyautogui` and Opencv `pip install opencv-python`
  3. Clone the repositry with `gh repo clone Skanda2007/Eye_Cursor`

##Running
  In the CLI open the repositry folder and enter `main.py`
