# 🔥 Fire Detection and Alerting System

## 📝 Overview

This project is a **Fire Detection and Alerting System** developed at **Neil Gogte Institute of Technology**, Hyderabad. It uses real-time video from a camera to detect fire via the **Haar Cascade Classifier** algorithm. Upon detection, it plays an alarm sound and sends WhatsApp alerts to designated recipients (e.g., property owner, fire station) using the **Rapiwha API**.

The system aims to reduce fire-related damage and casualties through early detection and cost-efficient implementation.

---

## ✨ Features

- **Real-Time Fire Detection**: Detects fire in live video using Haar Cascade Classifier.
- **Alarm System**: Plays an alert sound to prompt evacuation.
- **Automated Alerts**: Sends WhatsApp messages via Rapiwha API.
- **User Interface**: Displays video with a blue rectangle highlighting fire regions.

---

## 🖥️ Prerequisites

### ✅ Software Requirements

- **Operating System**: Windows 7 or higher
- **Python**: Version 3.x
- **Rapiwha Account**: For WhatsApp alerts (see [Rapiwha Setup](#📲-rapiwha-setup))

### ✅ Hardware Requirements

- **Processor**: Intel Pentium i3 Core or better (min 2.9 GHz)
- **RAM**: 4 GB (minimum)
- **Hard Disk**: 8 GB free space (minimum)
- **Camera**: Webcam or external camera

### ✅ Python Libraries

Install the required libraries using pip:

```bash
pip install playsound
pip install opencv-python
pip install opencv-contrib-python
pip install requests

```
---
## 📲 Rapiwha Setup

- **Create a Rapiwha Account**
    - Sign up at https://www.rapiwha.com.

     - Refer to the included Linking Rapiwha (For Sending WhatsApp API).pdf for setup instructions.

- **Obtain API Key**
    - Generate your API key from the Rapiwha API section.

- **Update Code**
    - Replace the apikey in querystring with your key. Also update the number and text fields.

---

## 🔭 Future Scope

- Integrate faster object detection algorithms (e.g., YOLO, SSD).
- Extend to detect smoke, gas leaks, or other hazards.
- Combine with IoT-based sprinkler/fire suppression systems.
- Develop a mobile application for real-time remote monitoring.

---

