---
Topic: Course 1: Supervised Machine Learning: Regression and Classification - Week 3
Source: [Link to Coursera module for this week]
Confidence: [Your rating from 1 to 5]
---

# Core Notes

* **My Legend:**
    * 🔑 **Key Definition:** For critical, must-know vocabulary.
    * ❓ **Question:** For things you don't understand or want to explore later.
    * 🔗 **Connection:** For links to your existing knowledge.
    * 💡 **Insight:** For "aha!" moments or key takeaways.
    * ⚠️ **Warning:** For common mistakes, pitfalls, or important limitations.

---

## Key Concept 1: The Problem of Overfitting

-   🔑 **Key Definitions:**
    -   **Underfitting (High Bias):** When a model is too simple to capture the underlying trend of the data. It performs poorly on both the training and test sets.
    -   **Overfitting (High Variance):** When a model is too complex and captures the noise in the training data. It performs well on the training set but poorly on the test set.
-   💡 **Insight:** The goal is to find a "Goldilocks" model that is not too simple and not too complex, generalizing well to new, unseen data.
-   ❓ **Questions:**
    -   How can you tell if your model is overfitting or underfitting? (By comparing training error to validation/test error).

## Key Concept 2: Regularization

-   🔑 **Key Definitions:**
    -   **Regularization:** A technique used to prevent overfitting by adding a penalty term to the cost function. This discourages the model from learning overly complex patterns.
    -   **L1 Regularization (Lasso):** Adds a penalty proportional to the absolute value of the coefficients. It can shrink some coefficients to exactly zero, performing feature selection.
    -   **L2 Regularization (Ridge):** Adds a penalty proportional to the square of the coefficients. It shrinks coefficients towards zero but doesn't usually set them to exactly zero.
-   ⚠️ **Warnings:**
    -   The regularization parameter (lambda) needs to be chosen carefully. If it's too large, it can lead to underfitting.

## Key Concept 3: The Normal Equation

-   🔑 **Key Definitions:**
    -   **Normal Equation:** An analytical approach to solving for the optimal parameters (theta) in linear regression without using an iterative method like Gradient Descent. It computes the solution directly using the formula: `θ = (XᵀX)⁻¹Xᵀy`.
-   💡 **Insight:** The Normal Equation is a good alternative to Gradient Descent for smaller datasets where computing the inverse of a matrix is feasible.
-   🔗 **Connections:**
    -   This is a closed-form solution, similar to solving a system of linear equations directly, whereas Gradient Descent is an iterative numerical method.
-   ⚠️ **Warnings:**
    -   The Normal Equation can be computationally expensive for large datasets (when the number of features 'n' is large) because of the matrix inversion step `(XᵀX)⁻¹`.
    -   It cannot be used for more complex algorithms like logistic regression.

---

# Module Summary

*(After finishing the module, write a 3-5 sentence summary here from memory **before** reviewing your notes above. This is a critical step for retention.)*

This week focused on improving the performance and generalization of machine learning models. I learned to diagnose the problems of overfitting (high variance) and underfitting (high bias). The main technique to combat overfitting, regularization (both L1 and L2), was introduced, which adds a penalty to the cost function to keep model parameters small. Finally, I learned about the Normal Equation as a direct, non-iterative method to solve for the optimal parameters in linear regression, understanding its advantages and disadvantages compared to Gradient Descent.
