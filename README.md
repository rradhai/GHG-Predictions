# GHG-Predictions
GHGRP Emissions Report to EPA - Trends and Predictions

About this project:
In this project, we used the data from GHGRP Emission report to EPA. GHGRP has collected data from various facilities in each state and submitted the report to EPA. 
GHGRP typically requires reporting of greenhouse gas (GHG) data and other relevant information from
- large GHG emission sources, 
- fuel and industrial gas suppliers, 
- and CO2 injection sites in the United States.
Approximately 8,000 facilities are required to report their emissions annually.

Facilities in the data we used come from the the following sectors
- Direct emitters: the facilities that combusts fuels or otherwise put GHG into the atmosphere directly
- SF6 - Sulphur Hexa Flouride emissions (SF6 is  a highly non-decomposable gas which is thousands of times more powerful than CO2 in holding the radiation in the atmosphere.)
- Direct Emissions by Local distribution companies of natural gases.
- Emission by Onshore Oil and Gas production.

Data Citation: U.S. Environmental Protection Agency Office of Atmospheric Programs Greenhouse Gas Reporting Program (GHGRP) [Compressed file contains a multi-year data summary spreadsheet containing the most important, high-level information for facilities, as well as yearly spreadsheets containing slightly more detailed information than the multi-year summary, including reported emissions by greenhouse gas and process.] Available at https://www.epa.gov/ghgreporting/data-sets Date accessed: [September, 2021]

Data Wrangling: 
The data was clean for the most part, expect for a few column name changes and a few missing values. Missing values were replaced by the mean of their group category.

Models are built using the following Algorithms:
- OLS Linear Regression
- Random Forest
- Multioutput Ridge Regressor
- Multioutput Random Forest Regressor

(Though the data is about the emissions overtime, we didn’t choose time series modelling since all we had was yearly data which wasn’t enough for a evaluating a time series model.)
Best Model: Random Forest was chosen for building the prediction model for its good R2 score (close to perfect) and its comparatively reasonable fit time.

Findings and Recommendations:

- The trends and predictions  made are based on the available data and how the emissions are handled in the decade 2011 - 2020. 
- They show that many states are heading positively towards reducing the emissions. 
- Also, with the advanced techniques and equipments that will be available in the near future,  the trend can be changed and so the emissions can be brought down more rapidly. 





  



