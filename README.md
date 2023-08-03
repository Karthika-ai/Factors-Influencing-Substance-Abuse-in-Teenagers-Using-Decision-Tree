# Factors-Influencing-Substance-Abuse-in-Teenagers-Using-Decision-Tree
This study utilizes Decision tree algorithms to predict the consumption of marijuana in teenagers using the National Survey on Drug Use and Health (NSDUH) data.

## Software
  R Studio
  
## Packages 
`library(tidyverse)`
`library(rpart)` 
`library(rpart.plot)`
`library(FSelector)`    
`library(tree)`         
`library(gbm)`          
`library(randomForest`) 

## Getting Started

Feature selection is done by using information gain function and imputing missing values

## Methods
 - Pruning
 - Tree Model
   - Ensembel Methods
     - Bagging 
     - Random Forest 
     - Boosting 

## Key Findings
- Classification of Marijuana Usage
    - If a person is not consuming tobacco and their friends are against using marijuana, they are not prone to marijuana consumption.
    - If a person consumes tobacco and their friends are against using marijuana, but their parents somewhat disapprove, they still consume marijuana.

- Classifying the Risk of Teenagers Consuming Marijuana
    - If the teenagers, their parents and their peers neither approve nor disapprove about using marijuana and the teenagers have the habit       of alcohol consumption, then they are at high risk of consuming marijuana at least once a week.
      
- Predicting the Frequency of Marijuana Consumption
    - If a teenager used tobacco and their parents somewhat disapprove of using it, most of the students in their grade are prone to using marijuana, and they result in using more than six cigarettes in a month. They tend to use marijuana 223 times in a year.
    - If a teenager does not use tobacco and also does not get access to alcohol at home, this results in teenagers using marijuana twice a       year.
      
## Results
The primary factors that were responsible for marijuana consumption were the other 10 substance usage such as alcohol and tobacco. This is because the use of one substance leads to the other. Here the study used a binary classification model to classify if a teenager used marijuana with a performance rate of 91%. The multi-class classification model using random forest was used to predict the risk of consuming marijuana more than once a week with the accuracy rate of 47%. Finally a regression model combined with the use of a boosting method was used to predict the frequency of marijuana usage in a year. This model’s training and test error were similar thus making the model a better fit



