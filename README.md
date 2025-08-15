# Tkinter Password Manager

A simple and functional **Password Manager** built using Python's Tkinter library. 
It allows you to generate strong passwords, copy them to the clipboard instantly, and save credentials locally for later use.

---

## Features

### 1. Password Generation
- Generates secure passwords containing **letters, numbers, and symbols**.
- Randomized length for better security.
- Automatically copied to the clipboard after generation.

**Preview:**  
![Password Generation](res/Screenshot%202025-08-12%20234606.png)

---

### 2. Data Storage
- Saves **Website**, **Email/Username**, and **Password** into `data.txt`.
- Requests confirmation before saving.
- Clears input fields after saving.

**Preview:**  
![Saved Data Example](res/Screenshot%202025-08-12%20234711.png)

---

### 3. User Interface
- Clean and simple Tkinter-based GUI.
- Website, email, and password entry fields.
- Logo at the top for better appearance.
- Buttons for password generation and saving credentials.

**Previews:**  
![Main Interface 1](res/Screenshot%202025-08-12%20234530.png)  
![Main Interface 2](res/Screenshot%202025-08-12%20234639.png)

---

## How It Works
1. **Enter Details:** Fill in the website and email fields.
2. **Generate Password:** Click "Generate Password" for a secure password or enter your own.
3. **Save:** Click "Add" to store the data into `data.txt`. The password will also be copied to your clipboard.

---

## Requirements
- Python 3.x
- `pyperclip` library for clipboard functions
- `tkinter` (comes pre-installed with Python)
- `logo.png` in the same folder as the script

---

## Output File Format
Credentials are saved in `data.txt` in the following format:
