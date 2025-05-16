# Placement-Prediction-System
With the growing importance of campus placements in shaping students’ careers, predicting placement outcomes based on academic and personal profiles can empower students to better prepare and align themselves with job market expectations. This project leverages machine learning techniques to analyze placement data and forecast the likelihood of a student getting placed.
## Objectives
1. Predict whether a student is likely to be placed or not based on various academic and demographic features.
2. Provide an intuitive web interface to collect input data and display predictions.
3. Help institutions and students understand key factors influencing placement.
## Focus Areas
Data Analysis:
Utilizing a structured dataset of student records to understand correlations and patterns affecting placement outcomes.

Machine Learning Model:
Training a classification model to make accurate placement predictions based on inputs like CGPA, gender, specialization, work experience, etc.

Web-Based Interface:
Developing an easy-to-use Flask web application for real-time predictions based on user inputs.
## Procedure
1. Data Collection & Preprocessing
   Source: placedata.csv

   The dataset includes the following fields:
- Gender
- SSC (Secondary Education) Percentage
- HSC (Higher Secondary Education) Percentage
- Degree Type & Percentage
- Work Experience
- Specialization
- MBA Percentage
- Placement Status

2. Model Training
   
   Tools: scikit-learn, pandas

- Applied logistic regression and random forest classifiers.
- Evaluated performance using metrics like accuracy, precision, recall.
- Best-performing model was saved as model.pkl.
  
3. Web Application

   Tech Stack: Flask, HTML, CSS

- Built a Flask app (app.py) to take user input via form.
- Model predicts placement outcome on submission.
- UI built with clean HTML templates (templates/index.html).

## Results
- Prediction Accuracy: ~85–90% (based on test data)
- User Experience: Seamless form submission and prediction display
- Deployment: Locally hosted Flask application
## Technologies Used
Programming: Python, HTML, CSS, JavaScript

ML Libraries: Scikit-learn, Pandas, NumPy

Web Framework: Flask

Data Visualization: Matplotlib, Seaborn 

Storage: CSV, Pickle




  


