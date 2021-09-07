# simpleRecommenderSystem
#Overview
There are some packages for implementing recommender systems. These packages simplify the process of creating
a recommender system. One of these packages is LightFM. LightFM is a Python implementation of a number of
popular recommendation algorithms for both implicit and explicit feedback. It also makes it possible to incorporate
both item and user metadata into the traditional matrix factorization algorithms. It represents each user and item as
the sum of the latent representations of their features, thus allowing recommendations to generalise to new items
(via item features) and to new users (via user features).\
# Goals
# 1-Compare models:\
LightFM models may have different "learning schedule" and "loss". The "learning-schedule" can be "adadelta"
or "adagrad". The "loss" can be "warp", "bpr", "logistic", or "warp-kos". You have to compare both "learning-
schedule" and four losses; Then, you should develop a model with better output and higher accuracy. Then, build
your final model and check its accuracy.\
# 2-Recommend with the best model:
Your model is now ready to be recommended to users. Use a sample-recommendation function and recommend 3
movies to 4 user.\
# 3-Conclusion:
Explain what you’ve learned in this homework assignment and the topics of the models, model evaluation, and
recommender functions.\
