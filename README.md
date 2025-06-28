# Parallel Detector Quality Control System

## Overview
This is a real-time industrial vision-based quality control system designed for detecting defects on pallet production lines. The system integrates PLC-controlled relay hardware, multi-camera vision setups, and custom backend software with a GUI for live monitoring and defect logging.

*Note: Source code is not shared due to intellectual property and company confidentiality.*

---

## Key Features
- Parallel multi-camera detection (hardware-triggered and timed cameras)
- Real-time YOLO-based defect detection (nail detection and board alignment)
- Custom GUI built with PySide6 for live visualization and control
- Relay control via serial port for defect handling
- Integrated fault history database with filtering and CSV export
- Camera recovery logic and robust error handling
- GPU and CPU compatible

---

## System Architecture

![Nails_image](https://github.com/user-attachments/assets/ad39508f-dca3-4df2-b568-018112d82615)


![Stringer-topboard-alignemnt-measurement](https://github.com/user-attachments/assets/d0af541b-5bd4-4a47-9c22-8f210f88f5e0)

---

## Technologies Used
- **Programming Languages:** Python
- **Frameworks:** PySide6 (GUI), PyTorch (YOLO Integration)
- **Database:** SQLite
- **Hardware:** Industrial cameras (Basler), PLC-controlled camera control and fault output logic (Siemens S7-1200 PLC)
- **Vision:** YOLO model integration for object detection

---

## Key Functionalities
- **Camera Control:**
  - Hardware-triggered and timed camera support
  - Automatic camera detection and management
- **Defect Detection:**
  - Board alignment measurement (pixel-to-mm conversion)
  - Nail detection with configurable confidence thresholds
- **Relay Hardware Integration:**
  - Serial communication with relay controller
  - Automatic defect-triggered relay switching
- **Fault Management:**
  - Fault history dashboard with filtering by date/type
  - CSV export and fault deletion features

---

## Demo
*(Optional: Insert YouTube unlisted video link here)*

If you would like to see the system in action, please contat me for a demo.

---

## Project Status
✅ Fully operational on a live production line  
✅ Successfully deployed and actively used for pallet quality control  

---

## Contact
For more information, feel free to reach out:
- 📧 sampsmith1998@gmail.com
- 💼 [Your LinkedIn](https://www.linkedin.com/in/sam-smith-0422aa356/)

---

## Notes
- Source code and full implementation are protected due to company and IP restrictions.
- Detailed case studies available upon request.

