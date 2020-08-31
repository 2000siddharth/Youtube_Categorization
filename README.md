# Youtube Video Categorization
The repository describes Machine learning methods used to implement a Youtube Video Categorization model which gives a caregory to a video given it's title or description.

## OBJECTIVE
### Classifying videos (based on title and description) into the following categories:

1. Travel  
2. Tutorial  
3. Science
4.  Arts
5.  History
6.  Movies
7.  Vlog  
8.  Food  
9.  Music  
10.  Fashion
 
## Machine Learning algorithms used:
1. K-Nearest Neighbours
2. Logistic Regression
3. Naive Bayes Classifier
4. Decision Tree Classifier
5. Random Forests Classifier
6. Support Vector Classifier
7. Ada Boost
8. XGBoost Classifer

# Results

| Algorithm | Hyperparameter | Accuracy |
| --------- | -------------- | ---------|
| Naive Bayes | Alpha - 10 | 86.5 |
| Logistic Regression | 0.01, L2 | 88.67 |
| KNN | K = 43 | 83.4 |
| Random Forests | Tf-IDF | 87.69 |
| XGBoost | Lemmatized | 89.97 |
| Gradient Boost | Tf-Idf | 88.01 |
| SVC | Linear , 'C' = 1 | 88.6 |

# EDA
I tried the **T-SNE algorithm** for finding the lower dimensional representation of the data.

![](https://github.com/2000siddharth/Youtube_Categorization/blob/master/tsne_yt.png)

## PCA decomposition

![](https://github.com/2000siddharth/Youtube_Categorization/blob/master/PCA_yt.png)
