# Cricket-DRS
The program is designed in Python with following as major modules :
  tkinter
  cv2 (open-CV)
  Python Image Library (PIL)
  threading, time, imutils, etc.

  It id designed to take fair decisions in case of Run-Outs.

Functionalities:
Allows the User to get a video file from computer for which we have to check whether the player is Out or Not-Out.
Video is converted into frames by using the CV2 module of Python.
There are 4 buttons, named as :
	Next_Fast : Shows the next frame after skipping 25 frames
	Next_Slow : Shows the next frame after skipping 2 frames
	Prev_Fast : Shows the previous frame after skipping 25 frames
	Prev_Slow : Shows the previous frame after skipping 2 frames
The result buttons are also given on tkinter window, which first shows the name of Sponser and then shows the Decision given by the Umpire.
Note: The file should named as "clip" in mp4 format
