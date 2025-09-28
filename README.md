# 🏡 House Price Prediction

This project implements **Linear Regression, Ridge, and Lasso models** to predict California house prices using key features and engineered ratios. The notebook includes data preprocessing, feature engineering, model training, evaluation, and visualization.

## 📊 Dataset

The dataset contains information such as location, median income, housing age, number of rooms/bedrooms, population, and median house value.  
**File:** `housing.csv`  
**Source:** [California Housing Dataset](https://raw.githubusercontent.com/ageron/handson-ml/master/datasets/housing/housing.csv)

---

## 🔑 Features Used

- `median_income`  
- `housing_median_age`  
- `RoomsPerHousehold` (engineered)  
- `BedroomsPerRoom` (engineered)  
- `PopulationPerHousehold` (engineered)

---

## 🧰 Models Trained

- **Linear Regression**  
- **Ridge Regression**  
- **Lasso Regression**

---

## 📈 Visualizations

- Correlation heatmap of features  
- Predicted vs Actual prices plot  
- Residuals distribution  
- Feature importance table

---

## 📊 Results & Insights

- **Median income** is the strongest predictor of house prices.  
- Engineered features improve model interpretability.  
- Residuals are centered around zero, indicating minimal bias.  
- Regularization stabilizes coefficients without major performance changes.  
- The models explain a significant portion of variance in house prices.

**Next Step:** Advanced models like Random Forest or Gradient Boosting could further improve prediction accuracy.

---

## 🚀 How to Run

1. Open the notebook `House_Price_Prediction.ipynb` in **Google Colab**.  
2. Upload the `housing.csv` dataset to the same folder or Colab environment.  
3. Run all cells to reproduce results and visualizations.

---

## 📝 License

This project is for educational purposes and internship submission.
