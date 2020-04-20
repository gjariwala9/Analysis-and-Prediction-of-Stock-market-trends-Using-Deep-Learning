# Analysis and Prediction of Stock market trend using Deep Learning

The project is desgined as 2nd opinion tool for stock market investments strategy.

The users needs to do his/her own research on a stock or a company before using this product.

This is a 3 step product:

STEP 1:

Predicting stock value for tomorrow by analysing historic data of a particular stock. Recurrent Neural Network (RNN) model is used for this system. Stock historic data is downloaded from yahoo finance.

STEP 2:

Verify the trend of the stock based on external factor and news which cannot be analysed using historic data. Both Support Vector Machine and Naive Bayes system are used. News headlines are web scrapped from moneycontrol.com.

STEP 3:

Use Risk Analysis System to find out to which cluster your stock belongs to and check the movement of other stock in that cluster, since stocks in a particular cluster are related to each other their movement is interdependent. Kmeans clustering is used to create this module. Data is 10 year historic data for (Open price - Close price) for a particular day.
