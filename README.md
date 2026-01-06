# Repository for final project
# NLP Emotion Detection (Watson NLP + Flask)

A web-based NLP application that detects emotions in user-provided text using IBM Watson NLP (Emotion Predict).  
It returns emotion scores (anger, disgust, fear, joy, sadness) and identifies the dominant emotion. The app is deployed with a Flask backend and a simple web UI.

## Features
- Emotion detection via Watson NLP Emotion Predict endpoint
- Returns formatted output:
  - `anger`, `disgust`, `fear`, `joy`, `sadness`, `dominant_emotion`
- Error handling for blank/invalid input (shows: `Invalid text! Please try again!`)
- Unit tests for dominant emotion validation
- Flask web interface with `/emotionDetector` route

## Tech Stack
- Python 3
- Flask
- Requests
- IBM Watson NLP (Emotion Predict)

## Project Structure
```bash
.
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
├── templates/
├── server.py
├── test_emotion_detection.py
└── README.md

