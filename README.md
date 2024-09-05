
# IoT Project: Microcontroller-based Wearable Blood Pressure Monitoring Device with GPS and SMS Feature

## Project Overview

This project aims to develop a **Microcontroller-based Wearable Blood Pressure Monitoring Device** integrated with **GPS** and **SMS** functionality. The system is designed to monitor blood pressure continuously and provide real-time data to users via a mobile app. In case of emergency, it sends alerts using SMS and displays location data via GPS.

## Features

- **Blood Pressure Monitoring**: Continuous measurement of blood pressure through wearable sensors.
- **GPS Integration**: Tracks the user's location and sends it along with blood pressure data.
- **SMS Alerts**: Sends an SMS alert with GPS location in case of abnormal readings.
- **Mobile App**: Displays real-time data and provides an interface for controlling the device.
  
## Components Used

- **Microcontroller**: ESP32 for its processing power and built-in WiFi/Bluetooth capability.
- **Sensors**: Blood pressure sensor to monitor the user's vitals.
- **GPS Module**: To provide real-time location tracking.
- **Mobile Application**: A custom app that interacts with the microcontroller to display data and alerts.
  
## Getting Started

### Prerequisites

- **ESP32** microcontroller
- **Blood Pressure Sensor**
- **GPS Module**
- **Mobile Phone** (for app interaction)

### Installation

1. **Hardware Setup**: 
   - Connect the sensors to the ESP32 microcontroller as described in the circuit diagram.
   - Ensure proper calibration of the blood pressure sensor.

2. **Software Setup**:
   - Install the necessary libraries for ESP32, GPS, and SMS.
   - Upload the code provided in the repository to the ESP32 using the Arduino IDE.

3. **Mobile App**:
   - Download the mobile app (link will be provided).
   - Follow the instructions to pair the app with the device.

### Usage

1. Power on the device and ensure the sensors are connected properly.
2. Open the mobile app to monitor real-time blood pressure data.
3. In case of an emergency, the device will send an SMS with your current location and abnormal blood pressure readings.

## Project Contributors

- Hojjat Yazdan
- Amirhossein Dibaj
- Artin Elhamirad

## License

This project is open-source under the MIT License. See the LICENSE file for more details.
