
# 🎮 ACE: AR Computer Vision Experience  

## Overview  
ACE: AR Computer Vision Experience is a **gesture-based gaming system** developed for **IKONIC 2k23**, a project expo at **Panimalar Engineering College**. Originally designed to integrate **Augmented Reality (AR)**, the project was adapted within the given time constraints to showcase **computer vision-based gesture controls** in a **Flappy Bird game built with Unity**.  

[![Watch the video](https://img.youtube.com/vi/EIRNBOqlXN0/0.jpg)](https://www.youtube.com/watch?v=EIRNBOqlXN0)  

🔗 [Watch the video on YouTube](https://www.youtube.com/watch?v=EIRNBOqlXN0)  

## 🎯 Project Concept  
The game replaces traditional keyboard input with **hand gestures**, specifically **thumb movement detection**, allowing players to control the Flappy Bird character through natural movements.  

### 🔥 Key Features  
- **🖐️ Gesture-Based Input** – Uses computer vision to track thumb positions for gameplay control.  
- **🎮 Flappy Bird in Unity** – A fun and interactive game environment built with **C# in Unity**.  
- **🧠 Computer Vision Integration** – Uses **Python + OpenCV** for real-time gesture detection.  
- **🔗 Socket Communication** – Connects OpenCV (Python) with Unity (C#) via sockets for seamless input transfer.  

## ⚙️ How It Works  
1. **Thumb Detection:** The system tracks the **position of the thumb** using OpenCV.  
2. **Game Controls:**  
   - **Thumb Up → Start the game**  
   - **Thumb Down → Triggers a jump (equivalent to pressing Spacebar)**  
3. **Socket Communication:** The detected input is **sent to Unity** via sockets, ensuring real-time responsiveness.  

## 🚀 Technologies Used  
- **Unity (C#)** – Game Development  
- **Python (OpenCV)** – Gesture Recognition  
- **Sockets (Python <-> C#)** – Data Communication  

## 📌 Lessons Learned  
- **Keeping it simple** – Starting with an **MVP approach** helped in timely implementation.  
- **Cross-language integration** – Learned to **connect Python (OpenCV) with Unity (C#)** using sockets.  
- **Real-time gesture tracking** – Explored the challenges of **computer vision-based controls in gaming**.  

## 📜 Disclaimer  
This project was developed for **educational purposes only** as part of IKONIC 2k23 at Panimalar Engineering College.  

---

🎮 **Bringing gesture-based interactions to classic games with Computer Vision & Unity!**  
