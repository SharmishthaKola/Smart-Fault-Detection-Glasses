# Smart Fault Detection Glasses

## Problem Statement:
Manual inspection for fault detection in industries is prone to human error and time consuming task. It is possible that minute defects or even major defects can go unnoticed sometimes due to the fatigue and repetitive work.

## Solution:
To address this problem, we developed a "Smart Fault Detection Glasses" using Raspberry Pi which detects the defects in real time using a camera module which is attached to the frame of the glasses. This is implemented using an ML model, designed by the team.

## Working:
- Camera module captures the imaage of the object that is to be tested and sends it to the Raspberry Pi
- Raspberry Pi processes the image, runs the ML model and inspects the image (OK/NOK)
- The processed data is sent to the server using Wi-Fi
- Server stores the inspection data
- Mobile application shows the inspection information from the database

## Hardware Components Used:
- Raspberry Pi 4 Model B
- Camera Module
- Battery
- Buzzer

## Software Used:

## Project Structure:

## Team Members:

## Future Scope:
