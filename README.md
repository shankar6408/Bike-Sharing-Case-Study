# Bike-Sharing-Case-Study
A linear regression model to analyze which attributes could impact the bike sharing business
# Problem Statement:
BoomBikes, a US-based bike-sharing provider, has faced significant revenue losses due to the COVID-19 pandemic. To recover, the company aims to devise a business plan by analyzing the demand for shared bikes post-lockdown. They seek to understand the factors influencing bike demand to effectively cater to customer needs, outperform competitors, and maximize profits.

*Objective:*
Using a large dataset on daily bike demand and influencing factors, develop a predictive model to:

- Identify significant variables affecting bike demand.
- Assess how these variables explain demand patterns.

*Business Goal:*
The model will guide BoomBikes in adjusting their business strategy, aligning with customer expectations, and understanding demand dynamics in new markets.

# Conclusion
# *Above coefficients formed with datamodel lm_rfe1 explains the data and its variance very well with vif<2 for all variables and variance explained up to ~80%*
- The equation formed would be
    - ## *cnt = 0.213365 + yr(0.228534) + holiday(-0.088259) + temp(0.596490) + hum(-0.153819) + windspeed(-0.193985) + mist_cloudy(-0.050166) + rainy(-0.232719) + summer(0.075578) + winter(0.135617)*
- year, temperature, summer and winter are directly proportional to count wheres holiday, humidity, cloudy day, rainy days impacted the count inversely.