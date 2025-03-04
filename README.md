# ESP32 Smart MediBox with IoT

## Overview

The **Smart MediBox** with IoT is an intelligent pharmaceutical storage system designed to efficiently manage medications. It leverages IoT technology to monitor medication schedules, storage conditions, and usage, ensuring timely reminders and proper storage.
This project was completed as part of the **Embedded Systems and Applications (EN2853)** module during Semester 4, where it was an **individual assignment**. The system incorporates the ESP32 microcontroller to interact with various sensors and actuators, including temperature and light sensors, a buzzer, and a servo motor. It uses MQTT for communication, allowing remote control and monitoring.


## Features

- **Medication Schedule Management**: Allows users to set reminders and schedules for taking medications.
- **Remote Monitoring**: View real-time data such as temperature and light levels via an IoT dashboard.
- **Automated Storage Control**: Uses sensors to monitor the storage conditions and automatically adjust the environment (e.g., temperature or humidity).
- **Alarms and Notifications**: Alerts users when medications need to be taken or if conditions inside the MediBox deviate from the set thresholds.
- **IoT Integration**: Real-time communication via MQTT for data transfer and remote control.

## Hardware Components

- **ESP32 Microcontroller**: Core controller for the MediBox system.
- **DHT22 Sensor**: Measures temperature and humidity within the box.
- **LDR Sensors**: Detect light intensity to ensure medications are stored in low-light conditions.
- **Servo Motor**: Controls the opening mechanism of the MediBox lid.
- **Buzzer**: Provides audio alerts for reminders and notifications.
- **Wi-Fi Module**: ESP32's in-built Wi-Fi module for IoT communication.
- **OLED Display (optional)**: Displays system information and reminders locally.

## Software Components

- **Arduino IDE**: Used for developing and uploading the code to the ESP32.
- **MQTT Protocol**: Facilitates communication between the MediBox and remote server or mobile application.
- **NTP Client**: Provides time synchronization for scheduled reminders.
- **PubSubClient Library**: Handles MQTT communication.

### Hardware Setup
1. Connect the DHT22 sensor to the ESP32.
2. Connect LDR sensors to detect ambient light.
3. Attach the servo motor for lid control.
4. Connect a buzzer for audio alerts.
5. (Optional) Connect an OLED display to show local information.
