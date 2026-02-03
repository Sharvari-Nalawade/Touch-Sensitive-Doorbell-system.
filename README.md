# Touch-Sensitive-Doorbell-system.
Touch Sensitive Doorbell System is a second-year engineering mini project demonstrating basic electronics and transistor switching. It uses human body conductivity to trigger a BC547 transistor, activating a DC buzzer and LED. The circuit is built on a breadboard using simple, low-cost components.

🔍 Project Overview

This project works on the principle of human body conductivity. When a user touches the sensing point, a small current is generated, which triggers a BC547 transistor. The transistor functions as both a switch and amplifier, allowing current to flow through the circuit and activate a DC buzzer and an LED. The buzzer provides an audible alert 🔔, while the LED indicates successful activation 💡.

The circuit is powered using a 9V battery and assembled on a breadboard using jumper wires, enabling easy prototyping, testing, and debugging 🧪. A 1 kΩ resistor is used to limit current and protect the transistor from damage ⚡.

Block Diagram

        ┌──────────────────┐
        │   Human Touch    │
        │  (Finger Input)  │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │  Touch Sensing   │
        │     Point        │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │  BC547 Transistor│
        │ (Switch & Ampl.) │
        └───────┬─────┬──-─┘
                │     │
                ▼     ▼
     ┌──────────────┐ ┌────────────┐
     │   DC Buzzer  │ │     LED    │
     │  (Sound Out) │ │(Indication)│
     └──────────────┘ └────────────┘

        ┌──────────────────┐
        │    9V Battery    │
        │   Power Supply   │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │ 1 kΩ Resistor    │
        │ (Current Limit)  │
        └────────┬─────────┘
                 │
                 ▼
        ┌──────────────────┐
        │  BC547 Transistor│
        └──────────────────┘


PROJECT IMAGES:
![WhatsApp Image 2025-11-08 at 9 54 29 AM](https://github.com/user-attachments/assets/61a2b0c1-0e35-4067-a058-d3fd091a24cf)
PROJECT WORKING VIDEO:


https://github.com/user-attachments/assets/168e69c9-aa11-4297-9e4c-fe745f99c9c1





PROJECT REPORT:
[043f31fa-203e-4adc-bc84-3728c7eb0980.docx](https://github.com/user-attachments/files/25046081/043f31fa-203e-4adc-bc84-3728c7eb0980.docx)

🧩 Components Used

1.BC547 Transistor

2. 1 kΩ Resistor

3. DC Buzzer

4. LED

5. 9V Battery

6. Battery Connector

7. Jumper Wires

8. Breadboard

🎯 Key Learnings

-Understanding of transistor switching and amplification

-Practical exposure to basic electronic circuit design

-Hands-on experience with breadboard-based prototyping

-Application of human body conductivity in real-world circuits

-Improved skills in testing, debugging, and component interfacing

-Familiarity with low-power electronic systems

🚀 Future Improvements

-Adjustable sensitivity control for better accuracy

-Protective enclosure for real-world deployment

-Integration with wireless or smart doorbell systems 📡

-Addition of power-saving features 🔋

-Expansion using microcontrollers or IoT modules
