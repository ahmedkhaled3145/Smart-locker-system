🔐 Arduino Smart Door Lock System

A password-protected smart door lock system built using Arduino UNO. The project uses a keypad for PIN entry, a servo motor to simulate door locking/unlocking, and an LCD display for user feedback. It also includes security features like attempt limiting and system lockout.

🚀 Features
🔢 4x4 Keypad password input system
🔐 Secure PIN authentication
🔄 Servo motor-based lock/unlock mechanism
📟 Real-time LCD feedback (I2C 16x2 display)
🚨 Buzzer alerts for wrong attempts
🔴🟢🔵 LED status indicators
⛔ Attempt limitation system (security lockout mode)
🔑 Recovery password system to reset lockout
⏳ Temporary delay after multiple failed attempts
🧰 Hardware Requirements
Arduino UNO
4x4 Keypad module
Servo motor
LCD 16x2 with I2C module
Buzzer
LEDs (Red, Green, Blue)
Resistors & jumper wires
Breadboard
⚙️ How It Works
User enters a 4-digit PIN using the keypad
Press * to submit the password
If correct:
Servo unlocks the door
Green LED turns ON
LCD shows success message
If incorrect:
Red LED + buzzer alert
Attempts are counted
After multiple failed attempts:
System enters lockout mode
Requires recovery password to reset
🔑 Passwords
Main Password: 1899
Recovery Password: 0000
🧑‍💻 Contributors
Ahmed Ayman Ibrahim
Ahmed Khaled Ibrahim
Ahmed Tamer Mohamed
Hamza Ahmed Abdelhady
Mazen Mohamed Elsayed
Mohamed Mostafa Hamza
📌 Author
Project developed by the team above
Embedded Systems / Arduino Project
