# Line Following Bot with Four IR Sensors

## Project Overview

This repository contains the fully tested code for a line-following bot equipped with four IR sensors. The bot is designed to follow a line autonomously by detecting it with the help of IR sensors. This project is a great starting point for anyone interested in robotics, programming, and automation.

## Features

- **High Precision Navigation:** The use of four IR sensors provides accurate line detection and smooth navigation.
- **Customizable Sensitivity:** Adjust the sensor sensitivity and bot speed as per your requirements.
- **Easy to Understand and Modify:** The code is well-commented and structured to facilitate easy understanding and modifications.

## Getting Started

### Prerequisites

To run this project, you will need the following:
- An Arduino-compatible microcontroller (e.g., Arduino Uno, Nano, Mega)
- Four IR sensors
- A line-following bot chassis with motors
- Jumper wires and a breadboard
- A computer with the Arduino IDE installed

### Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/Nauser-Alam/line-following-bot.git
    ```

2. **Open the Project:**
    Navigate to the project directory and open the `.ino` file in the Arduino IDE.

3. **Upload the Code:**
    Connect your microcontroller to your computer and upload the code to the board.

4. **Set Up the Hardware:**
    - Connect the IR sensors to the microcontroller as per the wiring diagram provided.
    - Attach the motors and ensure the bot is placed on a surface with a line to follow.

5. **Run the Bot:**
    Power on the bot and place it on the line. The bot should start following the line automatically.

## Code Explanation

The code consists of the following sections:
- **Setup:** Initializes the sensors and motors.
- **Main Loop:** Continuously reads sensor values and adjusts the motor speeds based on line detection.
- **Functions:** Includes custom functions for reading sensors and controlling motors.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with improvements or new features.

## Contact

For any questions or suggestions, please reach out to nauser522@gmail.com.
