
## **DAY 43 (31 Oct 2023):**
### Topic: Understanding Principal Component Analysis
PCA is a statistical procedure that transforms a set of correlated variables into a new set of uncorrelated variables known as principal components. It achieves this by identifying the directions of maximum variance in high-dimensional data and projecting it onto a new coordinate system.

**Topics Discussed in Notes:**
1. Idea Behind PCA
2. What are Principal Components
3. Eigen Decomposition Approach
4. Singular Value Decomposition Approach
5. Why do we maximize Variance
6. What is Explained Variance Ratio
7. How to select optimal no.of Prinicpal Components
8. Understanding Scree plot
9. Issues with PCA
10. Understanding Kernel PCA

**Key Takeaways:**
1. principal components are a set of linearly uncorrelated variables that are obtained by transforming the original data into a new space. These components help in reducing the dimensionality of the dataset while retaining the maximum possible information from the original data.

2. The first step in calculating Principal Components involves constructing the covariance matrix of the original data. Next, we find the Eigen values and Eigen Vectors for the covariance matrix, the eigen vector corresponding to highest eigen value is the first principal component. projecting the data onto these new dimensions to reduce the dimensionality.

3. Explained Variance Ratio tells us how much data can be explained through a principal component.

4. Scree Plot helps us visualize the relationship of Dimensions and the Explained Variance Ratios, be eyeballing this we can figure out the dimension at which EVR subsequently drops off, this is often referred to as elbow point.

5. Kernel PCA is used to perform complex nonlinear projections for dimensionality reduction. It is often good at preserving clusters of instances after projection, or sometimes even unrolling datasets that lie close to a twisted manifold.

Check out the Notes For More :)


Detailed Notes: [Day 43 Commit](https://github.com/ds-teja/100_Days_MLDL/tree/main/43.%20Day%2043%20-%20Understanding%20Principal%20Component%20Analysis)

LinkedIn post: [Day 43 Update](https://www.linkedin.com/feed/update/urn:li:activity:7125218940699435009?utm_source=share&utm_medium=member_desktop)

---