# 🦖 Dino Game Bot (Python Automation)

An automated bot that plays the **Chrome Dino Game** using screen capture and pixel detection. Built with Python, this script uses `pyautogui`, `keyboard`, and `Pillow` to mimic keystrokes and detect obstacles in real-time — all without using browser extensions or modifying the game!

## 🎮 How It Works

- Takes periodic screenshots of the game screen
- Detects obstacles (cacti or birds) based on color difference
- Simulates `UP` and `DOWN` key presses to jump or duck
- Learns acceleration and adapts by expanding the detection range

## 🚀 Features

- No external model or training required
- Works on Chrome's built-in offline game
- Adaptive to increasing game speed
- Supports both ground and flying obstacles
- Easy to run and lightweight

## 🧠 Tech Stack

- **Python**
- `pyautogui` – For screen capture
- `Pillow (PIL)` – Image processing
- `keyboard` – Keystroke simulation
- `math`, `time` – Logic and timing

## 📦 Setup Instructions

### Prerequisites

- Python 3.x installed
- Google Chrome browser
- Chrome Dino Game opened in full-screen or normal mode
- Required libraries installed

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/dino-game-bot.git
    cd dino-game-bot
    ```

2. Install dependencies:

    ```bash
    pip install pyautogui keyboard pillow
    ```

3. Run the bot:

    ```bash
    python dino_bot.py
    ```

4. You’ll have 3 seconds to switch to the Chrome Dino Game window.

5. Press `Q` anytime to stop the bot.

## 📁 Project Structure

```plaintext
├── dino_bot.py
├── dino.jpg (temporary screenshots)
├── README.md
└── requirements.txt
