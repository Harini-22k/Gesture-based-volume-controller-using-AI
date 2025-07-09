# Gesture-Based Volume Controller using AI

This project is an **AI-powered gesture-based volume control system** that allows users to control their computer’s audio volume using simple **hand gestures captured through a webcam**. The system leverages **computer vision** and **machine learning techniques** to detect hand landmarks in real-time and map finger movements to control the volume level without any physical contact.

It is built using **Python** along with popular libraries such as **OpenCV** for image processing, **MediaPipe** for hand tracking and landmark detection, and **Pycaw** for controlling the system's audio. This project demonstrates how artificial intelligence and computer vision can be used to create **hands-free, interactive, and intuitive human-computer interactions**.

---

##  Key Highlights:

 **Real-Time Hand Detection**: Uses MediaPipe to detect hand landmarks instantly.
 **Gesture Measurement**: Calculates the distance between thumb and index finger.
 **Volume Control**: Maps the gesture distance to system volume using Pycaw.
 **Visual Feedback**: Displays helpful on-screen graphics including finger markers, lines, and volume bars.
 **Fast and Efficient**: Runs smoothly on most standard laptops and webcams.

---

##  Technologies Used:

* Python 
* OpenCV 
* MediaPipe 
* Pycaw 

---

## How It Works:

1. The webcam captures video frames in real time.
2. MediaPipe processes these frames to detect the hand and its key landmarks.
3. The distance between the **thumb tip** and **index finger tip** is calculated.
4. This distance is mapped to control the system's audio volume.
5. Visual feedback (circles, lines, volume bar) is drawn to assist the user.

---


1. **Install required libraries:**

```bash
pip install -r requirements.txt
```

2. **Run the script:**

```bash
python gesture_volume_control.py
```

 Ensure that your webcam is connected and accessible.

---

##  Demo
![Screenshot 2025-07-09 101442](https://github.com/user-attachments/assets/c56271cd-9643-45d5-9e96-f3905804bb7e)

---

##  Use Cases

* Hands-free volume control while working, gaming, cooking, or exercising.
* Accessible technology for people with limited mobility.
* AI and computer vision demonstrations or educational projects.

