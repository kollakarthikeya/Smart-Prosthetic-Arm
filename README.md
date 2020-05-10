# Prosthetic_Arm
This is an implementaion of interfacing Leap Motion with arduino using NodeJS and johnny-five framework.

## Description
The prosthetic arms that exist today provide only preset grips or even only open and close functions. Our aim for this project was to create an arm that feels and works just like real hand. The major problem was to leverage existing technology and give the user an option to input custom gestures, the user can record custom gestures with the help of leap motion device which will run the arm in shadow-mode. The arm decides when to grip the object present in front of it by sensing it through the palm-camera, using object detection and forms an appropriate grip. 

## Outcome
The device is capable of performing multiple grips and gestures, successfully implementing both force and position control. With the exception of the battery, the device is self-contained, housing all electrical, mechanical, and software components within its frame. All unique parts, like the fingers, palm, and forearm, were 3D-printed with ABS plastic. The device is mechanically capable of grasping objects that may be used in daily life. These different grasps and gestures can be recorded previously. The device is capable of identifying objects and communicating the identification to the low-level controller for actuation of the fingers.