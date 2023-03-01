## WiDS Datathon 2023 - Temperature Prediction Task
This dataset is provided for the WiDS Datathon 2023, which involves predicting the sub-seasonal temperatures over a two-week period in various locations across the United States. The dataset contains weather and climate information for multiple locations and start dates, as well as the forecasted temperature and precipitation from different weather forecast models.

### Dataset Overview
Pre-prepared dataset consisting of weather and climate information for a number of US locations, for a number of start dates for the two-week observation, as well as the forecasted temperature and precipitation from a number of weather forecast models (we will reveal the source of our dataset after the competition closes). Each row in the data corresponds to a single location and a single start date for the two-week period. 

### Objective
The objective of the WiDS Datathon 2023 is to predict the arithmetic mean of the maximum and minimum temperature over the next 14 days for each location and start date. The predictions will be evaluated using the mean absolute error (MAE) metric.

### Data Source
The source of the dataset will be revealed after the competition closes.

### Dataset Format
The dataset is provided in CSV format and can be downloaded from the competition platform. The training set contains historical data from January 2015 to December 2022, while the test set contains data from January 2023 to March 2023. The test set does not contain the target variable.

### Methodologies
The project utilized two different machine learning methodologies, namely CatBoost and LSTM models.

CatBoost is a gradient boosting framework that utilizes decision trees to train models. It is well-suited for working with categorical data and has proven to be highly effective in many applications. In this project, CatBoost was used to predict weather patterns based on historical weather data.

LSTM is a type of recurrent neural network (RNN) that is capable of learning long-term dependencies in data. In this project, LSTM was used to predict weather patterns based on historical weather data.

The project was implemented using Python 3 programming language and several popular libraries, including NumPy, Pandas, Scikit-Learn, CatBoost, and TensorFlow. These libraries were used for data preprocessing, model training, and evaluation.

The dataset used in the project was also preprocessed using Python and the Pandas library to extract the necessary features for modeling.

The evaluation of the models was done using the Mean Absolute Error (MAE) metric.
