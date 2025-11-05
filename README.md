

# 📊 Advertising Sales Prediction using Machine Learning

## 🧠 Overview
This project focuses on predicting product sales based on advertising expenditure across various media — **TV, Radio, and Newspaper**.  
The objective is to understand how marketing budgets influence sales and to build a **Linear Regression model** that accurately predicts future sales.

---

## 🧰 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📂 Dataset
The dataset contains information about advertising spending and corresponding sales figures.

| Feature | Description |
|----------|-------------|
| TV | Advertising budget spent on TV (in thousands of dollars) |
| Radio | Advertising budget spent on Radio (in thousands of dollars) |
| Newspaper | Advertising budget spent on Newspaper (in thousands of dollars) |
| Sales | Product sales (in thousands of units) |

---

## ⚙️ Project Workflow
1. **Data Loading & Exploration**  
   - Imported and examined the dataset  
   - Checked for missing values and outliers  

2. **Data Visualization (EDA)**  
   - Used Matplotlib & Seaborn to visualize relationships  
   - Found strong correlation between **TV advertising** and **Sales**

3. **Feature Selection & Splitting**  
   - Selected TV, Radio, and Newspaper as independent variables  
   - Split dataset into training and testing sets (80:20)

4. **Model Training**  
   - Trained a **Linear Regression model** using Scikit-learn  

5. **Model Evaluation**  
   - Calculated R², MAE, MSE, and RMSE to evaluate performance  
   - Achieved R² ≈ **0.95** indicating excellent model fit  

6. **Prediction**  
   - Predicted future sales values using trained model  
   - Compared actual vs predicted values using scatter plots  

---

## 📈 Results
- **Best Performing Model:** Linear Regression  
- **R² Score:** ~0.95  
- **MAE:** ~1.2  
- **RMSE:** ~1.5  
- **Key Insight:** TV advertising has the most significant impact on product sales  

---

## 🖼️ Visualizations
- Pairplot and heatmap showing correlation  
- Actual vs Predicted Sales comparison  
- Regression line visualization  

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Advertising-Sales-Prediction.git
   cd Advertising-Sales-Prediction
