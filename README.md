# Face Recognition Based Attendance System

A Python GUI-integrated attendance system using face recognition to automate and secure attendance marking.

This project uses OpenCV for face detection and recognition, and Tkinter for building an intuitive, user-friendly graphical interface. It is ideal for educational institutions or workplaces where daily attendance logging is required.

## Directory Structure

aadhira22-face-recognition/
└── Face_recognition_based_attendance_system-master/
└── main.py


## Features

- Easy-to-use GUI interface (built with Tkinter)
- Real-time face detection and recognition
- Password-protected registration system
- Auto-generated CSV file for each day’s attendance
- Displays attendance records (Name, ID, Date, Time) live in table format
- Stores face images and training data
- Registration logs saved with ID and name

## Technologies Used

| Library         | Purpose                            |
|----------------|------------------------------------|
| Tkinter         | GUI (Graphical User Interface)     |
| OpenCV (cv2)    | Image capture and face recognition |
| LBPHFaceRecognizer | Face training and prediction   |
| CSV             | Logging attendance and student data |
| NumPy           | Array and matrix manipulation      |
| Pandas          | CSV reading/writing                |
| datetime, time  | Date and time tracking             |

## How It Works

### 1. Register a New User
- Click on Capture Face to take face images of a new student or employee.
- Click Register Face to save their profile securely (password-protected).
- The system stores the images in the TrainingImage/ directory.

### 2. Train the System
- It automatically trains using LBPHFaceRecognizer and stores the model in TrainingImageLabel/Trainner.yml.

### 3. Take Attendance
- Click Mark Attendance.
- System detects and recognizes faces using webcam.
- Logs the attendance in Attendance/Attendance_<date>.csv.



