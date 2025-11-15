#Gesture-Controlled Snake Game

This project combines computer vision and classic gaming by allowing players to control the Nokia Snake Game using hand gestures captured from a webcam.

📌 Features

Play the Snake game without a keyboard

Uses OpenCV to capture hand gestures

Real-time gesture detection for Up, Down, Left, Right

Smooth gameplay built with Pygame

Modular code with separate files for game logic and gesture control

📂 Project Structure
/project-folder
│
├── game_manager.py        # Main file connecting gesture controller + snake game
├── gesture_controller.py  # Handles webcam input and gesture detection
├── snake_core.py          # Snake game logic using pygame
├── requirements.txt       # Required dependencies
└── assets/                # Images, sounds (optional)

🛠️ Technologies Used

Python

OpenCV

MediaPipe (if used)

Pygame

▶️ How to Run

Install dependencies:

pip install -r requirements.txt


Run the game:

python game_manager.py


Allow webcam access and start playing with gestures.

🎮 Controls (Gestures)

Hand Up → Move Up

Hand Down → Move Down

Hand Left → Move Left

Hand Right → Move Right

🌟 Future Scope

Use in education for interactive learning

Hands-free smart home controls

Gesture-based robot or drone control

Applications in healthcare (touch-free systems)

Improve interaction in AR/VR environments

📧 Contact

For any feedback or improvements, please feel free to reach out.
