# RFID-Based Door Lock System 🔒

An IoT-based smart door lock system using RFID technology and Arduino, designed for secure, contactless access control.

# Project Overview
This project demonstrates the implementation of a low-cost, Arduino-powered RFID door locking system. It uses the RFID-RC522 module to read RFID cards and controls a servo motor to lock/unlock the door. An LCD display provides real-time feedback for user interaction.

# Features
- RFID-based authentication
- Contactless, secure door unlocking
- Real-time LCD display feedback
- Auto-relocking after access
- Simple and scalable for homes, offices, or institutions

# Technologies & Tools
- Arduino Uno
- RFID-RC522 Reader
- SG90 Micro Servo Motor
- 16x2 LCD Display (I2C)
- Arduino IDE (C/C++)
- Circuit design tools: Cirkit Designer, EasyEDA

# How It Works
1. RFID tag is scanned by the reader.
2. The Arduino checks the UID against authorized tags.
3. If valid, the servo unlocks the door and LCD shows “Access Granted”.
4. After 5 seconds, the system auto-locks the door.
5. Invalid tags are denied access with a message.

# Contributors
- Sayam Rai
- Stuti Timilsina
- Sushant Chaudhary
- Chirag K.C.
- Siddartha Amatya

# Future Improvements
- Add database integration for dynamic card registration
- Include Wi-Fi for remote access control
- Enable multi-user access logs via cloud storage
# Gallery
<img width="656" height="469" alt="image" src="https://github.com/user-attachments/assets/c4a85415-88fa-4cfd-a68d-64cf86045259" />
<img width="638" height="481" alt="image" src="https://github.com/user-attachments/assets/bb97ff16-bca9-4d76-a63b-5aeaebf08122" />


