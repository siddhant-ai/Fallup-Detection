This repository contains the code and documentation for a Fall Detection project using Nodemcu, MPU6050 and IFTTT.

## **Overview**
This project is aimed at detecting falls of elderly people or individuals with mobility issues and alerting their caregivers or emergency services. The project uses a Nodemcu microcontroller and an MPU6050 accelerometer and gyroscope sensor to detect falls. The Nodemcu is programmed to connect to the internet and send a message to IFTTT when a fall is detected. IFTTT then sends an alert to the caregiver's phone or to emergency services depending on the user's preference.

## **Components**
Nodemcu microcontroller

MPU6050 accelerometer and gyroscope sensor

Jumper wires

Breadboard

USB cable

Prerequisites

Arduino IDE

Nodemcu board package for Arduino IDE

MPU6050 library for Arduino IDE

IFTTT account


## **Installation**
Clone this repository to your local machine.

Connect the MPU6050 sensor to the Nodemcu board using jumper wires and a breadboard. Refer to the pinout diagram in the code.

Connect the Nodemcu board to your computer using a USB cable.

Install the Nodemcu board package and MPU6050 library in the Arduino IDE.

Open the fall_detection.ino sketch in the Arduino IDE.

Replace the placeholders in the code with your Wi-Fi credentials and IFTTT webhook key.

Upload the sketch to the Nodemcu board.

Test the project by simulating a fall or by gently tilting the sensor.

## **Usage**
When a fall is detected, the Nodemcu board sends a message to IFTTT. IFTTT then triggers an alert on your phone or sends an email to emergency services. You can customize the alert settings on IFTTT to suit your preferences.

## **Contributing**
Contributions are welcome! If you find a bug or have an improvement suggestion, please open an issue or submit a pull request.

![logo] (https://avatars.githubusercontent.com/u/57462939?v=4)

