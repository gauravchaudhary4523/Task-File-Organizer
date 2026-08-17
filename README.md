# 📁 File Organizer Automation

A Python-based file organizer that automatically sorts files into separate folders according to their file extensions.

## 🎯 Objective

The objective of this project is to automate the repetitive task of organizing files into appropriate folders.

This project was developed as **Task – Task Automation with Python Scripts** for the **CodeAlpha Python Programming Internship**.

## ✨ Features

- Automatically detects file extensions
- Creates category folders automatically
- Organizes files based on their type
- Supports images, documents, text, audio, videos, and archives
- Handles unknown file types using an `Others` folder
- Generates an organization report
- Uses Python file handling for automation

## 🗂️ File Categories

| Category | File Types |
|---|---|
| Images | JPG, JPEG, PNG, GIF, BMP |
| Documents | PDF, DOC, DOCX, PPT, PPTX |
| Text | TXT, CSV |
| Audio | MP3, WAV, AAC |
| Videos | MP4, AVI, MKV, MOV |
| Archives | ZIP, RAR, 7Z |
| Others | Other file types |

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- `os` module
- `shutil` module
- File Handling

## ⚙️ How It Works

1. The program scans the selected folder.
2. It identifies each file's extension.
3. It determines the appropriate category.
4. Required folders are created automatically.
5. Files are moved into their respective folders.
6. A report is generated showing the organized files.

## 📊 Example

Before organization:

```text
Test files/
├── photo.jpg
├── document.pdf
├── notes.txt
├── song.mp3
└── video.mp4
