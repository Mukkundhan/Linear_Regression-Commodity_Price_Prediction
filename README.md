# Linear_Regression-Commodity_Price_Prediction

# USO Price Prediction using Linear Regression

## Project Overview
This project implements a **Linear Regression model** to predict the **closing price of the US Oil Fund (USO ETF)** using historical market data. The goal is to understand the linear relationship between USO closing prices and its key trading indicators such as open price, high price, low price, and trading volume.

The project is implemented and executed in **Google Colab** using Python and standard data science libraries.

---

## Dataset Description
The dataset contains historical financial data related to commodities, indices, and ETFs. For this project, only the **USO-related features** are used.

The `Date` column is excluded from modeling as it is non-numeric.

---

## Methodology

1. **Data Loading**
   - Dataset is loaded using Pandas.
   - Initial inspection is performed to verify column names and structure.

2. **Data Preprocessing**
   - Non-numeric column (`Date`) is removed.
   - Relevant features and target variable are selected.

3. **Exploratory Data Analysis**
   - Correlation matrix is generated to analyze relationships between features and the target variable.
   - Scatter plots are used to visualize feature–target relationships.

4. **Model Building**
   - Linear Regression is implemented using `scikit-learn`.
   - Dataset is split into training (80%) and testing (20%) sets.

5. **Model Evaluation**
   - Model performance is evaluated using:
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)
     - R² Score

6. **Visualization**
   - Actual vs Predicted values are plotted to assess model performance.

---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Results and Conclusion
The Linear Regression model demonstrates a strong linear relationship between the USO closing price and its open, high, and low prices. Trading volume shows comparatively weaker influence. The model serves as a reliable baseline for commodity price prediction and can be extended using more advanced regression or time-series models.

---
