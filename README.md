# Machine-Learning-ClimateWins-python
ClimateWins explores tools to predict weather in mainland Europe,focusing on rising extreme events over the past 10–20 years. 
Using machine learning and historical data, it aims to build models that help forecast and plan for future conditions.

The following resources were consulted for this project: 
The European Climate Assessment and  Dataset website and the processed weather prediction dataset.
https://www.ecad.eu/

https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv

# Key Questions
How is machine learning used? Is it applicable to weather data?
Are some models more effective and accurate than others?
what are the machine learning biases and limitations?
What stations have performed the best ? the least?

# Finding

Based on the results, it looks like the Artificial Neural Network (ANN) gave the best 
predictions, followed by the Decision Tree and then the K-Nearest Neighbors (KNN). 
  
Madrid, Budapest, Belgrade, and Basel have kept the highest performance, with up to 88% 
accuracy and 93% precision. Valencia remains with the weakest results.  
Sonnblick is again perfectly accurate for predicting unpleasant weather, this could be a 
sign of overfitting where the model memorized the dominant class rather than learning 
generalizable patterns. 
Indeed, some stations probably perform better, their data is likely more reliable or maybe 
because they have more pleasant weather throughout the year such as Madrid. 
 Overall, I would recommend using the ANN, since it had the least mismatch with the 
actual weather conditions.
