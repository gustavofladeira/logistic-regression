# Logistic Regression from Scratch

## Project Overview

This project aims to provide a comprehensive understanding of logistic regression by implementing the model from scratch and comparing its performance with a pre-built model from scikit-learn. The implementation and testing are documented in a single notebook, making it easy to follow the entire process from theory to practical application.

### Steps:

1. **Theoretical Background:**
   The notebook begins with a detailed explanation of logistic regression, covering the underlying mathematics and how the algorithm works. This section is crucial for understanding the subsequent implementation.

2. **Logistic Regression Implementation**:  
   I implemented the logistic regression algorithm step by step using only NumPy. This process includes defining the sigmoid function, the cost function, and the gradient descent optimization to fit the model parameters. You can follow the entire implementation in the [logistic_regression.ipynb](logistic_regression.ipynb) notebook.

3. **Model Testing**:  
   After implementing the model, I tested it on a classification problem using a dataset from Kaggle. The performance of this custom model is then compared to a logistic regression model built using scikit-learn’s pre-built function.

### Results:

- Initially, the custom-built logistic regression model achieved an accuracy of 89%, while the model using a pre-built function achieved an accuracy of 95%. 
