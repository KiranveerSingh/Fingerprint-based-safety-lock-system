# 🔧 How I Made the Fingerprint-Based Door Lock System

---

## 1. Project Idea and Component Collection
I started with the idea of a **biometric door lock system** and collected the essential components: an **Arduino Uno** as the brain, an **R307 fingerprint sensor** for authentication, and a **solenoid lock** to secure the door. I also gathered a **relay module** to safely switch power to the solenoid, as well as **jumper wires** and a **9-12V power supply**.

---

## 2. Circuit Design and Assembly
I designed the circuit connections as follows:
- The **R307 sensor** was connected to the Arduino Uno's RX, TX, VCC, and GND pins.
- The **relay module** was connected to a digital pin on the Arduino to control it.
- The **solenoid lock** was connected to the output of the relay, allowing the Arduino to switch its power on and off.
- The entire system was powered by a **9-12V adapter**, which was connected to the Arduino's power jack.

---

## 3. Code Development and Testing
I created two separate Arduino sketches to handle the system's functionality:
- **`enrollment.ino`**: This code was used to register and store new fingerprints in the sensor's memory. I uploaded it and registered several authorized fingerprints.
- **`detection.ino`**: This code was uploaded next. It was responsible for verifying fingerprints and controlling the solenoid lock. I tested it with authorized fingers to confirm the lock would open, and with unauthorized fingers to ensure access was denied.

---

## 4. Hardware Assembly and Documentation
I physically assembled the project by mounting the **Arduino**, **relay**, and **fingerprint sensor** on a wooden structure. The **solenoid lock** was also mounted to the structure for demonstration. I made sure to document my work by organizing the files and creating a **GitHub repository**. I added a `README.md` file with a project overview and a `LICENSE` file to define the usage rights. Finally, I uploaded all the code and images of the circuit and prototype to the repository.

---

## 5. Final Validation
I performed a final round of testing with different fingerprints to validate the system's security and reliability. The successful demonstration confirmed the project was complete and fully functional.