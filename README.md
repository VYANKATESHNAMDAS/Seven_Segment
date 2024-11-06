# 7-Segment Display Counter

This project demonstrates a simple 7-segment display counter from 0 to 9 using the 8051 microcontroller and displays each digit sequentially.

### Project Overview
  - Microcontroller: 8051
  - Software Used: Keil (Embedded C), Proteus (Simulation, PCB Design, 3D View)
  - Languages: Embedded C

### Components:-
  - 1} 7-Segment Display
  - 2} 8051 Microcontroller (AT89C51)


### Description

This project initializes a 7-segment display to show digits from 0 to 9 sequentially. The delay between each digit is achieved using a simple loop in embedded C.

### Code Explanation

  - seg[10] array holds hexadecimal values representing each digit (0–9) for a common cathode 7-segment display.
  - P1=0x00 configures Port 1 as an output.
  - A loop iterates through seg array values and outputs each digit, creating a counter.

### Circuit Diagram

  - Port 1 (P1) of the 8051 microcontroller is connected to the 7-segment display.
  - Proteus simulation shows the 7-segment display connected to the 8051 with correct pin mapping to display the digits.

### PCB and 3D Design

  - The PCB layout and 3D view in Proteus provide a physical representation of the 7-segment display connected to the 8051 microcontroller.

### Setup and Simulation
  - 1) Open the project in Keil and compile the code.
  - 2) Load the compiled hex file into the Proteus simulation.
  - 3) Run the simulation to observe the 7-segment display counting from 0 to 9.

### Files Included

  - Code: Embedded C code (main.c)
  - Proteus Files: Schematic, PCB design, and 3D view files.
  - Documentation: This README file for project explanation.

### Getting Started

  - 1) Clone this repository:

   https://github.com/VYANKATESHNAMDAS/7-segment-counter.git

  - 2) Open main.c in Keil, compile and simulate it.
  - 3) Use Proteus for schematic and PCB layout.
