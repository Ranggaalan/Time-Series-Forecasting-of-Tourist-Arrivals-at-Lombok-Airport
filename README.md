# Time Series Forecasting of Tourist Arrivals at Lombok Airport
This project analyzes international tourist arrivals at Lombok International Airport through data exploration, stationarity and autocorrelation tests, visualization, and forecasting. Using ARIMA and SARIMA models, it predicts future arrivals to provide insights for better planning and decision-making.

## Project Methodology
In this project, I conducted an exploration and analysis of international tourist arrivals at Lombok International Airport from 2014 to 2016. The process includes:

🔹 Data Preparation – Importing and preparing data for further analysis.

🔹 Exploratory Data Analysis (EDA) – Stationarity tests, autocorrelation analysis, and various visualizations to understand patterns and data distribution.

🔹 Time Series Forecasting – Applying ARIMA and SARIMA models to predict future tourist arrivals.

## Model Accuracy Analysis

#### SARIMA Model Performance

Mean Absolute Error (MAE): 2,322.21

Mean Absolute Percentage Error (MAPE): 26.82%

#### ARIMA Model Performance

Mean Absolute Error (MAE): 2,566.90

Mean Absolute Percentage Error (MAPE): 30.71%

### Comparative Insights

SARIMA model shows better predictive accuracy
Lower error rates compared to ARIMA
Demonstrates improved capability in capturing seasonal patterns

#### Data Visualizations

Import Dataset 

![Image](https://github.com/user-attachments/assets/e0de2ff6-bf24-4152-a60f-5ba42b142c99)

Visualisasi Trend 

![Image](https://github.com/user-attachments/assets/269ff9c0-b90d-48c2-8859-50cbce5dfb92)

AUC

![Image](https://github.com/user-attachments/assets/6fa300d8-d26a-489c-a2df-98034e3c1048)

Visualisasi 2014-2016

![Image](https://github.com/user-attachments/assets/e83e4cd2-39af-4434-b389-a7a45fb31d29)

Hasil Arima

![Image](https://github.com/user-attachments/assets/38ee52f6-76a8-4d3a-b4ed-80f8ad281c19)

Hasil Sarima

![Image](https://github.com/user-attachments/assets/3cfcc737-465a-4db6-8680-7f202cae5341)

### Result

![Image](https://github.com/user-attachments/assets/2b3de633-c661-431a-8893-6674c6573229)
The forecasting results show that both ARIMA and SARIMA models have relatively low accuracy, with SARIMA performing slightly better in terms of MAE and MAPE. However, significant prediction errors remain, indicating the limitations of the models in capturing long-term trends and seasonal variations. One of the main challenges is the limited historical data (2014–2016), which may not be sufficient to fully capture seasonal dynamics and long-term trends in tourist arrivals.

### Key Findings and Insights

The forecasting results reveal important characteristics of tourist arrival predictions:
Model Performance

### Both ARIMA and SARIMA models show limitations in long-term trend prediction

SARIMA performs slightly better with lower MAE and MAPE
Significant prediction errors highlight the complexity of tourism forecasting

### SARIMA Model Predictions for 2017

April: Predicted 7,336 visitors

August: Peak at 7,646 visitors

December: Predicted 5,878 visitors (compared to actual 9,694 in December 2016)

### Challenges and Limitations

Limited historical data (2014–2016)

Difficulty in capturing complete seasonal dynamics

Variations in prediction accuracy across different months

### Recommendations

Expand historical dataset for more comprehensive analysis
Incorporate external economic and tourism factors
Develop more sophisticated forecasting techniques
Consider additional variables to improve prediction accuracy

### Technologies and Tools

Python
Pandas
NumPy
Statsmodels
Time Series Analysis Techniques
ARIMA and SARIMA Modeling

### Conclusion

While the current models provide valuable insights, there's significant potential for improvement in tourist arrival forecasting. The analysis demonstrates the complexity of predicting tourism trends and the importance of advanced statistical techniques.
Future Work. The SARIMA model's 2017 predictions reveal seasonal patterns similar to those in 2016, with high tourist arrivals in April (7,336 visitors) and a peak in August (7,646 visitors). However, the predicted December 2017 arrivals (5,878 visitors) are much lower than the actual peak in December 2016 (9,694 visitors). This highlights the importance of longer historical datasets and external factors (such as economic conditions and policy changes) to improve forecasting accuracy. Expanding the dataset and incorporating additional influencing factors could lead to more reliable and informative predictions.
