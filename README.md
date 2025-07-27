Code-Alpha-Internship-Task-3
📌 Overview
This repository contains the code and analysis for Task 3 of my CodeAlpha Data Analyst Internship.
The focus of this task was to perform Exploratory Data Analysis (EDA) and generate meaningful visualizations on the customer_data.csv dataset.

🎯 Primary Goals of this Task
Visualize the distribution of demographic and financial attributes.

Explore relationships between variables such as income, credit score, and annual mileage.

Identify trends, patterns, and anomalies in customer data.

Perform correlation analysis and visualize relationships using heatmaps and scatter plots.

Summarize key insights through statistical and visual analysis.

📂 Dataset
The dataset customer_data.csv contains 10,000 records with 19 columns, including demographic, financial, and behavioral information.

🔑 Key Columns:
Demographic attributes: age, gender, race, education

Financial attributes: income, credit_score

Vehicle details: vehicle_type, vehicle_year, annual_mileage

Behavioral data: speeding_violations, DUIs, past_accidents

Target variable: outcome

🛠 Steps Performed
1️⃣ Data Loading
Imported libraries such as pandas, numpy, matplotlib, seaborn.

Loaded dataset using pd.read_csv().

2️⃣ Data Exploration
Reviewed dataset structure using df.head(), df.info(), and df.describe().

3️⃣ Visualizations
Count plots of income groups and education levels.

Pie chart showing the proportion of customers by income class.

Histogram and distribution plots of credit_score and annual_mileage.

Scatter plot for Annual Mileage vs. Speeding Violations.

Heatmap of correlations among numeric features.

Boxplots for age distribution across income classes.

💡 Insights
Upper-class customers dominate in credit scores compared to other groups.

Annual mileage is mostly within 10,000 – 14,000 miles.

Positive correlation between some behavioral attributes (e.g., past accidents vs. speeding violations).

🚀 How to Run
Clone the repository:
git clone https://github.com/<your-username>/<your-repo>.git
Install dependencies:
pip install pandas numpy matplotlib seaborn
Run the notebook or script:
Open the Jupyter Notebook or .py file to explore the analysis and visualizations.

🖥 Technologies Used
Python Libraries: Pandas, NumPy, Matplotlib, Seaborn

Environment: Jupyter Notebook / Python 3.x

🙏 Acknowledgment
This project was completed as part of my CodeAlpha Data Analyst Internship (Task 3).
I am thankful to CodeAlpha for providing this opportunity and guidance.
