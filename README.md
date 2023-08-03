# Mouse-actions-control-by-hand
Project Name: AI Virtual Mouse

Description: AI Virtual Mouse is a Python project that uses hand tracking and mediapipe to detect hand gestures and
control the computer's mouse cursor. 
It allows users to move the mouse cursor and perform clicks using hand movements.

Features: 
1) Hand tracking and landmark detection.
2) Virtual mouse control using hand position.
3) Click simulation with hand gestures.

Installation:
Ensure you have Python 3 installed on your system.
Install the required libraries using pip:
#use the code given below: 
pip install mediapipe
pip install opencv-python
pip install autopy

Usage:
Run the handtracking.py script to launch the AI Virtual Mouse application.
When the application starts, it will display the webcam feed with hand landmarks.
Use your index finger to control the mouse cursor's movement.
If you raise your index and middle fingers together, it will simulate a mouse click.

Dependencies:
Python 3.x
mediapipe
opencv-python
autopy

Configuration:
No additional configuration is required. The application will use the default webcam for hand tracking.

Troubleshooting:
If the hand tracking is not accurate, try adjusting the frameR or smoothening parameters in the handtracking.py file.
Ensure that your hand is well-lit and visible to the webcam.

Contact:
For any questions or feedback, feel free to contact me via [shambhavibhardwaj29@gmail.com].
