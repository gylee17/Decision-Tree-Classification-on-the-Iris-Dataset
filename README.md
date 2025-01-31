# Decision-Tree-Classification-on-the-Iris-Dataset

### Overview
This project applies a Decision Tree Classifier to the Iris dataset, leveraging hyperparameter tuning with GridSearchCV to optimize model performance. The workflow includes data preprocessing, feature scaling, model training, evaluation, and visualization.

### Features
- Data Preprocessing: One-hot encoding, normalization, and summary statistics.
- Model Training: Decision Tree Classifier with hyperparameter tuning using GridSearchCV.
- Model Evaluation: Performance metrics and feature importance analysis.
- Visualization: Decision tree plot, feature importance ranking, and decision boundary visualization.

### Results
- The best model selected had max_depth=5, achieving 100% accuracy on the test set.
- Feature importance analysis identified key predictors.

### Dependencies
- scikit-learn
- numpy
- pandas
- matplotlib
- seaborn
