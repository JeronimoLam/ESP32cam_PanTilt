# ESP32cam_PanTilt

## Project Overview

The ESP32cam_PanTilt is an open-source project aimed at creating a versatile and affordable pan-tilt camera system using the ESP32-CAM module. This project is ideal for hobbyists, makers, and anyone interested in DIY home security, remote monitoring, or photography automation.

## Features

- **Real-Time Video Streaming**: Leverages the ESP32-CAM's onboard camera for live video streaming.
- **Pan and Tilt Control**: Remotely control the camera's movements to cover a wide area.
- **Wi-Fi Connectivity**: Connects to your home Wi-Fi network for remote access and control.
- **Web Interface**: A user-friendly web interface for camera control and video streaming.
- **Mobile Compatibility**: Access and control the camera system from any mobile device.
- **Integration Capability**: Easily integrates with home automation systems like Home Assistant.

## Hardware Requirements

- ESP32-CAM Module
- Two (2) SG90 servos or similar for pan and tilt functions
- Pan-Tilt bracket
- Power supply for ESP32-CAM and servos
- Miscellaneous: jumper wires, screws, and mounting tools

## Software Requirements

- Arduino IDE
- ESP32-CAM library
- Servo library

## Setup Instructions

1. **Assemble the Hardware**: Attach the ESP32-CAM to the pan-tilt bracket and connect the servos.
2. **Install Software**: Download and install the Arduino IDE and add the ESP32 board manager.
3. **Load the Code**: Download the latest version of the ESP32cam_PanTilt software from this repository and upload it to your ESP32-CAM module using the Arduino IDE.
4. **Connect to Wi-Fi**: Configure the ESP32-CAM to connect to your Wi-Fi network via the provided web interface.
5. **Access the Web Interface**: Once connected, use your web browser to control the camera and view the live video.

## Usage

Control the camera via the web interface, which allows you to:
- Adjust the camera angle using pan and tilt controls.
- View the live streaming video.
- Configure settings like Wi-Fi credentials and camera parameters.

## Contributing

Contributions to the ESP32cam_PanTilt project are welcome! Feel free to fork the repository and submit a pull request if you have suggestions for improvements or have developed new features.

## License

This project is released under the MIT License, permitting modification, distribution, and both private and commercial use.

## Contact

For support or feedback, please submit an issue in the project repository.

## Documentation and Updates

For detailed documentation and the latest updates, visit the project's GitHub page.
