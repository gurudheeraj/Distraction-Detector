# Distraction-Detector
Real-Time Student Mobile Phone Usage Detection and Alert System
This project is designed to detect and track students using mobile phones in classrooms.
If a student is found using a mobile phone continuously for more than 30 seconds, the system will:
Record a short video clip of the incident
Send an email alert to the class teacher with the clip attached
This helps in reducing distractions and ensuring discipline in classrooms using AI and computer vision.

# Objectives
1. Detect students and mobile phones in real-time.
2. Track each student individually using object tracking.
3. Monitor the duration of mobile phone usage.
4. Record a video clip of violations automatically.
5. Send email alerts with video proof to teachers.
# Technology Stack
1. Language: Python 3.8+
2. AI Model: YOLOv8 (Ultralytics)
3. Computer Vision: OpenCV
4. Tracking: DeepSORT / ByteTrack
5. Alert System: SMTP (Email Notifications)
6. Optional: Flask / FastAPI for dashboard, SQLite/MySQL for logs
