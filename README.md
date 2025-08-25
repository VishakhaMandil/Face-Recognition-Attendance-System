🎯 Face Recognition Attendance System

A Flask + OpenCV based attendance management system that uses face recognition to mark attendance automatically.

This project captures faces, trains a recognition model, and logs attendance into a CSV file for each day.

🚀 Features

✅ Register new users with their face images (minimum 5 images required).
✅ Train a KNN model for face recognition.
✅ Mark attendance automatically by detecting faces in real-time via webcam.
✅ Store attendance in daily CSV files (Attendance/Attendance-mm_dd_yy.csv).
✅ View all registered users.
✅ Delete users and retrain the model.
✅ Simple and modern Bootstrap-based frontend.

🛠️ Tech Stack

Python (Flask, OpenCV, NumPy, Pandas, scikit-learn)

HTML, CSS, Bootstrap (for frontend)

Joblib (for saving ML models)

📂 Project Structure
Face-Attendance-System/
│── app.py                  # Main Flask application
│── haarcascade_frontalface_default.xml  # Haarcascade model for face detection
│── Attendance/             # Stores attendance CSV files
│── static/
│   ├── faces/              # User face images
│   ├── face_recognition_model.pkl  # Trained KNN model
│── templates/
│   ├── base.html
│   ├── home.html
│   ├── listusers.html
│   ├── add.html
│── requirements.txt        # Python dependencies
│── README.md               # Project documentation

⚙️ Installation
1️⃣ Clone the repository
git clone https://(https://github.com/VishakhaMandil/Face-Recognition-Attendance-System)
cd face-attendance-system

2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the Flask app
python app.py

5️⃣ Open in browser

Go to 👉 http://127.0.0.1:5000/

📸 Usage
➕ Add a User

Navigate to Add User.

Enter Name & Roll Number.

Capture at least 5 face images.

🎥 Start Attendance

Click Start Attendance.

The webcam will open.

Detected faces will be identified and logged in CSV.

📋 View Attendance

Attendance is saved in Attendance/Attendance-mm_dd_yy.csv.

View attendance on Home Page.

👥 Manage Users

Go to Users to see all registered users.

Delete a user if needed (retrain will happen automatically).

📊 Example Screenshots

🔹 Home Page


🔹 Add User Page


🔹 Attendance Marking


📌 Dependencies
Flask
opencv-python
numpy
pandas
scikit-learn
joblib


(Also included in requirements.txt)

🔮 Future Improvements

✅ Add face embedding models (DeepFace / dlib) for higher accuracy.

✅ Deploy on Heroku/Render with remote webcam access.

✅ Add email notifications for attendance.

✅ Build an Admin Dashboard with charts.

👩‍💻 Author(Vishakha Mandil)


Developed by Your Name
 🚀
