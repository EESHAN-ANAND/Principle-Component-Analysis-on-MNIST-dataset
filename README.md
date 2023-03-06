# Principle-Component-Analysis-on-MNIST-dataset
This code highlights the implementation of Principle Component Analysis technique on the famous MNIST dataset.  

### The PCA is one the most important steps for feature creation in Machine Learning

<li>PCA, or Principal Component Analysis, is a statistical method used in machine learning for reducing the dimensionality of large data sets. In essence, PCA transforms the original variables into a new set of variables, called principal components, that are linear combinations of the original variables. These principal components capture the maximum amount of variance in the original data, allowing us to represent the data in a more compact form.</li>

<li>PCA can be used for a variety of purposes, including data compression, visualization, and feature extraction. It is commonly used in image processing, signal processing, and bioinformatics, as well as in many other fields.</li>

<li>The PCA algorithm works by first calculating the covariance matrix of the data. This matrix describes how the variables in the data are related to each other. Next, the algorithm finds the eigenvectors and eigenvalues of this matrix. The eigenvectors represent the directions of maximum variance in the data, while the eigenvalues represent the amount of variance along each of these directions.</li>

<li>The eigenvectors are used to construct a new coordinate system in which the data is represented. This new coordinate system is chosen such that the first principal component (the eigenvector with the largest eigenvalue) represents the direction of maximum variance in the data, the second principal component (the eigenvector with the second largest eigenvalue) represents the direction of maximum variance orthogonal to the first, and so on. By projecting the original data onto this new coordinate system, we can represent the data in a reduced-dimensional space that captures most of the variation in the original data.</li>

### Using PCA, their is immense advanatge dealing with the data:-
<ol>
<li>Reduces dimensionality: PCA can effectively reduce the number of dimensions in a dataset while retaining most of the information, making it easier to work with and visualize large datasets.</li>

<li>Identifies important features: PCA helps identify the most important features in a dataset, which can be useful in feature selection and in building more efficient models.</li>

<li>Reduces noise: PCA can help reduce noise in a dataset by removing dimensions that do not contribute significantly to the overall variation in the data.</li>

<li>Increases model accuracy: By reducing the number of dimensions, PCA can help improve the accuracy of machine learning models by reducing overfitting and simplifying the relationships between variables.</li>

<li>Improves computational efficiency: PCA can help speed up the training process for machine learning models by reducing the number of computations required to process the data.</li>
  </ol>
  
### However using PCA comes at a cost and there are several disadvantages realted to PCA:-

<ol>
<li>Loss of interpretability: PCA transforms the original variables into new components, which can be more difficult to interpret than the original variables. This can make it more challenging to understand the underlying relationships between variables.</li>

<li>Information loss: While PCA retains most of the variation in the original data, there is still some information loss in the transformation process. Depending on the level of compression required, this loss of information can be significant.</li>

<li>Sensitivity to outliers: PCA is sensitive to outliers in the data, which can distort the principal components and lead to inaccurate results.</li>

<li>Computationally intensive: Computing the covariance matrix and eigenvectors can be computationally intensive for large datasets, which can be a disadvantage in terms of computational resources and time required for analysis.</li>

<li>Assumption of linearity: PCA assumes that the relationships between variables are linear, which may not always be the case in real-world datasets. In cases where the relationships are non-linear, other techniques may be more appropriate.</li>
  </ol>
