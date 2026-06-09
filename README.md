# FitVision AI - Real-time AI Gym Coach

An AI-powered real-time gym coaching app that uses computer vision to track exercises, count reps, and provide live voice feedback.

## Features
- Real-time pose detection using MediaPipe and OpenCV
- Automatic rep counting for Squats, Push-ups, Bicep Curls, Lunges, Shoulder Press
- AI voice coaching powered by Groq LLM + gTTS
- Session tracking and workout history
- User authentication

## Tech Stack
- Python, Streamlit, MediaPipe, OpenCV
- Groq API, gTTS, streamlit-webrtc
- SQLite

## How to Use
1. Clone the repo
2. Install dependencies: pip install -r requirements.txt
3. Create .env file with GROQ_API_KEY=your_key
4. Run: streamlit run main.py

## Links
- GitHub: https://github.com/kadekarunakar/AI-GYM-COACH

## License
MIT License
