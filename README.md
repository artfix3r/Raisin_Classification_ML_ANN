## About Dataset
Dataset Description
This dataset contains 900 raisin grain samples (450 from each of the two varieties: Kecimen and Besni), 
along with 7 extracted morphological features for each grain. These features have been calculated from images of the raisins, and the dataset is intended for classification tasks to distinguish between the two varieties of raisins.


### Columns 
* Area: The number of pixels within the boundary of the raisin.
* MajorAxisLength: The length of the longest axis that can be drawn on the raisin.
* MinorAxisLength: The length of the shortest axis that can be drawn on the raisin.
* Eccentricity: A measure of how elongated the raisin is compared to a perfect circle.
* ConvexArea: The number of pixels of the smallest convex hull surrounding the raisin.
* Extent: The ratio of the region formed by the raisin to the total number of pixels in the bounding box.
* Perimeter: The distance around the boundary of the raisin.
* Class: The classification label indicates whether the raisin is of the Kecimen or Besni variety.


### Dataset Summary
* Total Number of Samples: 900
* Number of Features: 7
* Classes: Kecimen, Besni
* Source: Classification of Raisin Grains Using Machine Vision and Artificial Intelligence Methods, Gazi Journal of Engineering Sciences, December 2020.


### Tried multiple Machine Learning models such as : 

* Logistic Regression
* Support Vector Machine
* Random Forest Classifier
* Decision Tree Classifier
* Gaussian Naive Bayes
* Gradient Boosting Classifier
* Ada Boost Classifier

#### After trying this ML algorithm, Logistic Regression, Random Forest, and Ada Boost show better results than others. So, we used a randomized search algorithm for hyperparameter optimization. The final results are :
**Random Forest**
Model performance for Training set
- Accuracy: 0.9917
- F1 score: 0.9917
- Precision: 0.9834
- Recall: 1.0000
- Roc Auc Score: 0.9918
----------------------------------
Model performance for Test set
- Accuracy: 0.8500
- F1 score: 0.8500
- Precision: 0.8526
- Recall: 0.8617
- Roc Auc Score: 0.8495

![image](https://github.com/user-attachments/assets/e0c38d1c-eed3-45cb-ac23-8df7259ccbb4)

**===================================**

**AdaBoost**
Model performance for Training set
- Accuracy: 0.8694
- F1 score: 0.8691
- Precision: 0.8308
- Recall: 0.9242
- Roc Auc Score: 0.8700
----------------------------------
Model performance for Test set
- Accuracy: 0.8500
- F1 score: 0.8500
- Precision: 0.8602
- Recall: 0.8511
- Roc Auc Score: 0.8500

  ![image](https://github.com/user-attachments/assets/b682a330-8437-426a-b93e-064d9afbfba4)

**===================================**  
**Logistic Regression**
Model performance for Training set
- Accuracy: 0.8694
- F1 score: 0.8694
- Precision: 0.8522
- Recall: 0.8904
- Roc Auc Score: 0.8697
----------------------------------
Model performance for Test set
- Accuracy: 0.8611
- F1 score: 0.8612
- Precision: 0.8876
- Recall: 0.8404
- Roc Auc Score: 0.8621

![image](https://github.com/user-attachments/assets/8d69d20a-5a35-4eb3-9ffd-b56679e2aeb7)

**===================================**  


## Also, a simple ANN was built to solve this problem.
4 layers
**The final model accuracy is 91.35%** 
