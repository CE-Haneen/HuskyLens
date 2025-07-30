# HuskyLens Object Recognition Demo

## 📷 What is HuskyLens?
HuskyLens is an easy-to-use AI vision sensor powered by a built-in machine learning chip.  
It allows devices like Arduino to recognize:

- Objects  
- Faces  
- Colors  
- Tags  
- Lines  
- QR codes  

All without writing complex AI code!

##  What Can It Do?
Using HuskyLens, you can:
- Detect and label objects (e.g. bottle, chair, `diningtable`)
- Recognize and track faces
- Follow lines or shapes
- Scan barcodes or AprilTags
- Trigger actions when certain objects are seen

---

## 🛠 Example Use-Case
In this example:
- HuskyLens is connected to a microcontroller (e.g. Arduino)
- It recognizes objects like bottles and chairs
- Detected objects are labeled directly on the device screen
- The system can act based on what it sees (like move a robot or open a gate)

---

## 🔌 HuskyLens Ports

| Pin Label | Description         |
|-----------|---------------------|
| T       | TX (Transmit data)  |
| R       | RX (Receive data)   |
| +       | Power (5V)          |
| -       | Ground (GND)        |

Connect it via UART or I2C based on your setup.

---

## 🖼️] Sample Output
The screen on the HuskyLens shows real-time detection with bounding boxes and labels for recognized objects.
## Pic
![Image](https://github.com/user-attachments/assets/7dbb75e0-3c68-4456-aefe-9c1a0dadff77)
![Image](https://github.com/user-attachments/assets/e3260ffb-ba42-4bfc-b802-6bcd3d9d3a99)
![Image](https://github.com/user-attachments/assets/d680b129-c04d-4f21-96ea-0fa4a6d11e58)
