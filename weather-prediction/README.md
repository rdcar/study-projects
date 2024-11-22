# Predicting the Weather Using Machine Learning

## Introduction
In this project, we leverage machine learning to predict weather patterns using historical data from a weather station at Oakland International Airport (). The dataset spans from 1960 to 2021, with each row representing one day and columns representing various weather measurements.

## Project Overview
The primary goal of this project is to predict the maximum temperature for the next day based on previous days' weather data. We employed Ridge Regression, also known as Tikhonov regularization, for this task. Here's a brief overview of the steps involved in the project:

1. **Data Importation**: Imported weather data from the Oakland International Airport station.
2. **Exploratory Data Analysis (EDA)**: Analyzed the dataset to understand its structure and identify patterns.
3. **Data Cleaning and Imputation**: Handled missing values using different techniques tailored for various data types.
4. **Model Training**: Trained the Ridge Regression model.
5. **Model Evaluation**: Assessed the model's performance.
6. **Feature Engineering**: Created new indicators to enhance model accuracy.
7. **Conclusion**: Summarized the findings and proposed future improvements.

## Dataset
The dataset consists of daily weather records from 1960 to 2021, including measurements such as temperature, humidity, wind speed, and more. 

## Methods
### Data Cleaning and Imputation
- Different imputation techniques were applied to handle missing data appropriately, ensuring the dataset was robust for training.

### Model Training
- We used Ridge Regression to train our predictive model. This technique helps to manage multicollinearity and enhance the model's generalization.

### Feature Engineering
- Created additional features to improve the prediction accuracy.

### Model Evaluation
- The model's performance was evaluated, and adjustments were made to fine-tune the model.

## Results
- The Ridge Regression model demonstrated its effectiveness in forecasting with an acceptable average error.
- The model predicted the maximum temperature of the next day with an average error margin of 1.873 degrees Celsius.
- After incorporating new indicators, the average error was further reduced to 1.805 degrees Celsius, indicating a significant improvement.

## Conclusion
The Ridge Regression model proved to be effective in predicting weather with a respectable level of accuracy. Our model successfully predicted the maximum temperature for the next day based on historical data with a margin of error of 1.873 degrees Celsius, which was further improved to 1.805 degrees Celsius after adding new features.

Through this project, we gained practical experience with supervised learning techniques, particularly linear regression models. We also calculated the Pearson correlation matrix to identify additional correlations and suggest new insights.

## Future Work
To enhance the model further, we suggest the following:
1. Extend the prediction to forecast an entire week instead of just one day.
2. Utilize data from multiple NOAA stations for a more comprehensive dataset.
3. Incorporate more indicators to capture additional weather patterns.
4. Experiment with multiple machine learning models to compare performance.
5. Use a test group spanning more than one year for robust evaluation.

## Acknowledgements
We would like to thank the open-source community and the developers of the libraries used in this project. Special thanks to [NOAA](https://www.ncdc.noaa.gov/cdo-web/search) for providing the weather data.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Happy forecasting! 🌤️

---