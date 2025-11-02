---
Topic: Course 1: Supervised Machine Learning: Regression and Classification - Week 2
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

## Key Concept 1: Multiple Linear Regression

-   🔑 **Key Definitions:**
    -   **Multiple Linear Regression:** An extension of simple linear regression that uses multiple features (variables) to predict an outcome. The hypothesis is of the form `h(x) = θ₀ + θ₁x₁ + θ₂x₂ + ... + θₙxₙ`.
    -   **Vectorization:** The practice of using matrix and vector operations to perform calculations on large datasets instead of using loops. This is much more efficient.
-   💡 **Insight:** Vectorization is a key technique for making machine learning algorithms run faster. Instead of iterating over each training example, we can process them all at once in a single matrix operation.

## Key Concept 2: Feature Scaling and Mean Normalization

-   🔑 **Key Definitions:**
    -   **Feature Scaling:** The process of scaling input features to a similar range. This helps gradient descent converge more quickly.
    -   **Mean Normalization:** A specific type of feature scaling where you subtract the mean from each feature and divide by the range (max - min) or standard deviation.
-   ⚠️ **Warnings:**
    -   When you use feature scaling, you must apply the same scaling to new inputs when making predictions.

## Key Concept 3: Logistic Regression for Classification

-   🔑 **Key Definitions:**
    -   **Logistic Regression:** A classification algorithm that models the probability of a discrete outcome. Despite its name, it's used for classification, not regression.
    -   **Sigmoid (Logistic) Function:** A function that maps any real-valued number to a value between 0 and 1. It's used as the hypothesis function in logistic regression. `g(z) = 1 / (1 + e⁻ᶻ)`.
-   💡 **Insight:** The output of the sigmoid function can be interpreted as the probability of the positive class (e.g., the probability that an email is spam).

## Key Concept 4: Decision Boundary

-   🔑 **Key Definitions:**
    -   **Decision Boundary:** The line or surface that separates the different classes in a classification problem. It is a property of the hypothesis function, not the dataset.
-   ❓ **Questions:**
    -   Can decision boundaries be non-linear? (Yes, by using polynomial features in logistic regression).
    -   How do you visualize a decision boundary for a dataset with more than two features?

---

# Module Summary

*(After finishing the module, write a 3-5 sentence summary here from memory **before** reviewing your notes above. This is a critical step for retention.)*

This week built upon the foundations of linear regression by extending it to multiple features. I learned the importance of vectorization for efficiency and feature scaling for faster convergence of gradient descent. The focus then shifted to classification problems, introducing logistic regression and the sigmoid function to predict probabilities. A key concept was the decision boundary, which visually separates the classes learned by the model.
