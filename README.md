# Task-7-Support-Vector-Machines-SVM-

#Tools & Libraries Scikit-learn – for model building and evaluation NumPy – for numerical computations Matplotlib – for visualizations

#Project Structure / Steps

Load and Prepare Dataset Used make_classification from sklearn.datasets to generate a 2D binary classification dataset. Features are scaled using StandardScaler for better SVM performance. Data split into training and test sets using train_test_split.

Train SVM Models Trained two SVM classifiers: Linear Kernel RBF (Radial Basis Function) Kernel

Visualize Decision Boundaries Used a mesh grid and plt.contourf() to plot the decision surface. Plotted training points to visualize how well the classifier separates the classes.

Hyperparameter Tuning Applied GridSearchCV to find the best C and gamma values for the RBF kernel. Searched across a grid: C: [0.1, 1, 10, 100] gamma: ['scale', 0.01, 0.1, 1]

Evaluate Performance Evaluated the best model on the test set using: Precision Recall F1-score Accuracy

📊 Outputs Decision boundary plots for both kernels. Best hyperparameters found via Grid Search. Classification report on the test data.
