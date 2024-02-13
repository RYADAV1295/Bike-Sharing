# Project Name
> Bike Sharing System


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Bike Sharing Systems are a new generation of traditional bike rentals where the whole process from membership, rental and return back has become automatic. Through these systems, the user is able to easily rent a bike from a particular position and 
return back at another position.
- To understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.
- Which variables are significant in predicting the demand for shared bikes?
- How well those variables describe the bike demands?


## Conclusions
As per Final Model below are the top 3 predictors which influence the bike bookings:
- **Year (yr):** The coefficient for the "yr" variable is 0.2354 with a very low p-value (p < 0.001), indicating a highly significant positive effect on bike demand. This suggests that there has been a significant increase in bike rentals over time.
- **Temperature (temp):** The coefficient for the "temp" variable is 0.4078 with a very low p-value (p < 0.001), indicating a highly significant positive effect on bike demand. This suggests that higher temperatures lead to increased bike rentals, which is intuitive as people are more likely to ride bikes in warmer weather.
- **Weather Situation (weathersit):** Both "weathersit_2" (partly cloudy) and "weathersit_3" (rain/snow/fog) variables have significant coefficients with very low p-values (p < 0.001). However, their coefficients have negative values, indicating a negative effect on bike demand. This suggests that adverse weather conditions (partly cloudy, rain, snow, fog) lead to decreased bike rentals, which is reasonable as people may be less inclined to ride bikes in such weather conditions.

Then the next considerable predictors would be as follows:

- **Season (season):** Spring season has co-efficient of **-0.1162** which indicates that a unit increase in this variable, **decreases** the bike rental by 0.1162 units. Also Winter season has co-effficient of **0.0480**, which indicates that a unit increase in this variable, **increases** the bike rental by **0.0480** units.
- **wiindspeed:** This variable state that a unit increase in this will decrease the bike rental by **0.1356** units.




## Technologies Used
- sklearn
- matplotlib.pyplot
- pandas
- numpy
- statsmodels.api
- statsmodels.stats.outliers_influence


## Acknowledgements
Give credit here.
- This project was based on [this tutorial](https://learn.upgrad.com/).


## Contact
Created by [@RYADAV1295] - feel free to contact me!


Optional
## License
This project is open source and available under the [GNU GENERAL PUBLIC LICENS]().
