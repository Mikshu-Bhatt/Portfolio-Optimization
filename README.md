# Portfolio-Optimization

# NOTE - This Project is for tutorial purpose only and it is not any kind financial advise nor I am a certified advisor. I will not be held responsible for any of the future actions taken by the inspiration of this project.

In this project we are trying to make a optimized portfolio from the companies which are listed in BSE sensex. We are going to maximize the sharpe ratio of our portfolio.

Keeping in mind that we are going to hold on this positions for the longer period of time.

First we are importing or installing the required libraries.

I have already uploaded the csv file to my drive so now we need to mount drive to colab and get the required data from the file.

We are using a library called py-portfolio-optimization which basiccaly helps us to optimize the portfolio of our choice.

Here we are using some of the features of the library. To know more about pypfopt go to https://pypi.org/project/pyportfolioopt/

We are getting the weights for each company in such a manner that sharpe ratio is maximized and predicting the performance of the portfolio.

We are also showing the allocation of shares of different companies by giving a perticular portfolio value.

To check the effectiveness of the method we are dividing our dataset into to parts, on the first part we will do the analysis and predict the expected return of portfolio.

We are going to cross check that with the second part of dataset. we found the actual annual portfolio return and it comes out to be near to the expected return, though it may not happen in every case.

annual Return of the portfolio beats the annual market return.

Finnaly we are using the historical data to determine the optimized portfolio and the return and risks related to that.

P.S. - We are only optimizing for the long position as we are planning to hold it for longer span of time and market has general tendency to go up with the time so short positions may not be helpful. Though you can consider shorting just by changing the weight bounds to (-1,1) from (0,1).
