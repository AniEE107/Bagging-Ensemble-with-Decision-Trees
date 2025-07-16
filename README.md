# Bagging-Ensemble-with-Decision-Trees
This Jupyter Notebook demonstrates the Bagging ensemble method using Decision Trees on the Iris dataset. It covers data preparation, subset creation, individual tree training, and ensemble prediction, illustrating how bagging reduces variance and improves model stability.

# Overview & Purpose
This Jupyter Notebook provides a practical demonstration of the Bagging (Bootstrap Aggregating) ensemble learning technique. Bagging is a powerful method used to reduce variance and improve the stability and accuracy of machine learning algorithms, particularly decision trees. This project illustrates the core concepts of bagging by applying it to the well-known Iris dataset, showcasing how multiple "weak" learners (individual decision trees) can be combined to form a more robust "strong" learner.

The purpose is to:
Demystify Bagging: Provide a clear, step-by-step implementation of the bagging algorithm.
Showcase Ensemble Power: Illustrate how combining multiple models can lead to better generalization and reduced overfitting compared to a single model.
Practical Application: Apply the technique to a classic classification problem (Iris dataset) to demonstrate its effectiveness.

# Key Concepts & Functionality
Data Loading & Preprocessing: Loads the Iris dataset, performs initial data inspection, and applies LabelEncoder to the target variable (species).
Data Splitting: Divides the dataset into training, validation, and test sets.
Bootstrap Sampling: Demonstrates how bootstrap samples (random sampling with replacement) are created from the training data to train individual base learners.
Decision Tree Classifiers: Utilizes DecisionTreeClassifier as the base estimator for the bagging ensemble.
Ensemble Prediction: Shows how predictions from individual trees are aggregated (e.g., majority voting for classification) to make the final ensemble prediction.
Visualization: Includes scatter plots to visualize the dataset and potentially decision boundaries (though the provided snippet only shows the initial scatter plot).

# Technologies Used
Python
Pandas (for data manipulation)
NumPy (for numerical operations)
Scikit-learn (DecisionTreeClassifier, LabelEncoder, accuracy_score)
Matplotlib & Seaborn (for data visualization)
mlxtend.plotting (for plotting decision regions, if used in later cells)
Jupyter Notebook
