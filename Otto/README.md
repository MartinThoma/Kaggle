## Otto Group Product Classification Challenge

* 93 Features
* 9 Klassen

### Evaluation

https://www.kaggle.com/c/otto-group-product-classification-challenge/details/evaluation

logloss


### Leaderboard

https://www.kaggle.com/c/otto-group-product-classification-challenge/leaderboard


### Forums

https://www.kaggle.com/c/otto-group-product-classification-challenge/forums

### Try

clf = DBN(
[number_features, 64, 64, 9],
learn_rates=0.1,
learn_rate_decays=0.66,
epochs=20
)