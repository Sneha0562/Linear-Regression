# 🔥 Calories Burned Prediction using Linear Regression

This project demonstrates how to use **Linear Regression** to predict the number of calories burned during physical activity using a simple dataset with basic preprocessing.

---

## 📘 Project Overview

The goal of this project is to predict **calories burned** based on various physical and workout-related features like age, weight, height, duration, heart rate, and temperature. This is a beginner-friendly machine learning project without advanced techniques like scaling or model evaluation metrics.

---

## 📊 Dataset Features

| Feature     | Description                          |
| ----------- | ------------------------------------ |
| Gender      | Categorical (male/female)            |
| Age         | Age in years                         |
| Height      | Height in cm                         |
| Weight      | Weight in kg                         |
| Duration    | Exercise duration in minutes         |
| Heart\_Rate | Average heart rate during activity   |
| Body\_Temp  | Body temperature in °C               |
| Calories    | 🔥 Calories burned (Target variable) |

---

## ⚙️ What’s Included

* Gender column is converted to numeric using `.map()`
* Used **LinearRegression** from `sklearn.linear_model`
* Performed **correlation analysis** to check feature relationships
* MAE for prediction

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Sneha0562/Linear-Regression.git
   cd Linear-Regression
   ```

2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook Calories_Burned_Prediction.ipynb
   ```

---

## 💡 Future Improvements

* Add model evaluation metrics like R², MAE, MSE
* Use feature scaling for better performance
* Deploy the model using Streamlit or Flask

---

## 👩‍💻 Author

**Sneha Hegde**
📍 MCA Student | Aspiring Data Scientist
[GitHub: @Sneha0562](https://github.com/Sneha0562)

---





