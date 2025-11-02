---
Topic: "Course 1: Supervised Machine Learning: Regression and Classification - Week 1"
Source: "[Link to Coursera module for this week]"
Confidence: "[Your rating from 1 to 5]"
---

# Core Notes

* **My Legend:**
    * 🔑 **Key Definition:** For critical, must-know vocabulary.
    * ❓ **Question:** For things you don't understand or want to explore later.
    * 🔗 **Connection:** For links to your existing knowledge.
    * 💡 **Insight:** For "aha!" moments or key takeaways.
    * ⚠️ **Warning:** For common mistakes, pitfalls, or important limitations.

---

## Key Concept 1: Introduction to Supervised Learning

-   🔑 **Key Definitions:**
    -   **Machine Learning:** The field of study that gives computers the ability to learn without being explicitly programmed.
    -   **Supervised Learning:** A type of machine learning where the algorithm learns from labeled data. The data consists of input features and corresponding output labels.
    -   **Unsupervised Learning:** A type of machine learning where the algorithm learns from unlabeled data, finding patterns or structure in the data on its own.
-   💡 **Insight:** The key difference between supervised and unsupervised learning is the presence of a "ground truth" or "correct output" during the training phase.

## Key Concept 2: Regression and Classification

-   🔑 **Key Definitions:**
    -   **Regression:** A supervised learning task where the output is a continuous value (e.g., predicting the price of a house).
    -   **Classification:** A supervised learning task where the output is a discrete category (e.g., classifying an email as "spam" or "not spam").
-   ❓ **Questions:**
    -   What are the most common algorithms for regression and classification?
    -   Can a problem be both regression and classification?

## Key Concept 3: Linear Regression with One Variable

-   🔑 **Key Definitions:**
    -   **Hypothesis Function (h(x)):** The function that maps input features (x) to an output prediction (y). In linear regression with one variable, it is of the form `h(x) = θ₀ + θ₁x`.
    -   **Cost Function (J(θ₀, θ₁)):** A function that measures the accuracy of the hypothesis function. It calculates the average squared difference between the predicted values and the actual values. The goal is to minimize this function.
-   💡 **Insight:** The cost function provides a way to quantify how "wrong" our model's predictions are. By minimizing the cost, we find the best-fit line for our data.

## Key Concept 4: Gradient Descent

-   🔑 **Key Definitions:**
    -   **Gradient Descent:** An optimization algorithm used to minimize a cost function. It iteratively moves in the direction of the steepest descent of the function.
    -   **Learning Rate (α):** A parameter that controls how big of a step we take during each iteration of gradient descent.
-   ⚠️ **Warnings:**
    -   If the learning rate is too small, gradient descent can be very slow.
    -   If the learning rate is too large, gradient descent can overshoot the minimum and fail to converge.

---

# Module Summary

*(After finishing the module, write a 3-5 sentence summary here from memory **before** reviewing your notes above. This is a critical step for retention.)*

This week introduced the fundamental concepts of supervised machine learning. I learned about the difference between supervised and unsupervised learning, and the two main types of supervised learning problems: regression and classification. The core of the week was understanding linear regression with one variable, how to measure its performance with a cost function, and how to optimize it using gradient descent.
