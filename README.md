# wine-quality-classification-Random-forest

This is an academic deep-dive into the fundamental limitations of single decision trees and the power of ensemble methods for regression and classification tasks. Using the UCI Wine Quality dataset, we empirically demonstrate how random forests and ensemble techniques overcome the inherent overfitting problem of fully-grown decision trees through variance reduction.

We will discuss:
- Overfitting in Single Decision Trees - Understanding the bias-variance tradeoff
- Feature Subsampling (ρ) - How random feature selection decorrelates ensemble members
- Generalization: Training a Forest to reduce variance (improve Test scores)
- Bagging
- Pruning: Playing with ccp_alpha to control complexity.
- Feature Importance: Comparing MDI (Default) vs. Permutation Importance.
