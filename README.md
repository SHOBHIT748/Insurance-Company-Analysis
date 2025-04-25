🏢 Insurance Company Analysis

Tools Used: Power BI, Python (Pandas, Matplotlib, NLTK/TextBlob)

Project Focus: Risk Profiling, Customer Insights & Business Intelligence

🔍 Overview

This project delivers a detailed analysis of an insurance company's dataset using both Power BI and Python libraries. The objective is to extract valuable insights into customer behavior, financial performance, and claim activity. These insights support data-driven decision-making, optimize claim processing, and enhance strategic planning.

🧹 Data Preparation

To ensure accuracy and consistency in analysis, the dataset underwent a comprehensive cleaning, transformation, and preprocessing phase. The key preparation steps included:

Handling missing or inconsistent values

Standardizing column formats for dates, numerical entries, and text

Creating age-based groupings for customer segmentation

Deriving new metrics such as active/inactive policy status, total claims per policy, and customer tenure

Removing duplicate entries and irrelevant records

Normalizing categorical fields including gender, policy type, and claim status

Data transformation was performed using both Power Query Editor (in Power BI) and Python (Pandas).

📌 Key Insights & Features

Active vs Inactive Policies
Analyzed policy status to evaluate customer retention and engagement patterns. This helped highlight the percentage of customers currently engaged with the insurer.

Policy Type Distribution
Categorized policies into major types such as Health, Auto, Home, and Life to identify the most common products and evaluate their relative performance.

Financial Metrics
Assessed and compared the following financial indicators:

Premiums paid by customers

Coverage amounts offered by the company

Claim amounts submitted by policyholders

The visual comparisons helped identify gaps between risk coverage, premiums collected, and actual claims, enabling better risk pricing strategies.

Gender-Based Analysis
Investigated differences in policy ownership, claim behavior, and premium contribution between male and female policyholders. This provided meaningful insights for demographic-based targeting and product design.

Claim Status Evaluation
Claims were analyzed across three categories: Approved, Rejected, and Pending. This helped assess operational efficiency and pinpoint where delays or inconsistencies might occur.

Claim Amount by Age Group
Divided customers into age brackets (18–30, 31–45, 46–60, 60+) to explore how age affects claim amounts and behavior. This analysis supported actuarial evaluations and targeted policy structuring.

Matrix Visualization
Generated a correlation matrix heatmap to visualize relationships between numeric fields such as age, premium, coverage, and claim amount. The matrix helped identify patterns and multicollinearity between variables.

Sentiment Analysis
Customer feedback was analyzed using TextBlob to classify sentiments into positive, neutral, or negative. Word clouds and sentiment score distributions were also created to visualize overall customer perception and areas for improvement.

📁  Files Included

Insurance Project.pbix – The main Power BI report file.

InsuranceData.csv – Cleaned dataset used for analysis

Customer Feedback.csv  - Dataset of reviews


📸 Screenshots

![image](https://github.com/user-attachments/assets/66560071-4d73-484b-98f5-5b0fe786120b)




