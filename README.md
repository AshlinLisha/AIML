# 📡 Signal Blackout: The Last Transmission

An interactive 3D escape room game powered by Machine Learning. Investigates suspicious access logs, signal profiles, and encrypted messages to solve detective clues.

## 🌐 Live Application
- **Play Online:** [https://ashlinlisha.github.io/AIML/](https://ashlinlisha.github.io/AIML/)
- **Backend API:** Hosted on Render

## 🛠 Tech Stack
- **Frontend:** HTML5, JavaScript (Three.js), CSS3
- **Backend:** Python, Flask, `flask-cors`, Gunicorn
- **ML Models:** `scikit-learn` (Decision Tree, KNN, Naive Bayes), `pandas`

## 🚀 Running Locally
pip install -r requirements.txt && python app.py
Open [http://127.0.0.1:5000](http://127.0.0.1:5000) or index.html in your browser. Needs internet once for Three.js (cdnjs). CSVs are generated on first run; models train at startup.
