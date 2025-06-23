# MSCS_634_Lab4_Regression_Models

# MSCS 634 – Lab 4: Regression Analysis with Regularization

## 🧪 Lab Overview
In this lab, I explored multiple regression techniques using the **Diabetes dataset** from `sklearn.datasets`. The main objective was to build models that predict disease progression based on various medical features and to evaluate how regularization can help reduce overfitting and improve performance.

## 📂 Files Included
- **Lab4_Regression_and_Regularization.ipynb**  
  This Jupyter Notebook contains all the code, model implementations, visualizations, and evaluation metrics.
- **README.md**  
  You're reading it! I’ve documented the purpose, process, insights, and challenges faced during the lab here.

---

## 🔍 Objectives
My goals for this lab were to:
- Implement and compare:
  - Simple Linear Regression
  - Multiple Linear Regression
  - Polynomial Regression
  - Ridge Regression
  - Lasso Regression
- Use and interpret evaluation metrics like:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)
- Visualize predictions and residuals for better understanding.
- Explore how regularization helps control model complexity and avoid overfitting.

---

## 📊 Key Insights
- I found that **Multiple Regression** performed better than Simple Linear Regression by utilizing all available features.
- **Polynomial Regression** showed improved accuracy at low degrees, but quickly began to overfit as the degree increased.
- **Ridge and Lasso Regression** both helped in managing overfitting. Ridge was effective in reducing model variance, while Lasso also performed feature selection by shrinking some coefficients to zero.
- Regularization played a key role in improving the generalization of the model.

---

## ⚠️ Challenges Faced
- It was tricky to determine the right degree for Polynomial Regression without overfitting.
- Selecting appropriate `alpha` values for Ridge and Lasso required experimentation and comparison.
- Visualizing model performance for high-dimensional regressions wasn’t straightforward, so I relied heavily on residual plots and performance metrics.

---

## 🛠️ Technologies Used
- Python 3
- Jupyter Notebook
- Libraries: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## ✅ How to Run
1. Clone or download this repository.
2. Open the file `Lab4_Regression_and_Regularization.ipynb` using Jupyter Notebook, JupyterLab, or Google Colab.
3. Run the cells sequentially to reproduce my results and visualizations.

---

## 📌 About Me
I'm currently enrolled in **MSCS 634 – Data Analytics** at the **University of the Cumberlands**.  
This lab is part of my coursework and was a valuable experience in understanding how different regression models perform and how regularization helps improve predictions.
