# Restaurant Turnover Prediction

This project uses machine learning to predict the annual turnover of restaurants based on business and location features.

## 📌 Objective
Assist restaurant owners or investors in estimating potential revenue using location, seating capacity, alcohol license, etc.

## 🛠 Tools & Technologies
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Linear Regression

## 📈 Process Overview
1. **EDA:**
   - Restaurants in major cities had higher turnover
   - Alcohol license and terrace seating positively impacted revenue

2. **Feature Engineering:**
   - Handled categorical variables
   - Applied standardization

3. **Modeling:**
   - Linear Regression for interpretability
   - Evaluated using MAE, RMSE, and R²
   - Checked for overfitting using test set

## 💡 Insights
- Alcohol license = Higher annual turnover
- Paris-based restaurants and those with more seating had better revenues

## 🚧 Challenges
- Multicollinearity and feature scaling needed special attention

## 🧠 Learnings
- Better understanding of regression evaluation metrics
- Learned to balance model complexity with interpretability

## 📁 Files
- `Restaurant_Turnover_Predictions.html` – Project code
- `Train_dataset.csv` – Training data
- `Test_dataset.csv` – Test data
- `Restaurant_Turnover_Predictions.csv` – Output .csv file
