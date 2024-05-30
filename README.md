# Face Recognition Attendance System

This repository contains a Face Recognition Attendance System that leverages the K-Nearest Neighbors (KNN) machine learning algorithm for face recognition and includes a web application interface for user interaction. The system automates the process of attendance management by recognizing faces in real-time and recording attendance.


## Features

* __Face Recognition:__ Utilizes the K-Nearest Neighbors (KNN) algorithm for accurate face recognition.

* __Real-Time Detection:__ Recognizes faces in real-time using the device's camera.

* __Automated Attendance:__ Automatically marks attendance when a face is recognized.

* __User Management__: Allows adding and removing users with their facial data.

* __Web Interface:__ Provides a user-friendly web interface for managing the system.

* __Database Integration:__ Stores attendance records in a database for easy retrieval and management.

* __Reports Generation:__ Generates attendance reports for specified periods.


## Technologies Used

* __Python:__ For back-end processing and machine learning.

* __OpenCV(cv2):__ For real-time face detection.

* __Face Recognition Library:__ A Python library that simplifies face recognition tasks.

* __Scikit-learn:__ For implementing the KNN algorithm.

* __Streamlit:__ For building the web application.

## How to Use
* __Accessing the Web App:__ Open your web browser and navigate to http://localhost:8501 (or the appropriate URL provided by Streamlit).

* __Adding Users:__ Go to the "Add User" section, enter the user details, and capture the user's face to register.

* __Marking Attendance:__ Users can mark their attendance by standing in front of the camera. The system will recognize the face using the KNN algorithm and record the attendance.

* __Viewing Attendance:__ Admins can view attendance records in the "Attendance Records" section.

* __Generating Reports:__ Generate attendance reports by specifying the desired date range in the "Reports" section.


## Screenshots
![Screenshot (58)](https://github.com/AyushPatel0028/face-recognition-attendance-system/assets/149039733/e1e3792f-d5bb-41ea-b232-7b19eab5905b)


![Screenshot (60)](https://github.com/AyushPatel0028/face-recognition-attendance-system/assets/149039733/96f5893d-4564-4ba6-9f92-eb903de40852)


## Contributing

* Contributions are welcome! Please follow these steps to contribute:

* Fork the repository.

* Create a new branch (git checkout -b feature-branch).

* Make your changes and commit them (git commit -m 'Add new feature').

* Push to the branch (git push origin feature-branch).

* Open a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

If you have any questions or suggestions, feel free to reach out to me at ayushpatel2808@gmail.com.


