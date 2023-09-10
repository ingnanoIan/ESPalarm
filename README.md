# ESPalarm
Door Openings Logging Project with ESP32 and Database

Project Objective:
Create a program for an ESP32 that uses an MPU6050 sensor to detect motion and turns on an LED when significant motion is detected. The program also displays a message on the serial monitor when motion is detected and records the time and day when the detection occurred.

Components Used:

ESP32
MPU6050 Sensor

Code Functionality:

Initialization of communication with the MPU6050 sensor and the serial monitor.
Continuous monitoring of acceleration provided by the sensor.
Detection of motion when acceleration exceeds a configured threshold.
Turning on the LED and recording the detection time and day.
