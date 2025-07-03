📊 Financial Inclusion in South Africa
This project investigates financial inclusion trends in South Africa using open financial datasets. It includes data cleaning, analysis, dashboards, and a machine learning model to predict loan default risk.

🧰 Tools & Technologies
Python (Pandas, Seaborn, Scikit-learn)

Power BI (interactive dashboard)

Tableau (storytelling dashboard)

Jupyter Notebook

Open financial datasets (Global Findex, SARB, Stats SA)

🎯 Project Objectives
Understand disparities in access to banking & credit

Identify socio-economic factors behind exclusion

Predict likelihood of loan default using ML

Present findings through clear visual dashboards

📁 Project Structure
bash
Copy
Edit
financial-inclusion/
├── data/
│   └── cleaned_financial_data.csv
├── notebooks/
│   └── financial_analysis.ipynb
├── dashboards/
│   ├── powerbi_dashboard.pbix
│   └── tableau_dashboard.twbx
└── model/
    └── loan_default_model.py
🧼 Data Cleaning
Performed in Python:

Filled missing income/employment values

Removed duplicates & irrelevant columns

Categorical encoding and normalization

📊 Power BI Dashboard
Key insights:

% unbanked by age & gender

Credit access vs. income level

Map of underserved provinces

💡 Screenshot goes here (add .png file to dashboards/ folder)

📈 Tableau Dashboard
A storytelling dashboard highlighting:

How financial access has changed over time

Correlation between education and credit access

💡 Add your Tableau screenshots or embed GIF previews

🤖 ML Model – Loan Default Prediction
Python model using:

Logistic Regression & Decision Trees

Features: income, employment, age, credit history

Output: likelihood of default

bash
Copy
Edit
# Run model
python model/loan_default_model.py
Result: ~82% accuracy on test data

💬 Key Findings
Youth (18–25) and informal workers are underbanked

Education strongly correlates with financial access

Default risk is higher among low-income, unemployed users

🙋‍♀️ Author
Ivy Sadiki
Senior Test Analyst | Data & Automation Enthusiast
🔗 GitHub Profile
