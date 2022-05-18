# CPSC392_Assignment1
GENERAL INSTRUCTIONS:
For all ggplots, make sure you make changes so that the data viz is effective, clear, and does not contain distracting elements, graphs will be graded both on correctness (did you plot the right hting) as well as on effectiveness (does this graph thoughtfully demonstrate the principles we learned in our data viz lectures).
CLEARLY mark where you are answering each question (see here for an example format).
Show all code necessary for the analysis, but remove superfluous code
Using the dataset linked here, build a linear regression model to predict reaction time from a lab based cognitive task (reaction time refers to the amount of time it takes a person to react after seeing a stimuli on a screen) based on all the other variables.
Variables
age: age in years
boredom_rating: a scale of 0-100 with 0 being completely not bored, 100 is completely bored
risk_propensity: a scale of 0-28 where higher scored indicate a person is more likely to take risks
height: height in cm
left_handed: 0 if the person is right handed, 1 if they are left handed
reaction_time: reaction time in ms
Instructions
a) use an 80/20 train test split for model validation and make sure you z score your continuous/interval variables ONLY
b) check the linearity assumption for your continuous variables using ggplot (using all the training data). Discuss in detail what you are checking for and specifically what you see for this model (regardless of the results, continue building the linear regression model, as we do not have any other alternatives yet).
c) check the assumption of homoscedasticity by plotting predicted reaction times and residuals using ggplot (using the training set). Discuss in detail what you are checking for and what patterns you see specifically for this model.
d) plot the actual vs. predicted reaction times (for both train an test set separately), as well as print out the mean absolute error for both train and test and  𝑅2  for your model for both train and test. Discuss how well your model did based on these metrics, and how can you tell.
e) is your model overfit? Discuss in detail how you can tell.
f) use ggplot to make a bar chart showing the coefficient values (x should be each coef name, the height of each bar should be the value of the coefficient). DO NOT include the intercept in this plot. Briefly discuss the impact of each variable on reaction time.
Feel free to add cells to this notebook in order to execute the code, but for parts b,c, and d, make sure you put the discussion part in a Markdown cell, do not use code comments to answer.
