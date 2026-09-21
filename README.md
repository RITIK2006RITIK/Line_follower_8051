# 8051 Line Follower Robot 🤖

An embedded systems project implementing an autonomous line-following robot using the **8051 microcontroller**, **infrared (IR) sensors**, and the **L293D motor driver**. The system detects the path using IR sensors and controls the DC motors in real time based on the detected line position.

## 📌 Project Overview

The robot continuously reads the output of IR sensors to determine whether it is on, left, or right of the line. Based on the sensor states, the **8051 microcontroller** generates appropriate control signals for the **L293D motor driver**, which drives the two DC motors.

The project demonstrates fundamental concepts of:

- Microcontroller programming
- Embedded C
- Sensor interfacing
- Motor control
- Digital I/O
- Real-time decision making
- Embedded hardware simulation

## 🛠️ Components Used

| Component | Purpose |
|---|---|
| 8051 Microcontroller | Main controller |
| IR Sensors | Line detection |
| L293D | DC motor driver |
| DC Motors | Robot movement |
| 7805 Voltage Regulator | Regulated 5V supply |
| Crystal Oscillator | 8051 clock source |
| Capacitor | Reset/clock circuitry |
| Resistors | Pull-up/reset circuitry |
| Power Supply | Circuit power |

## 🔧 Circuit Architecture

<img width="1253" height="843" alt="image" src="https://github.com/user-attachments/assets/12058f95-0493-4aca-a689-bda6c93773c1" />
