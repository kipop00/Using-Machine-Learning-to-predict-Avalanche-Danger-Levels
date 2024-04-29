# Using-Machine-Learning-to-predict-Avalanche-Danger-Levels

Welcome to the Avalanche Danger Level Prediction project! This project explores the application of various machine learning algorithms to predict the danger levels of avalanches based on environmental and meteorological data. The goal is to provide insight into what can help in the planning and safety measures for activities in snow-covered mountainous regions.

Project Overview: <br />
Avalanches pose significant risks in mountainous areas, affecting not only adventurers such as skiers and mountaineers but also the residents living in these areas. By using data collected by the Swiss who have undeniable expertise on the subject, the strive is to understand the effectiveness of machine learning and draw insights into the most important features. The hope is that regions with less robust infrastructure could make more accurate predictions while putting fewer people at risk.

In this project, I have experimented with three different machine-learning models:

Decision Trees: These models are easy to interpret and are useful for understanding the features directly influencing the prediction outcomes.
Random Forests: An ensemble method that uses multiple decision trees to improve prediction accuracy and control over-fitting compared to a single decision tree.
Logistic Regression: A statistical model that estimates the probabilities of avalanche danger levels being high based on predictor variables.

Each of the models has been implemented with the goal of predicting the danger level categorized on a scale from 1 to 5, with 1 being the lowest.

Key findings and results: <br />

The performance of the models was evaluated based on accuracy primarily but also weighted recall and precision which favor overestimation more than underestimation and punish differences of more than 1 level. With that, a Decision Tree fitting resulted in 82% accuracy on the training set and 80% on the test while using 13 features. Forests are extremely overfitted and do not produce valuable models by themself. On the other hand logistic regression, despite not delivering the best initial results at 70%, I hypothesise that with more research into parameter fittings, a model could be achieved that performs at least as well as the decision tree. 


Dataset: <br />
Citation of dataset contribution:
Pérez-Guillén, C., Techel, F., Hendrick, M., Volpi, M., van Herwijnen, A., Olevski, T., Obozinski, G., Pérez-Cruz, F., Schweizer, J. (2022). Weather, snowpack and danger ratings data for automated avalanche danger level predictions.  EnviDat.  https://www.doi.org/10.16904/envidat.330.

