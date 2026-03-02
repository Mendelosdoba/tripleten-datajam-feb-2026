Has Inflation Permanently Changed Consumer Behavior in the U.S.?
Project Overview

This project investigates whether the inflation surge following COVID-19 permanently changed consumer behavior in the United States.

We analyze macroeconomic data from the Federal Reserve Economic Data (FRED) database to study how key economic indicators relate to three consumer behavior metrics:

Consumer Spending

Saving Rate

Consumer Credit

The project combines Data Science modeling and Business Intelligence visualization to provide both quantitative insights and clear visual storytelling.

Data Sources

All datasets were obtained from FRED (Federal Reserve Economic Data).

Key indicators used:

Real Personal Consumption Expenditures

Personal Saving Rate

Consumer Credit Owned

Inflation Index (CPI)

Federal Funds Interest Rate

Real Disposable Income

Unemployment Rate

These indicators allow us to analyze how economic conditions influence household financial behavior.

Methodology
Data Preparation

Datasets were cleaned and aligned by date

Economic indicators were merged into a single dataset

Only matching time periods were kept to ensure valid comparisons

Modeling Approach

We created linear regression models to estimate relationships between macroeconomic drivers and consumer behavior.

Three models were built:

Spending Model

Saving Model

Credit Model

Models were evaluated using:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

Model coefficients were also analyzed to understand how each economic factor influences behavior.

Key Findings
Spending

Inflation shows a strong positive relationship with spending.

Real disposable income increases consumer spending.

Unemployment has a strong negative effect.

This suggests inflation and income changes significantly influence spending behavior.

Saving

Inflation has a slight negative relationship with savings.

Disposable income has a positive effect.

This suggests higher inflation may reduce households' ability to save.

Credit

Credit usage increased during periods of economic stress, suggesting households may rely more on borrowing when purchasing power declines.

Business Intelligence Dashboard

A Tableau dashboard was created to visualize trends and relationships between macroeconomic indicators and consumer behavior.

Dashboard file:

Dashboard_of_COVID_impact.twbx

The dashboard provides visual exploration of:

Spending trends

Saving rate changes

Credit usage

Macroeconomic indicators over time

Repository Structure
data.ipynb                → Data analysis and modeling
*.csv                     → FRED macroeconomic datasets
Dashboard_of_COVID_impact.twbx → Tableau visualization dashboard
README.md                 → Project documentation
Team Contributions

Data Science (DS)

Data cleaning and integration

Model development

Regression analysis

Model evaluation

Business Intelligence (BIA)

Data visualization

Tableau dashboard development

Visual interpretation of trends

Tools Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Tableau

GitHub

Conclusion

The analysis suggests that inflation and macroeconomic shocks influence consumer behavior significantly. The post-COVID inflation period appears to have had measurable effects on spending, saving, and credit usage.

Combining statistical modeling with visualization helps provide a more complete understanding of these economic dynamics.



# tripleten-datajam-feb-2026
First screenshot from Dashboard_of_COVID_impact that shows a massive affect the pandemic had on savings while only a small affect on PCE and barely anything on credit:
<img width="1035" height="868" alt="Screenshot 2026-03-02 at 1 17 03 PM" src="https://github.com/user-attachments/assets/1ddac7dc-6b74-4299-b247-ead6ef8e0380" />
Second screenshot from Dashboard_of_COVID_impact that only shows post-COVID data. We can see that consuming habits and credit steadily go up while savings fluxuate greatly as inflation goes up and down.
<img width="1049" height="872" alt="Screenshot 2026-03-02 at 1 17 19 PM" src="https://github.com/user-attachments/assets/60b36dfd-b3a9-4dc8-8986-8489b61f93bc" />





