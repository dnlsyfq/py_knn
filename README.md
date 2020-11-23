
KNN Algorithms


1. Normalize the Data
    * Method:
        * Min Max
2. Find K 
    * Initiate with random K
3. Classify new points based on neighbors

```
Normalization usually means to scale a variable to have a values between 0 and 1, 
Standardization transforms data to have a mean of zero and a standard deviation of 1.
```

```
Overfitting is a concept that will appear almost any time you are writing a machine learning algorithm. Overfitting occurs when you rely too heavily on your training data; you assume that data in the real world will always behave exactly like your training data. In the case of K-Nearest Neighbors, overfitting happens when you don’t consider enough neighbors.
```

When k is small, overfitting occurs and the accuracy is relatively low. On the other hand, when k gets too large, underfitting occurs and accuracy starts to drop.