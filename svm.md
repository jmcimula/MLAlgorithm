#Support Vector Machines

Support Vector Machines are perhaps one of the most popular and talked about machine learning algorithms.

A hyperplane is a line that splits the input variable space. In SVM, a hyperplane is selected to best separate the points in the input variable space by their class, either class 0 or class 1.

In two-dimensions you can visualize this as a line and let's assume that all of our input points can be completely separated by this line.

The SVM learning algorithm finds the coefficients that results in the best separation of the classes by the hyperplane.

The distance between the hyperplane and the closest data points is referred to as the margin. The best or optimal hyperplane that can separate the two classes is the line that as the largest margin.

Only these points are relevant in defining the hyperplane and in the construction of the classifier.

These points are called the support vectors. They support or define the hyperplane.

In practice, an optimization algorithm is used to find the values for the coefficients that maximizes the margin.

SVM might be one of the most powerful out-of-the-box classifiers and worth trying on your dataset.