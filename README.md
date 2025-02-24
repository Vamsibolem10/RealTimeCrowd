# Real-Time People Counting Using Deep Learning
AI-powered people counting system using YOLO and OpenCV for real-time crowd analytics.
Track, count, and analyse movement in dynamic environments with precision!

# Overview
Ever wondered how many people pass through a certain area in real time? This project combines deep learning and computer vision to detect and count people in videos using YOLO. It’s designed for applications like smart surveillance, retail analytics, and public safety monitoring.
🔹 Tracks movement in real time
🔹 Logs entry & exit timestamps
🔹 Applies noise-reducing morphological processing
🔹 Works with video datasets & live feeds

# Key Features
YOLO-powered detection – Fast & accurate people tracking
Real-time processing – No delay in counting
Morphological mask filtering – Noise reduction for precise detection
Adaptable to different environments – Works in various lighting conditions

# Tech Stack
🔹 Deep Learning: YOLO (You Only Look Once)
🔹 Computer Vision: OpenCV
🔹 Programming Language: Python
🔹 Video Processing: Background Subtraction, Object Tracking
🔹 Hardware Support: Runs on CPUs, GPUs, and embedded devices

# Project Structure
📜 Person.py – Defines the Person class for tracking individuals.
📜 main.py – Core script for real-time people counting.
📂 dataset/ – Contains video files used for testing (e.g., TestVideo.avi).
📜 log.txt – Stores entry and exit timestamps of detected people.
📜 README.md – Project documentation and setup guide.
📜 requirements.txt – List of required dependencies for the project.
