# Ensemble Learning from Scratch: Decision Trees & Random Forests

This repository contains a ground-up implementation of supervised learning algorithms to solve the classic Titanic survival prediction problem. Rather than relying on high-level libraries for model training, this project focuses on implementing the underlying mathematical and logical structures of ensemble methods.

## Key Features
* **Custom Decision Tree:** Built from scratch using Information Gain and Entropy as splitting criteria. Includes logic for handling categorical features and recursive tree depth.
* **Random Forest Ensemble:** Implemented bootstrapping (sampling with replacement) and feature bagging to create a robust ensemble of custom decision trees.
* **SVM Comparative Analysis:** Includes a Support Vector Machine implementation to benchmark the performance of custom ensemble methods against traditional kernel-based classifiers.
* **Mathematical Rigor:** Manual calculation of entropy and node purity, demonstrating a deep understanding of how non-linear decision boundaries are constructed.

## Tech Stack
* **Language:** Python
* **Libraries:** NumPy, Pandas, Matplotlib (used primarily for data handling and visualization).
* **Algorithms:** Decision Trees (ID3/C4.5 logic), Random Forest, SVM.

## Analytical Insights
* **Algorithm Benchmarking:** The custom Random Forest demonstrated superior robustness to noise compared to a single Decision Tree, effectively reducing variance through bagging.
* **Hyperparameter Impact:** Detailed analysis of how tree depth and the number of estimators (trees) affect model generalization and the risk of overfitting.
* **Feature Importance:** Evaluation of which passenger attributes (e.g., class, age, gender) contributed most to the model's predictive power.
