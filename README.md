# Overview

The purpose of this analysis is to help the Alphabet Soup corporation with a tool that can help select applicants for funding with the best chance of success in their ventures. With over 34,000 data points of historical data, we looked at the following parameters

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special considerations for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

# Results:

* Data Preprocessing
* Dropped the EIN and NAME columns as they are non beneficial to the analysis
* Limited the APPLICATION_TYPE to those with over 200 applications.
* Limited Classification to those with over 1000 campaigns
encoded non-numeric data
* Split the processed data, the target being the "IS_SUCCESSFUL" column. The remaining columns are features to use for analysis
* Scaled the data
* Compile, Train, and Evaluate
* The initial model ended up being the most successful

* 2 hidden layers each with 10 neurons each
* Each hidden layer utilized the Relu activation method
* Loss of 55% and Accuracy of 72.66%

Target of 75% NOT met
