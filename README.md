# DengAI - Analysing the Effects of Climate on the Spread of Dengue
An accurate model to predict possible outbreaks of Dengue Fever enables a nation to equip itself in the fightagainst the disease. In this study,  we present a model capable of forecasting the emergence of Dengue cases. With the help of statistical and analytical techniques we gain insight into how the weather conditions and vegetation of a region affects the number of Dengue cases reported, enabling our model to performaccurate predictions about the outbreaks. These predictions would serve as an early warning estimate.

# Team Members
[Aditi Killedar](https://github.com/aditikilledar)

[Chandradhar Rao](https://github.com/chandradharrao)

[Dhruval PB](https://github.com/Dhruval360)

# Dataset
The dataset of choice is from the DengAI competition hosted on www.drivendata.org. The data for this competition comes from multiple sources aimed at supporting the ”Predict the Next Pandemic Initiative”. Dengue surveillance data is provided by the U.S. Centers for Disease Control and
prevention, as well as the Department of Defense’s Naval Medical Research Unit 6 and the Armed Forces Health Surveillance Center, in collaboration with the Peruvian government and U.S. universities. Environmental and climate data is provided by the National Oceanic and Atmospheric Administration (NOAA), an agency of the U.S.Department of Commerce. The Dataset consist of readings for the cities of San Juan, Puerto Rico and Iquitos, Peru.

# Files
1. [EDA.ipynb](./EDA.ipynb): Has our exploratory data analysis of the dataset.
2. [XGBoost.ipynb](./XGBoost.ipynb): Contains the XGBoost model and a Negative Binomial Regression model (used as a benchmark) trained on the dataset.
3. [AdaBoost.ipynb](./AdaBoost.ipynb): Contains the AdaBoost model trained on the dataset.