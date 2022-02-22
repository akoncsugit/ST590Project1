# ST590 Project 1
First Python Project - Bike Details Data
Authors: George Bridges and Ashley Ko

Purpose: To demonstrate python skills through the processing, analysis, prediction of `bikeDetails.csv` take from Kaggel.com.


For this project we utilized python to explore used motorcycle listing data obtained from [Kaggle.com](https://www.kaggle.com/nehalbirla/motorcycle-dataset?select=BIKE+DETAILS.csv). The data set, `bikeDetails.csv`, was originally complied from [BIKEWALE](www.bikewale.com). It contains 7 variables: `name` (of motorcycle), `selling_price`, `year` (of motorcycle, not sale), `seller_type` (Individual or Dealer), `owner` (1st, 2nd, 3rd, or 4th owner), `km_driven`, `ex_showroom_price`. After processing the data appropriately, we performed exploratory data analysis to summarize the data. The results of which shaped the direction of our predictions of `selling_price`. We created algorithms to predict `selling_price` using grid search, essentially a brute force approach and gradient descent, which finds the minimum value for the loss function by ascertaining where it has zero slope which indicates an extremum.
