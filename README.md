# EDA-Projects
**📊 Bank Marketing Campaign - EDA & Target Variable Analysis**
**📝 Project Overview**
This project performs an Exploratory Data Analysis (EDA) on a Bank Marketing Dataset to understand customer behavior and identify patterns that influence whether a client will subscribe to a term deposit (y - the target variable). The dataset contains marketing campaign data from a Portuguese banking institution.

🎯 Objective
Understand the structure and quality of the dataset.

Explore distributions and correlations between features.

Analyze the target variable (y) and its relationship with other variables.

Derive insights for potential predictive modeling.

📁 Dataset Description
The dataset includes various attributes related to:

Client Information: age, job, marital status, education, default status, balance, etc.

Campaign Data: contact method, number of contacts, days since last contact.

Socio-economic Indicators: employment variation rate, consumer price index, etc.

Target Variable:

y - whether the client has subscribed to a term deposit (binary: 'yes' or 'no').

🧰 Technologies Used
Python 🐍

Pandas – for data manipulation

NumPy – for numerical operations

Matplotlib & Seaborn – for data visualization

Jupyter Notebook / VS Code – development environment

🔍 Key Analysis Steps
**Loading and Inspection**

Checked null values, data types, and overall structure.

**Univariate Analysis**

Distribution plots of categorical and numerical variables.

**Bivariate Analysis**

Relationships between features and the target variable using:

Cross-tabulations

Boxplots

Countplots with hue

**Target Variable Analysis**

Class imbalance check (distribution of 'yes' vs 'no').

Variable importance via visual exploration.

**Correlation Heatmap**

Identified relationships between numerical variables.

**Insights & Recommendations**

Identified factors influencing target behavior.

Suggested features potentially useful for a predictive model.

##📈 Key Insights##
Job and education play a crucial role in determining the likelihood of subscribing.

Contact type and month also show distinct patterns in customer responses.

The dataset is imbalanced, with fewer "yes" responses, which is vital for future model selection.

✅ Next Steps (Suggestions)
Handle class imbalance using techniques like SMOTE or class weighting.

Train classification models (e.g., Logistic Regression, Random Forest).

Perform feature engineering and dimensionality reduction.

📂 Project Structure
arduino
Copy
Edit
bank_marketing_eda/
│
├── bank_marketing_data.csv
├── bank_marketing_eda.ipynb
├── README.md
└── plots/   # Saved visualizations (optional)
