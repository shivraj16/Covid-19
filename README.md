# Covid-19
Predicting the total  number of confirmed cases of coronavirus in India on 15th May 2020

There are 3 files in this Repository 1. ExploratoryDataAnalysis.ipynb,2. PredictedModel.ipynb 3.PredictedModel2.ipynb
1.The ExploratoryDataAnalysis.ipynb compares the distribution of newly reported cases in the countries worst affected by the virus
2.The PredictedModel.ipynb contains the code for the 4th degree polynomial regression model we used for prediction 
3.The PredictedModel2.ipynb contains the code for a different Polynomial regression model of degree 5 which has a slight varience problem but could also make accurate predictions


We have considered the following factors before making the prediction:
1.From the observations and reports of several mathematicians the graph of total number of confirmed cases vs time is a Logistic curve
2.The logistic curve has a point of Inflection after which the rate of growth decreases(i.e the second derivative of the function is negative)
3.Most of the countries haven't reached the inflection point which means the number of confirmed cases is to be expected to rise rapidly
4.Although few countries who have managed to control/limit the spread of virus very well have passed  the inflection point
5.Countries like Australia and Germany are amongst the nations who have passed the inflection point the following 2 links will redirect     you to the graph of total number of confirmed cases in Germany and Australia respectively
  https://www.worldometers.info/coronavirus/country/germany/
  https://www.worldometers.info/coronavirus/country/australia/
6.The repository also contains the dataset used for training the prediction model
7.The dataset contains only the data until 28th April
8.We have also assumed that India will not reach its inflection point before 15th May 2020

