**Customer Churn Analysis (Python & Power BI)**
**Project Overview**
Customer churn is a critical business problem where customers stop using a company’s product or service.
This project aims to analyze customer behavior, identify key drivers of churn, and provide actionable insights using Python for data analysis and Power BI for visualization.

<img width="581" height="324" alt="image" src="https://github.com/user-attachments/assets/6c073904-042d-4fa7-a5a4-676e3205cff3" /> <img width="580" height="325" alt="image" src="https://github.com/user-attachments/assets/daa21a26-4ef5-45a6-88d0-f4418e4815ca" /> <img width="580" height="325" alt="image" src="https://github.com/user-attachments/assets/45ab4ee9-7a9e-4e5b-9c41-feaa6949e33b" /> <img width="580" height="325" alt="image" src="https://github.com/user-attachments/assets/c75b77b7-1c1f-4ce2-a5ef-509cb9198752" />




**Dataset Description**
The dataset contains customer-level information including:
-	Demographic attributes
-	Usage and transaction-related features
-	Cashback / engagement-related variables
-	Churn indicator (Churn = 1 means customer left)
The data was first explored and cleaned using Python, then imported into Power BI for visualization and insight generation.

**Exploratory Data Analysis (EDA)**
EDA was conducted in Python to understand the structure and quality of the data.
Key steps included:
-	Inspecting data types and missing values 
-	Analyzing distributions of numerical features
-	Understanding churn vs non-churn customer behavior
-	Identifying correlations between variables

**Data Cleaning & Preprocessing**
The following data cleaning steps were applied:
-	Handling missing values (using the median)
-	Removing or treating outliers where necessary
-	Ensuring correct data types
-	Preparing clean, analysis-ready data for visualization

All cleaning was completed before importing the dataset into Power BI, ensuring accurate and reliable insights.


 
 **Correlation Analysis (Heatmap)**
A correlation heatmap was created using Python to:
-	Identify strong positive and negative relationships
-	Detect multicollinearity between numerical variables
-	Highlight features potentially linked to churn behavior

This step helped prioritize variables for deeper analysis in Power BI and supported feature selection for modeling.

**Machine Learning: Churn Prediction Model**
A Decision Tree Classifier was implemented to predict customer churn.
A Decision Tree:
-	Handles non-linear relationships
-	Easy to interpret
-	Works well with mixed feature types
-	Suitable for business stakeholders

**Power BI Dashboard**
The Power BI report includes interactive visuals such as:
-	Churn rate overview KPIs
-	Churn distribution across customer segments
-	Cashback and engagement analysis
-	Heatmap insights translated into business-friendly visuals
-	Filters and slicers for dynamic exploration

**Key Insights**
-	New customers have the highest churn risk
-	Low cashback engagement strongly correlates with churn
-	Recency and complaints are powerful early churn indicators
-	 Behavioral factors outperform demographic variables
These insights can help businesses design targeted retention strategies.

**Business Recommendations**
-	Strengthen early / first-month customer onboarding
-	Introduce cashback-based retention incentives
-	Monitor complaints as churn warning signals
-	Trigger proactive retention campaigns for inactive customers exceeds 15–30 days

**Tools & Technologies**
-	Python (Pandas, NumPy, Matplotlib, Seaborn)
-	Power BI
-	Jupyter Notebook
-	GitHub

**How to Use This Project**
1.	Review the EDA and cleaning steps in the Python notebook

2.	Open churn analysis.pbix in Power BI Desktop

3.	Interact with filters and visuals to explore churn drivers

4.	Use insights to support business decisions and retention strategies

 **Conclusion**
This project demonstrates an end-to-end data analysis workflow, combining Python for data preparation and EDA with Power BI for visualization and storytelling.
The results provide clear, actionable insights into customer churn and highlight how analytics can drive business value.

