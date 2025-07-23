# 🚗 Car Price Prediction using Machine Learning

This project aims to predict the price of used cars based on various features using machine learning regression techniques. It is built using Python and popular data science libraries.

---

## 📌 Problem Statement

Given a dataset containing attributes of used cars such as brand, model, manufacturing, kilometers driven, fuel type, etc., build a machine learning model that accurately predicts the selling price.

---

## 📊 Dataset

The dataset was obtained from Kaggle and includes the following features:

- ID	
- Price
- Levy
- Manufacturer
- Model
- Prod. year
- Category
- Leather interior	
- Fuel type
- Engine volume
- Mileage
- Cylinders
- Gear box type
- Drive wheels
- Doors
- Wheel
- Color
- Airbags

---

## 🧠 Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data preprocessing
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Model building and evaluation

---

## 🛠️ Project Workflow

1. **Data Preprocessing**
   - Converted categorical features using Label Encoding
   - Feature selection

2. **Exploratory Data Analysis (EDA)**
   - Plotted distribution graphs, correlation matrix
   - Analyzed relationships between features and target

3. **Model Training**
   - Trained a **Random Forest Regressor** model
   - Split data into training and testing sets

4. **Model Evaluation**
   - Calculated model accuracy using:
     - R² Score
     - Root Mean Square Error (RMSE)

---

## ✅ Results

The Random Forest model was able to predict car prices with good accuracy. You can further improve results by trying:
- Ridge/Lasso Regression
- GridSearchCV for hyperparameter tuning

---

## 📁 File Structure
-car_price_prediction/
-├── car_price.ipynb   # Jupyter Notebook with code and results
-├── README.md   # Project summary

---

## 🚀 Future Enhancements

- Try advanced regression models (XGBoost)
- Deploy the model using Flask or Streamlit
- Add user interface for prediction inputs

---

## 👩‍💻 Author

**Shivani Nautiyal**  
📍 Rishikesh, Uttarakhand  
📧 [shivaninautiyal1812@gmail.com]
🔗 [LinkedIn](https://www.linkedin.com/in/shivani-nautiyal-18xyz) | 

---
