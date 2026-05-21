🔐 Smart Door Lock System (Arduino Project)

Smart Door Lock System is an embedded C++ project built using Arduino UNO. It simulates a secure access control system using a keypad, servo motor, and LCD display, with multiple security layers and lockout protection.

✨ Features

🔢 Keypad-Based Access System
4x4 keypad used for secure PIN entry.

🔐 Password Authentication
Checks entered PIN against stored password for access control.

📟 LCD Real-Time Feedback
Displays system status, prompts, and access messages on a 16x2 I2C LCD.

🔄 Servo Motor Door Control
Simulates locking and unlocking of a door mechanism.

🚨 Buzzer Alerts System
Provides sound feedback for successful and failed attempts.

🔴🟢🔵 LED Status Indicators
Visual feedback for system states (locked, unlocked, error).

⛔ Security Lockout System
Limits incorrect attempts and triggers temporary/permanent lock states.

🔑 Recovery Mode
Allows system reset using a recovery password after lockout.

⏳ Delay Protection Mechanism
Adds waiting time after repeated failed attempts.

🧰 Technologies Used
Arduino UNO
C++ (Embedded Programming)
Keypad Library
Servo Motor Library
I2C LCD Library (LiquidCrystal_I2C)
Digital I/O Control (LEDs & Buzzer)
🎯 Purpose

This project was developed to simulate a real-world embedded security system using Arduino.
It demonstrates concepts of authentication, state management, hardware interfacing, and basic cybersecurity logic in embedded systems.

🧠 System Logic
User enters a 4-digit PIN using keypad
Press * to submit password
If correct → door unlocks (servo rotates)
If incorrect → attempt counter increases
After multiple failures → system enters lockout mode
Recovery password can restore system access
🔑 Credentials
Main Password: 1899
Recovery Password: 0000
🧑‍💻 Team
Ahmed Ayman Ibrahim
Ahmed Khaled Ibrahim
Ahmed Tamer Mohamed
Hamza Ahmed Abdelhady
Mazen Mohamed Elsayed
Mohamed Mostafa Hamza
