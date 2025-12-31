# Voice-Gesture-Controlled-Virtual-Mouse-and-Volume-System
Voice &amp; Gesture Controlled Virtual Mouse and Volume System using Python, OpenCV, and MediaPipe. Control mouse movement, clicks, and system volume using hand gestures, activated through voice commands.

# 🖐️ Voice & Gesture Controlled Virtual Mouse

This project implements a **hands-free human–computer interaction system** that allows users to control **mouse movement, mouse clicks, and system volume** using **voice commands and hand gestures** through a webcam.

The system uses **speech recognition** to switch between modes and **computer vision** (MediaPipe Hands) to track finger positions in real time.

---

## 🚀 Features

- 🎙️ **Voice Control**
  - Say **"click"** → activates virtual mouse mode
  - Say **"volume"** → activates volume control mode

- 🖱️ **Virtual Mouse Mode**
  - Move cursor using **index finger**
  - Perform mouse click by bringing **thumb and index finger close**

- 🔊 **Volume Control Mode**
  - Increase volume when fingers move apart
  - Decrease volume when fingers move closer

- 📷 Real-time webcam tracking
- 🧠 No external hardware required

---

## 🛠️ Tech Stack

- **Python 3**
- **OpenCV** – video processing
- **MediaPipe** – hand landmark detection
- **SpeechRecognition** – voice command input
- **PyAutoGUI** – mouse & keyboard automation
- **Math** – gesture distance calculation

---

## 📂 Project Structure

├── main.py # Main application file
└── README.md # Project documentation

yaml
Copy code

---

## ⚙️ Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/virtual-mouse-voice-control.git
cd virtual-mouse-voice-control
Install dependencies

bash
Copy code
pip install opencv-python mediapipe pyautogui SpeechRecognition pyaudio
⚠️ If pyaudio fails on Windows, install the precompiled wheel.

▶️ How It Works
Run the script:

bash
Copy code
python main.py
Speak one of the commands:

"click" → Virtual Mouse Mode

"volume" → Volume Control Mode

Use hand gestures in front of the camera to control the system.

🧠 Gesture Logic
Action	Gesture
Cursor Move	Index finger movement
Mouse Click	Thumb & index finger close
Volume Up	Fingers apart
Volume Down	Fingers close

📌 Use Cases
Touch-free computer interaction

Accessibility solutions

AI & Computer Vision learning projects

Human–Machine Interface (HMI) demos

🔮 Future Improvements
Gesture smoothing & stability

Multi-hand support

GUI mode selector

Custom gesture mapping

Linux & macOS optimization

👤 Author
Arpit Baviskar
Robotics | AI | Computer Vision | Automation

📜 License
This project is open-source and available under the MIT License.
