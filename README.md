# Financial-Data-ANOVA-Analysis
The report aims to investigate differences in daily realised volatility of the ASX market and assess potential seasonal effects where relevant 
There are essentially five parts of the report:
1. Exploratory Analysis to confirm effects of weekday and season of the year on realised volatility of the ASX market
2. Statistical evidence using two separate one-way ANOVA tests
3. Discussion on data cleaning and manipulation performed on the dataset
4. Two-way ANOVA test
5. Report Summary

The dataset involves notable columns below:
- ’Date’, which gives the date the data correspond to
- ’r data’, which is the log-return on that day
- ’rv data not scaled’, which is the calculated 5 min RV for that day. Each day’s 5 min RV is meant to be an accurate proxy of return volatility on that day
- Square root of RV on the percentage return scale
- A day of the week indicator
- Dummy variables for each day of the week
- A season indicator
- Dummy variables for each season
