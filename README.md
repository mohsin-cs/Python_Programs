# Python Programs

Python programs written while learning the language, from core concepts to small applications.

## Contents

| Folder | What's inside |
|---|---|
| `Python_Concepts/` | Short examples of core features: lists, tuples, sets, dictionaries, loops, `enumerate`, short-hand if/else, local vs global variables, exception handling, raising errors, the `os` module, and simple encryption/decryption |
| `Assignments/` | Small console programs: MCQ test, rock-paper-scissors game, student registration system using file handling |
| `Projects/` | **Facial Attendance System**: marks attendance by recognising faces from a webcam feed |

## Facial Attendance System

Loads known faces from a folder, recognises them in the live webcam stream, and records each person's name and time to an attendance sheet.

**Built with:** Python, OpenCV, `face_recognition` (dlib), pandas

Before running, change the `known_faces_dir` path in the script to a folder of `.jpg`/`.png` face images named after each person.

```bash
pip install opencv-python face_recognition pandas keyboard
```

## Running the other programs

Each file runs on its own:

```bash
python Python_Concepts/Lists_Operations.py
```

## Author

**Mohsin Shahzad** · [LinkedIn](https://www.linkedin.com/in/mohsin-cs)
