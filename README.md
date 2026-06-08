# Bank-Customer-Churn-Analysis

🏦 **Bank Customer Churn Analysis Using Pandas, Matplotlib, and Seaborn**

📖 **Project Overview**

Customer churn refers to customers who stop using a bank's services. Retaining existing customers is generally more cost-effective than acquiring new ones. This project analyzes customer data to identify patterns and factors contributing to customer churn.
Using Pandas, Matplotlib, and Seaborn, we perform data cleaning, exploratory data analysis (EDA), and visualization to uncover actionable business insights.

**🛠 Tools and Libraries Used**

🐼 Pandas - Data manipulation and analysis

🔢 NumPy - Numerical operations

📊 Matplotlib - Data visualization

🎨 Seaborn - Statistical visualization

📓 Jupyter Notebook - Development environment

**🗂 Dataset Description**

The dataset contains customer information from a bank.

**Column Name	    Description**

**CustomerId** -- Unique customer identifier

**Surname** -- Customer surname

**CreditScore** -- Credit score of customer

**Geography** -- Customer country

**Gender** -- Male/Female

**Age** -- Customer age

**Tenure** -- Number of years with bank

**Balance** -- Account balance

**NumOfProducts** -- Number of bank products

**HasCrCard** -- Credit card ownership

**IsActiveMember** -- Active membership status

**EstimatedSalary** -- Estimated annual salary

**Exited** -- Churn status (1 = Churned, 0 = Retained)

**🔄 Steps Followed**

1️⃣ 📥 **Data Collection**
•	Obtained the Bank Customer Churn dataset. 
•	Loaded the dataset into a Pandas DataFrame. 
2️⃣ 🔍 **Data Understanding**
•	Examined dataset structure, dimensions, and data types. 
•	Reviewed column descriptions and business context. 
3️⃣ 🧹 **Data Cleaning**
•	Checked for missing values and duplicates. 
•	Verified data quality and consistency. 
4️⃣ 📊 **Exploratory Data Analysis (EDA)**
•	Performed Univariate Analysis. 
•	Performed Bivariate Analysis. 
•	Performed Multivariate Analysis. 
•	Generated statistical summaries. 
5️⃣ 📈 **Data Visualization**
•	Created bar charts, histograms, pie charts, box plots, scatter plots, and heatmaps. 
•	Used subplots to compare multiple variables effectively. 
6️⃣ 📋 **GroupBy & Pivot Table Analysis**
•	Analyzed customer behavior using aggregation techniques. 
•	Summarized key metrics across customer segments. 
7️⃣ 🔥 **Correlation Analysis**
•	Examined relationships between numerical features. 
•	Identified variables strongly associated with churn. 
8️⃣ 💡 **Business Insights Generation**
•	Identified customer groups with higher churn probability. 
•	Discovered patterns related to age, geography, balance, and activity status. 
9️⃣ ✅ **Recommendations**
•	Suggested customer retention strategies. 
•	Proposed targeted engagement and loyalty initiatives. 
🔟 📝 **Documentation & Reporting**
•	Compiled findings, visualizations, insights, and recommendations into a structured report. 

💡 **Key Business Insights**

👥 **Customer Demographics**
•	Customers aged above 45 show higher churn rates. 
•	Female customers churn slightly more frequently. 

🌍 **Geographic Trends**
•	Germany has the highest churn rate. 
•	France shows the highest retention rate. 
💰 **Financial Behavior**
•	Customers with higher balances are more likely to churn. 
•	Credit score has limited impact on churn. 
🏦 **Banking Activity**
•	Inactive members have significantly higher churn rates. 
•	Customers with multiple products tend to remain loyal.

📊 **Visualizations Created**
📉 **Bar Charts**
Used for:
•	Customer Churn Distribution 
•	Churn by Gender
Purpose:
Compare categorical variables.

🥧 **Pie Chart**
Used for:
•	Gender Distribution 
Purpose:
Display proportion of male vs female customers.

📈 **Histogram**
Used for:
•	Age Distribution  
Purpose:
Understand distribution patterns.

📦 **Box Plots**
Used for:
•	IsActive vs Churn 
Purpose:
Identify outliers and spread of data.

🔵 **Scatter Plot**
Used for:
•	Age vs Balance 
Purpose:
Study relationships between numerical variables.

🔥 **Heatmap**
Used for:
•	Correlation Analysis 
Purpose:
Identify relationships among numerical features.

📊 **Count Plot**
Used for:
•	Geography vs Churn
Purpose:
Displays the frequency of categorical variables. 

📈 **Line Chart**
Used for:
•	Average Balance vs Tenure
Purpose:
Helps identify increasing or decreasing relationships.

🎻 **Violin Plot**
Used For
•	Age Distribution by Gender
Purpose:
Provides deeper insight into the spread of values.

🧩 **Pair Plot**
Used For
•	Age, Balance, Estimated Salary, and Churn Analysis
Purpose:
Displays pairwise relationships among multiple numerical variables.

📑 **Subplots**
Used For
•	Display multiple charts in a single figure for easier comparison.
Purpose:
Improved dashboard appearance and better comparison across variables.


⚡ **Interactive Plotly Visualization**
Used For
•	Interactive Age vs Balance Analysis
Purpose:
Allows zooming, filtering, and hovering over data points. Also, enhances user interaction with visualizations. 

📁 **Files Included**

The project consists of the following files and folders:
📈 Bank_Churn.csv – Original dataset used for customer churn analysis.
📊 Bank Customer Churn Analysis.ipynb - Jupyter Notebook containing data cleaning, EDA, visualizations, and analysis.
📜 README.md - Project overview, setup instructions, and documentation.

🚀 **How to Use**

1. Open Bank Customer Churn Analysis.ipynb using Jupyter Notebook or JupyterLab. 
2. Run the notebook cells step by step to view data cleaning, analysis, and visualizations. 
3. Modify the code to explore additional insights if needed.

✅ **Recommendations**

🎯 Improve Customer Engagement
•	Target inactive customers with loyalty programs. 
•	Increase personalized communication. 
🎁 Product Bundling
•	Encourage customers to use multiple banking products. 
🌍 Region-Specific Strategies
•	Focus retention campaigns in Germany. 
👨‍💼 High-Value Customer Retention
•	Monitor high-balance customers for early churn indicators.

📚 **Conclusion**

This Bank Customer Churn Analysis project provides a comprehensive understanding of customer behavior and churn patterns. By leveraging Python's data analysis and visualization libraries, banks can make data-driven decisions to improve customer retention, increase customer satisfaction, and enhance long-term profitability.

👤 **Author**

Revathy Menon | Aspiring Data Analyst
