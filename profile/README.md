# Welcome to Attendora 🎉

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)
[![GitHub Stars](https://img.shields.io/github/stars/attendora?style=social)](https://github.com/attendora)

👋 Hi there! **Attendora** is an innovative attendance monitoring system designed to simplify and secure the process of tracking attendance in educational institutions. By leveraging cutting-edge technologies like **facial recognition**, **RFID**, and **IoT**, Attendora ensures a seamless, fraud-resistant, and scalable solution for attendance management.

---

## About Attendora 🌟

The **Attendora** project was born out of the need to address the inefficiencies and vulnerabilities of manual attendance systems. Traditional methods are prone to disturbances, fraud, and data compromise, making them unreliable and difficult to analyze. Attendora solves these challenges by providing a secure, automated, and scalable attendance monitoring system.

Our mission is to:
- **Simplify attendance tracking** with a seamless user experience.
- **Prevent fraud** using advanced biometric and RFID technologies.
- **Secure data** with end-to-end encryption and robust authentication mechanisms.

---

## Key Features 🚀

- **Seamless Check-in Process**: Effortless attendance tracking using facial recognition and RFID.
- **Fraud Prevention**: On-device detection and backend rechecks to ensure authenticity.
- **Scalable Infrastructure**: Supports over **1,000 devices per server** (1 CPU, 1GB RAM).
- **Secure Data Handling**: End-to-end TLS encryption, biometric authentication, and data encryption at rest.
- **Real-time Notifications**: Alerts for faulty attempts or fraudulent activities.
- **Administrative Actions**: Tools for administrators to manage and act on fraudulent activities.

---

## Tech Stack 🛠️

### Embedded Systems
- **ESP8266 & ESP32**: Powerful chips enabling network connectivity.
- **MFRC522**: Reliable RFID reader for attendance tracking.
- **OV2640**: Battle-tested camera for IoT applications and facial recognition.

### Backend
- **Node.js & Express**: For building scalable and modular APIs.
- **MARIADB**: For secure and efficient data storage.
- **FastAPI**: For high-performance backend services.
- **OPENCV & Tensorflow**: For Machine Learning.

### Frontend
- **Svelte & TypeScript**: For building a responsive and user-friendly dashboard.
- **TailwindCSS**: For modern and customizable UI components.

### Tools & Infrastructure
- **GitHub Workflows**: Automatically deploys backend and frontend code after each commit.
- **Public Reverse Proxy**: Ensures secure and reliable access to the system.
- **HDD Storage**: Economical cold storage for large datasets (e.g., 1.8TB for a typical school setup).

---

## How It Works 🔍

1. **Facial Recognition**: The system captures and verifies attendee identities using on-device AI and backend rechecks.
2. **RFID Integration**: Attendees can also check in using RFID cards for added convenience.
3. **Real-time Monitoring**: Administrators can track attendance in real-time through the Attendora dashboard.
4. **Fraud Detection**: The system flags and notifies administrators of any fraudulent attempts.
5. **Data Analysis**: Attendance data is securely stored and can be analyzed for insights.

---

## Storage needs Case Study: ENSAM Casablanca 🏫

- **Image Size**: 2MB
- **Class Size**: 90 students max
- **Number of Classes**: 25
- **Sessions per Week**: 12

### Storage Calculation
Using the formula:
size_video × size_class × num_classes × num_sessions × 32 (weeks studied)

Copy
The system requires approximately **1.8TB to 2TB** of storage, which can be handled using economical HDD disks.

---

## What Sets Us Apart ✨

- **AI-Powered Facial Recognition**: Ensures accurate and fraud-resistant attendance tracking.
- **Scalable Architecture**: Designed to handle large-scale deployments with ease.
- **Secure Infrastructure**: Built with industry-standard security measures to protect data and prevent unauthorized access.

---

## Get Involved 🤝

We welcome contributions from the community! Whether you're a developer, designer, or just someone with great ideas, there are many ways to get involved:

- **Contribute Code**: Check out our [Contributing Guidelines](CONTRIBUTING.md) to get started.
- **Report Issues**: Found a bug or have a feature request? Open an issue on the relevant repository.
- **Spread the Word**: Star our repositories and share them with your network!

---

## License 📜

All Attendora projects are open-source and licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the license terms.

---

## Contact Us 📧

Have questions or want to collaborate? Reach out to us:
- **Email**: [hello@attendora.com](mailto:hello@attendora.com)
- **Website**: [https://attendora.com](https://attendora.com)
- **Twitter**: [@AttendoraHQ](https://twitter.com/AttendoraHQ)

---

## Acknowledgments 🙏

We'd like to thank all our contributors, supporters, and the open-source community for helping us make Attendora a success. Special thanks to:
- **Prfessor BEN TARLA Lahssan** for his ideas and contributions.
- **Professor ZAZ Ghita** for her guidance and support.
- **H2U and Ensam Casa**

---

Made with ❤️ by **Attendora**. Let's revolutionize attendance monitoring together! 🚀