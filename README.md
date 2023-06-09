# Spaceship Titanic Teleport Prediction
> The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

### Summary
This project compares the accuracy of multiple classification models in predicting passenger teleportation. Models performing worse than the baseline Logistic Regression model with accuracy 77.3% were eliminated which left only 4 Ensemble models. 

The final performance per model is as follows:

|Model| Accuracy - untuned | Accuracy - tuned| % Change |
|-----|--------------------|-----------------|----------|
|Random Forest| 80.99% |   79.4%               |-1.59|
|XGBoost  | 81.40% |         81.81%              | +0.41|
|AdaBoost | 80.16% |      81.52%                |+1.36|
|GBM |  81.63% |           81.55%               |-0.08|


Opting for the XGBoost model since it could more easily handle the missing values in the test set, we scored a final value of 80.336%.

> This information is subject to change if and when the model is updated


### Citation
#### Spaceship Titanic
- **Authors:** Addison Howard, Ashley Chow, Ryan Holbrook
- **Title:** Spaceship Titanic
- **Publisher:** Kaggle
- **Year:** 2022
- **URL:** [https://kaggle.com/competitions/spaceship-titanic](https://kaggle.com/competitions/spaceship-titanic)
