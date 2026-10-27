# Smart Worker Guidance and Safety System

An ESP32-based worker safety system designed to monitor muscle activity and body movement, identify abnormal conditions, and alert the worker or supervisor.

## Project Overview

This project aims to improve worker safety in industrial and agricultural environments. It uses muscle activity and motion sensors to help identify potential strain or abnormal movement.

## Hardware Components

- ESP32 development board
- EMG sensor
- MPU9250 motion sensor
- Red LED and green LED
- Buzzer
- Push button
- Connecting wires and power supply

## Working Principle

1. The EMG sensor measures muscle activity.
2. The MPU9250 monitors movement and orientation.
3. When a configured abnormal condition is detected, the system activates a red LED and buzzer.
4. The push button resets a latched alert.
5. When Wi-Fi and Telegram are configured correctly, the system can send an alert message.

## Project Photos

Project hardware and demonstration photos will be displayed here.

## Project Demonstration Video

[View the uploaded project video](video.mp4)

## Technologies Used

- Embedded C / Arduino programming
- ESP32
- EMG sensing
- Motion sensing
- Wi-Fi and Telegram notifications

## Project Goal

To develop an affordable prototype that supports worker safety by providing early alerts for potentially abnormal muscle activity and movement.
