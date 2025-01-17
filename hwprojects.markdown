---
layout: post
title: Hardware Coursework
subtitle: My Hardware Experience
permalink: /hwprojects/
---

## **ECE‐UY 2004: Fundamentals of Electric Circuits**

**Grade:** A

**Topics Learned:**

- RC/RL Circuits & Transient Measurements
- Nodal / Mesh Analysis
- Ohm’s Law & Kirchhoff’s Laws
- Thevenin / Norton equivalent circuits

**Lab Work:**

- Designed and built analog circuits using resistors, capacitors, and inductors
- Hands-on experience with oscilloscopes (Digilent Analog Discovery 2), logic analyzer, multimeters, and signal generators
- Analyzed circuit behavior under varying frequencies and load conditions

![code1](../assets/image.png){: style="width: 100%;" :}

*Transient Response of the Capacitor when the Resistance of the Potentiometer is 0 ꭥ*

![code1](../assets/image (1).png){: style="width: 100%;" :}

*Transient Response of the Capacitor when the Potentiometer is at ¼ turn*

## **ECE/CS 2204: Digital Logic and State Machine Design**

**Grade:** A

**Topics Learned:**

- Combinational and sequential circuit design, state machines
- Verilog HDL and logic synthesis
- PLA, PAL, FPGA
- Latches & Flip-Flops Storage Devices

**Lab Work:**

- Implemented digital circuits on FPGA boards using ModelSim and Xilinx Vivado
- Built Verilog model of a Serial Adder as a Finite State Machine
- Learned how to validate FSM performance using a Verilog testbench

![code1](../assets/image (2).png){: style="width: 100%;" :}

*Verilog Code for a 16-bit Adder*


![code1](../assets/image (3).png){: style="width: 100%;" :}


*The Simulated Waveform of the 16-bit Adder*

<iframe width="471" height="838" src="https://www.youtube.com/embed/3MRbYeDaeF8" title="Zack Nguyen - lab4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


*4-bit 2’s Complement Adder on 7-Segment Display*


![code1](../assets/image (4).png){: style="width: 100%;" :}


*Waveform for 3-bit Ripple Counter*


| State | Input at State | Input |  | Output |
| --- | --- | --- | --- | --- |
|  |  | X = 0 | X = 1 |  |
| Sempty | ___ | S0 | S1 | 0 |
| S0 | 0000 | S0 | S2 |  |
| S1 | ___1 | S3 | S1 | 0 |
| S2 | __01 | S4 | S5 | 0 |
| S3 | __10 | S3 | S6 | 0 |
| S4 | _010 | SEnd | S6 | 0 |
| S5 | _011 | SEnd | S1 | 0 |
| S6 | _101 | S4 | SEnd | 0 |
| SEnd |  | SEmpty | SEmpty | 1 |

*FDM State Table for detecting 4-bit patterns (1011, 0110, 0100)*

![code1](../assets/image (5).png){: style="width: 100%;" :}


*Waveform of Test-bench Simulation*

## **ECE4144: Intro to Embedded Systems**

**Grade:** A

**Topics Learned:**

- Programming the Atmega32u4 using ANSI C and Arduino Framework
- Bidirectional communication between microcontrollers using UART Serial Communication and Interrupt Subroutines
- Building an Analog-to-Digital Converter (ADC) using Pulse-Width-Modulation (PWM)
- Differences and use-cases for Fast PWM and Phase-Correct PWM
- Pin multiplexing (Pin Muxing) in  ATmega32U4 microcontroller for GPIO
- DSP - Moving Average, IIR, and FIR filters
- Synchronous and Asynchronous communication protocols (UART and I2C)
- Configuring timers on the 32U4 processor by modifying timers’ registers using Atmel datasheet

**Lab Work:**


![code1](../assets/image.gif){: style="width: 100%;" :}


*When percentage (potentiometer) is between 0% and 33% (Only 1 (red) LED lights up)*


![code1](../assets/image (1).gif){: style="width: 100%;" :}


*When percentage (potentiometer) is between 33% and 66% (2 LEDs light up)*


![code1](../assets/image (6).png){: style="width: 100%;" :}

*Decoding a sine wave encoded inside a PWM signal using RC Low Pass Filter*


![code1](../assets/image (7).png){: style="width: 100%;" :}



![code1](../assets/image (8).png){: style="width: 100%;" :}


![code1](../assets/image (9).png){: style="width: 100%;" :}

*Controlling the frequency with the potentiometer*

## **ECE-UY-3114: Solid State Electronic Devices and Circuits I**

**Grade:** A

**Topics Learned:**

- Operational Amplifiers, Frequency Response, and Applications
- Diodes and Rectifiers
- PN Junction (with Applied Voltage & Capacitive Effects)
- Bipolar junction transistor (BJT), NPN and PNP analysis
- Field-Effect Transistors (FET and MOSFET)
- General Charge Concentration Analysis

**Lab Work:**

![code1](../assets/image (10).png){: style="width: 49%;" :}
![code2](../assets/image (11).png){: style="float:left; width: 49%;" :}

{: style="margin: 0rem;" :}
{: style="clear:both;" :}

*Circuit Diagram For Measuring IV Characteristics & Breadboard Circuit For Current to Voltage Conversion*


![code1](../assets/image (12).png){: style="width: 100%;" :}


*IV Characteristic of the General-Purpose 1N4003 Diode*


![code1](../assets/image (13).png){: style="width: 100%;" :}

 *Input Signal and Signal Through Zener Diode*


![code1](../assets/image (14).png){: style="width: 100%;" :}


*Half-Wave Rectifier With Capacitive Filtering (100 F)*


![code1](../assets/image (15).png){: style="width: 100%;" :}

*Two Half-Wave Rectifiers with  Offset*


![code1](../assets/image (16).png){: style="width: 100%;" :}

*Full-Wave Rectifier with Capacitive Filtration (10 uF capacitor)*

![code1](../assets/image (17).png){: style="width: 100%;" :}

*MOSFET Transfer Characteristic Gate Voltage and Drain Current Relationship*
