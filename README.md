# Gesture Controlled Gaming Console 🎮✋

This project demonstrates a real-time gesture recognition system that allows users to control a game using body movements, eliminating the need for physical input devices. Built using **OpenCV**, **MediaPipe**, and **PyAutoGUI**, the system offers an intuitive, accessible, and immersive gaming experience using just a standard webcam.

## 🔧 Technologies Used

- **Python 3**
- **OpenCV** – for image/video processing
- **MediaPipe** – for pose and landmark detection
- **PyAutoGUI** – to simulate keyboard input
- **NumPy** – numerical operations

## 🧠 How It Works

1. Captures live video using your webcam.
2. Detects body pose using MediaPipe Pose.
3. Calculates joint angles and hand positions.
4. Classifies gestures like:
   - **Hands Joined** → Start game or press "Space"
   - **Jumping / Crouching** → Move up/down
   - **Lean Left / Right** → Move left/right
5. Simulates key presses using PyAutoGUI to control the game.

## 📸 Key Gestures

| Gesture         | Action        |
|----------------|---------------|
| Hands Joined    | Start / Jump  |
| Standing        | Idle          |
| Crouch          | Down Arrow    |
| Jump            | Up Arrow      |
| Slide Left      | Left Arrow    |
| Slide Right     | Right Arrow   |

## 📁 Folder Structure

```

📦GestureControlledGame
┣ 📜main.py               # Main program
┣ 📜README.md             # This file
┣ 📜requirements.txt      # Required packages

````

## 🖥️ Demo

Here’s a snapshot of the system in action:
- Recognizes standing, jumping, crouching, and side movements.
- Smooth and responsive under varied lighting conditions.

![image](https://github.com/user-attachments/assets/ac123969-e079-4929-896e-1ad44582b633)

![image](https://github.com/user-attachments/assets/a00af3de-b524-4432-bfb4-01f59c4a95a0)

![image](https://github.com/user-attachments/assets/8a270b2e-3735-48c9-a980-d3882f4dbf91)

![image](https://github.com/user-attachments/assets/d786e007-c2c9-4704-8482-798689220ec6)

![image](https://github.com/user-attachments/assets/9694fdef-1db7-4a7b-8276-3b1b8496c67c)


## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Webcam

### Installation

1. Terminal:
    ```bash
    pip install virtualenv
    python.exe -m pip install --upgrade pip
    vitualenv game_en
   ```   

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the game controller:

   ```bash
   .\game_env\Scripts\activate
   python main.py
   ```

## 📌 Applications

* Touchless gaming
* Interactive learning environments
* Accessibility for physically challenged users
* Gesture-based virtual controls

