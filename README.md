# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict house prices based on key features such as area, number of bedrooms, bathrooms, location, and property type.
It demonstrates the complete machine learning pipeline including data preprocessing, model training, evaluation, and visualization.

---

## 🎯 Objectives

* Build a predictive model for house prices
* Analyze the impact of different features on pricing
* Compare multiple machine learning algorithms
* Visualize model performance and insights

---

## 📊 Dataset Description

The dataset contains the following features:

* **Area** – Size of the property (in sq. ft.)
* **Bedrooms** – Number of bedrooms
* **Bathrooms** – Number of bathrooms
* **Age** – Age of the property
* **Location** – City Center / Suburb / Rural
* **Property Type** – House / Villa / Apartment
* **Price** – Target variable

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🧠 Machine Learning Models Used

* Linear Regression
* Random Forest Regressor

---

## 🔄 Workflow

1. **Data Loading & Exploration**

   * Checked dataset structure and missing values
   * Visualized relationships using pairplot

2. **Data Preprocessing**

   * Removed irrelevant columns
   * Handled missing values
   * Applied One-Hot Encoding for categorical variables

3. **Model Training**

   * Trained Linear Regression model
   * Trained Random Forest model

4. **Model Evaluation**

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)
   * R² Score

5. **Visualization**

   * Actual vs Predicted Prices
   * Feature Importance Graph
   * Residual Plot

---

## 📈 Results

| Model             | R² Score           |
| ----------------- | -------------------|
| Linear Regression | 0.9406371185112241 |
| Random Forest     | 0.9670554535338627 |

✔ Random Forest significantly outperformed Linear Regression
✔ Model explains ~96% of variance in house prices

---

## 🔍 Key Insights

* **Area** is the most influential feature affecting price
* **Location** plays a major role (City Center properties are costlier)
* **Property Type** impacts pricing (Villas > Houses > Apartments)
* **Age** has relatively less impact

---

## 📊 Visualizations

### 📌 Actual vs Predicted

* Shows strong alignment between predicted and actual values

### 📌 Feature Importance

* Highlights key contributing features

### 📌 Residual Plot

* Confirms model has minimal error patterns

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/varshh219/Week8-Assignment.git
cd house-price-prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook house_price_prediction.ipynb
```

---

## 📂 Project Structure

```
House-Price-Prediction/
│
├── house_price_prediction.ipynb
├── house_data.csv
├── predictions_vs_actual.png
├── feature_importance.png
├── model_evaluation_report.md
├── requirements.txt
└── README.md
```

---

## 💡 Future Improvements

* Hyperparameter tuning for better accuracy
* Deployment using Streamlit or Flask
* Integration with real-time housing datasets
* Feature engineering (price per sqft, location scoring)

---

---

## ⭐ Conclusion

This project successfully demonstrates how machine learning can be used to predict house prices with high accuracy.
The Random Forest model achieved excellent performance and provided valuable insights into key pricing factors.

---
