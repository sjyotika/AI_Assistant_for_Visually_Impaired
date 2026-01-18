# 👁️ AI Assistant for Visually Impaired Users  
### Real-Time Object Awareness & Audio Guidance

---

## 📌 Overview
This project is a **real-time AI assistant** designed to help **visually impaired users** better understand their immediate surroundings using **computer vision and audio feedback**.

The system uses a webcam to detect nearby objects and provides **simple, directional voice guidance** such as *“Person ahead”* or *“Obstacle on the left”*, helping users navigate indoor environments more safely and independently.

---

## 🎯 Problem Statement
Visually impaired individuals often face challenges in identifying:
- Nearby people
- Obstacles in their path
- Objects placed in unfamiliar environments

Most existing solutions are either expensive, hardware-dependent, or overwhelm users with excessive information instead of **actionable guidance**.

---

## 💡 Proposed Solution
This project provides a **lightweight, camera-based assistive system** that:
- Detects common objects in real time
- Understands their relative position (left / center / right)
- Prioritizes safety-critical information
- Communicates guidance through **clear audio instructions**

The system is designed to be **simple, explainable, and accessible**, running entirely on a standard laptop without specialized hardware.

---

## ⭐ Key Features
- ✅ Real-time object detection using a webcam  
- ✅ Directional awareness (left / center / right)  
- ✅ Proximity estimation using bounding box size  
- ✅ Priority-based object announcements  
- ✅ Offline text-to-speech guidance  
- ✅ CPU-only execution (no GPU required)  
- ✅ No dataset or model training needed  

---

## 🆕 Innovation & Uniqueness
Unlike traditional object detection demos that list everything visible, this system focuses on **usability and safety**:

- **Actionable guidance instead of object lists**
- **Priority-based speech to avoid information overload**
- **Explainable logic based on spatial reasoning**
- **Assistive-first design philosophy**

This makes the system practical for real-world assistive scenarios rather than just a technical demonstration.

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Object Detection:** YOLOv8 (pretrained, nano version)  
- **Video Processing:** OpenCV  
- **Numerical Computation:** NumPy  
- **Audio Output:** pyttsx3 (offline text-to-speech)  

---

## 🧠 System Workflow

Webcam Input  

↓  

Object Detection (YOLOv8)  

↓  

Bounding Box Analysis  

↓  

Relative Position & Priority Logic  

↓  

Audio Guidance to User  

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ai-visual-assistant.git
cd ai-visual-assistant
```
2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python main.py

📷 Ensure your webcam is enabled and accessible.

🧪 Testing & Validation

The system was tested in indoor environments with:

Objects placed on the left, right, and center

People approaching the camera

Multiple objects present simultaneously

The assistant prioritizes safety-relevant alerts and avoids repetitive announcements, ensuring a smooth and usable experience.

⚠️ Limitations

Designed primarily for indoor, short-range assistance

Performance depends on lighting and camera quality

Not a replacement for mobility aids or professional assistance

🚀 Future Improvements

Distance-based warning levels

Customizable voice speed and alert frequency

Support for outdoor environments

Mobile or wearable device integration

Emergency alert mode

🌍 Real-World Impact

Enhances independence for visually impaired users

Improves safety in unfamiliar environments

Provides an affordable assistive technology prototype

Demonstrates responsible and human-centered AI

📌 Conclusion

This project showcases how computer vision can be applied ethically and practically to assist real users. By focusing on clarity, priority, and usability, it demonstrates how AI systems can make meaningful real-world impact beyond accuracy metrics.

🙋 Author

Jyotika Satav

(Computer Vision / AI Enthusiast)
