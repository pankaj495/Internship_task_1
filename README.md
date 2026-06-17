1 Objective
 The objective of this project is to design and simulate a Smart Temperature Monitoring
System using Arduino UNO and a TMP36 temperature sensor. The system continuously
monitors ambient temperature and provides visual indications using LEDs.

2 Introduction to Embedded Systems
 An embedded system is a specialized computer system designed to perform a dedicated
function within a larger system. These systems combine hardware and software to per
form real-time operations efficiently.
Examples
• Washing Machine
• Microwave Oven
• Smart Watch
• Traffic Light Controller
• Smart Home Devices

3 Applications of Embedded Systems
 • Smart Home Automation
 • Automotive Systems
 • Healthcare Devices
 • Robotics
 • Industrial Automation
 • Internet of Things (IoT)
 
4 Microcontroller vs Microprocessor
 Microcontroller
CPU, RAMandROMonasingle
chip
Microprocessor
Primarily CPU only
Low power consumption
Used in embedded systems
Higher power consumption
Used in computers
Cost effective
More expensive
3

5 Component Study
 5.1 Arduino UNO
Arduino UNO is a microcontroller development board based on the ATmega328P micro
controller. It is easy to program and widely used in embedded system projects.
 5.2 ESP32
ESP32 is a powerful microcontroller with built-in Wi-Fi and Bluetooth connectivity. It
is commonly used in IoT applications.
 5.3 Raspberry Pi Pico
Raspberry Pi Pico is a low-cost microcontroller board based on the RP2040 chip.
 5.4 Sensors Used
• Temperature Sensor (TMP36): Measures ambient temperature and provides analog
output proportional to temperature.
• Motion Sensor (PIR): Detects motion and human presence.
• Light Sensor (LDR): Measures light intensity.

6 Project Description
 Project Name: Smart Temperature Monitoring System
Components Used
• Arduino UNO
• TMP36 Temperature Sensor
• Green LED
• Yellow LED
• Red LED
• Resistors
• Breadboard
• Connecting Wires
4
Working Principle
The TMP36 temperature sensor continuously measures the surrounding temperature and
sends analog signals to Arduino UNO through Analog Pin A0.
The Arduino compares the measured temperature with predefined ranges:
• Below 25°C → Green LED ON
• 25°C to 35°C → Yellow LED ON
• Above 35°C → Red LED ON
This provides real-time visual monitoring of temperature conditions.
