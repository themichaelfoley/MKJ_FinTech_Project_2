# Team 3, Project 2: Michael Foley, Karen Garcia, Jason Raeppold

# Drink Up or Up in SMOTE?
![Jim_e_pig]()

## Alcohol Vs. Cannabis Stocks- A Revised Outlook Using Machine Learning Models 

[Long Trading Algo Code](https://github.com/themichaelfoley/MKJ_FinTech_Project_2/blob/main/Files/BUD_long_algo.ipynb) 

[Short Trading Algo Code](https://github.com/themichaelfoley/MKJ_FinTech_Project_2/blob/main/Files/VFF_short_algo.ipynb) 

[LSTM Model 1 Code](https://github.com/themichaelfoley/MKJ_FinTech_Project_2/blob/main/Files/LSTM_model_1.ipynb) 

[LSTM Model 2 Code](https://github.com/themichaelfoley/MKJ_FinTech_Project_2/blob/main/Files/LSTM_model_2.ipynb) 

[Random Forest Model Code]()

[Linear Regression Model Code]()

[Presentation Slides and Plots]()

## Abstract
For our second project, we decided to repurpose the data we presented in project one to build scalable machine learning models that can trade and predict 
stocks prices with limited price data. We wanted to see how our selected stocks would behave and if we expected to see similarities in the outcomes we obtained for project one now that we have a better understanding on how and why our data behaved the way it did. We focused on Trading Algorithms, Linear Regression, and LSTM Models which are all methods used to predict and deploy time series data in order to develop predictions on stock votatility. 

## Expected Results and Trouble
Since we were already familiar with the data and what the outcomes might be, we were hopeful that we would get good models and our data processing would be straighforward. However, we quickly realized that comparing our stocks to the SP500 benchmark was hurting our models because of the SP500's predictability. In turn, the initial results were slightly underfit causing us to have to modify our parameters repeatedly to generate better models. We were also working with limited data which definitely impacted our final results. 

## Models and Results 
The initial part of our project focusing on trading algorithms. Our models proved to be inbalanced due to several outliers such as not having enough data and having to possibly adjust the features. Our end results gave us trading algorithms that were not very suitable for trading decisions. For this reason, we decided to create additional models (LSTM, Linear Regression/Random Forests/Confusion Matrix) in hopes of creating better models for our data. Consequently, we realized all our models ran into similar problems due to our data not being as robust. 

![gp_cards](https://www.eurixgroup.com/wp-content/uploads/2021/01/ml-e1610553826718.jpg)
