# Student Performance Prediction (Machine Learning)

## Overview
This project predicts student exam scores using machine learning based on factors such as study hours, sleep patterns, attendance, and previous academic performance.

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Dataset Features
- Hours Studied
- Sleep Hours
- Attendance Percentage
- Previous Scores

---

## Models Used
- Linear Regression
- Random Forest Regressor

---

## Model Performance

| Model | R² Score | MAE |
|------|--------|-----|
| Linear Regression | 0.85 | 2.31 |
| Random Forest | 0.79 | 2.97 |

### Key Insight
Linear Regression outperformed Random Forest on this dataset, indicating a strong linear relationship between input features and exam scores. Simpler models generalized better due to the small dataset size.

---

## Visualization
- Scatter plot of actual vs predicted values  
- Feature importance (Random Forest)  
- Correlation heatmap  

---

## Key Learnings
- Multi-variable regression modeling  
- Model comparison and evaluation  
- Feature importance analysis  
- Data visualization techniques  

---

## Files
- `student-performance-ml-regression.ipynb` – Main notebook  
- Dataset file  

---

## Future Improvements
- Larger dataset  
- Hyperparameter tuning  
- Advanced models (XGBoost)
- 
