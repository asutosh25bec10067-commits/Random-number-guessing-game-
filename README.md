# Number Guess Challenge 🎲

A simple, interactive Desktop GUI game built with Python and Tkinter. Test your luck and logic by guessing a secret number between 1 and 50 before you run out of chances!

## 📋 Table of Contents
- [About the Game](#about-the-game)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [How to Play](#how-to-play)
- [Code Structure](#code-structure)

## 🧐 About the Game
The **Number Guess Challenge** generates a random number between 1 and 50. The player starts with a score of 5 (representing 5 lives/chances). For every guess made, the game provides a hint ("Too high" or "Too low"). The goal is to find the number before your score hits zero.

## ✨ Features
* **Interactive GUI:** Built using the lightweight `tkinter` library.
* **Randomization:** A new secret number is generated every time the app is launched.
* **Hint System:** Dynamic feedback tells you if your guess is too high, too low, or out of bounds.
* **Score Tracking:** Real-time score updates as you play.
* **Input Validation:** Prevents the game from crashing if non-numeric characters are entered.

## ⚙️ Prerequisites
To run this application, you need to have **Python 3.x** installed on your system.

Tkinter is included with standard Python installations on Windows and macOS. If you are on Linux, you may need to install it separately:
```bash
sudo apt-get install python3-tk
