# **AdRevenue-AI: Sales Prediction Using Advertising Expenditures**

## **Project Overview**
AdRevenue-AI is a machine learning project that predicts product sales based on advertising expenditures across TV, Radio, and Newspapers. The project leverages linear regression to analyze advertising impact and optimize marketing strategies.

---

## **Features**
- Predict product sales using advertising data.
- Identify the most impactful advertising medium.
- Improve model performance through normalization.
- Visualize insights into advertising effectiveness.

---

## **Dataset**
The dataset includes 200 records with the following fields:
- **Campaign**: Identifier for each advertising campaign.
- **TV**: Advertising expenditure on TV.
- **Radio**: Advertising expenditure on Radio.
- **Newspaper**: Advertising expenditure on Newspapers.
- **Sales**: Units sold corresponding to advertising.

Key insights:
- **TV ads** have the highest impact on sales, with the highest R² score.
- **Radio ads** show moderate correlation with sales (Pearson: 0.35, Spearman: 0.34).

---

## **Technical Details**
1. **Exploratory Data Analysis**:
   - Imputed missing values for Radio expenditures with the column mean.
   - Visualized advertising expenditures and their impact on sales.

2. **Model Training**:
   - Linear regression achieved **R² = 0.909** and **Adjusted R² = 0.901**.
   - Normalization improved model performance slightly.

3. **Prediction**:
   - Sales predicted for a new advertising budget (TV=$200, Radio=$40, Newspaper=$50): **~20.5 units**.

---

## **Technologies Used**
- **Python**: Programming language
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tools**: Jupyter Notebook

---

## **Results**
- **TV advertising** is the most significant predictor of sales, with a strong R² score of **0.909**.
- **Normalization** slightly improved the model's performance, aligning feature scales.
- Excluding TV from predictors dropped the R² score to **0.119**, showing its critical role.
- Predicting sales for new advertising budgets (TV=$200, Radio=$40, Newspaper=$50) gave **~20.5 units**.

---

## **Future Scope**
- **Additional Advertising Platforms**: Incorporate digital advertising data for a holistic analysis.
- **Advanced Machine Learning Models**: Experiment with Ridge Regression, Random Forests, or Neural Networks for better accuracy.
- **Web Interface**: Build an interactive web app for real-time sales predictions.
- **Cost Optimization Analysis**: Recommend optimal budgets for maximum sales impact.

---
