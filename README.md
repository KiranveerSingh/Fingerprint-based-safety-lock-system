# 🔐 Fingerprint-Based Door Lock System

## 📌 Project Overview
This project is a **biometric door lock system** using an **R307 fingerprint sensor**, **Arduino Uno**, and a **solenoid lock**. It provides secure, keyless access by allowing only authorized users to unlock the door using their fingerprint.

## 🛠️ Features
- Biometric fingerprint authentication
- Fingerprint enrollment and matching
- Solenoid-based electronic door lock
- Secure, keyless access control
- Simple, low-cost hardware setup
- Easy to expand and modify

## 🎯 Use Cases
- Home security systems
- Office/lab access control
- Hostel/room entry systems
- Secure lockers or cabinets

## 🧩 Components Used

| Component                        | Role                                                             |
|----------------------------------|------------------------------------------------------------------|
| Arduino Uno                      | Controls logic and sensor communication                          |
| R307 Fingerprint Sensor          | Captures and verifies fingerprints                               |
| Solenoid Lock                    | Electrically locks/unlocks the door                              |
| Relay Module / NPN Transistor    | Switches solenoid power safely via Arduino                       |
| Resistor (e.g., 220Ω/1kΩ)        | Limits current to protect components                             |
| Jumper Wires                     | Connects all components                                          |
| Power Supply (e.g., 12V Adapter) | Powers the Arduino and solenoid                                  |

## ⚙️ Working Principle
1. User enrolls their fingerprint into the sensor’s memory.
2. On placing a finger, the sensor compares it to stored templates.
3. If matched, Arduino activates the solenoid to unlock the door.
4. If unmatched, access is denied and the door remains locked.

## 💡 Future Scope
- Mobile app integration for remote access
- Multi-biometric (fingerprint + face/voice)
- IoT/cloud connectivity for logs and control
- Battery backup and tamper alerts

## 📁 File Structure
Fingerprint-Door-Lock-System/
│
├── Arduino_Code.ino        # Arduino code (enrollment + verification)
├── README.md               # Project documentation (intro, features, etc.)
├── images/                 # Store circuit diagrams or project photos
│   ├── circuit.png
│   └── working.jpg
└── Components_Table.docx   # (Optional, if you want a Word table)



## ✅ How to Use
1. Upload the Arduino sketch to your Arduino Uno.
2. Connect the components as shown in the wiring diagram.
3. Enroll fingerprints via the serial monitor.
4. Try unlocking with the enrolled fingerprint.

## 📷 Optional
Include wiring diagrams or circuit images in the `/images` folder and link them in the README.

## 📄 License
This project is open-source under the [MIT License](LICENSE).

---

**Built by [Kiranveer Singh]** for learning and real-world biometric access control.
