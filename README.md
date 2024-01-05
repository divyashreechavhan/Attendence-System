# Attendance System using OpenCV and Flask
Overview
This project implements a personalized attendance system utilizing OpenCV for face recognition and Flask for creating a web interface. The system aims to automate the attendance tracking process in a personalized manner by recognizing individual faces.

Features
1. Face Recognition
OpenCV: Utilizes OpenCV for face detection and recognition.
Personalized Identification: Recognizes individual faces to mark attendance accurately.
2. Web Interface with Flask
Flask Framework: Implements a user-friendly web interface for interacting with the attendance system.
Attendance Logging: Allows users to log and view attendance records.
How to Use
Camera Setup: Ensure a camera is connected and accessible for face detection.
Dataset Creation: Collect a dataset of faces for training the recognition model.
Flask Web Interface: Start the Flask app to access attendance features through a web browser.
Implementation Details
Face Detection: OpenCV is employed for accurate face detection in real-time.
Face Recognition Model: A face recognition model is trained on the provided dataset for personalized identification.
Flask Routes: Different routes in Flask for logging attendance, viewing records, and other functionalities.
Files
app.py: Main implementation of the Flask app and integration with OpenCV.
templates/: Directory containing HTML templates for the web interface.
data/: Directory storing the face dataset for training the recognition model.
Dependencies
Python 3.x
OpenCV
Flask
Usage
Clone the repository: git clone https://github.com/your-username/attendance-system.git
Navigate to the project directory: cd attendance-system
Install dependencies: pip install -r requirements.txt
Run the Flask app: python app.py
Access the web interface at http://localhost:5000 in your browser.
Feel free to customize and enhance the system based on your requirements. Happy tracking!

