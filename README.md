# Mini Project on Machine Learning: Predicting Diabetes using Logistic Regression

This repository contains the code and resources for a mini project aimed at predicting whether a patient is diabetic or non-diabetic. The project utilizes Logistic Regression and is implemented as a web application using Python Flask, HTML, CSS, and other technologies.
You can access the deployed web app here: https://diabetes-prediction-kiu0.onrender.com

# Project Overview

# Purpose
The primary goal of this project is to predict the likelihood of a patient having diabetes based on a set of input features. Early detection of diabetes is crucial for effective medical intervention, and machine learning models can assist in identifying individuals at risk.

# Technologies Used
    - Python for machine learning model development
    - Flask for building the web application
    - HTML and CSS for the frontend
    - Logistic Regression for predictive modeling
    - Jupyter Notebook for data analysis and model development

# Data
The dataset used for this project contains patient information, including factors such as age, BMI, blood pressure, and glucose levels. This data is used to train the Logistic Regression model.

# Getting Started
To run the project locally, follow these steps:

    1. Clone this repository to your local machine.
git clone https://github.com/your-username/diabetes-prediction.git

    2. Navigate to the project directory.
cd diabetes-prediction

    3. Create a virtual environment and activate it (optional but recommended).
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

    4. Install the project dependencies.
pip install -r requirements.txt

    5. Run the Flask application.
python app.py

    6. Open a web browser and access the web application at http://localhost:5000.

# Project Structure
    The project directory is organized as follows:

├── app.py               # Flask web application code

├── static/              # Static assets (CSS, images, etc.)

├── templates/           # HTML templates

├── data/                # Dataset used for model training

├── models/              # Trained machine learning models

├── notebooks/           # Jupyter notebooks for data analysis and model development

├── requirements.txt     # Project dependencies

├── README.md            # Project documentation

# Model Training
The machine learning model used for diabetes prediction is trained using the provided dataset. You can explore the model development process and analysis in the Jupyter notebooks located in the notebooks/ directory.

# Contributions
Contributions to this project are welcome. If you want to make improvements, fix issues, or add new features, please create a pull request.
