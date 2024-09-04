## NodeRed (Medibox - Advanced Embedded Medication Management System)

This repository contains the code and Node-RED flow for Medibox, a smart medication management system enhanced with advanced features for optimal medicine storage. This project is a part of the EN2853: Embedded Systems and Applications course, designed to help users effectively manage their medication schedules and ensure safe storage of sensitive medicines.

### Key Features:
- **Light Intensity Monitoring**: Utilizes two Light Dependent Resistors (LDRs) to monitor light intensity, ensuring medicines sensitive to light are stored in optimal conditions.
- **Dynamic Shaded Sliding Window**: Controlled by a servo motor, the sliding window adjusts based on light intensity to regulate exposure, ensuring medicine safety.
- **Customizable Parameters**: Users can adjust the minimum angle and controlling factor for the sliding window based on specific medicine requirements via a Node-RED dashboard.
- **Real-Time Dashboard**: A Node-RED dashboard that displays real-time data of light intensity, motor angle adjustments, and customizable settings for different medicines.

### Technologies Used:
- ESP32
- Node-RED
- MQTT Protocol
- Wokwi Platform

This project enhances Medibox functionality and provides a user-friendly interface for better control of medicine storage and reminders.

