# CDSS
## Inspiration
Protecting the environment has always been the goal of human’s joint effort. Greenhouse gas is one of the major impact on influencing the environment. In this project, we aimed to reduce the emission by controlling the energy use of the bulidings in New York City.

## What it does
Utilizing a standardized Energy Use Intensity (EUI) to compute the relatively electricity and natural gas consumption in order to achieve the emission goal. It is a highly customize model that can accurately predict the energy use given a set emission value for the city of New York.

## How we built it
First performed visualization to do EDA on our dataset and obtain many meaningful insights from our exploration of data such as why some property use more electricity than others and it's not avoidable.

Next, we build a function that automatically perform feature selection using univariate feature selection.

We eventually use XGBoost to build a prediction model using features such as Property type, Total green house gas intensity, and other more important features in the data set.

## Challenges we ran into
Due to the nature of the data, our model building process was very limited, such as linear regression model were not usable at all on this data. And feature selection was also a pain to do.

## Accomplishments that we're proud of
We attained many insightful opinions from our EDA. The final model got a high R^2 score, which can accurately predict the Energy use base on a give emission value.

## What we learned
How to utilize statistical and mathematical approaches into a real problem. Also, when we are facing a big data, what's the most efficient way to selected the most important and valuable categories instead of analyzing some unnecessary datasets. Most importantly, never underestimate our capabilities and don't overestimate the difficulty of a big problem.

## What's next for How to use Energy to help our environment
The next step is for the government to find out an ideal greenhouse gas emission and we can use this emission to set up the relatively electricity and natural gas consumption goals.
