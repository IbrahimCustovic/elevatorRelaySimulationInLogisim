# Elevator Relay Simulation in Logisim

This repository contains a Digital Design project focused on the **implementation of elevator control logic** and the comparison between **classic relay-based control** and its **digital logic simulation in Logisim Evolution**.

## Project overview
The project explains how a **4-floor elevator system** can be controlled using relays and how the same behavior can be recreated using digital logic circuits. The report covers both the hardware-oriented logic behind relay control and a simplified digital implementation suitable for simulation and learning. fileciteturn15file0

## Main topics covered
- elevator basics and historical background
- relay fundamentals and relay types
- relay-based elevator control for a 4-floor building
- digital simulation of relay behavior in Logisim Evolution
- comparison of relay systems and digital logic systems

## Elevator logic in the project
The elevator control concept includes:
- floor call buttons for each floor
- request memory/latching
- direction control for **up** and **down** movement
- request clearing when the elevator reaches a floor
- motor and speed control logic
- door lock and safety conditions before movement

According to the report, the relay-based version uses floor relays, direction contactors, speed control, magnetic switches, and door-lock protection to decide when the elevator moves, where it stops, and when doors may open. fileciteturn15file0

## Digital logic simulation
The Logisim-based interpretation breaks the system into several functional blocks:
- **Request latching** – stores floor requests using D flip-flops
- **Direction logic** – determines travel direction using encoders, comparators, and logic gates
- **Request clearing logic** – resets stored requests once the elevator arrives at the correct floor
- **Motor and speed control** – switches between high-speed and low-speed behavior depending on distance to the target floor

These modules are presented in the report as separate parts of the overall elevator controller design. fileciteturn15file0

## Tools
- **Logisim Evolution** for digital circuit simulation
- digital logic elements such as:
  - D flip-flops
  - AND gates
  - OR gates
  - comparators
  - encoders

## Learning goal
This project is intended as an educational demonstration of how older **relay-based automation logic** can be understood and approximated using **digital logic design**. It is useful for understanding control systems, sequential logic, and the transition from electromechanical control to digital implementation. fileciteturn15file0

## Conclusion
The project highlights that both approaches have advantages:
- **digital logic** offers smaller size, lower energy consumption, higher speed, and greater flexibility
- **relays** remain useful in robust industrial environments and high-voltage applications

The main value of the project is in understanding the relationship between these two implementation styles through the example of an elevator system. fileciteturn15file0

## Author
**Ibrahim Čustović**  
International University of Sarajevo  
Academic year 2024–2025
