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
