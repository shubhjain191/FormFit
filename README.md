# **FormFit: Gym Exercise Detection and Monitoring System**

## **Project Overview**  
**FormFit** is an AI-powered fitness tracking system designed to assist users in improving their workout techniques. The system leverages **MediaPipe Pose Estimation**, **Deep Learning**, and **Computer Vision** to detect exercises, count repetitions, provide live feedback, and generate detailed performance reports. This innovative solution focuses on enhancing user fitness experiences by delivering real-time feedback and actionable insights.

---

## **Features**
- **User Authentication**: Secure registration and login using Firebase.  
- **Pose Detection**: Real-time detection of user body landmarks using MediaPipe.  
- **Rep Counting**: Automatic counting of exercise repetitions (correct and incorrect).  
- **Exercise Classification**: Identification of exercises using neural networks.  
- **Real-Time Feedback**: Guidance during workouts with suggestions like "Perfect," "Too Fast," or "Adjust Depth."  
- **Session Report Generation**: Summary reports, including reps, performance metrics, and feedback.  

---

## **Technology Stack**
### **Languages**  
- **Python**: Core programming language for backend logic and pose detection.  
- **HTML, CSS, JavaScript**: Frontend for user interface design and interaction.  

### **Frameworks and Libraries**  
- **Flask/Django**: Backend framework for creating RESTful APIs and handling user requests.  
- **MediaPipe**: For real-time pose detection and joint angle calculations.  
- **OpenCV**: For capturing and processing video frames.  
- **TensorFlow/Keras**: For deep learning-based exercise classification.  

### **Database**  
- **Firebase Realtime Database**: For storing user details, session logs, and reports.  

### **Other Tools**  
- **Jupyter Notebook**: For prototyping and testing machine learning models.  
- **GitHub**: For version control and project collaboration.  

---

## **System Architecture**  
The system consists of the following modules:
1. **User Interaction**: Handles user registration, login, and workout session initialization.  
2. **Pose Detection**: Captures video input, processes frames, and detects key body landmarks using MediaPipe.  
3. **Session Management**: Tracks target repetitions, exercises, and progress throughout a session.  
4. **Feedback System**: Provides live feedback on exercise performance.  
5. **Data Management**: Stores user details, exercise logs, and generates session reports.  

---

## **Usage**
1. **User Login/Registration**: Start by creating an account or logging in.  
2. **Set Workout Targets**: Choose your target repetitions and start the workout session.  
3. **Perform Exercises**: Follow the system's instructions. Real-time feedback will guide your movements.  
4. **View Reports**: Check detailed session performance at the end.

---
