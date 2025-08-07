# 🏡 Task 3: Linear Regression - Housing Price Prediction

This project is part of the **AI & ML Internship Program** and focuses on building a **Simple & Multiple Linear Regression** model using the **Housing Price Dataset**.

---

## 📌 Objective

Implement and understand **simple and multiple linear regression** using Scikit-learn to predict house prices based on various features.

---

## 📁 Dataset

- Dataset Used: `Housing.csv`
- Features include: area, bedrooms, bathrooms, stories, parking, and categorical features like air conditioning, furnishing status, etc.

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📊 Steps Performed

1. **Data Loading & Exploration**
2. **Data Preprocessing**
   - One-hot encoding of categorical variables
3. **Splitting** the data into training and testing sets
4. **Training** a Linear Regression model using `sklearn.linear_model`
5. **Model Evaluation** using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
6. **Visualizations**:
   - Actual vs Predicted plot
   - Feature importance bar chart

---

## ✅ Results

- **MAE**: ~₹9.7 Lakhs
- **MSE**: 1.75 × 10¹²
- **R² Score**: 0.653

The model explains approximately **65.3% of the variance** in house prices.

---

## 📉 Key Insights

- Bathrooms, Air Conditioning, Hot Water Heating, and Preferred Area are among the most influential features.
- Linear regression provides a baseline model for understanding the data and relationships.

---

## 🧠 Concepts Practiced

- Regression Modeling
- Evaluation Metrics
- Feature Importance
- Model Interpretation
