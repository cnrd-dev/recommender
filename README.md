# Article recommendation system

The project explores a dataset from IBM and builds various recommender systems to recommend articles to new and existing users.

The main file is a Jupyter Notebook called `Recommendations_with_IBM.ipynb`. The notebook has four main sections:

- I. Exploratory Data Analysis
- II. Rank Based Recommendations
- III. User-User Based Collaborative Filtering
- V. Matrix Factorization

## Results

Various recommendation models was tested and the accuracy of recommendations may not be good as there is a large imbalance in the dataset. Content based recommendations were not included but may provide better recommendations, especially for new users.

## Instructions

Libraries and virtual environment details are located in the `Pipfile` which can be used with `pipenv`.

## References

Thanks to Sanjeev Yadav for his article on [Medium](https://sanjeevai.medium.com/recommendations-with-ibm-7f89d25375fc#:~:text=%20Recommendations%20with%20IBM%20%201%20Exploratory%20Data,create%20user_item_matrix%20from%20df%20in%20which...%20More%20) when I got stuck.
Also, Purva Huilgol, for her [Medium](https://medium.com/analytics-vidhya/accuracy-vs-f1-score-6258237beca2) article on Accuracy vs. F1-Score.

Project based on Udacity Data Science Nanodegree.
