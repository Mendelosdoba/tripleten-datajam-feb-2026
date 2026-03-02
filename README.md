Did Inflation Permanently Change U.S. Consumer Behavior?
Project Overview

This project analyzes whether the economic shocks following COVID-19 and the inflation surge led to a lasting change in how U.S. households spend, save, and borrow.

Using macroeconomic data from the Federal Reserve Economic Data (FRED) database, we compare pre-COVID trends with post-COVID outcomes to determine whether consumer financial behavior shifted structurally.

The project combines:

Counterfactual trend modeling

Regression analysis with macroeconomic drivers

Visualization of economic trends

A Tableau dashboard for interactive exploration

Data Sources

All datasets come from FRED (Federal Reserve Economic Data).

Key indicators used:

Consumer Behavior Variables

Real Personal Consumption Expenditures (consumer spending)

Personal Saving Rate

Consumer Credit Outstanding

Macroeconomic Drivers

CPI Inflation Index

Federal Funds Interest Rate

Real Disposable Personal Income

Unemployment Rate

Food CPI

Energy CPI

Shelter CPI

Average Hourly Earnings

Credit Card Delinquency Rate

The datasets were merged by date to create a unified time-series dataset.

Methodology
1. Counterfactual Analysis

To evaluate whether consumer behavior changed after COVID, we trained linear regression models using only pre-March 2020 data.

These models estimate what consumer behavior would have looked like if historical trends continued unchanged.

We then compared the predicted values with actual post-COVID observations.

Metrics used:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² (Coefficient of Determination)

2. Behavioral Models

We also estimated regression models linking consumer behavior to macroeconomic variables.

Three models were built:

Spending Model

Predictors:

Inflation Index

Real Disposable Income

Unemployment Rate

Saving Model

Predictors:

Inflation Index

Real Disposable Income

Credit Model

Predictors:

Federal Funds Rate

Real Disposable Income

These models help explain what economic forces drive spending, saving, and borrowing behavior.

Key Results
Consumer Spending

The counterfactual model trained on pre-COVID data performed poorly when predicting post-COVID spending:

R² ≈ 0.018

RMSE ≈ 981

MAE ≈ 898

This suggests that historical spending trends explain only about 1.8% of post-COVID variation, indicating a structural break in consumer spending behavior.

Regression analysis shows:

Spending increases with inflation

Spending increases with disposable income

Spending decreases with higher unemployment

Saving Rate

The saving model shows an even stronger structural shift:

R² < 0 (negative)

A negative R² means the historical trend performs worse than a simple average prediction.

During the pandemic:

Saving rates surged due to stimulus payments and reduced consumption opportunities

Later they fell sharply as inflation eroded purchasing power

This confirms that saving behavior changed dramatically during and after COVID.

Consumer Credit

Credit behavior shows a different pattern:

R² ≈ 0.338

About 34% of the variation in credit levels can still be explained by historical trends.

However, credit continued to rise even during periods of higher interest rates, suggesting households increasingly relied on borrowing to maintain consumption.

Regression results show:

Credit increases with higher interest rates

Credit increases with higher disposable income

This suggests borrowing remained strong despite rising financing costs.

Overall Conclusion

The analysis suggests that the post-COVID inflation shock led to a structural shift in household financial behavior.

Key observations:

Consumer spending recovered and remains near its historical trend

The saving rate remains structurally lower than expected

Consumer credit has risen above historical levels

These patterns indicate that households may be financing consumption differently than before, relying more on borrowing and less on savings.

This points to a lasting behavioral adjustment rather than a temporary disruption.

# tripleten-datajam-feb-2026






