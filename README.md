# IoT-Based Coma Patient Monitoring System

This repository contains the project files for the IoT-based coma patient monitoring system, developed as part of a research initiative to create low-cost, efficient healthcare monitoring solutions for resource-constrained environments.

## Overview

Coma patients require continuous and real-time monitoring of vital signs to ensure timely medical intervention. In developing countries or areas with limited healthcare infrastructure, this poses significant challenges due to a lack of resources, personnel, and stable network connectivity. This project presents an Internet of Things (IoT)-based solution that provides remote monitoring of coma patients using affordable hardware components and a robust software architecture.

## Features

- **Real-time Monitoring**: Tracks vital signs like heart rate, body temperature, blood pressure, eye movement, and body positioning using cost-effective sensors.
- **Low-Cost Implementation**: Entire system is built using affordable components such as the Arduino Uno, GSM module, and ESP8266 Wi-Fi module, with a total cost under $30.
- **Resilient Communication**: Capable of operating with limited or intermittent internet connectivity, utilizing a GSM module for emergency alerts.
- **Scalability**: Can be adapted for different healthcare environments, from single-patient setups in clinics to multi-patient systems in larger hospitals.
- **Locally Hosted Application**: Allows for local data storage and access to vital signs, ensuring system functionality even when no internet connection is available.

## System Components

- **Hardware**: 
    - Arduino Uno microcontroller
    - Biometric sensors: heartbeat, body temperature, blood pressure, eye blink, and body movement sensors
    - Wi-Fi module (ESP8266)
    - GSM module for SMS alerts
    - 20x4 LCD display and LED indicators for local feedback

- **Software**:
    - Arduino firmware to process sensor data and manage communication with external servers
    - MySQL database for storing patient information and vital signs
    - Web application (PHP, HTML, CSS, JavaScript) for real-time monitoring and alert management

## Repository Structure

- `comma patient/code`: Source code for the Arduino microcontroller and web application.
- `comma patient/images`: Diagrams and figures used in the paper.
- `comma patient/images`: Diagrams and figures used in the paper.
- `comma patient/images`: Diagrams and figures used in the paper.
- `comma patient/hardware`: Schematics and descriptions of the hardware setup.
- `README.md`: Project overview and instructions.

## How to Run

To set up the system, follow these steps:

1. Clone the repository.
2. Upload the Arduino firmware from the `/code` directory to your Arduino board.
3. Set up the MySQL database and import the schema provided in the `/code/database` folder.
4. Launch the web application using a local server (e.g., XAMPP or LAMP).
5. Connect the sensors to the Arduino as per the schematic in the `/hardware` folder.

## Future Work

We plan to integrate predictive analytics and anomaly detection into the system using machine learning techniques. Our goal is to further enhance the system's capability to anticipate critical patient conditions before they arise, leveraging AI-driven insights while maintaining cost-efficiency.

## License

This project is open-source and licensed under the MIT License.
