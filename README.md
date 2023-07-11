# HousePrice
Stacking technique to enhance predictive performance

Stacking technique stacks a model on top of already built strong learner (the models built in training phase) to enhance the predictive power of the overall model.
In this project, a neural network is used as a meta-learner. The individual learners are made to predict on a dataset, and the meta-learners uses those predictions
and true value to learn about any missed signals.

The project uses a dataset containing house prices in various blocks in the state of California, USA.
The variables used are Longitude, Latitude, median income, median house age, total rooms, total bedrooms, ocean proximity, population, and households.
