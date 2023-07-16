# HomeAutomationSystem
Objective:

The main objective of this project is to design and implement a smart door locking system using facial recognition technology for access control. Specifically, the project aims to:

Develop a camera module that can capture high-quality facial images for facial recognition.

Implement a facial recognition algorithm that can accurately recognize authorized individuals and deny access to unauthorized individuals.

Design and implement a microcontroller unit that can process the facial images and control the locking mechanism of the door.

Integrate the facial recognition system with the locking mechanism to provide a secure and convenient access control solution.

Provide a notification system that sends an alert message to the owner's phone when an unauthorized person attempts to enter the home.

Test the performance of the system using a dataset of faces and evaluate its accuracy, reliability, and scalability.

Provide a cost-effective, scalable, and secure solution for granting access to authorized individuals using facial recognition technology while ensuring the safety of the homeowner.

Overall, the objective of this project is to develop a smart door locking system using facial recognition technology that can provide a reliable, convenient, and secure solution for access control in homes while alerting the homeowner when an unauthorized individual attempts to enter the home.

Software Dependencies:

1.Python 
2.dlib (to install face_recognition)
3.face_recognition

Hardware Dependencies:

Arduino
ESP32-CAM
Solenoid lock
Connecting Wires
DC Power Supply

Installation for face_recognition:

This module is tough to install as installing dlib, which is a dependency for this module is quite challenging. Linux users may have some easy in installation as they can use pip to install them directly. But windows users are recommended to go through the following tutorial for the installation process.

ageitgey/face_recognition#175 (comment)

Other useful links are listed below:

https://pypi.org/project/dlib/
https://pypi.org/project/face_recognition/

Interfacing Arduino:

The arduino used here is Arduino Uno and is programmed with Arduino IDE. Further information can be found in the following link. https://www.arduino.cc/
