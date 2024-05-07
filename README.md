# Bike-Sharing
Building a model for the prediction of bike rental daily count based on the environmental and seasonal settings

## Problem Statement
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

<b>The company wants to know:</b>
Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands

<b>Goal:</b>
Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables.
It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.

## Data Source
Dataset given - 'day.csv'

## Tools
Jupyter Python Notebook

## <i>Data Preparation</i>
In the initial data preparation phase, the following tasks are performed:
1. Data loading and inspection
2. Handling missing values
3. Data Cleaning and formatting

## <i>Data Analysis</i>
The below analysis is used to solve the right problem and draw insights which is coherent with the needs of the business. The analysis has a clear structure and the flow is easy to understand.
1. Univariate analysis
2. Bivariate analysis

## <i>Model Building</i>
Building a model using 'cnt' as the target variable. 'cnt' represents the total number of bike rentals, including both casual and registered users.

## <i>Model Evaluation</i>
After model building and making predictions on the test set, the R-squared score is calculated using the code snippet:
"from sklearn.metrics import r2_score
r2_score(y_test, y_pred)"
'y_test' is used for the test dataset of the target variable and 'y_pred' for the predicted values on the test set.

## Conclusion
1. The company's growth strategy should prioritize expanding its operations during the spring season, capitalizing on the favorable weather and increased outdoor activities.
2. September presents an opportune time for the company to intensify its business expansion efforts, leveraging the peak demand and favorable market conditions characteristic of this month.
3. During periods of light snow or rain, there is anticipated to be a decline in bookings. This downtime can be utilized by the company for bike servicing activities, minimizing the impact on business operation.
4. Following the return to normalacy, the company should roll out new promotional offers tailored to the spring season, taking advantage of the pleasant weather conditions to attract customers.
5. Additionally, targeted advertising efforts should be directed towards September, maximizing business opportunities during this peak period.
6. Significant variables to predict the demand for share bikes: holiday, temp, humidity, windspeed, Season, months, Year, Sunday, weathersit
