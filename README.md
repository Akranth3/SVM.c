This repo has the code and results for the parallel implementation of Support vector machine algorithm, parallelization is acheived using OPENMP.


# Notes (from PRML book)
- An important property of support vector machines is that the determination of the model parameters corresponds to a convex optimization problem, and so any local solution is also a global optimum<br>
- If there are multiple solutions all of
which classify the training data set exactly, then we should try to find the one that
will give the smallest generalization error<br>
- The support vector machine approaches
this problem through the concept of the margin, which is defined to be the smallest
distance between the decision boundary and any of the samples
- 
