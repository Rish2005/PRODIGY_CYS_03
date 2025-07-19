# 🧠 Linux Keylogger using Pyxhook

This project is a **keylogger built in Python** using the `pyxhook` module (Linux-based). It captures all keyboard input and saves it to a timestamped `.log` file.

> ⚠️ This tool is strictly for **ethical and educational purposes only** such as **learning**, **testing environments**, and **authorized security demos**.

---

## 🔐 Features

- Logs every keystroke (including Enter key)
- Saves logs in real-time to a local `.log` file
- Timestamped filenames
- Works on Linux/X11 systems
- Minimal and clean codebase

---

## 🖥️ How It Works

- Uses the `pyxhook` module to hook into keyboard input at the system level
- Captures key presses via the `OnKeyPress` function
- Writes each key (or newline on Enter) to a file named like:  
