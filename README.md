# AdaBoost
In this project, we explore the application of AdaBoost using a toy example, specifically utilizing the Wisconsin breast cancer dataset. The goal is to instantiate an AdaBoost classifier for each depth in the range 1 to 5. The base learner for each instantiation is set to be a decision tree of the corresponding depth. The primary metric of interest is the 10-fold cross-validated error calculated on the entire breast cancer dataset.

The procedure involves the following steps:
1. Iterate over depths 1 through 5.
2. For each depth, instantiate an AdaBoost classifier with a decision tree of that depth as the base learner.
3. Record the 10-fold cross-validated error on the entire breast cancer dataset for each instantiation.
4. Plot the resulting curve of accuracy against the depth of the base classifier.

The objective is to observe how the accuracy of the AdaBoost classifier varies with different depths of the base learner. This analysis provides insights into the impact of base learner complexity on the overall performance of the AdaBoost ensemble. The resulting curve serves as a visual representation of the relationship between accuracy and the depth of the decision tree base learner in the AdaBoost framework.
