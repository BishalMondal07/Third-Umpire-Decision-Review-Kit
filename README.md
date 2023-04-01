# Third Umpire Decision Review Kit
This is a Python program that simulates the third umpire decision review system used in cricket matches. It allows the user to view a video clip and make a decision on whether the batsman is out or not out.

# Requirements
To use this program, you must have Python 3 installed on your system. Additionally, you will need to install the following libraries:

Open Command Prompt in your Windows - 

● OpenCV (cv2) - Type - pip install opencv-python

● tkinter - Type - pip install tkinter 

● PIL (Pillow) - Type - pip install Pillow

● imutils - Type - pip install imutils



# How to Use
1. Download the program files and ensure that all dependencies are installed.
2. Replace the video clip, welcome screen, pending screen, out screen, not out screen, and sponsor screen with your own video and image files. Ensure that they have the same file names as the provided files.
3. Run the program by executing the command python third_umpire.py in the terminal.
4. The video clip will be displayed on the screen, and the user can control playback using the buttons provided. To make a decision, click on the "Give Out" or "Give Not Out" button. A "Decision Pending" message will be displayed until a decision is made.
5. The program will display the appropriate screen depending on the decision made.

# Buttons
● << Previous (fast): move the video playback back by 25 frames

● << Previous (slow): move the video playback back by 2 frames

● Next (slow) >>: move the video playback forward by 2 frames

● Next (fast) >>: move the video playback forward by 25 frames

● Give Out: make a decision that the batsman is out

● Give Not Out: make a decision that the batsman is not out

