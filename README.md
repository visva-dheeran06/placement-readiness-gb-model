# placement-readiness-gb-model
PlacementIQ — AI-powered system that predicts placement readiness using a Gradient Boosting model and delivers personalized insights via an interactive dashboard.

PlacementIQ — Placement Readiness Predictor

PlacementIQ is a machine learning-based system that predicts how ready a student is for placements. It uses a trained Gradient Boosting model to evaluate key academic and skill-based inputs and presents the result through a simple, interactive web interface.

The goal of this project is to move beyond assumptions and provide a data-driven view of placement preparedness.

Overview

This system takes five inputs from a user:

1.CGPA
2.DSA performance
3.Communication skills
4.Internship experience
5.Number of projects

These inputs are scaled and passed into a trained Gradient Boosting model. The model generates a readiness score, which is then visualized through charts and structured feedback.

Model Details
Algorithm: Gradient Boosting Regressor
Number of trees: 200
Learning rate: 0.05
Accuracy: R² ≈ 0.97

Feature importance observed during training:

DSA Score: 62%
CGPA: 17%
Internship Experience: 14%
Projects: 4.5%
Communication Skills: 2.6%

The model indicates that problem-solving ability (DSA) has the highest impact on placement readiness.

How It Works
The user provides input through the web interface.
Data is normalized using MinMaxScaler.
The trained model processes the input.
A readiness score is generated.
The result is displayed along with visual insights and suggestions.
Project Structure

PlacementIQ

frontend → HTML, CSS, JavaScript files
model → trained model and scaler (.pkl files)
notebook → Jupyter notebook used for training
results → generated plots and visual outputs
Technologies Used
Frontend: HTML, CSS, JavaScript
Visualization: Chart.js
Machine Learning: Python, scikit-learn

Purpose

This project is designed to help students understand where they stand in terms of placement readiness and identify areas that need improvement. It provides a structured, data-backed perspective instead of relying on guesswork.
