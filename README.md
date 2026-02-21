🚗 Smart Parking Management System
A Computer Vision and Machine Learning Based Smart Parking Management System
📘 Overview

This project aims to design an intelligent parking management system that uses Computer Vision (CV) and Machine Learning (ML) techniques to efficiently monitor, detect, and manage parking slots in real-time.
The system reduces human effort, improves space utilization, and provides a seamless parking experience through automation.

🧠 Key Features

🎯 Real-Time Parking Detection: Detects empty and occupied parking spaces using CCTV camera feeds.

🧩 Computer Vision Integration: Uses image processing to identify vehicle presence.

🤖 Machine Learning Model: Classifies parking slots as occupied or free. 

📡 Smart Backend: Stores and manages parking data using a robust API.

💻 Frontend Dashboard: Displays live parking status and analytics to users.

🏗️ Project Architecture
SmartParking/
│
├── Backend/           # Node.js / Express backend server
│   ├── routes/        # API routes for parking management
│   ├── models/        # Database models (PostgreSQL)
│   └── controllers/   # Logic for user requests
│
├── cv_module_/        # Computer Vision module (Python)
│   ├── detect_parking.py   # Detects available/occupied slots
│   ├── utils/              # Image preprocessing, ROI handling
│
├── ml_module_/        # Machine Learning module (Python)
│   ├── train_model.py     # Model training script
│   ├── model.pkl          # Trained model file
│
├── frontend/          # Next.js frontend
│   ├── pages/         # UI pages (Home, Dashboard, Admin)
│   ├── components/    # Reusable UI components
│
├── README.md          # Project documentation
└── run                # Entry point / run script

⚙️ Technologies Used
Frontend:

Next.js (React Framework)

Tailwind CSS

Backend:

Node.js

Express.js

PostgreSQL

Computer Vision:

OpenCV

NumPy

Image Preprocessing

Machine Learning:

Scikit-learn / TensorFlow

Pandas

Numpy

🚀 How It Works

The camera feed is processed by the CV module using OpenCV to detect each parking slot.

The extracted images are analyzed by the ML model to classify slots as empty or occupied.

The Backend API stores the slot status in the PostgreSQL database.

The Frontend Dashboard displays real-time slot availability to users.

🧪 Future Enhancements

📲 Integration with a mobile app for live updates

🚘 Automatic number plate recognition (ANPR)

💡 Predictive parking using deep learning models

🔔 Voice-based or notification alerts for users

👨‍💻 Team Members

Sahil Ghidode – Machine learning Model

Ranu Patidar – backend ,database and project integration

Richa Mishra – Computer Vision & Image Processing

Ruchi verma 4 – Frontend 

🧾 License

This project is developed for academic purposes and can be extended for real-world smart city applications.
