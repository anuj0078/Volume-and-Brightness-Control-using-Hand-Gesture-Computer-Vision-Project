# Volume-and-Brightness-Control-using-Hand-Gesture-Computer-Vision-Project

This project aims to control the system volume and screen brightness using hand gestures. Your left hand controls brightness, and your right hand controls volume. It uses the Mediapipe library to detect hand landmarks.

# How to run this script:

Clone this repo

Create a virtual environment

Activate virtual environment

Install all the dependencies

Run app.py file

# Explanation

The code uses a library called Mediapipe to spot where your hands are and figure out if they're left or right. If it sees just one hand, it decides whether it's left or right and then adjusts brightness or volume accordingly. But if it spots both hands, it does both brightness and volume adjustments at the same time, each in its own little task.
