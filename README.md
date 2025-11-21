# Heart-Pulse-Monitoring-System
Overview

This project is a portable and low-cost heart rate monitoring system built using Arduino UNO, an IR pulse sensor, and a 16×2 LCD display. It detects heartbeats from a fingertip and displays the calculated BPM (Beats Per Minute) in real time. The project is intended for basic health monitoring and can be extended for early abnormal heartbeat detection.

Features

Accurate heartbeat detection using IR reflective sensing

Real-time BPM display on 16×2 LCD

Portable, low-power design

Suitable for continuous monitoring

Can be extended with buzzer alerts or IoT integration

Hardware Components

Arduino UNO

IR Pulse Sensor

16×2 LCD

10kΩ Potentiometer
System Working

IR sensor detects blood flow variations from fingertip.

Arduino reads analog pulse variations.

Signal is processed to identify peaks (heartbeats).

Time interval between peaks is used to calculate BPM.

BPM value is updated on LCD every second.

Applications

Basic home health monitoring

Portable biomedical devices

Early detection of irregular heart rates

Student/academic biomedical projects

Connecting wires

Breadboard
