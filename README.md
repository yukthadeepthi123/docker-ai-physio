# Docker AI Physiotherapy Assistant

## Overview
A Streamlit app that analyzes physiotherapy exercise videos using AI. It detects poses with MediaPipe, calculates right arm angles, and gives real-time feedback for stroke patients. Docker-powered.

## Features
- Upload MP4/AVI videos.
- Detects right arm angle and provides feedback.
- Logs data to JSON.

## Setup
1. Install Docker.
2. Build: `docker build -t physio-app .`
3. Run: `docker run -p 8501:8501 physio-app`
4. Open http://localhost:8501.

## Demo
[Add 30-sec screencast link later]

## Tech Stack
- Streamlit, OpenCV, MediaPipe, Docker
