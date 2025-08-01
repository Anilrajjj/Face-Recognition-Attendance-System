# Face Recognition Attendance System 🎓🧠

An AI-powered attendance system that uses face recognition to mark student attendance automatically. Built with Python, OpenCV, dlib, and CNN models, this system ensures accurate and real-time attendance tracking from live webcam or group images.

## 🔍 Features

- 📸 Real-time face detection and recognition using webcam  
- 🖼️ Recognition from group images (up to 64+ faces)  
- 📂 Face dataset management with individual folders per student  
- 📊 Attendance report generation in **CSV and PDF**  
- 🧠 CNN and Haar Cascade based detection  
- 🗃️ Unrecognized faces are marked as 'Unknown'  
- 🔐 Admin interface for uploading and reviewing records *(Future scope: Web integration)*

## 🚀 Tech Stack

- **Frontend:** HTML, CSS (for future web integration)  
- **Backend:** Python (Flask for web), OpenCV, dlib, face_recognition  
- **Database:** CSV for attendance logs, SQLite for user logins  
- **Libraries:** NumPy, pandas, reportlab, datetime

  Face-Recognition-Attendance-System/
│
├── dataset/ # Stores images of each student (one folder per student)
├── static/ # Static files (CSS/images for Flask)
├── templates/ # HTML templates (Flask)
├── app.py # Main Flask app
├── train_model.py # Script to encode faces and train recognition model
├── recognize_face.py # Main face recognition script
├── attendance.csv # Output attendance record
├── requirements.txt # Python dependencies
└── README.md # Project documentation

bash
Copy
Edit

## 🧪 How to Run

1. **Clone the repository**
  
   git clone https://github.com/Anilrajjj/Face-Recognition-Attendance-System.git
   cd Face-Recognition-Attendance-System
Install dependencies

pip install -r requirements.txt
Add student images

Create a folder for each student under dataset/

Add multiple images per student (frontal, side angles)

Train the model

python train_model.py
Run the recognition system

python recognize_face.py
(Optional) Run the Flask Web App:

python app.py
📷 Sample Output
Real-time webcam feed with bounding boxes

Console output with student names and timestamps

CSV & PDF export of attendance

🔐 Future Enhancements
Firebase integration for cloud-based attendance

Raspberry Pi + IoT implementation

Email/Telegram alerts for unknown faces

Web-based dashboard for faculty

🏆 Achievements
Published in Mini Project Expo 2025 at KSIT

Successfully demonstrated multi-face recognition from group images

Certificate of Publication included

📚 References
OpenCV Documentation

dlib Face Landmark Detector

face_recognition GitHub library

Research papers on CNN-based face detection

📬 Contact
K M Anil Kumar
6th Semester CSE, KS Institute of Technology
📧 anil632514@gmail.com
🔗 GitHub



## 📁 Folder Structure

