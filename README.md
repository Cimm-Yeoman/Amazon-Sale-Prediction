# Amazon-Sale-Prediction
This is an e-commerce data set examining different variables related to Amazon.ca browsing sessions and 
purchases. The response variable, **Revenue**, indicates whether or a purchase and sale were made. 
Some of the predictor variables include: **Month**, **SpecialDay** (whether or not the purchase was made 
near a holiday), and **BounceRates** (visitors who visit a page and then leave, with no purchase or other 
action performed). Other variables describe visitor characteristics, geography, Google Analytics, etc. 

The data set contains **12,330** observations of online shopping sessions. From these sessions, only
**1,908** involved a purchase and sale, while **10,422** sessions did not. This is a sale rate of about
**15.5%**. The response variable **Revenue** indicates whether or not an online shopping session
resulted in a sale or not. Using non-linear Support Vector Machine (SVM) and random forest modelling, 
this report will attempt to predict the outcome of sale, based on the combinations of the predictor 
variables for each Amazon.ca browsing session. 
