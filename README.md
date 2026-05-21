🔐 Smart Door Lock System (Arduino Project)

Smart Door Lock System is an embedded C++ project built using Arduino UNO.

It simulates a secure access control system using a keypad, servo motor, and LCD display, with multiple security layers and lockout protection.

✨ Features
🔢 Keypad-Based Access System

4x4 keypad used for secure PIN entry.

🔐 Password Authentication

Checks entered PIN against stored password for access control.

📟 LCD Real-Time Feedback

Displays system status, prompts, and messages on a 16x2 I2C LCD.

🔄 Servo Motor Door Control

Simulates locking and unlocking of a door mechanism.

🚨 Buzzer Alerts System

Provides sound feedback for correct and incorrect attempts.

🔴🟢🔵 LED Status Indicators

Visual feedback for system states (locked, unlocked, error).

⛔ Security Lockout System

Limits incorrect attempts and triggers temporary or permanent lock states.

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

Digital I/O (LEDs & Buzzer)

🎯 Purpose

This project simulates a real-world embedded security system using Arduino.

It demonstrates authentication, hardware interfacing, state control, and security logic in embedded systems.


🧠 System Logic

User enters a 4-digit PIN using keypad

Press * to submit password

If correct → servo unlocks door

If incorrect → attempt counter increases

After multiple failures → system lockout

Recovery password restores system access

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
