# 🤖 Line Follower Robot using ESP32

An advanced autonomous line follower robot built using **ESP32**, implementing **centroid-based path detection** and intelligent control algorithms for smooth and accurate navigation.

## 📌 Overview

This project focuses on designing a high-performance line follower robot capable of handling complex tracks including sharp turns, junctions, and broken paths. The system uses an **IR sensor array** to detect the line and applies a **centroid algorithm** to determine precise movement.

## ⚙️ Features

*  Centroid-based line tracking for high accuracy
*  Micro-turn correction for smooth navigation
*  Junction detection and decision-making logic
*  Line recovery algorithm when path is lost
*  PWM-based motor speed control
*  Real-time embedded system optimization

## 🛠️ Tech Stack

* ESP32 Microcontroller
* IR Sensor Array
* Motor Driver (L298N / similar)
* Embedded C / Arduino IDE

## 🔧 Working Principle

The robot continuously reads values from the IR sensor array to detect the position of the line. Using a **centroid calculation**, it determines the deviation from the center and adjusts motor speeds accordingly using PWM signals.

Advanced logic is implemented to:

* Handle sharp turns using differential speed control
* Detect junctions based on multiple sensor triggers
* Recover the line if all sensors lose track

## 📊 Results

* Smooth navigation on curved and sharp tracks
* Stable performance with minimal oscillations
* Successful junction detection and path correction
* Real-time response with optimized control logic


## 📌 Key Learnings

* Applied control system concepts in real-time robotics
* Implemented centroid-based decision algorithms
* Optimized embedded system performance
* Designed robust recovery and navigation logic

## 🔮 Future Improvements

* PID-based control for enhanced stability
* Camera-based line detection (Computer Vision)
* AI-based path optimization
* Wireless monitoring system

---
