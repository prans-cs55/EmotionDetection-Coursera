# EmotionDetection-Coursera
📄 README.md
# 🎭 Emotion Detector Web App

This is a Flask-based web application that analyzes text and detects the most likely **emotion** being conveyed.  
It uses a simple Natural Language Processing (NLP) model to classify input text into five emotions:

- 😡 Anger  
- 😖 Disgust  
- 😨 Fear  
- 😃 Joy  
- 😢 Sadness  

---

## 🚀 Features
- Web-based UI built with **Flask + Bootstrap**  
- Real-time emotion detection from user input  
- Displays **confidence scores** for all emotions  
- Highlights the **dominant emotion**  
- AJAX-powered frontend (no page reloads)  

---

## 🛠️ Tech Stack
- **Backend**: Python, Flask  
- **Frontend**: HTML, CSS, Bootstrap, JavaScript (Fetch API)  
- **NLP Logic**: Custom function (`emotion_detector`)  

---

## 📂 Project Structure


final_project/
│── EmotionDetection/
│ ├── init.py
│ ├── emotion_detection.py # Core emotion detection logic
│
│── templates/
│ ├── index.html # Frontend UI
│
│── static/ # (optional: styles, JS, images)
│
│── server.py # Flask server entry point
│── test_emotion_detection.py # Unit tests
│── README.md


---

## ▶️ How to Run

### 1. Clone the repository
git clone <>
cd final_project

2. Create a virtual environment (recommended)
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt


(If you don’t have requirements.txt, install Flask manually:)

pip install flask

4. Start the server
python3 server.py

5. Open the app

In your browser, go to:

http://127.0.0.1:5000

🧪 Running Tests

To run the unit tests:

python3 -m unittest test_emotion_detection.py

📸 Screenshots

<img width="2842" height="1436" alt="Screenshot 2025-09-02 191705" src="https://github.com/user-attachments/assets/c0491168-f8d7-4025-9d75-e1a546e2e499" />


📌 Future Improvements

Add visual charts (bar graph of emotion scores)

Support for more emotions

Deploy to cloud (Heroku, Render, or AWS)

Multilingual emotion detection

