# EDA-Reflection-Project
This is the Exploratory Data Analysis Project I created after learning EDA, for reflection and application purpose. 
## Objectives 
- Perform univariate analysis
- Perform bivariate analysis
- Visualize data distributions
- Explore relationships between variables
- Draw business insights from the data
## Tools Used 
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
## Files 
- EDA-Reflection-Project.ipynb: Main notebook containing the analysis.
## Key Findings 
CONCLUSION:
- Market segment shows the largest, most interpretable gap. Group bookings are cancelled about 4 times as often as Direct bookings (61% vs 15%). Long lead time is the strongest general warning sign. Deposit type has the highest single rate (Non Refund, 99.4%). 
- Groups booking segment and Non Refund deposit type establish highest correlation rate with cancellation.
- Seasonality does not exhibit strong correlation to cancellation (<50%>), but it has been shown that seasonality also differs for types of hotels (Resort > City)
- Notably, the correlation between Non Refund deposit type and cancellation is a surprising result, counter-intuitive and also contrary to the intitial hypothesis (Guests who pay a non-refundable deposit cancel less, because they would lose money.)
## Reflection
- Initially, I encountered my first hardship from choosing what variables to analyse and what insight should I find when doing this project. Then I ultilize Claude to generate me a guide pdf file on HOW should I determine my project objectives and HOW to choose suitable elements for analyzing their relationships.
- That's when I did the big question and the supplementary questions for each link, and also split up the variables into two groups (information-known-after-booking and before-booking), then I decided to analyze on the relationship of the information-known-before-booking with cancellation.
- In the process of executing analysis, I encounter another problem of "choosing what functions to use" and "how to report on the charts and graphs". But then I now acknowledge that how I report depends on the nature of the variables (numerical/ categorical) and also the objectives I am heading to.
- While doing the project, I also discover some new useful functions (groupby, crosstab, ...)
## Author Khoa Anh Thu Nguyen (Phan)
