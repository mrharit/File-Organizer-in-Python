# 📂 File Organizer in Python
### Mini Project 2

---

## 📌 Project Overview

The **File Organizer** is a simple Python automation script that helps organize files in a directory by sorting them into folders based on their file extensions.

Instead of manually cleaning cluttered folders, this script automatically:
- Scans the current directory
- Creates category folders (PDFs, Images, Videos, etc.)
- Moves files into the correct folders

---

## 🎯 Objective

The goal of this project is to:
- Practice **file handling and OS operations in Python**
- Understand directory traversal and automation
- Build a practical real-world utility using Python basics

---

## 🛠️ Technologies Used

- **Python**
- Built-in libraries:
  - `os`
  - `shutil`

No external packages are required.

---

## 📂 Folder Categories

The script organizes files into the following folders:

| Folder Name     | File Extensions              |
|-----------------|-----------------------------|
| PDFs            | `.pdf`                      |
| Word_Files      | `.doc`, `.docx`             |
| Images          | `.jpg`, `.jpeg`, `.png`     |
| Videos          | `.mp4`, `.mkv`              |
| Text_Files      | `.txt`                      |

---

## ⚙️ How the Script Works

1. Gets the **current working directory**
2. Defines file categories with extensions
3. Creates folders if they don’t already exist
4. Scans all files in the directory
5. Moves each file to its respective folder based on extension

---

## ▶️ How to Run the Project

1. Place the Python script in the folder you want to organize
2. Make sure Python is installed
3. Run the script:

   ```bash
   python file_organizer.py
