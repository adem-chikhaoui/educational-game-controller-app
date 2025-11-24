<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Educational%20Game&fontSize=60&fontColor=fff&animation=twinkling&fontAlignY=32" width="100%"/>
</div>

<div align="center">

## 🎮 2D Game with Custom Arduino Controller

[![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![SDL2](https://img.shields.io/badge/SDL2-FF6F00?style=for-the-badge)](https://www.libsdl.org/)
[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)

**Educational gaming experience with physical controller about mythology and history**

[Features](#-key-features) • [Tech Stack](#️-tech-stack) • [Installation](#-quick-start) • [Hardware](#-hardware-setup)

</div>

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## 📋 About

<img align="right" width="350" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" alt="Gaming">

An **educational 2D game** that combines software and hardware for an immersive learning experience. Players explore Greek and Roman mythology through interactive gameplay while using a custom-built Arduino controller.

**Why this project?**

Learning through gaming is proven to be more effective. By adding a physical controller, we create a hands-on experience that makes education fun and memorable.

<br clear="both">

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## ✨ Key Features

<table>
<tr>
<td width="50%">

### 🎮 Game Features
- 2D side-scrolling gameplay
- Multiple levels with progressive difficulty
- Mythology-themed puzzles & quizzes
- Score system & achievements
- Save/Load game progress

</td>
<td width="50%">

### 🕹️ Arduino Controller
- Physical buttons & joystick
- LED visual feedback
- Vibration motor haptics
- USB plug-and-play
- Keyboard fallback support

</td>
</tr>
</table>

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## 🛠️ Tech Stack

<div align="center">

**Software**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SDL2](https://img.shields.io/badge/SDL2-FF6F00?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Hardware**

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

</div>

**Libraries:** SDL2 • SDL2_image • SDL2_ttf • SDL2_mixer • Serial Communication

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## 🚀 Quick Start

### Prerequisites
Linux (Ubuntu/Debian)
sudo apt-get install build-essential libsdl2-dev libsdl2-image-dev
sudo apt-get install libsdl2-ttf-dev libsdl2-mixer-dev

macOS (Homebrew)
brew install sdl2 sdl2_image sdl2_ttf sdl2_mixer

Arduino IDE for controller
text

### Installation

Clone the repository
git clone https://github.com/adem-chikhaoui/educational-game-controller-app.git
cd educational-game-controller-app

Compile the game
make

Upload Arduino code (optional)
Open arduino/controller.ino in Arduino IDE and upload
Run the game
./game

text

### Controls
**Arduino Controller:** Joystick (Move) • Button A (Jump) • Button B (Action) • Button C (Pause)  
**Keyboard Fallback:** Arrow Keys (Move) • Space (Jump) • Enter (Action) • Esc (Pause)

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## 🔌 Hardware Setup

### Components Needed
- 1x Arduino Uno/Mega
- 1x Analog Joystick Module
- 3x Push Buttons
- 3x LEDs (RGB)
- 1x Vibration Motor
- Resistors & Jumper Wires

### Pin Configuration
Arduino Connections:
├── A0, A1: Joystick (X, Y)
├── D2-D4: Buttons (A, B, C)
├── D5-D7: LEDs (Red, Green, Blue)
└── D9: Vibration Motor (PWM)

text

> 📐 Detailed wiring diagram available in `/hardware/schematic.png`

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## 📸 Demo

> 🚧 **Gameplay screenshots and video coming soon**

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/adem-chikhaoui/educational-game-controller-app/issues).

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

<br>

## 📬 Contact

**Adem Chikhaoui** - Computer Engineering Student @ ESPRIT

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adem-chikhaoui-aa0840371)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ademchikhaoui105@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adem-chikhaoui)

**Project Link:** [https://github.com/adem-chikhaoui/educational-game-controller-app](https://github.com/adem-chikhaoui/educational-game-controller-app)

<br>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>
</div>

<div align="center">
  
  **⭐ Star this repository if you enjoyed the game! ⭐**
  
</div>
