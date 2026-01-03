# 🔐 Password Manager & Generator (Python + Tkinter)

A simple **Password Manager desktop application** built using **Python** and **Tkinter**.  
This app allows users to **generate strong random passwords** and **securely store them locally** along with website and email details.

---

## ✨ Features

- 🔑 Generates **strong random passwords**
  - Mix of uppercase & lowercase letters
  - Numbers
  - Special characters
- 📋 One-click password generation
- 💾 Save website, email, and password locally
- ⚠️ Validation for empty fields
- ✅ Confirmation popup before saving
- 🎨 Clean and minimal Tkinter GUI

---

## 🛠️ Tech Stack

- **Python 3**
- **Tkinter** – GUI framework
- **Random module** – password generation
- **Tkinter MessageBox** – alerts & confirmations

---

## 📁 File Structure

```text
Password-Manager/
├── main.py
│   ├─ Password generation logic
│   ├─ Randomized character selection
│   ├─ Data validation and confirmation
│   ├─ File handling for saving credentials
│   └─ Tkinter GUI setup
│
├── data.txt
│   └─ Stores saved credentials in plain text
│
├── logo.png
│   └─ Logo image displayed in the application UI
│
└── README.md
    └─ Project documentation