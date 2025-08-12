🧠 K-Nearest Neighbors (KNN) Classification with Decision Boundaries
This project demonstrates K-Nearest Neighbors (KNN) classification using Python’s scikit-learn.
It covers dataset generation, feature normalization, model training for multiple values of K, performance evaluation, and decision boundary visualization to understand how K affects model complexity.

📌 Project Workflow
1️⃣ Dataset Creation
Used make_classification from sklearn.datasets to create a 2D synthetic dataset.

Chose 2 informative features for easy visualization.

Balanced binary classification problem.

2️⃣ Feature Scaling
Applied StandardScaler to normalize features.

Scaling ensures that distance calculations in KNN are fair and not biased toward features with larger numeric ranges.

3️⃣ Train-Test Split
Split dataset into 70% training and 30% testing using train_test_split.

Ensures unbiased evaluation of the model.

4️⃣ Model Training & Evaluation
Trained KNeighborsClassifier for K = 1, 3, 5, 7.

Evaluated performance using:

Accuracy Score

Confusion Matrix (via ConfusionMatrixDisplay)

5️⃣ Decision Boundary Visualization
Used a meshgrid to predict labels for each coordinate in the feature space.

Plotted decision regions to see how K changes boundary complexity.

Low K → tight, complex boundaries (risk of overfitting).

High K → smoother boundaries (risk of underfitting).
