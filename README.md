# Predicting global migration flows

Global migration is both an old and a new complex social phenomenon. It is old because migration is as old as humanity itself - and it is new because globalisation and rapid technological progress have made it a ubiquitous fact of modern life. Our motivation for this statistical analysis is simple: can we predict whether a country will experience an inflow or an outflow of migrants and how large this population change will be relative to its total population in a given year? We consider indicators of a country's wealth, income inequality, human development, conflict, democracy, human rights and geographical region to make predictions. 

The report is structured as follows: we will first assess the ethical implications and challenges of our project. Then, we will provide a brief introduction into the dataset and perform some basic exploratory data analysis. As a baseline model, we consider multiple linear regression and compare this model to other machine learning techniques with varying degrees of flexibility and interpretability. In total, we compare a single decision tree, random Forest regression, extreme gradient boosting, a neural network, ridge regression and the lasso. At the end, we address the limitations and remaining uncertainties of our analysis.

The model with the best predictive accuracy used in this analysis was the extreme gradient boost. The variables that turned out to be most important for predicting migration across all models were GDP per capita, Democracy Index, Child Mortality Rate, GDP growth, Income level and Human Development.

Data obtained from:
World Bank, "World Bank Open Data" The World Bank Group, accessed May 22, 2021, https://data.worldbank.org/.
