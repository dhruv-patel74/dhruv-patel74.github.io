---
layout: post
title: Articulated Iron Man Helmet
description: Robotics Intern @ Ideal Institute of Technology & RobotLAB South Jersey
skills: 
- Fusion 360
- Robotic Design
- Engineering Notebook
- FDM (3D Printing)
- Breadboarding (circuit testing)
- Circuit Assembly / Wiring
- Actuators (Servos, Vibration Motors)
- Microcontrollers (Arduino Nano Every)
- Power Systems (battery integration, voltage regulation)
- Arduino Programming
main-image: /project.webp
---

## Overview  
As part of my robotics internship at **Ideal Institute of Technology & RobotLAB South Jersey**, I developed an **articulated Iron Man helmet** featuring motorized faceplate movement, LED integration, and wireless control. This project combined **mechanical design, electronics integration, and microcontroller programming**, showcasing how robotics concepts can be applied to wearable tech.

---

## Design & Fabrication  
- Edited helmet components in **Fusion 360** and modified designs for servo integration  
- Used **FDM 3D printing** for custom parts and combined with pre-made components for structural integrity  
- Designed **hinge mechanisms** to ensure smooth faceplate motion  

---

## Electronics & Hardware Integration  
- Installed **micro servos** to control helmet articulation  
- Integrated **Arduino Nano Every** for motor control and LED lighting  
- Developed a **power management system** for stable voltage delivery across servos and LEDs  
- Used **breadboarding for circuit testing**, then transitioned to permanent wiring with soldered connections  


---

## Software & Control  
- Programmed in **Arduino IDE** for precise servo actuation and LED sequences  
- Implemented **PWM control** for smooth servo motion  
- Added **input triggers** (button or wireless module) to control open/close animations  

```cpp
// Example Arduino snippet for servo control
#include <Servo.h>
Servo faceplateServo;
void setup() {
  faceplateServo.attach(9);
}
void loop() {
  faceplateServo.write(0);   // closed position
  delay(2000);
  faceplateServo.write(90);  // open position
  delay(2000);
}

