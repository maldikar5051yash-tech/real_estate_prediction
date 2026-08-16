# Real Estate Price Prediction

A machine learning web application that predicts real estate prices using **Multiple Linear Regression** and **Flask**.

## Project Overview

This project uses a real estate dataset to train a Multiple Linear Regression model for predicting the **house price of unit area** based on different property and location-related features.

The trained machine learning model is integrated with a Flask web application where users can enter property details and receive a predicted house price.

## Features

* Multiple Linear Regression for price prediction
* Train-test split for model evaluation
* Model evaluation using MSE and R² Score
* Trained model saved using Pickle
* Flask-based web application
* User-friendly prediction form
* Real-time prediction through the web interface

## Input Features

The model uses the following five features:

1. House Age
2. Distance to the Nearest Station
3. Number of Convenience Stores
4. Latitude
5. Longitude

### Target Variable

**House Price of Unit Area**

## Dataset

The dataset contains **414 records** and includes real estate-related information such as house age, distance to the nearest station, number of convenience stores, latitude, longitude, and house price of unit area.

## Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Multiple Linear Regression
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Save Model using Pickle
   ↓
Flask Web Application
   ↓
House Price Prediction
```

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Flask
* Pickle
* HTML/CSS
* Jupyter Notebook

## Project Structure

```text
real-estate-price-prediction/
│
├── app.py
├── REPPModel.pkl
├── Realestate.csv
├── real_estate_price_prediction.ipynb
├── requirements.txt
├── README.md
│
└── templates/
    └── index.html
```

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/real-estate-price-prediction.git
```

Go to the project directory:

```bash
cd real-estate-price-prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the Flask application:

```bash
python app.py
```

Then open the following URL in your browser:

```text
http://127.0.0.1:5000/
```

## Model

The model is trained using:

```text
LinearRegression()
```

The trained model is saved as:

```text
REPPModel.pkl
```

## Prediction

Users provide:

* House Age
* Distance to Nearest Station
* Number of Convenience Stores
* Latitude
* Longitude

The Flask application passes these values to the trained model and displays the predicted **house price of unit area**.

## Future Improvements

* Improve model performance using additional regression algorithms
* Add data visualization to the web application
* Add model comparison
* Improve the user interface
* Deploy the application online

## Author

**Yogesh Vajanath Ankam**

B.Tech – Artificial Intelligence & Machine Learning
