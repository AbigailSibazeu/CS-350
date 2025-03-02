# CS-350
CS350 Emerging System Architectures and Technologies - Portfolio Submission

Overview

This repository contains two projects completed as part of the CS350 course, demonstrating key concepts in emerging system architectures and technologies. The projects involve working with hardware interfaces, controlling devices using Python, and utilizing Raspberry Pi for real-world applications. These artifacts highlight my ability to implement hardware control software, analyze system architecture considerations, and recommend emerging technologies based on business requirements.

Projects

1. PWM Control using Raspberry Pi

Problem Solved: This project focuses on controlling the brightness of an LED using Pulse Width Modulation (PWM) on a Raspberry Pi. The goal was to smoothly adjust brightness by varying the duty cycle of a PWM signal.

Key Technologies: Raspberry Pi, GPIO, PWM, Python.

My Contributions: Implemented Python code to generate PWM signals, dynamically adjusting brightness levels.

Reflection: This project reinforced my understanding of hardware-level programming and real-time control mechanisms.

2. Serial Communication for Remote Light Control

Problem Solved: This project enables remote control of a light via serial commands. The system listens for ON or OFF commands and toggles a GPIO pin accordingly.

Key Technologies: Raspberry Pi, Serial Communication, GPIO, Python.

My Contributions: Developed a Python server to handle serial inputs and control the GPIO output accordingly.

Reflection: This project strengthened my skills in serial communication, hardware interaction, and real-time data handling.

Reflection Questions

What did you do particularly well?

I effectively implemented hardware control using Python and Raspberry Pi, ensuring smooth PWM adjustments and real-time serial communication. My code was structured, commented, and maintainable, allowing for future enhancements.

Where could you improve?

I could further optimize the serial communication project by incorporating error handling and security mechanisms to prevent unintended commands from being executed.

What tools and/or resources are you adding to your support network?

I relied on the Raspberry Pi GPIO documentation, online resources, and debugging tools like serial monitors. Moving forward, I plan to explore additional IoT frameworks to enhance my projects.

What skills from this project will be particularly transferable?

Hardware and software integration

Real-time system programming

Serial communication and remote device control

Optimized scripting for embedded systems

How did you make this project maintainable, readable, and adaptable?

I followed best coding practices, including:

Writing clear, modular, and well-commented code.

Structuring the repository with relevant files and documentation.

Ensuring the scripts can be easily modified for additional functionalities.

Repository Structure

|-- cs350Module2assignment/
|   |-- PARTONE.py  # PWM Control Script
|   |-- Milestone 1.docx  # Documentation
|   |-- project1 video.mp4  # Demo Video
|
|-- cs350Module3assignment/
|   |-- SerialLightsControl-Server.py  # Serial Control Script
|   |-- Milestone 2.docx  # Documentation
|   |-- Diagram.JPG  # System Diagram
|   |-- project2 video.mp4  # Demo Video

Submission

This repository serves as a portfolio artifact for CS350, showcasing my ability to develop interface software for hardware control and analyze hardware architecture considerations. The artifacts uploaded here demonstrate practical applications of emerging system technologies.
