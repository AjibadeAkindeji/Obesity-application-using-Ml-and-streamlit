# Obesity Prediction Application

This is a machine learning-powered web application built using Streamlit that predicts the level of obesity based on user-input health and lifestyle data. The model is trained on a publicly available dataset and provides real-time predictions through an interactive web interface.

## Live Demo

Access the live Streamlit app here:  
[**Obesity Prediction App**](https://obesity-application-using-ml-and-app-cihnwkddnyireo4lcnb5fi.streamlit.app/)

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Performance](#model-performance)
- [Author](#author)

---

## Overview

This project helps users understand their obesity category (e.g., normal weight, overweight, obesity type I, II, etc.) by analyzing inputs such as age, gender, physical activity, food consumption, and body metrics. The app aims to promote awareness about obesity and encourage healthier lifestyles through predictive insights.

---

## Dataset

- **Source**: [UCI Machine Learning Repository](https://www.kaggle.com/datasets)
- **Features**: 
  - Age, Gender, Height, Weight
  - Eating habits (frequency of fast food, water intake, etc.)
  - Lifestyle choices (physical activity, transportation methods, etc.)
- **Target**: Obesity Category

---

## Technologies Used

- **Languages**: Python
- **Libraries**: 
  - `pandas`, `numpy`, `scikit-learn`
  - `matplotlib`, `seaborn` (for EDA)
  - `streamlit` (for web deployment)
  - `joblib` (for model serialization)
- **Platform**: Streamlit Cloud (for hosting)

---

## Installation

To run the app locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/AjibadeAkindeji/Obesity-application-using-Ml-and-streamlit.git
   cd Obesity-application-using-Ml-and-streamlit

	2.	Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows


	3.	Install dependencies:

pip install -r requirements.txt


	4.	Launch the Streamlit app:

streamlit run app.py

## Usage

	1.	Open the web app (locally or via Streamlit Cloud)
	2.	Fill in your health/lifestyle metrics
	3.	Click the Predict button
	4.	View your obesity category result

## Project Structure
<pre>
```
├── app.py                  # Streamlit frontend
├── model.pkl               # Trained ML model
├── scaler.pkl              # Standard scaler
├── obesity_dataset.csv     # Raw dataset
├── data.ipynb              # Data analysis and model training
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```
</pre>


## Model Performance

	•	Algorithm Used: Random Forest Classifier
	•	Accuracy: 93% on test set
	•	Evaluation Metrics: Confusion Matrix, Precision, Recall, F1 Score

## Author

Ajibade Akindeji Qudus
	
 •	GitHub: AjibadeAkindeji
	
 •	Streamlit App: Obesity Prediction
 
 •	Email[ajibade_1@icloud.com]
