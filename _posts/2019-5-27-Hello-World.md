---
layout: post
title: Project 5
---

In the business world, the saying goes that “Cheap/Fast/Good? You can only have two of the three.” Cheap and Fast results in work of questionable quality. Fast and Good will be expensive. Cheap and Good will take a long time, as the amount you’re paying probably won’t make it a top priority.

My 5th project for General Assembly’s DSI immersive was to participate in a one day long hackathon, where the goal was to create the best performing model we could. The target prediction was to predict whether a person would make above $50,000 per year and the probability that they would do so given information such as wage, marital status, etc. We were split up into three teams under varying constraints. My group’s restriction was that we had to use RandomForest classification as our model. We created a Pipeline in order to automate the process, and used RandomizedSearchCV in order to find the most optimal hyperparameters for our model. We chose RandomizedSearchCV over GridSearchCV, as it was a way to reduce the dimensionality of the parameters we were looking for so that it wouldn’t take a prohibitively long time to run our model.

In the end, we scored a 97.7 percent accuracy rate on test data that was not initially provided to us.
