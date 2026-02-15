# Spam-Ham Classifier Web App

A production-ready Machine Learning web application that classifies messages as **Spam** or **Ham** (Legitimate) using Natural Language Processing (NLP) and Support Vector Machines.

**Live Demo:** `https://spam-ham-classifier-pipeline.streamlit.app/`

## Features
* **Machine Learning Pipeline:** Integrated `TfidfVectorizer` and `Support Vector Classifier (SVC)` into a single Scikit-Learn Pipeline for consistent data transformation.
* **Real-time Inference:** Users can input custom text via a web interface and receive instant classification.
* **Production Deployment:** Fully hosted on **Heroku** using a Flask/Streamlit backend.
* **Clean Code:** Follows modular programming principles for easy maintenance and scalability.

## Tech Stack
* **Language:** Python
* **ML Libraries:** Scikit-Learn, NLTK, Pandas, NumPy
* **Deployment:** Heroku
* **Web Framework:** [Flask / Streamlit - Choose one]
* **Environment Management:** Gunicorn, Pip

## Model Performance
The model was trained on the [UCI SMS Spam Collection Dataset] and optimized using GridSearch Cross-Validation.
* **Algorithm:** Support Vector Classifier (SVC)
* **Vectorization:** TF-IDF (Term Frequency-Inverse Document Frequency)
* **Precision:** [Insert your % here] (Prioritized to reduce False Positives)
* **Accuracy:** [Insert your % here]

## 📂 Project Structure
```text
├── app.py                # Web framework execution script
├── model_pipeline.pkl    # Serialized SVC Pipeline (Tfidf + Model)
├── requirements.txt      # List of dependencies for Heroku
├── Procfile              # Heroku deployment commands
├── runtime.txt           # Python version specification
└── README.md             # Project documentation
