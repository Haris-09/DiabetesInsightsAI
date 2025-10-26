# DiabetesInsightsAI

Personal AI/ML project for managing type 2 diabetes through data analysis and predictive modeling. Uses logged data on blood glucose, blood pressure, exercise, and meals to provide insights, forecasts, and recommendations.

## Overview
This repository contains tools and models built with Python, leveraging AI, ML, Computer Vision, and Data Science to analyze personal diabetes management data. Started in October 2025, it's inspired by two months of logged metrics and aims to help optimize daily routines for better blood sugar control.

Key goals:
- Predict blood glucose levels based on inputs like meals and exercise.
- Visualize trends and correlations in health data.
- Automate meal analysis using computer vision (future feature).
- Generate personalized suggestions for meals, activities, and timings.

## Features
- **Blood Glucose Prediction Model**: ML-based forecasting using time series data (e.g., LSTM or random forests).
- **Interactive Dashboard**: Visualizations of trends, heatmaps, and anomalies with libraries like Plotly or Dash.
- **Meal Impact Analyzer**: CV for food recognition and nutrient estimation, linked to post-meal glucose changes.
- **Recommendation System**: AI suggestions for optimal routines.
- **Anomaly Detection**: Alerts for unusual patterns in blood sugar or pressure.
- **Chatbot Interface**: Conversational AI for querying data and advice.

## Data Structure
Data is logged in CSV format (or similar). Example columns:
- Timestamp
- Blood Glucose (mg/dL)
- Blood Pressure (systolic/diastolic)
- Exercise (type, duration, intensity)
- Meal (description, carbs, timing)
