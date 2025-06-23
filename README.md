# Atliqo Bank Project: Credit Card Launch Strategy

### Project Overview
This project focuses on developing a data-driven strategy for Atliqo Bank, a new entrant in the Indian banking sector, to successfully launch a competitive credit card. Given the intense market competition and the bank's lack of primary customer data, the initiative involved leveraging secondary data to identify optimal target audiences, understand spending patterns, and design compelling credit card offers. A crucial phase of the project included validating the proposed offer's effectiveness through a controlled A/B test before a full-scale market launch.

### Problem Statement
Atliqo Bank faces the challenge of launching a new credit card in a highly competitive Indian market without existing customer data. The core problems addressed by this project include:

- Identifying Profitable Customer Segments: Determining which customer demographics and profiles are most likely to be receptive and profitable.
- Understanding Spending Behaviors and Payment Preferences: Analyzing existing transaction data to uncover insights into how customers spend and prefer to pay.
- Designing a Compelling Credit Card Offer: Crafting an offer that stands out from competitors and attracts the identified target audience, based on data-driven insights.
- Validating Offer Effectiveness: Conducting a controlled trial (A/B test) to statistically prove the new offer's impact before a widespread launch, minimizing risk and maximizing success.

### Key Features & Methodology
The project followed a structured analytical approach:

- Data Acquisition & Understanding: Utilized secondary customer, transaction, and credit data from data.lelo.
- Exploratory Data Analysis (EDA): Performed extensive data cleaning, handling missing values, outlier detection (e.g., in annual income and age), and feature engineering to prepare the data for analysis.
- Demographic Segmentation: Segmented the customer base based on age, income, region, and other relevant demographic factors to identify potential target groups.
- Spending Pattern Analysis: Analyzed transaction data to understand typical spending categories, average transaction amounts, and payment frequencies.
- Credit Profile Assessment: Evaluated credit scores and credit utilization to understand the financial health and risk profiles of different customer segments.
- A/B Testing Implementation: Designed and executed an A/B test with a control group (existing offer) and a test group (new credit card offer) to compare key metrics like average transaction amount.
- Statistical Hypothesis Testing: Applied t-tests (or similar appropriate tests) to determine the statistical significance of the differences observed between the control and test groups, validating the effectiveness of the new offer.

### Technologies Used
- Python: The primary programming language for data analysis.
- Jupyter Notebook: For interactive data analysis, visualization, and documentation.
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib: For static data visualizations.
- Seaborn: For enhanced statistical data visualizations.
- SciPy: For scientific computing and statistical functions (e.g., t-tests).
- Statsmodels: For statistical modeling and hypothesis testing.

### Outcome
The project successfully concluded that the proposed credit card offer led to a statistically significant increase in average transaction amounts compared to the existing offers. Through rigorous A/B testing and hypothesis validation (p-value less than significance level), the null hypothesis (no difference between groups) was rejected. This outcome provided strong quantitative evidence, leading to the recommendation and decision for Atliqo Bank to proceed with the full-scale launch of the new credit card.

### How to View
To view the analysis and insights:

- Clone this repository to your local machine.
- Ensure you have Python and Jupyter Notebook installed.
- Install the required libraries: pandas, numpy, matplotlib, seaborn, scipy, statsmodels. You can do this via pip:

pip install pandas numpy matplotlib seaborn scipy statsmodels

- Navigate to the project directory in your terminal.
- Run Jupyter Notebook:

jupyter notebook

- Open the Atliqo Bank Project - Maths and Stats.ipynb notebook from the Jupyter interface.
