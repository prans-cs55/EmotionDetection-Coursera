# EmotionDetection-Coursera
📄 README.md
# 🎭 Emotion Detection Web Application

This project is the **Final Peer-Graded Assignment** of the Coursera course offered by IBM.  
The goal is to build an **AI-based web application** using the **IBM Watson NLP library & API** that detects emotions from text.  

---

## 📌 Project Tasks

✔️ **Task 1: Clone the project repository**  
Set up the base project and dependencies.  

✔️ **Task 2: Create an emotion detection application**  
Implemented `emotion_detector` function using **IBM Watson NLP API**.  

✔️ **Task 3: Format the output**  
Return a JSON with confidence scores for all emotions and highlight the **dominant one**.  

✔️ **Task 4: Package the application**  
Organized code into a Python package for easy imports.  

✔️ **Task 5: Run Unit tests**  
Added test cases with `unittest` to validate correctness.  

✔️ **Task 6: Web deployment with Flask**  
Built a Flask app to allow users to input text and see results on a webpage.  

✔️ **Task 7: Error handling**  
Handled invalid inputs, empty strings, and API failures gracefully.  

✔️ **Task 8: Static code analysis**  
Ensured code quality with `pylint` and best practices.  

---

## 🚀 Features
- Detects **5 emotions**: Joy, Anger, Disgust, Sadness, Fear  
- Returns **confidence scores** from IBM Watson NLP API  
- Highlights the dominant detected emotion  
- Web interface with **AJAX/Fetch API** for real-time updates  
- Fully **tested & error-handled**  

---

## 🛠️ Tech Stack
- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, Bootstrap, JavaScript  
- **AI/NLP Engine:** IBM Watson NLP API  
- **Testing:** unittest  
- **Code Quality:** pylint  

---

## ⚙️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/prans-cs55/EmotionDetection-Coursera
   cd EmotionDetection-Coursera


## ▶️ How to Run

### 1. Clone the repository
git clone https://github.com/prans-cs55/EmotionDetection-Coursera
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

