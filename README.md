# KeyLogger Project using python

This project is a basic **Keylogger** built with Python's [`pynput`](https://pypi.org/project/pynput/) module. It captures and logs keystrokes made by the user and writes them to a text file.

> ⚠️ **Note**: This project is intended strictly for educational and ethical purposes. Do **not** run this software on any system without explicit permission. Unauthorized use may be illegal.

---

##  Features

- Logs all keyboard inputs (alphanumeric + special keys)
- Saves keystrokes to a local `log.txt` file
- Graceful shutdown using `Esc` key
- Easily customizable and extendable

---

##  How It Works

- Captures each key pressed using `pynput.keyboard.Listener`
- Appends each key to a log list
- Writes each key to a file `log.txt` in real-time
- Stops recording when the Escape key is released

---

## 🛠 Installation

### 1. Clone the repository

   
   git clone https://github.com/your-username/python-keylogger.git
   cd python-keylogger

### 2. Install dependencies

pip install pynput

### 3. Run the keylogger

python keylogger.py

----

## Disclaimer
This software is developed for learning and educational use only. Running a keylogger without the knowledge and consent of the device owner is strictly prohibited and may be illegal in many regions.


