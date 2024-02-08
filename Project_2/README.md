#**Implementation**
Question 1: Logistic Regression & Overfitting (15 points)
Implementation:

For this question, we plot the sigmoid function for three different values of the parameter w: 1, 5, and 100. Using Python and its libraries, particularly matplotlib, we generate the plots to visualize the behavior of the sigmoid function concerning varying values of w.
Findings:

    The plots clearly illustrate how the sigmoid function behaves differently for different values of w. As w increases, the sigmoid function becomes more prone to overfitting, leading to sharper transitions and potentially poor generalization to unseen data.
    Regularization of the parameter w can indeed help address overfitting in logistic regression. We recommend using L2 regularization (ridge regression) to penalize large weights and promote smoother decision boundaries.

Question 2: Ridge Regression (15 points)
Implementation:

In this question, we express the optimization problem of ridge regression as a problem of minimizing Euclidean distances. We derive the solution step by step, showing the analytical process of obtaining the closed-form solution.
Findings:

    By minimizing the Euclidean distance between the observed and predicted values, ridge regression effectively shrinks the coefficients towards zero, mitigating overfitting.
    The solution to the ridge regression problem is unique when λ > 0 because the addition of the regularization term ensures a unique minimum exists.

Question 3: Face Recognition (70 points)
Implementation:

This question involves several tasks related to the Eigenfaces method for face recognition.

    Task I: We write a function, loadImages(path, set_number), to load images from the Yale B face dataset, returning a data matrix with corresponding labels.
    Task II: Using the loaded images from Set_1, we train the Eigenfaces method with dimensions d = 9 and d = 30. We then evaluate its performance on Sets 1 to 5, reporting classification accuracy for each set and dimension.
    Task III: We display the top principal eigenvectors obtained after training the Eigenfaces method on Set_1.
    Task IV: Using the obtained Eigenfaces, we reconstruct random images from each of the 5 sets for different values of d and assess the reconstruction quality.
    Task V: We display the top principal singular vectors obtained after applying SVD to the data matrix of Set_1 and discuss any differences from eigenvectors.

Conclusion

Through thorough implementation and analysis, we gain insights into various aspects of machine learning and regression analysis. From understanding the impact of parameter values on overfitting in logistic regression to exploring the effectiveness of ridge regression in handling multicollinearity, and finally, applying the Eigenfaces method for face recognition, this project provides valuable practical experience in these domains.
