# Third Eye for Blinds

"Third Eye for Blinds" is an innovative IoT-based project designed to assist visually impaired individuals in navigating their surroundings independently and safely.

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithm](#algorithm)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The "Third Eye for Blinds" project utilizes IoT technology to enhance the mobility of blind individuals. It features a wearable device based on Arduino equipped with an ultrasonic sensor. The device detects obstacles in real-time and provides auditory feedback through varying beeping frequencies as obstacles approach, facilitating safer navigation.

## Problem Statement

Existing mobility aids for visually impaired individuals, such as white canes and guide dogs, have limitations including fragility, high cost, and extensive training requirements. These factors restrict their effectiveness and usability in various environments, necessitating a more reliable and accessible solution.

## Features

- **Real-time Obstacle Detection:** Utilizes ultrasonic sensors to detect obstacles and provides immediate auditory alerts.
- **Automatic Alert System:** Beep frequency increases as obstacles get closer, helping users gauge proximity.
- **Wearable Design:** Enables convenient use without requiring constant handling, potentially integrated into clothing.
- **Low Power Consumption:** Designed for efficiency to extend battery life during use.
- **Scalable and Versatile:** Suitable for both indoor and outdoor environments, adaptable to various user needs.

## Prerequisites

To replicate or further develop this project, the following components are required:
- Arduino UNO
- Ultrasonic sensor
- Buzzer
- Jumper wires
- Hardware battery and connectors
- Arduino IDE (software)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ashok-AT/Third-Eye-for-Blind-Peoples.git
   cd Third-Eye-for-Blinds-Peoples
   ```
2. **Set up Arduino IDE:**

Connect Arduino UNO to your computer.
Open Arduino IDE and upload the code provided in the repository (ThirdEyeForBlinds.ino).

3. **Assemble the hardware:**

Connect the ultrasonic sensor, buzzer, and other components following the circuit diagram provided (hardware_diagram.png).

## Usage

1. **Power on the device:**

Ensure the hardware components are properly connected and powered.

2. **Navigate your surroundings:**

Wear the device or place it in a convenient location.
Move around to detect obstacles using the auditory feedback from the buzzer.

## Algorithm

- <b>Sensor Integration:</b> Connect and configure all sensors using IoT principles.
- Distance Calculation: Utilize the ultrasonic sensor to measure the distance of detected objects.
- Alert System: Emit alert sounds through the buzzer upon detecting objects.
- Proximity Feedback: Increase beep frequency as objects approach closer.
- Automatic Control: Automatically cease beeping when obstacles move away from the sensor's range.

## Future Enhancements
Future developments include:

Integration into a wearable jacket for continuous and inconspicuous use.
Use of specialized boards and advanced sensors for faster response times in crowded environments.
Further feature enhancements leveraging technological advancements for broader applications beyond navigation assistance.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. Ensure your code follows the project's coding standards and includes relevant documentation.

License
