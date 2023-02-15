# Project Title
Analysis of Air Quality in 10 Major US Cities
## Table of Contents
- [About](#about)
- [Questions](#questions)
- [Contributing](#contributing)
## About
This project uses a large amount of air quality data and we have shown ten major cities and their air quality patterns. We have determined which cities are the "best" in terms of air quality and which are the "worst".
## Questions
1) If I am prone to respiratory illness, what major city should I live in?
If you are prone to a respiratory illness you should live in San Antonio. To determine this, we gathered the Air Quality Index using the Air Pollution api on OpenWeatherMap.org. This data was available in hourly timesteps. We grouped the data by days, and determined a single value to be the maximum AQI reported in that 24 hour period. This is a similar style used by the Environmental Protection Agency. We ran two years of data to see if the there was any major differences between 2021 and 2022. In the end, we determined there were no major differences, so we choose to go with only 2022 data. To achieve our final verdict which we then ranked cities 1-10 to live in.
2) Is there a seasonal pattern to the air quality in two biggest major cities in 2022?
We analyzed the weather patterns for the two biggest cities on our list: New York and Los Angeles. We concluded that Los Angeles had the best weather from mid-spring to early fall. From the data we could not conclude that any season In New York City was vastly different than the others.
3) Can we identify a geographical pattern to air quality across the country?
Based on our data we determined that living in the middle part of the country was the best part of the country to live in. This is because the top four cities were located in that region. The east coast then ranked the second best to live in since they came in the middle three of our rankings. The west coast was determined to be the worst since they had little to no good days of air quality as all four cities came in on the bottom of our list.

