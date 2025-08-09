# Sentiment Analysis:
Sentiment Analysis Web App
A Flask-based web application for analyzing the sentiment of text (Positive or Negative) using a Logistic Regression model trained on the NLTK Movie Reviews dataset.

### 🚀 Features
Text Sentiment Classification — Detects whether input text is positive or negative.

Web Interface — Simple UI built with HTML templates for user interaction.

Pre-trained Model — Uses TF-IDF vectorization and a Logistic Regression classifier.

Persistent Model Storage — Model and vectorizer saved with joblib for fast loading.

### 🛠 Tech Stack
Backend: Python, Flask

ML: Scikit-learn, NLTK

Data: NLTK Movie Reviews Dataset

Serialization: Joblib

Frontend: HTML (Jinja2 templates)

### ⚙️ Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/sentiment-analysis-webapp.git
cd sentiment-analysis-webapp
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
(Optional) Train the model yourself

bash
Copy
Edit
python model.py
Run the app

bash
Copy
Edit
python app.py
Open in browser

cpp
Copy
Edit
http://127.0.0.1:5000
### 📊 Model Details
Dataset: NLTK Movie Reviews (nltk.corpus.movie_reviews)

Vectorizer: TF-IDF

Classifier: Logistic Regression

Labels: Positive (1) / Negative (0)

### 🖼 Example
Input:
"This movie was absolutely fantastic with brilliant performances."
Output:
Sentiment: Positive

Output:
Sentiment: Positive
