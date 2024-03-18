# Bike Sharing Case Study with Linear Regression Model 
# - Khuraijam Gunindro
<img src='bikes.webp'><br/>
# Problem Statement:

BoomBikes, a US bike-sharing provider, seeks to understand the demand for shared bikes post-lockdown to formulate a strategic business plan for revenue acceleration. The company aims to identify significant variables affecting bike demand and develop a predictive model to facilitate informed decision-making.

## Objective(Business Goals):

The objective is to model the demand for shared bikes based on available independent variables. This model will aid management in understanding demand dynamics, manipulating business strategies to meet demand levels, and expanding into new markets effectively.

### Key Tasks:

- Data Preparation: Convert categorical variables into appropriate values we can work with for the business goals.

- Model Building: Develop a multiple linear regression model with 'cnt' (total bike rentals) as the target variable, considering 'casual' and 'registered' users as independent variables.

- Model Evaluation: Calculate the R-squared score on the test set to assess model performance.

## Conclusions
- From our calculations and implementation we can say that the best fitted line is explained by this equation: <br/><br/>
$ cnt = 0.1736 + 0.472 \times  temp + 0.2343  \times  yr + 0.079 \times season Winter + 0.075 \times mnth Sept + 0.0058 \times workingday + 0.0433 \times season Summer - 0.0389 \times mnth January - 0.04822 \times mnth July - 0.0561 \times holiday - 0.0597 \times season Spring - 0.082621 \times weathersit Mist Cloudy - 0.1562 \times windspeed - 0.2917 \times weathersit Light Snow Rain $ 

- Observations concluded from our analysis: 
    - Seasonal Focus: Prioritize expansion efforts during Fall, Summer, and Winter for optimal demand utilization.

    - September Surge: Leverage September's high demand for targeted promotional activities and business expansion initiatives.

    - Yearly Growth Trend: Anticipate post-COVID demand surge based on the observed yearly growth from 2018 to 2019.

    - Weather Sensitivity: Adjust operations to account for decreased demand during adverse weather conditions, especially Bad and Severe weather.

    - Holiday Considerations: Implement targeted marketing or promotions to stimulate demand during holiday periods.

## Technologies Used
- numpy - version 1.26.3
- pandas - version 2.1.4
- seaborn - version 0.12.2
- sklearn - version 1.2.2
- statsmodel.api - version 0.14.0

## Contact
Created by [@KhGunindro] - feel free to contact me!

