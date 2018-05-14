Introduction:
DengAI is a machine learning project with the goal of predicting the spread of Dengue fever across the globe. Specifically, the aim of the project is to predict the next pandemic of the disease before it occurs in San Juan, Puerto Rico or Iquitos, Peru. Dengue fever is primarily transmitted through mosquitos carrying the disease, and it is therefore highly dependent on climate and vegetation factors.

Setup:
Language used : Python 
Put the *.ipynb inside your anaconda workspace and open this file.

Data set: [Dengue Data](https://github.com/dhwanikaneria/DenguePrediction/tree/master/Data)

Feature Engineering:
It is the process to make Algorithms of Machine Learning efficient by introducing new features to the dataset or transforming our features.
From observing the dataset, we found that cases recorded for a given week are not the result of that week but of the previous week. The most likely reason for this is that the incubation period is 4-7 days. Therefore the infection in the given week is directly related to previous week.
To apply this on the dataset, we shifted data by one week. We experimented with shifting data by 1 week, 2 weeks, and 3 weeks to get an idea regarding how the data pattern is effected by time period.


Model Training and Validation:
We are using below Performance metrics.
Mean Absolute Error: MAE measures the average magnitude of the errors in a set of predictions, without considering their direction.
