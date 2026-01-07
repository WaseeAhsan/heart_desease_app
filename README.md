# Heart Disease Prediction API

This is a **FastAPI** application that predicts the presence of heart disease using a **RandomForestClassifier** model.  
The application is **Dockerized** and can be deployed to cloud platforms like **Render**.


## Heart Disease Prediction API
This is a high-performance FastAPI application that serves a Machine Learning model to predict the likelihood of heart disease based on medical parameters. It provides a RESTful interface for real-time predictions.

## 🚀 Features

- **/health** - Check server health
- **/info** - Get model info and input features
- **/predict** - Predict heart disease from patient data

FastAPI Backend: Lightweight, fast, and easy-to-use API framework.

ML Model Integration: Uses a trained model (Scikit-learn) to process health data.

Automatic Docs: Built-in support for Swagger UI and ReDoc for easy endpoint testing.

JSON Support: Accepts input data and returns predictions in standard JSON format.

🛠️ Tech Stack
Language: Python

API Framework: FastAPI

Web Server: Uvicorn

Data Science: Scikit-learn, Pandas, NumPy

⚙️ Installation & Local Setup
Clone the repository:

Bash

git clone https://github.com/WaseeAhsan/heart_desease_app.git
cd heart_desease_app
Install required packages:

Bash

pip install -r requirements.txt
Start the server:

Bash

uvicorn main:app --reload
