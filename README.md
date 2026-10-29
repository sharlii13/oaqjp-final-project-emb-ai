## Final Project

An AI-based web app that detects emotions (anger, disgust, fear, joy, sadness) in text
using the Watson NLP EmotionPredict library, packaged as `EmotionDetection`, deployed with Flask.

## Structure
- `EmotionDetection/emotion_detection.py` – application function `emotion_detector`
- `EmotionDetection/__init__.py` – package init
- `test_emotion_detection.py` – unit tests
- `server.py` – Flask deployment

## Run
```bash
python3.11 server.py   # open http://localhost:5000
```
