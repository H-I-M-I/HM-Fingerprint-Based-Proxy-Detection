# HM_Fingerprint-Based Proxy Detection

This project is a **microprocessor and microcontroller** system designed to detect proxy attendance using fingerprint recognition. The system utilizes the **ESP8266 microcontroller** and **Arduino Uno** to implement both wired and wireless configurations. In the wireless setup, fingerprint enrollments from multiple devices are registered on a central computer. Data is managed via Firebase.

## Project Structure

The project folder contains the following subfolders:

- **Firebase-Backend**: Responsible for managing the connection to Firebase, where attendance data is stored and retrieved in real-time.
  
- **Connect-to-Arduino**: Contains Java programs that establish communication between the ESP8266/Arduino and the fingerprint sensor, and manage the connection with Firebase.
  
- **Fingerprint-Enrollment**: Manages the fingerprint enrollment process, allowing new users to be registered in the system.

## Setup Instructions

1. The repository should be cloned to a local machine.
2. The Java code from the `connect-to-arduino` folder is uploaded to the ESP8266/Arduino.
3. Firebase is configured following the instructions in the `Firebase-backend` folder.
4. The `fingerprint-enrollment` program is used to enroll fingerprints and link them to user profiles.

## Tools & Technologies Used

- **Microprocessor & Microcontroller: Arduino Uno, ESP8266**
- **Fingerprint Sensor**
- **Firebase (for backend)**
- **Java**

