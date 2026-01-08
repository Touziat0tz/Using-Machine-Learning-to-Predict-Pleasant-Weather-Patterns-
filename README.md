# Using Machine Learning to Predict Pleasant Weather Patterns

## Project Overview
This project explores how supervised machine learning models can be used to predict **pleasant weather conditions** across European cities. The analysis was conducted as part of the **ClimateWins Weather Prediction Project**, with the goal of comparing different classification algorithms and understanding their strengths, limitations, and optimization requirements.

The target variable was pre-labeled (pleasant vs. not pleasant), making this a supervised classification problem.

---

## Objectives
- Predict pleasant weather conditions using historical climate data  
- Compare multiple supervised learning algorithms  
- Evaluate the impact of data scaling and feature selection  
- Understand trade-offs between model accuracy, interpretability, and computational cost  

---

## Research Hypotheses
- Supervised machine learning models can classify pleasant vs. unpleasant weather  
- Feature selection and data scaling improve model performance  
- KNN and ANN models will outperform Decision Trees  

---

## Data Description
- Historical European weather data provided by ClimateWins  
- Multiple weather stations representing different cities  
- Features include temperature and other weather-related variables  
- Target variable: **pleasant weather (binary classification)**  

---

## Data Preparation & Optimization
- Removed weather stations with insufficient data  
- Dropped non-predictive variables (e.g., DATE, MONTH)  
- Tested both scaled and unscaled datasets  
- Applied train-test split for model evaluation  

These steps helped reduce noise, improve generalization, and minimize overfitting.

---

## Models Used
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Artificial Neural Network (ANN)**

### Optimization Techniques
- Feature selection
- Data scaling
- Gradient Descent (used for ANN optimization)
- Hyperparameter tuning

---

## Model Performance Summary

| Model | Average Accuracy | Key Notes |
|------|-----------------|-----------|
| KNN | ~88–89% | Best overall performance, efficient and effective |
| ANN | ~85–90% | Strong performance, captures non-linear patterns |
| Decision Tree | ~40–46% | Lower performance due to overfitting |

---

## Key Findings
- Scaled data improved overall model performance  
- KNN provided the best balance between accuracy and efficiency  
- ANN captured complex weather patterns but required higher computational cost  
- Decision Trees struggled to generalize complex climate data  
- Comparing multiple models leads to better decision-making  

---

## Limitations
- Data quality and availability constraints  
- Sensitivity to feature selection  
- Higher computational cost for ANN  
- Limited geographic coverage  

---

## Post-Processing & Future Work
- Error analysis and model retraining  
- Continuous performance monitoring  
- Incorporate more recent climate data  
- Expand geographic coverage  
- Explore ensemble learning and advanced neural networks  

---

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Machine Learning (Supervised Learning)  
 

