# Football Analysis Project

## Introduction
The objective of this project is to detect and track players, referees, and footballs in video footage using YOLO, one of the leading AI models for object detection. We will also train the model to enhance its accuracy. In addition, we'll assign players to their respective teams by analyzing the color of their jerseys through pixel segmentation and clustering using Kmeans. With this data, we'll be able to calculate each team's ball possession percentage during the game. Moreover, optical flow will be used to measure camera movement across frames, helping us accurately track player movements. We'll also apply perspective transformation to account for depth and distance in the scene, enabling the measurement of player movement in meters instead of pixels. Lastly, we will calculate each player's speed and the distance they cover.

The reference for this project is the video "Build an AI/ML Football Analysis System with YOLO, OpenCV, and Python" from the Code In a Jiffy YouTube channel, which provides an excellent foundation and insights for implementing such a system. This project covers multiple key concepts and solves real-world challenges, making it ideal for both newcomers and experienced machine learning engineers.

You can find the original video at the following link: [Code In a Jiffy - Build an AI/ML Football Analysis system.](https://www.youtube.com/watch?v=neBZ6huolkg&ab_channel=CodeInaJiffy)
![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
