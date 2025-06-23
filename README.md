# 🗂️ File Organizer Script (Python)

A simple Python automation script that organizes files in a folder (like Downloads) by their type — placing them into categorized subfolders such as `Images`, `Documents`, `Archives`, and more.

---

## 📌 Features

- Automatically organizes files based on their extensions
- Creates folders if they don't already exist
- Supports multiple categories (Images, PDFs, Archives, etc.)
- Includes logging and exception handling
- Lightweight and beginner-friendly

---

## 🛠️ Technologies Used

- Python 3.x
- `os` module – for interacting with the file system
- `shutil` – for moving files
- `logging` – for logging events and errors

---

## 📁 File Categories Handled

| Category   | Extensions                      |
|------------|----------------------------------|
| Images     | `.jpg`, `.jpeg`, `.png`, `.gif`  |
| Documents  | `.pdf`, `.docx`, `.txt`, `.xlsx` |
| Videos     | `.mp4`, `.mov`, `.avi`           |
| Music      | `.mp3`, `.wav`                   |
| Archives   | `.zip`, `.rar`, `.7z`            |
| Scripts    | `.py`, `.js`, `.html`            |
| Others     | Any file not matching above types|

---

## 🚀 How to Run

1. Clone this repo or download the Python script.

2. Replace the folder path in the script:
   ```python
   SOURCE_FOLDER = r"C:\Users\YourUsername\Downloads"
