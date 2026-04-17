# IoT-Prototype-Architect
An AI-powered web application built on AWS PartyRock to help engineers architect IoT systems by generating sensor lists and wiring guides for microcontrollers like the ESP32.
Project Overview
The IoT Prototype Architect is a specialized AI application built on the AWS PartyRock platform. It serves as a technical bridge for engineers, moving from a conceptual "Smart System" idea to a concrete hardware architecture and wiring plan.

Key Features
Dynamic Hardware Context: Users can specify microcontrollers like the ESP32, allowing the AI to tailor pin assignments and protocol suggestions (I2C/SPI) to the specific board's architecture.

Intelligent Component Mapping: By inputting a system goal—such as an "Automated Incubator"—the app utilizes custom prompt logic to generate a specialized Sensor List (including components like the CCS811 for gas monitoring).

Project-to-Implementation Workflow: The app provides technical descriptions for each component, ensuring the user understands the role of each sensor in the larger IoT ecosystem.

Technical Implementation
This app exceeds basic chatbot functionality by utilizing a multi-widget architecture:

Input Widget ("A Smart System"): Captures user requirements.

Input Widget ("Hardware Choice"): Establishes physical constraints.

AI Output Widget ("Sensor List"): Merges the two inputs using prompt engineering to deliver a technical specification.

Live Demo
Explore the interactive application here: https://partyrock.aws/u/tulsi23/swk_iidog/IoT-Prototype-Architect
