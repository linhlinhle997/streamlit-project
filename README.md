# Streamlit Project

This Streamlit application showcases various machine learning models and utilities, including scripts for calculating Levenshtein distance, performing object detection with a MobileNet SSD model, and a simple chatbot implementation.

## Installation
1. Clone the repository:
```sh
git clone https://github.com/yourusername/streamlit-project.git
cd streamlit-project
```
2. (Optional) Create and activate a virtual environment:
```sh
python3 -m venv .venv
source .venv/bin/activate
```
3. Install the required dependencies:
```sh
pip install -r requirements.txt
```

## Running the Application
Once everything is ready, you can launch the application by running one of the following commands:
- Levenshtein Distance Calculation:
```sh
streamlit run scripts/01_levenshtein_distance.py
```
- Object Detection:
```sh
streamlit run scripts/02_object_detection.py
```
- Chatbot:
```sh
streamlit run scripts/03_chatbot.py
```