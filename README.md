# Power Consumption and Trend Analysis
A data science project aimed at providing homeowners with valuable insights into their energy consumption patterns to help them understand and manage their energy usage effectively.

## Project Overview
This project analyzes household energy consumption data to forecast energy usage, identify peak/off-peak loading times, and detect seasonal trends. It uses a combination of data visualization, feature engineering, and regression models to derive actionable insights for energy management.

### Data Handling
* Data Collection: Loaded the dataset containing household energy usage, timestamps, and relevant features.
* Data Cleaning: Addressed missing values, removed duplicates, converted data types (e.g., to numeric), and parsed timestamps correctly.
* Data Exploration and Feature Engineering:
* Explored patterns using visualization techniques like line plots and box plots.
* Created features such as hour, day of the week, and seasonality.
* Normalization: Scaled relevant features using Min-Max Scaling to standardize the data.

### Regression Models
* Model Selection: Chose regression models, including Random Forest Regressor, based on the dataset characteristics.
* Model Training: Trained the model using selected features such as hour, sub-metering data, and seasonal indicators.
* Model Evaluation: Evaluated the model using metrics like Mean Squared Error (MSE) and R-squared to determine accuracy.
* Tuning and Improvement: Fine-tuned hyperparameters and compared model performance to achieve optimal results.

### Insights and Visualization
* Peak/Off-peak Loading Times:
  - Analyzed hourly energy consumption patterns for weekdays and weekends.
  - Visualized the average hourly consumption to highlight peak usage periods.

* Seasonal Trend Analysis:
  - Evaluated seasonal variations in energy consumption by grouping data into spring, summer, fall, and winter.
  - Created visualizations to compare average energy usage across different seasons.

* Model Performance
  - Random Forest Regression Results:
    - Achieved an MSE of 0.0117 and an R-squared value of 0.754, indicating the model’s effectiveness in predicting energy consumption.
    - Feature importance analysis revealed that sub-metering data and hour are the most significant contributors to energy consumption predictions.

* Visualizations
  - Plotted time-based and seasonal visualizations to illustrate patterns and trends in energy usage.
  - Displayed feature importance to help understand which factors most influence energy consumption predictions.

* Future Work
  - Explore other machine learning models to improve prediction accuracy.
  - Investigate additional external factors like weather data or appliance usage logs to enhance the model’s ability to predict consumption.
