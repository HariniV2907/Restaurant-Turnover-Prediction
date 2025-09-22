# 🍴 Restaurant Annual Turnover Prediction  

## 📌 Context  
India’s food scene is vast and diverse — from bustling street stalls to 5-star fine dining. For Indians, dining out is a **joyous occasion**, with restaurants being chosen for various reasons like taste, ambience, nostalgia, or popularity.  

From a **business perspective**, a restaurant’s **popularity directly impacts its annual turnover**. To survive and thrive, restaurants need strong turnover, which depends on factors such as:  
- Location and neighbourhood  
- Cuisine type and themes  
- Social media popularity  
- Ratings from platforms like Zomato  
- Customer surveys and mystery visitor audits  

This project aims to **predict the annual turnover** of restaurants across India using a rich dataset that combines operational details, customer insights, and external popularity indicators.  

---

## 🎯 Goal  
To build a machine learning model that predicts the **Annual Turnover** of restaurants based on the provided variables.  

---

## 📊 Dataset Information  
The dataset is split into two parts:  

- **Train Dataset** – Includes restaurant details and their actual turnover values.  
- **Test Dataset** – Includes restaurant details but without turnover values. The goal is to predict these.  
- **Data Dictionary.csv** – Provides descriptions of all variables included in the datasets.  

---

## 📑 Data Fields (Examples)  
- `Registration Number` – Unique restaurant ID  
- `Location` – Restaurant location (city/area)  
- `Opening Date` – When the restaurant started operations  
- `Cuisine Type` – Primary cuisine offered  
- `Theme` – Restaurant’s theme/ambience  
- `Social Media Popularity Index` – Popularity score from online platforms  
- `Zomato Rating` – Average customer rating  
- `Customer Survey Data` – Survey feedback from customers  
- `Mystery Visitor Rating` – Independent third-party audit rating  
- `Turnover` – **Target variable (Annual Turnover in Train dataset only)**  

---

## 📌 Evaluation Metric  
The model performance will be evaluated using **RMSE (Root Mean Squared Error)**.  
- Lower RMSE → Better predictions.  
- Predictions in the Test dataset will be compared with actual turnover values.  

---

## 📂 Submission Format  
The final submission file should be a **CSV** with:  
- Exactly **500 rows + header row**  
- Exactly **two columns**:  

| Registration Number | Annual Turnover |
|---------------------|-----------------|
| R001                | 123456          |
| R002                | 987654          |
| ...                 | ...             |

---

## 🚀 Approach  
1. Perform **EDA** to understand the factors influencing turnover.  
2. Preprocess data (handle missing values, categorical encoding, feature scaling).  
3. Experiment with **ML models**: Linear Regression, Random Forest, Gradient Boosting, XGBoost.  
4. Tune hyperparameters for optimal performance.  
5. Evaluate on **RMSE metric**.  
6. Generate predictions on Test dataset and prepare submission file.  

---

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Pandas / NumPy** – Data processing  
- **Matplotlib / Seaborn** – Visualization  
- **Scikit-learn / XGBoost / LightGBM** – Modeling  
- **Jupyter Notebook** – Development  

---

## 📌 Expected Outcomes  
- Predict restaurant annual turnover with minimal RMSE.  
- Identify **key drivers** of turnover such as location, cuisine, ratings, and popularity.  
- Provide insights for restaurant owners and investors on factors contributing to financial success.  

---

## 📁 Files
- `Restaurant_Turnover_Predictions.html` – Project code
- `Train_dataset.csv` – Training data
- `Test_dataset.csv` – Test data
- `Restaurant_Turnover_Predictions.csv` – Output .csv file
