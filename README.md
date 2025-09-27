# 🔐 Random Password Generator – Visual Entropy Based

This project generates strong, dynamic passwords every second using visual entropy from animated circles on the screen. It captures the current screen pixels, shuffles them, and generates a SHA-256 hash to produce a unique password continuously.

## 🚀 Features

- A **new password every second** based on screen pixel data
- Visually dynamic with **smooth animated circles**
- One-click **copy to clipboard** button
- **No lag** – runs smoothly using background threading
- Supports **fullscreen** mode

## 🛠 Installation

### Requirements

- Python 3.8+
- Install required packages:
  ```bash
  pip install pygame numpy pyperclip

### Run the program

		python main.py
	

## 🧪 Screen Size & Entropy

The larger the window, the more pixel data is available, increasing the randomness and entropy of each generated password. It works in smaller windows too, but with slightly reduced randomness.

## 👤 Developer

**Name:** İhsan  
**GitHub:** [https://github.com/genilax](https://github.com/genilax)


