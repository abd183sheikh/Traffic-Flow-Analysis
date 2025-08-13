# Traffic-Flow-Analysis


# Overview

This project detects and classifies vehicles in three distinct lanes using YOLOv8, providing real-time lane-specific vehicle counts and traffic status (High, Medium, Low). It also calculates the average detection confidence and displays it on video output.

# Features

1) Lane-wise vehicle detection and counting
2) Real-time traffic status (High/Medium/Low)
3) Average detection confidence monitoring
4) Adjustable detection confidence threshold
5) Works with recorded videos or live camera feed

# Technologies Used

1) Python
2) YOLOv8 (Ultralytics)
3) OpenCV
4) NumPy

# Traffic Status Rules

1) High Traffic: More than 7 vehicles in a lane
2) Medium Traffic: 3–7 vehicles
3) Low Traffic: Less than 3 vehicles

# Model Performance

1) YOLOv8n → 50–55% accuracy
2) YOLOv8m → 65–70% accuracy
3) YOLOv8l → 80–85% accuracy (Final Model)