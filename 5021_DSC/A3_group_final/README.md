# Data Science Computing 

### Course Project: Spark Data Analysis

- Set up a Spark environment on a Hadoop cluster, which can be a virtualized local cluster, or through any cloud service.

- Project title: Exploring MovieLens 25M Dataset (https://grouplens.org/datasets/movielens/25m/Links).

- contents: 
    - codes: names corresponds to requirements below
    - Report (5 pages max)

#### Requirements

##### Part I: Basic Data Manipulation & Simple Recommendation

1. Read in the rating file and create an RDD consisting of parsed lines, then count the number of ratings.
2. Recommend 5 movies with the highest average rating.
3. Other operations to enrich your data analysis.
4. Try to create visualizations to convey the insights.

##### Part II: Rating Prediction

1. split rating data into 70% training set and 30% testing set.
2. Choose one matrix factorization algorithm to predict the rating score based on the rating data file only.
3. Extract features from movies and users (join movie and user data and do some feature transformation), then build another machine learning model to predict rating scores for the testing set.
4. Compare the pros and cons of these two models and report it.
