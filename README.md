# Principle Components Analysis

Principal Component Analysis (PCA) is used in machine learning applications to reduce the dimensionality of the data. It has been especially useful for image compression among other applications.

Implement PCA with the following steps:

See the [notebook](https://github.com/lephanthutra/PCA-Principle-Components-Analysis/blob/main/PCA_G2.ipynb) for more detail.

**Step 1**: Subtract the Mean

**Step 2**: Calculate the Covariance Matrix.

**Step 3**: Calculate Eigenvectors and Eigenvalues of Covariance Matrix.

**Step 4**: Reduce dimensionality and form feature vector.

**Step 5**: Derive the data.

Source [code](https://colab.research.google.com/drive/12sVqKaYb3WKdFe1yf91TYuwUv6j-5rmJ) in Google Colab.

# Model Fitting: Linear Regression Model

See [this notebook](https://github.com/lephanthutra/PCA-Principle-Components-Analysis/blob/main/Model_Fitting.ipynb) for more details.

In this section, I observed the dataset in 3 phases including:

**1. Before applying PCA.**

- Use **LinearRegression()** from **sklearn.linear_model**.

- The linear regression function is y = 1.004 * x + 0.083.

**2. Apply PCA.**

- Apply **PCA** from the **sklearn.decomposition** to the original dataset.

**3. After applying PCA.**

- Use **LinearRegression()** from **sklearn.linear_model**.

- The linear regression function is y = 0.



Reference: 
[1] https://towardsdatascience.com/principal-components-of-pca-bea010cc1d33
