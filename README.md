# Face-Recognition-Based-Student-Attendance-Management-System
This project is a Python-based desktop application that automates student attendance tracking using facial recognition. Developed using OpenCV, Tkinter, and MySQL/CSV, it provides a simple and secure way to capture and store student attendance data through face detection and recognition.


📷 Face Image Capture: Capture images of students using a webcam and store them for training.

🧠 Model Training: Train a face recognition model using the captured images (LBPH algorithm).

🧍‍♂️ Real-Time Recognition: Detect and recognize faces in real-time to mark attendance.

🧾 Attendance Logging: Automatically logs attendance with student ID, name, date, and time in a CSV file.

🔐 Password Protection: Secures training functionality with password access.

🖥️ User-Friendly GUI: Simple graphical user interface built using Tkinter.

📅 Date and Time Display: Displays current date and time on the main dashboard.



📁 Folder Structure

.
├── Attendance/                  # Attendance records (CSV files)
├── StudentDetails/             # Student registration info
├── TrainingImage/              # Captured face images
├── TrainingImageLabel/         # Trained model and password file
├── haarcascade_frontalface_default.xml
└── main.py                     # Main application code (GUI + logic)




🚀 How It Works

Register Student: Enter name and ID → Capture face images → Save profile.

Train Model: Train the LBPH face recognizer using captured images.

Mark Attendance: Recognize faces in real-time and log attendance.

View Attendance: CSV file logs attendance for each date.

🛠️ Tech Stack

Python 

OpenCV

Tkinter

NumPy

Pandas

CSV File Handling

(MySQL can optionally be integrated for extended data storage.)

🔐 Default Password Setup

On first use, you’ll be prompted to set a password for training. It will be stored in TrainingImageLabel_sd.txt. You can later change it using the "Change Password" option.





