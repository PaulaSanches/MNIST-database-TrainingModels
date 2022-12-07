# MNIST-database-TrainingModels
The MNIST (Modified National Institute of Standards and Technology) is a set of 70,000 small image digits handwritten. It is used for training models to recognize handwritten, face recognition and medical diagnosis. 

# Random Forest Results & Discussion
The labels range from 0 to 9, which are the images that we have in this experiment. The training data set will be 60 K, and the number of estimators will be 20 decision trees. The frequency of each class is shown in the picture below.

Accuracy was in general 96% which is not sufficient to measure the experiment. The precision to define each of these classes can say better about the learning method. The best precision was with label 1, which means the method was classified correctly. Labels 5 and 8 were necessary to recall more than label nine because of the round format image. 

Confusion Matrix indicates that label 1 received 1375 points, 1367 were classified correctly, but 4 were classified as label 2. The worst-case scenario is for label 8, which received 81 points divided not correctly with another label. 
A classifier with 100% accuracy would produce a pure diagonal matrix with all the points classified in their correct class.
In Random Forest, cross-validation is not necessary; it can be used "out of bag error", which defines the quality of the data.

# Conclusion
Random Forests work well for a large range of data than the decision trees overcoming the problem of overfitting or combining the different results of decision trees. Also, they are flexible and possess a high level of accuracy. Moreover, Random Forests have good accuracy even some data is missing. However, they are much harder time consuming than decision trees, making them slow and requiring more computational resources. Beyond this, Random Forest do not work very well with data complexity.

Regards to Support Vector Machine (SVM) works well with high-dimensional space, and it is also memory effective. The most significant disadvantage is that the data needs to be standardized in preparation stage, and overfitting occasionally happens. 




