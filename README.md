# Sampling
<h2> What is Sampling? </h2>

Sampling is a statistical technique used in research and data analysis to select a subset of individuals or observations from a larger population. Instead of collecting data from the entire population, researchers gather information from a representative sample. The goal is to make inferences and draw conclusions about the entire population based on the characteristics observed in the selected sample. Sampling is employed to save time, resources, and costs, while still providing reliable insights when done with appropriate methods and considerations for representativeness.

<h2>Why do we need Sampling? </h2>
Sampling is a statistical method used to select a representative subset from a larger population, providing a more practical and cost-efficient way to gather insights. It saves resources, conserves time, and is often necessary when studying large or inaccessible populations. Proper sampling allows researchers to make accurate inferences about the entire population based on the characteristics of the chosen subset, making it a crucial tool in data analysis and research.

<h2>Sampling Techniques</h2>
Apply Various sampling techniques to address class imbalance:
<h3>Oversampling:</h3>
Random Oversampling: balance the class distribution by randomly duplicating the instances of the minority class
SMOTE: Generates synthetic samples by focusing on the minority samples
<h3>Undersampling:</h3>
Random Undersampling: balance the class distribution by randomly duplicating the instances of the majority class
Tomek Links: Identifies and remove instances that are considered ambiguous or near the decision boundary between classes
Near miss: Identifies instances which are close to instances from minority class, aiming to retain the instances that are more difficult to classify correctly

<h2> Models Used </h2>
<h3>Gradient Boosting:</h3>
Gradient Boosting is an ensemble learning method that builds a series of weak learners sequentially, with each one correcting the errors of the previous, making it robust for handling imbalanced datasets.

<h3>K-Nearest Neighbors (KNN):</h3>
KNN is a non-parametric classification algorithm that assigns an observation to the majority class of its k-nearest neighbors, making it suitable for sampling as it relies on local patterns.

<h3>Logistic Regression:</h3>
Logistic Regression is a linear model for binary classification that estimates the probability of an instance belonging to a particular class, often used with various sampling techniques to address class imbalance.

<h3>Random Forest:</h3>
Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their predictions, providing stability and accuracy, especially when dealing with imbalanced datasets.

<h3>Support Vector Machine (SVM):</h3>
SVM is a powerful classification algorithm that aims to find the hyperplane that best separates classes in a high-dimensional space, and it can benefit from sampling techniques to handle class imbalance effectively.










