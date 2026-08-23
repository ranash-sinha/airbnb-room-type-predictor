# Airbnb Room Type Predictor

A machine learning classification application that predicts the room type of an Airbnb listing based on listing, location, pricing, review, and availability features.

## Live Demo

https://airbnb-room-type-predictor-classification.onrender.com/

## Problem Statement

Predict whether an Airbnb listing is:

- Entire Home/Apartment
- Private Room
- Shared Room

## Machine Learning

- Python
- Pandas
- NumPy
- Scikit-learn
- Classification

## Model Performance

| Model | Accuracy | F1 Score |
|---|---:|---:|
| Logistic Regression | 66.3% | 0.526 |
| Decision Tree | 78.4% | 0.650 |
| Random Forest | **85.2%** | **0.736** |
| Gradient Boosting | 85.0% | 0.708 |

### Best Model

**Random Forest** achieved the best overall performance with:

- Accuracy: **85.2%**
- F1 Score: **0.736**

## Backend

- FastAPI
- Uvicorn
- REST API

## Deployment

- Render

## Input Features

- Latitude
- Longitude
- Neighbourhood
- Borough
- Price
- Minimum Nights
- Number of Reviews
- Reviews per Month
- Host Listings Count
- Availability

## ML Pipeline

Data → Preprocessing → Model → Prediction → FastAPI → Web Application

## Run Locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload
