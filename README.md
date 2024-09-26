# football_analysis_project

Football Analysis Project
Introduction
This project aims to detect and track players, referees, and the football in video footage using YOLO, one of the top AI models for object detection. The model will be further trained to enhance its accuracy. Additionally, Kmeans clustering will be applied for pixel segmentation to differentiate between players based on their t-shirt colors, allowing us to assign them to specific teams. With this information, we can calculate a team's ball possession percentage throughout the match. Optical flow will be used to assess camera movements between frames, helping us track player movements accurately. Furthermore, perspective transformation will be employed to convert pixel-based measurements into meters by taking into account the depth and perspective of the scene. Using this method, we will compute each player's speed and the total distance covered during the game. The project integrates various techniques, making it an excellent resource for both beginners and advanced machine learning engineers as it tackles practical, real-world challenges.

Modules Used
The project uses the following modules:
YOLO: AI model for object detection
Kmeans: Pixel segmentation and clustering for t-shirt color recognition
Optical Flow: For measuring camera movement
Perspective Transformation: For visualizing scene depth and perspective
Speed and Distance Calculation: Per player
Trained Models
Trained YOLO v5 model
Sample Video
Example input video
Requirements

To run this project, you'll need the following dependencies:
Python 3.x
ultralytics
supervision
OpenCV
NumPy
Matplotlib
Pandas
