# PlacementIQ

PlacementIQ is a machine learning-based system that estimates student placement readiness using a Gradient Boosting Regressor.

The system evaluates five career-related inputs — CGPA, DSA performance, communication skills, internship experience, and number of projects — and converts them into a readiness score through a trained machine learning pipeline.

The result is presented through an interactive web interface with visual insights and personalized improvement suggestions.

🔗 **Live Demo:** https://visva-dheeran06.github.io/placement-readiness-gb-model/


## Overview

PlacementIQ is designed to help students understand their current level of placement preparedness through a data-driven readiness assessment.

Instead of relying only on assumptions, the system evaluates multiple academic and skill-related factors and generates an estimated readiness score.

The current system focuses on five inputs:

1. **CGPA**
2. **DSA Performance**
3. **Communication Skills**
4. **Internship Experience**
5. **Number of Projects**

These inputs are preprocessed and passed through a trained Gradient Boosting model. The resulting score is presented through an interactive web interface along with visual insights and personalized suggestions.


## Key Features

- Placement readiness estimation using Gradient Boosting
- Five-factor student assessment
- Data preprocessing and feature scaling
- Interactive web interface
- Visual representation of prediction results
- Personalized improvement suggestions
- Feature importance analysis
- Trained machine learning model and preprocessing pipeline


## How It Works

The system follows the following pipeline:

```text
User Input
    ↓
Data Preprocessing
    ↓
MinMaxScaler
    ↓
Gradient Boosting Regressor
    ↓
Readiness Score
    ↓
Visual Insights
    ↓
Personalized Suggestions
