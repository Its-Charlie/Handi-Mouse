# Handi-Mouse: AI-Based Gesture Control System

Handi-Mouse is a real-time, computer vision-driven system that allows users to control their computer's mouse and execution commands using natural hand gestures. By leveraging **Python**, **OpenCV**, and **MediaPipe**, the application maps complex tracking coordinates to system-level inputs using **PyAutoGUI**, entirely eliminating the need for physical hardware peripherals.

---

## 🚀 Demo Video
https://github.com/user-attachments/assets/YOUR-VIDEO-LINK-HERE

---

## ✨ Features & Gesture Map

The application differentiates between your **Left** and **Right** hand to offer a full range of desktop functionalities seamlessly.

### 🛑 Right Hand (Navigation & Editing)
* **Cursor Movement:** Simply move your right hand. The cursor utilizes an exponential smoothing algorithm ($0.75$) to reduce trembling and keep motion fluid.
* **Right Click:** Pinch your **Thumb + Index finger** together.
* **Scroll Mode:** Pinch your **Thumb + Middle finger**. Drag up or down to scroll documents or webpages dynamically.
* **Text Selection (Click & Drag):** Pinch your **Thumb + Ring finger** to engage a mouse-down state; release to finish selecting text.
* **Copy (Ctrl + C):** Pinch your **Thumb + Pinky finger**.
* **Paste (Ctrl + V):** Pinch your **Thumb + Index + Middle fingers** simultaneously.

### 👈 Left Hand (Execution & Sizing)
* **Left Click:** Pinch your **Thumb + Index finger** together.
* **Zoom Control:** Pinch your **Thumb + Middle finger** together. Moving your hand upwards zooms in (`Ctrl + +`), while moving downwards zooms out (`Ctrl + -`).

---

## 📸 System Interface

| Tracking Feed & Live Status Overlay |
| :---: |
| ![Handi-Mouse Interface](images/interface_demo.png) |

---

## 🛠️ Installation & Setup

Ensure you have Python installed on your machine. Then, follow these steps to set up Handi-Mouse locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR-USERNAME/Handi-Mouse.git](https://github.com/YOUR-USERNAME/Handi-Mouse.git)
cd Handi-Mouse
