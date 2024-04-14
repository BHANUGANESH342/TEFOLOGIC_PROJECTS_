Facial Recognition System
Overview
This project implements a facial recognition system using Python and various libraries such as OpenCV, dlib, Keras, and tkinter. The system allows for new user registrations, training of a recognition model, and real-time face recognition for attendance tracking.

Features
New Registrations: Allows users to register new individuals by capturing their images and storing their information in a CSV file.
Model Training: Trains a recognition model using the registered images and saves the trained model for later use.
Real-time Face Recognition: Recognizes registered individuals in real-time using a webcam, tracks their attendance, and logs it in CSV files.
File Structure
data_files/: Contains pre-trained models and configuration files for facial landmark detection and emotion analysis.
images/: Contains background images used in the GUI.
TrainingImage/: Stores images used for training the recognition model.
TrainingImageLabel/: Stores the trained recognition model.
StudentDetails/: Stores information about registered users in CSV format.
Attendance/: Stores attendance records in CSV files.
Dependencies
Python 3.x
OpenCV
dlib
Keras
tkinter
numpy
pandas
pyttsx3
PIL
Usage
Run main.py to start the application.
Use the GUI to perform actions such as registering new users, training the recognition model, and tracking attendance.
Process of Working
New Registrations:

Start the application.
Click on the "New Registration" button in the GUI.
Capture images of the new individual using the webcam.
Enter their details such as name, ID, etc.
Click on the "Register" button to save the information.
Model Training:

After registering individuals, click on the "Train Model" button in the GUI.
The system will use the registered images to train a recognition model.
Once training is complete, the model will be saved for later use.
Real-time Face Recognition:

Click on the "Start Recognition" button in the GUI.
The webcam will activate and start detecting faces in real-time.
If a registered individual is detected, their name and attendance will be recorded.
Attendances are logged in CSV files stored in the "Attendance" directory.
Outputs
New Registrations Output: After registering a new individual, their details are saved in the "StudentDetails" directory as a CSV file.
Model Training Output: The trained recognition model is saved in the "TrainingImageLabel" directory.
Real-time Face Recognition Output: Detected faces are displayed in the GUI with the corresponding recognized names. Attendance records are logged in CSV files in the "Attendance" directory.
Contributors
[Your Name]
[Your Email]
