# Gyroscope-Raspberry-Pi
# Description
This project detects turbulence using the gyroscope module on Raspberry Pi. This code also uses an email class with smtplib to send a notication via email when the voltage reading is high. This project assumes that you have already setup your Raspberry Pi and have the Freenove Starter kit directory. If you do not you will need to setup Raspberry Pi and Freenove before you start this project. 

# Materials Needed
## Hardware
1. Raspberry Pi x1
2. GPIO Extension Board & Ribbon Cable x1
3. Breadboard x1
4. GY-521 Module
5. Male-to-Male Jumper Wires x4


## Software
1. turbulance.py from this repository

# Setup and Configuration
## Hardware
Below is the following pinout for this project:
![gyroscope](https://user-images.githubusercontent.com/66813474/167408574-044871b9-a269-4f9d-8c3c-1d665e63fa97.PNG)

# Code Setup
1. Download turbulance.py
2. Open tyrbulance.py and change the following lines to correspond with the email notication:
    1. line 85: enter the email that you want to send the notification from
    2. line 86: enter the password to the email from line 10
    3. line 138: enter the recipient email
    4. line 139(optional): you can change the email subject
    5. line 140(optional): you can change the contents of the email
4. Run turbulance.py and tilt the gyroscope module to measure turbulence
