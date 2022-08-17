# Machine-Learning-Model
The Linear Regression Model on Boom bikes- To analyse the significant features which are affecting the demand for shared bikes (Boom bikes).
 

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of coursework from IIIT-Bangalore. 
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc. 
- The Boombikes bike rental dataset is being used. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The R-squared value of the train set is 83.6% whereas the test set has a value of 80.4% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
- The training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.
- Equation of the best fit line is: 
  
  **cnt**= 0.199648 + (0.233482 * yr)-(0.098013 * holiday)+(0.491508 * temp)-(0.147977 * windspeed)-(0.066942 * spring)+(0.045280 * summer)+ (0.083084 * winter)
       -(0.285155 * light Rain)-(0.081558 * mist)-(0.052418 * jul)+(0.076686 * sep)
- As per the final model, the top 3 predictor variables that influence bike booking are:

      1) Temperature (Temp): A coefficient value of ‘0.491508’ indicated that a temperature has significant impact on bike rentals
      2)	Light Rain: A coefficient value of ‘-0.2852’ indicated that the light snow and rain deters people from renting out bikes
      3)	Year (yr): A coefficient value of ‘0.2335’ indicated that year wise the rental numbers are increasing


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Created by [@VasundharaLK]
For contact - vasundharalkadekodi@gmail.com 

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
