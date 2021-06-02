# DecisionTreeRegression

A 1D regression with decision tree.

The decision trees is used to fit a sine curve with addition noisy observation. As a result, it learns local linear regressions approximating the sine curve.

We can see that if the maximum depth of the tree (controlled by the max_depth parameter) is set too high, the decision trees learn too fine details of the training data and learn from the noise, i.e. they overfit.

![plot](https://user-images.githubusercontent.com/82667439/120518922-ef22c780-c386-11eb-9f86-3c493e7174c1.jpg)

