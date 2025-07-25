#  Face Recognition Attendance System

This project is a real-time **face recognition-based attendance system** built using **OpenCV**, **K-Nearest Neighbors (KNN)**, and **Streamlit**. It captures face data, trains a model, marks attendance via webcam, and displays/downloads the attendance records through a web interface.

---

##  Features

-  Face detection using Haar Cascade
-  Face recognition using KNN
-  Stores data using `pickle`
-  Generates CSV files for daily attendance
-  Voice confirmation with Windows text-to-speech
-  Streamlit dashboard for visualization & CSV download

---


---

## 🚀 How It Works

### Step 1: Add Face Data

Run the following to add a new person's face to the dataset:

```bash
python Add_faces.py

Step 2: Run Face Recognition & Mark Attendance
python test.py

Step 3: View Attendance in Streamlit

streamlit run app.py


Requirements
Install required dependencies with:

bash
Copy
Edit
pip install -r requirements.txt


## Sample Attendance File

NAME,TIME
John Doe,14:12:53
Jane Smith,14:14:21



