# Humanoid Robot Firmware  

This repository contains the **firmware** for the **limb control system** of a humanoid robot developed as part of my **BE final year project**. The firmware is designed to interface with hardware components to enable precise motion control and sensor integration.  

## Features  
- ✅ **Servo Control** – Uses **PCA9685** PWM driver to control multiple servos.  
- ✅ **Inertial Measurement Unit (IMU)** – Reads **MPU6050** data for motion tracking.  
- ✅ **UART Communication** – Interfaces with external modules via serial communication.  
- ✅ **PWM & GPIO** – Handles various control signals for motor drivers.  
- ✅ **ADC Support** – Reads analog sensor inputs for real-time feedback.  

## Hardware Used  
- **BeagleBone Black Rev C** (Single-board computer)  
- **PCA9685** (16-channel PWM driver for servo motors)  
- **MPU6050** (6-axis IMU for motion sensing)  
- **Various GPIO, ADC, and UART peripherals**  

## Project Scope  
This firmware is a **low-level control system** for the robot’s limbs and sensors. It is designed to be **integrated with higher-level software** for computer vision (OpenCV) and motion planning (ROS).  

## Confidentiality Notice  
The full humanoid robot source code, including **ROS and OpenCV integration**, is confidential as this project was part of my **BE final year thesis**. This repository only contains the firmware responsible for hardware-level control.  

## Future Work  
If you are interested in extending this project or collaborating on a similar robotics framework, feel free to open an issue or reach out! 🚀  


