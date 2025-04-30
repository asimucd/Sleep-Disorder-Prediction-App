# 💤 Sleep Disorder Prediction App

This project is a **Flask-based web application** that predicts sleep disorders such as **Insomnia**, **Sleep Apnea** or **No disorder** using a trained Random Forest model. It also offers a **REST API** endpoint for developers to integrate with external applications.

---

## 🌐 Live Demo

Try the deployed app here: 

👉 [http://[<your-ec2-public-ip>](http://ec2-18-116-85-249.us-east-2.compute.amazonaws.com/):8080](http://[<your-ec2-public-ip>](http://ec2-18-116-85-249.us-east-2.compute.amazonaws.com/):8080)

---

## 📊 Overview

The model uses user inputs like age, BMI, sleep duration, stress level, blood pressure, and other lifestyle factors to predict whether a person is likely to have:
- **No disorder**
- **Insomnia**
- **Sleep Apnea**

---

## 💡 Technologies Used

- Flask (Web Framework)
- Scikit-learn (ML Model)
- WTForms (Form validation)
- HTML/CSS + Bootstrap (Frontend)
- Joblib (Model Serialization)

---

## Setup Instructions

1. **Clone the Repository**
    ```bash
    git clone https://github.com/asimucd/Sleep-Disorder-Prediction.git
    cd Sleep-Disorder-Prediction

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    
3. **Run the Web App Locally**
    ```bash
    python app.py

Access it at: http://localhost:8080

4. **Run the REST API**
    ```bash
    python flask-api.py
