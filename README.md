🌌 Habitability of Exoplanets – AI-Powered Prediction System

An end-to-end Machine Learning + Web Application that predicts whether an exoplanet is habitable or non-habitable, provides a habitability score, ranks top candidate planets, and visualizes scientific insights using real astronomical data.

🔗 Live Deployment:
👉 https://habitability-of-exoplanets-5.onrender.com

📌 Project Overview

The search for habitable exoplanets is one of the most important challenges in modern astrophysics. This project leverages machine learning models trained on NASA Exoplanet Archive data to predict habitability based on key planetary and stellar parameters.

The system provides:

Habitability prediction (Habitable / Non-Habitable)

Continuous habitability score

Ranking of top habitable exoplanets

Scientific visualizations for analysis

Web-based interactive dashboard

🚀 Features
🔍 Prediction

Takes user input:

Planet radius

Planet mass

Surface temperature

Predicts:

Habitability class

Habitability score (0–1)

🏆 Ranking

Displays Top 10 Habitable Exoplanets

Ranked using hybrid ML + rule-based scoring

Real planetary data (CSV-based)

📊 Visualization Dashboard

Habitability score distribution

Planet radius vs habitability

Surface temperature vs habitability

Stellar temperature influence

Feature correlation heatmap

🌐 Web Interface

Glassmorphism UI

Responsive layout

Professional scientific dashboard design

🧠 Machine Learning Models Used

Random Forest Classifier (Primary model)

Logistic Regression

Decision Tree

XGBoost (multi-class)

Hybrid scoring (ML probability + physics constraints)

⚙️ Tech Stack
Backend

Python

Flask

Flask-CORS

Gunicorn

Machine Learning

Scikit-learn

XGBoost

NumPy

Pandas

Joblib

Frontend

HTML5

CSS3 (Glassmorphism UI)

JavaScript

Bootstrap 5

Deployment

Render (Free tier)

🌍 Deployment Notes

Deployed using Render Free Web Service

Cold-start delay (20–60 seconds) is expected

ML models load during initialization

After startup, predictions are fast

📚 Data Source

NASA Exoplanet Archive
https://exoplanetarchive.ipac.caltech.edu/

🎯 Applications

Astrophysics research assistance

Educational demonstrations

Scientific data analysis

AI + space science projects

Hackathons & academic submissions

📌 Future Enhancements

Real-time API integration with NASA archive

Advanced deep learning models

User authentication

Cloud database (PostgreSQL)

Mobile-friendly UI

PDF/Excel export of reports

🏁 Conclusion

This project successfully demonstrates the integration of machine learning, scientific data, and web technologies to solve a real-world astrophysical problem. It highlights practical deployment challenges and showcases a complete ML lifecycle from data to deployment.
