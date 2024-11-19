# Medical Insurance Price Prediction

This project predicts medical insurance charges based on user-specific attributes such as age, BMI, smoking status, region, and more. It leverages machine learning techniques to build a regression model that can assist insurance companies in pricing policies and identifying high-risk groups.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Technologies Used](#technologies-used)
4. [Project Workflow](#project-workflow)
5. [Key Features](#key-features)
6. [How to Use](#how-to-use)
7. [Deployment](#deployment)
8. [Future Enhancements](#future-enhancements)
9. [License](#license)

---

## Project Overview
The goal of this project is to:
- Predict medical insurance charges for individuals based on demographic and health factors.
- Provide insights into the key factors affecting insurance costs.
- Help insurance companies price policies more effectively and reduce risks.

---

## Dataset Description
The dataset used for this project contains 1,338 records with the following attributes:

| Column     | Description                                |
|------------|--------------------------------------------|
| `age`      | Age of the individual (18–64 years)       |
| `sex`      | Gender (`male`, `female`)                 |
| `bmi`      | Body Mass Index (16–53)                  |
| `children` | Number of dependents (0–5)               |
| `smoker`   | Smoking status (`yes`, `no`)             |
| `region`   | Residential region (`northeast`, etc.)    |
| `charges`  | Medical insurance charges (USD)          |

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- **Tools**:
  - Jupyter Notebook
  - Flask/Streamlit (for deployment)

---

## Project Workflow
1. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Encoded categorical features.
   - Scaled numerical features.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized correlations and distributions.
   - Analyzed key factors influencing `charges`.

3. **Model Training**:
   - Built regression models (Linear Regression, Random Forest, etc.).
   - Evaluated performance using RMSE and R².

4.**Future Improvisation**:
 **Deployment**:
   - Created a web interface for user interaction.
   - Deployed the model using Flask or Streamlit.

---

## Key Features
- Predicts insurance charges based on user inputs.
- Provides insights into key factors affecting costs.
- Interactive visualizations for better understanding.


