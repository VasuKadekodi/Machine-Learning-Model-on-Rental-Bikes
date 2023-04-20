# 🚲 Machine-Learning-Model On Rental Bikes

The Linear Regression Model on Boom bikes - To analyze the significant features which are affecting the demand for shared bikes (Boom bikes).

## 📝 Table of Contents
- [General Information](#general-information)
- [Conclusions](#conclusions)
- [Recommendations to improve the business](#recommendations-to-improve-the-business)
- [Technologies Used](#technologies-used)

## 📊 General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of coursework from IIIT-Bangalore.
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.
- The Boombikes bike rental dataset is being used.

## 📈 Conclusions
- The R-squared value of the train set is 83.6% whereas the test set has a value of 80.4% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
- The training and testing datasets suggest that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.
- Equation of the best fit line is: 
  
  **cnt**= 0.199648 + (0.233482 * yr)-(0.098013 * holiday)+(0.491508 * temp)-(0.147977 * windspeed)-(0.066942 * spring)+(0.045280 * summer)+ (0.083084 * winter)
       -(0.285155 * light Rain)-(0.081558 * mist)-(0.052418 * jul)+(0.076686 * sep)
- As per the final model, the top 3 predictor variables that influence bike booking are:
  1. Temperature (Temp): A coefficient value of ‘0.491508’ indicated that temperature has a significant impact on bike rentals.
  2. Light Rain: A coefficient value of ‘-0.2852’ indicated that light snow and rain deter people from renting out bikes.
  3. Year (yr): A coefficient value of ‘0.2335’ indicated that year wise the rental numbers are increasing.

## 💡 Recommendations to improve the business
- It is recommended to give utmost importance to these three variables while planning to achieve maximum bike rental booking.
- As high temperature and good weather positively impacts bike rentals, it is recommended that bike availability and promotions to be increased during summer months to further increase bike rentals.

## 🛠️ Technologies Used
- pandas 🐼
- seaborn 📊
- matplotlib 📈
- statsmodels 📊
- sci-kit learn 🧮
- numpy 📈

## 👩‍💻 Created by
[@VasundharaLK](https://github.com/VasundharaLK)

For contact: vasundharalkadekodi@gmail.com
