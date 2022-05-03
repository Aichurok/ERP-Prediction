# ERP-Prediction

***DATA***
To perform our research we choose SP 500 index and Treasury Bill as a risky and risk-free investment,
respectively. We use SP 500 index returns from Center for Research in Security Press(CRSP) and the
Treasury-bill rates, from 1926 to 2005, which gives 86 observations. The data contains 13 explanatory
variables and dependent variable Next Log Equity Risk Premium.
The first group of explanatory variables give information that relates to stock:
• Dividend Price Ratio is the difference between the log of dividend and the log of prices
• Dividend Yield is the difference between the log of dividends and the log of lagged prices
• Earnings Price Ratio is the difference between the log of earnings and the log of prices
• Stock Variance is calculated as sum of squared daily returns on the S&P 500
• Book-to-Market Ratio is the ratio of book value to market value
• Net Equity Expansion is the ratio of 12-month moving sums of net issues by NYSE listed stocks
divided by the total market capitalization of NYSE stocks
• Percent Equity Issuing is the ratio of equity issuing activity as a fraction of total issuing
The second group of explanatory variables provide information about interest-rate :
• Treasury-bill Rates
• The Default Return Spread is the difference between long-term corporate bond and long-term government
bond returns
• Default Yield Spread ) is the difference between BAA and AAA-rated corporate bond yields
• Long Term Rate of Returns
• The Term Spread is the difference between the long term yield on government bonds and the
Treasury-bill
• Inflation
***METHODOLOGY***
The Equity Risk Premium (ERP) is the extra return that’s available to equity investors above the return
they could get by investing in a risk-free investment. The higher ERP, the more odds that investors
would fill their portfolio with equities rather than with bonds. Hence, the accurate prediction of ERP is
crucial in order to make better investment decisions. So the aim of our research is to find which variables
could predict ERP more accurately and which adjustments we could make to improve the accuracy of
the models.
Our research use SP 500 index and Treasury Bill as a risky and risk-free investment, respectively.
Our data have 13 explanatory variables and the variable which we want to predict Next Log Equity Risk
Premium. To make predictions we use multiple linear regression and OLS method to obtain estimations
for unknown parameters.
The results of this paper found that model with all 13 explanatory variables have the best results for
R2, Adjusted R2, while the model with Net Equity Expansion and Dividend Yield variables have the best
results for AIC and BIC. Also we found that models’ prediction accuracy could be improved by adding
powers of fitted values and by splitting data into two dataset, the breakpoint is 1980.

***RESULTS***
In conclusion, there are two models which can be used to predict equity risk premium, the full model and
the model obtained by variable selection with Net Equity Expansion and Dividend Yield as explanatory
variables. However, the conducted tests tell that both models have omitted variables as powers
of fitted values from two to four. Thus, we can improve our models’ prediction accuracy by adding those
omitted variables.
Moreover, the Chow’s Tests detected that we have a structural change in our data before 1980 and
after 1980. So, two separate regression lines best fit a split set of data.
