Final Project
Project Name
Final Project
Description
This repository contains the Final Project for the course: an Emotion Detector web
application built with Python and Flask, using IBM Watson NLP's emotion prediction
service to analyze text and determine the emotions expressed in it (anger, disgust,
fear, joy, and sadness).
Features
Analyzes input text and returns emotion scores (anger, disgust, fear, joy, sadness)
Identifies the dominant emotion in the text
Includes input validation and error handling for blank text
Deployed as a simple web application using Flask
Includes unit tests to verify core functionality
Project Structure
```
Final-Project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── test_emotion_detection.py
├── server.py
└── README.md
```
How to Run
Clone this repository.
Install dependencies: `pip install flask requests`
Run the server: `python server.py`
Open a browser and navigate to `http://localhost:5000`
Author
Ademo
