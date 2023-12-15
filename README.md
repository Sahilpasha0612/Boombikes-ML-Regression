# Boombikes-ML-Regression
# Project :  Linear Regression Model - Boom Bikes sharing
> Requirement is to buid the model to analyse the demand for shared bikes with the available independent variables. It will be used by the Boom Bikes management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents

- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)


# General Information
-A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- Background : 
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


- Business probem :
Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    .Which variables are significant in predicting the demand for shared bikes.
    .How well those variables describe the bike demands.

- Dataset that is being used :
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### Datasets

- [Bike Rentals Data Set](https://ml-course2-upgrad.s3.amazonaws.com/Linear+Regression+Assignment/Bike+Sharing+Assignment/day.csv): This contains the bike rentals made in the year 2018 and 2019.
- [Data Dictionary](https://drive.google.com/file/d/1x4Vi_FF0DEmTN1Cf6BnPHUuQP9p0s0Pz/view?usp=sharing): This dataset describes the meaning of the variables mentioned in the Bike Rentals Data Set.

---

## Conclusions

We have selected 10 features for our model, and following are the results.

<table>
<tr><td style="vertical-align: baseline;">

| Features | p_value | t_value | VIF |
| --- | --- | --- | --- |
| spring | 0.008 | -2.654 | 1.994 |
| windspeed | 0.000 | -5.854 | 4.595 |
| temp | 0.000 | 14.423 | 3.838 |
| 2019 | 0.000 | 28.237 | 2.066 |
| summer | 0.000 | 4.350 | 1.903 |
| winter | 0.000 | 5.630 | 1.629 |
| MST | 0.000 | -8.938 | 1.549 |
| Sep | 0.000 | 5.566 | 1.229 |
| LRS | 0.000 | -11.444 | 1.081 |
| holiday | 0.000 | -3.668 | 1.043 |

</td><td style="vertical-align: baseline;">

|                | Train Set | Test Set |
| -------------- | --------- | -------- |
| R-Squared      | 0.832     | 0.804    |
| Adj. R-Squared | 0.829     | N.A.     |
| F-statistic    | 248.4     | N.A.     |

</td>
</tr>
</table>

<img src="images/test_actual_vs_predicted.png" alt="Test - Actual vs Predicted" width="50%">

---

## Technologies Used

Python 3.9.16

| Library      | Version |
| ------------ | ------- |
| pandas       | 1.4.4   |
| matplotlib   | 3.7.1   |
| seaborn      | 0.12.2  |
| statsmodels  | 0.13.5  |
| scikit-learn | 1.2.2   |

---

Assignment done by: [Sahil Pasha M B](https://github.com/Sahilpasha0612)


