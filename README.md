# Eye-Controlled Mouse

Control your mouse cursor using your eyes and blink to click, no hands needed. This fun little project uses your webcam to track facial landmarks in real-time and lets you interact with your system using just eye movements and blinks.

---

## Features

- Real-time **eye tracking** using a webcam  
- Moves the mouse cursor based on **iris position**  
- Detects **blinks to perform clicks**  
- Simple and intuitive — just run and go  

---

## Technologies Used

- **Python**
- **OpenCV** – for webcam access and image processing
- **MediaPipe** – for facial landmark and iris detection
- **PyAutoGUI** – for controlling the mouse on your screen

---

## How to Run

1. Make sure you have **Python 3.10** installed (MediaPipe doesn't support 3.11+).
2. Install the required packages:
   ```bash
   pip install opencv-python mediapipe pyautogui
````

3. Run the script:

   ```bash
   python "Eye Controlled Mouse.py"
   ```
4. Allow camera access. Look around to move the cursor. Blink to click.

---

##  What I Learned

* How to use **MediaPipe FaceMesh** for precise facial landmark detection
* How to map camera-based positions to **screen coordinates**
* Basics of **eye-based control systems** and **hands-free interaction**
* The power of combining simple tools to create something that feels magical

---

## Author

**Swasti Gupta**
Just a curious coder playing around with computer vision, automation, and fun side projects.

---
