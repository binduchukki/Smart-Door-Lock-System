# 🔐 Smart Door Lock System using Arduino

## 📌 Description
This project is a **Smart Door Lock System** built using Arduino to enhance security by allowing access only to authorized users. The system uses a **password (keypad) or RFID card** for authentication and controls a **servo motor or solenoid lock** to open/close the door.

---

## 🔧 Features
- 🔐 Secure access using password or RFID  
- 🔘 Keypad input for password entry  
- 📟 LCD display for status messages  
- 🔊 Buzzer alert for wrong attempts  
- 🔁 Automatic locking after access  
- 🚫 Unauthorized access prevention  

---

## 🧰 Components Used
- Arduino Uno  
- Keypad (4x4) / RFID Module  
- Servo Motor / Solenoid Lock  
- LCD 16x2 (I2C optional)  
- Buzzer  
- LEDs (optional)  
- Resistors  
- Breadboard  
- Jumper Wires  

---

## ⚙️ Working Principle
1. User enters a password using the keypad (or scans RFID card)  
2. Arduino verifies the entered password with the stored data  
3. If correct:
   - Door unlocks using servo/lock  
   - LCD displays "Access Granted"  
4. If incorrect:
   - Access is denied  
   - Buzzer alert is triggered  
5. After a few seconds, the door automatically locks again  

---

## 🔌 Circuit Diagram
<img width="977" height="591" alt="image" src="https://github.com/user-attachments/assets/9d58ce5a-7f13-4274-947b-629a8b1e444a" />

Downloaded from https://wokwi.com/

Simulate this project on https://wokwi.com

