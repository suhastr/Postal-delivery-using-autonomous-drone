# 🚀 Drone-Based Postal Delivery System

## 📌 About the Project
The **Drone-Based Postal Delivery System** is an innovative project designed to automate lightweight package deliveries using a quadcopter. By leveraging modern microcontrollers, GPS technology, and communication modules, the drone can autonomously transport goods with minimal human intervention. This project aims to enhance transportation management by reducing delivery time, fuel costs, and human labor.

## 🎯 Goal
The primary goal of this project is to develop a drone-based delivery system capable of:
- **Autonomous flight** for delivering lightweight packages.
- **Remote-controlled operation** for precise navigation.
- **Payload handling** via a servo-controlled delivery mechanism.
- **Live location tracking** with GPS integration.

## 🛠 Technologies Used
The project incorporates multiple technologies and hardware components:
- **Microcontrollers**: Arduino UNO
- **Flight Controller**: Pixhawk 2.4.8
- **Programming Languages**: C/C++ (for microcontroller programming)
- **Communication Protocols**: GSM module for remote control, MAVLink for telemetry
- **Ground Station Software**: QGroundControl

## 🏗 Equipment & Materials Used
| Component          | Specifications |
|--------------------|---------------|
| **Drone Frame**   | 450mm frame |
| **Motors**        | Avionics 2836 (880 RPM/Volt) |
| **Propellers**    | 10cm length, 4.5cm pitch |
| **Battery**       | 4-cell, 3300mAh |
| **Electronic Speed Controllers (ESCs)** | 40A |
| **GPS Module**    | For live tracking |
| **Radio Transmitter** | For remote control |
| **Payload Box**   | Sunmica board (10mm thickness) |
| **Servo Motor**   | For door mechanism |
| **GSM Module**    | For payload communication |

## 📖 Physics Behind the Project
The project relies on several fundamental physics principles:
- **Aerodynamics**: Lift is generated using four propellers arranged in a quadcopter formation.
- **Newton’s Third Law**: Propellers push air downwards, creating an upward lift force.
- **Torque & Stability**: Controlled via differential motor speeds.
- **Energy Management**: Efficient power distribution from the battery via ESCs.
- **Wireless Communication**: MAVLink protocol enables drone-ground station connectivity.

## 💰 Approximate Cost Breakdown
| Item | Cost (Approx.) |
|------|--------------|
| Frame | $30 |
| Motors (x4) | $80 |
| Propellers | $15 |
| Flight Controller (Pixhawk 2.4.8) | $100 |
| Battery | $40 |
| ESCs (x4) | $60 |
| GPS Module | $50 |
| Arduino UNO | $25 |
| GSM Module | $20 |
| Servo Motor | $10 |
| Payload Box | $15 |
| Radio Transmitter | $80 |
| **Total Cost** | **$525** |

## 🛫 Stages of Flight

1. **Drone Assembly**
   - Assemble motors, ESCs, propellers, and frame.
   - Connect the power distribution board.
   - Integrate the flight controller (Pixhawk 2.4.8).

2. **Payload Design**
   - Build the payload box using a Sunmica board.
   - Install the servo motor for package handling.
   - Integrate Arduino and GSM module for communication.

3. **Autonomous Test**
   - Connect Mavlink for drone telemetry.
   - Configure waypoints and autonomous flight paths.
   - Test GPS connectivity and mission execution.

4. **Final Integration & Testing**
   - Attach the payload to the drone.
   - Test remote opening/closing of the payload using GSM commands.
   - Conduct live package delivery trials.

## 📸 Stages of Flight with Images
| Flight Stage | Description |
|-------------|------------|
| **Drone Assembly** | ![Drone Assembly](https://github.com/user-attachments/assets/1e682902-1ed8-4bb4-8375-50a27c0634fd) |
| **Payload Integration** | ![Payload](https://github.com/user-attachments/assets/73ade9a4-4ed2-469d-969d-b8e5a7d751f8) |
| **Autonomous Flight Testing** | ![Testing](https://github.com/user-attachments/assets/ef9525f5-e188-45ec-b37d-0ec1fe4ed8be) |
| **Final Package Delivery** | ![Delivery](https://github.com/user-attachments/assets/d7d41ae4-97eb-4bc5-ad76-ac84d387eeec) |


## 🛡 Safety Considerations
- Perform **pre-arm safety checks** before takeoff.
- Verify **GPS lock** for accurate navigation.
- Ensure **battery health** before every flight.
- Follow **local drone regulations** to avoid legal issues.

## Project Sponsor
- **Vidyavardhaka College of Engineering**, Mysuru, Karnataka, 570016

---


