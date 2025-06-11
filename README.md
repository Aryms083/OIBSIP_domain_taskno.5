# OIBSIP_domain_taskno.5
📌 Objective
Predict monthly sales amounts using historical advertising campaign data (e.g., from Advertising.csv), leveraging machine learning to model the relationship between ad spends and generated sales 

🔍 Steps Performed
Data Acquisition & Exploration

Loaded the dataset (typically featuring variables like TV, radio, newspaper budgets, and sales figures).

Conducted exploratory data analysis (scatter plots, correlation matrices) to understand relationships.

Data Cleaning & Preprocessing

Checked for missing values or outliers and handled them.

Scaled/normalized features if needed for model performance.

Modeling & Evaluation

Split the data into training and testing sets.

Trained regression algorithms—likely linear regression and possibly others (e.g., decision trees, random forest).

Evaluated models using metrics such as RMSE and R², comparing actual vs predicted sales.

Result Visualization

Visualized model fit and residuals.

Showed feature importance or regression coefficients to interpret the model.

🛠️ Tools & Libraries Used
Python ecosystem: pandas, NumPy, matplotlib, seaborn

Scikit-learn for modeling: regression models, train-test split, evaluation metrics

✅ Outcome
Developed a regression-based model that predicts ad-based sales with decent accuracy.

Demonstrated the influence of each advertising channel on total sales.

Provided insights into how marketing spend allocates impact across mass media platforms.

🧭 How to Use
Obtain the Advertising.csv dataset.

Install necessary dependencies:

nginx
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Run the notebook end-to-end:

EDA → Preprocessing → Modeling → Evaluation → Visualization

Plug in new ad-budget scenarios to estimate expected sales.

🚀 Conclusion
This notebook offers a clear, end-to-end tutorial: from data exploration to predictive modeling. It’s a useful starting point for anyone looking to analyze the ROI of advertising spend using regression techniques.

