#Bias, Variance and the Trade-off

Machine learning algorithms can best be understood through the lens of the bias-variance trade-off.

Bias are the simplifying assumptions made by a model to make the target function easier to learn.

Generally parametric algorithms have a high bias making them fast to learn and easier to understand but generally less flexible. In turn they have lower predictive performance on complex problems that fail to meet the simplifying assumptions of the algorithms bias.

Decision trees are an example of a low bias algorithm, whereas linear regression is an example of a high-bias algorithm.

Variance is the amount that the estimate of the target function will change if different training data was used. The target function is estimated from the training data by a machine learning algorithm, so we should expect the algorithm to have some variance, not zero variance.

The k-Nearest Neighbors algorithm is an example of a high-variance algorithm, whereas Linear Discriminant Analysis is an example of a low variance algorithm.

The goal of any predictive modeling machine learning algorithm is to achieve low bias and low variance. In turn the algorithm should achieve good prediction performance. The parameterization of machine learning algorithms is often a battle to balance out bias and variance.

(1) Increasing the bias will decrease the variance.
(2) Increasing the variance will decrease the bias.