# deep-learning-challenge

## Skills Used
neural network machine learning, pandas, google colab

## Overview
The nonprofit foundation - Alphabet Soup, wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Their business team have provided a dataset containing 34,000 organizations that have received funding from Alphabet Soup over the years. Using this dataset we have designed a neural network which uses a binary classification model to predict if an Alphabet Soup-funded organization will be successful. Two models are contained within this repo. The original created model and an optimized model in which increasing the accurary of the predictions was the goal. 

## Results

### Data Processing
- What variable(s) are the target(s) for the model? </br>

The goal is to predict if an organization will be successful. The `"IS_SUCCESSFUL"` field uses binary code to represent Y/N </br>

![image](https://github.com/nicduffee/deep-learning-challenge/assets/91498217/cd76c139-e3e0-4211-ab56-7eeb6e2c5d79) </br>
_Figure 1_

- What variable(s) are the features for your model? </br>

In the original model we used all the remaining columns except `"EIN"` and `"NAME"`.These columns were dropped because they are primarily for identification purposes and won't help us to predict the success of other organizations. </br>

In the optimized model we reduced the number of factors. We looked at 5 factors: `"APPLICATION_TYPE"`, `"AFFLIATION"`, `"CLASSIFICATION"`, `"ORGANIZATION"` and `"INCOME_AMT"` </br>

![image](https://github.com/nicduffee/deep-learning-challenge/assets/91498217/f93e192c-e465-4ec6-8420-9a7d16c8b969) </br>
_Figure 2_

- What variable(s) should be removed from the input data because they are neither targets nor features?

`"EIN"` and `"NAME"` were dropped. As stated above, they are neither targets nor features, only acting as identification. </br>

![image](https://github.com/nicduffee/deep-learning-challenge/assets/91498217/d978ee50-e19b-4627-a625-31ff15a384ce) </br>
_Figure 3_








