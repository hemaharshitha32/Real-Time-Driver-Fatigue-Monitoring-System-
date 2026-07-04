# Real-Time Driver Fatigue Monitoring System

A real-time AI-powered driver fatigue detection system that monitors a driver's eye movements using a webcam. The application detects signs of drowsiness by analyzing the Eye Aspect Ratio (EAR) using MediaPipe facial landmarks and provides instant alerts to improve road safety.

The project is built using Python, OpenCV, MediaPipe, and Streamlit, providing a simple web interface with fast real-time performance.

---

# Overview

Driver fatigue is one of the major causes of road accidents. This project helps reduce that risk by continuously monitoring the driver's eyes through a webcam. If the driver's eyes remain closed for a certain period, the system identifies fatigue and generates an alert.

The application runs locally, processes video frames in real time, and provides a lightweight and user-friendly interface.

---

# Features

## Real-Time Monitoring

- Live webcam video processing
- Continuous eye tracking
- Low-latency performance

## Fatigue Detection

- Eye Aspect Ratio (EAR) calculation
- Blink detection
- Drowsiness detection
- Real-time safety alerts

## Computer Vision

- Facial landmark detection
- Face tracking using MediaPipe
- Eye movement analysis
- Accurate fatigue monitoring

## User Interface

- Built with Streamlit
- Simple and interactive dashboard
- Browser-based access
- Fast application startup

## Performance

- Lightweight application
- Efficient frame processing
- Optimized resource usage
- Modular and scalable architecture

---

# Technology Stack

## Programming Language

- Python

## Libraries

- OpenCV
- MediaPipe
- Streamlit
- NumPy
- Pandas

## Computer Vision

- Eye Aspect Ratio (EAR)
- Facial Landmark Detection
- Real-Time Video Processing

## Tools

- Git
- GitHub

---

# Project Structure

```text
driver-fatigue-monitor/
│
├── app.py
├── detector.py
├── utils.py
├── requirements.txt
├── README.md
├── assets/
├── models/
└── screenshots/
```

---

# Usage

Run the application using Streamlit:

```bash
streamlit run app.py
```

Allow camera access when prompted.

The application starts monitoring the driver's eyes in real time and generates alerts whenever signs of fatigue are detected.

---

# How It Works

1. Captures live video from the webcam.
2. Detects the driver's face using MediaPipe.
3. Identifies facial landmarks around both eyes.
4. Calculates the Eye Aspect Ratio (EAR).
5. Detects prolonged eye closure.
6. Generates a fatigue alert when required.

---

# Key Features

- Real-time fatigue detection
- Eye Aspect Ratio (EAR) analysis
- Facial landmark detection
- Blink monitoring
- Live webcam processing
- Browser-based interface
- Low-latency performance
- Modular architecture

---

# Applications

- Driver Safety Systems
- Smart Transportation
- Fleet Monitoring
- AI-Based Safety Systems
- Computer Vision Projects
- Research and Academic Projects

---

# Future Improvements

- Head pose estimation
- Yawning detection
- Mobile application support
- Email and SMS alerts
- Cloud-based monitoring
- Driver performance analytics
- Night vision support
- Multi-driver support

---

# Tech Stack

- Python
- OpenCV
- MediaPipe
- Streamlit
- NumPy
- Pandas
- Computer Vision
- Eye Aspect Ratio (EAR)
- Git
- GitHub

---



# Acknowledgments

- OpenCV
- MediaPipe
- Streamlit
- NumPy
- Pandas
