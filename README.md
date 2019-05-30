# Stock Market Price Prediction 
A Stock Market Price Prediction Application built and designed with Python and Machine Learning.

## Implementation
Basic Machine Learning Regression algorithms like Linear Regression, Support Vector Regressor and Decision Tree Regressor are used for Tie Series Forecasting of stock market price prediction. The most popular companies on which the mass invests on are Alphabet, Apple, and Amazon as they stay to be the most profitable companies out there in the market. These 3 companies have been fixated in the application. A GUI is designed to make the user comfortable to work with the application. Dataset is acquired from Quandl which provides data of stock prices of the companies. Feature extraction is performed with the attributes on the dataset. The attributes are transformed to represent the High-Low percentage and Percentage Change of the day. The prediction then is performed using the Machine Learning Regression Algorithms.

## GUI
tkinter has been used to give the user an intuitive approach to use the application. A Menu bar with drop-down buttons is maintained with the name of the companies. The drop-down menu of the corresponding company opens with 3 regression algorithms. The application is then displayed with the predicted price for the next few days. The user is also displayed with a graph of the previous plot of the price and the future price vs date. 

### Modules required for the project
1. [BUILT-IN]sklearn
2. [BUILT-IN]tkinter
3. [BUILT-IN]math
4. [BUILT-IN]matplotlib
5. [BUILT-IN]datetime
6. [DOWNLOAD]pandas:  
  python -m pipinstall pandas
7. [DOWNLOAD]numpy:  
  python -m pipinstall numpy
8. [DOWNLOAD]quandl:  
  python -m pipinstall quandl

### Notebooks
The notrbooks for each algorithm have been provided explaning each step ofthe entire process.
