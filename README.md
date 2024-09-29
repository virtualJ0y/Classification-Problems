# Classification-Problems

This project is part of a machine learning course at the University of Macedonia. The task is to develop a classification model that predicts whether a company declared bankruptcy or not, based on financial data from Greek companies between 2006 and 2009.

The project involves working with an imbalanced dataset, applying various classification models, and evaluating their performance using different metrics. A key focus is on handling class imbalances using the SMOTE (Synthetic Minority Over-sampling Technique) method.

Dataset
The dataset consists of financial indicators and other economic information about Greek companies from 2006 to 2009. The target variable is binary, indicating whether a company went bankrupt.

Data Preprocessing
Normalization: Min-Max normalization was applied to scale the features between [0, 1].
Imbalanced Dataset Handling: The SMOTE technique was used to balance the dataset, which originally had many more healthy companies than bankrupt ones.
Methods Used
Data Loading
The dataset was loaded using Pandas and split into training, testing, and validation sets using train_test_split.
Classification Algorithms
The following classification algorithms were used:

Decision Tree Classifier (DTM)
Logistic Regression Classifier (LR)
k-Nearest Neighbors (KNN)
Support Vector Machine (SVM)`
Each algorithm was trained on the transformed dataset, and predictions were made on both training and test sets.

Evaluation Metrics
Several evaluation metrics were used to assess the model performance:

Accuracy: The overall correctness of the model's predictions.
Precision: The proportion of positive predictions that were correct.
Recall: The proportion of actual positives that were correctly identified.
F1 Score: The harmonic mean of precision and recall, used for imbalanced data scenarios.
Confusion Matrix: Used to visualize true positives, true negatives, false positives, and false negatives.

Visualizations
Confusion matrices and F1 score graphs were generated to better understand the model performance. The visualizations highlighted the disparities between training and test results, particularly in F1 scores due to the imbalanced nature of the dataset.

Future Improvements
Tuning KNN Hyperparameters: Overfitting in KNN suggests the need for increasing n_neighbors.
Exploring Other Oversampling Techniques: Beyond SMOTE, exploring other methods for handling imbalanced datasets could improve results.
Cross-Validation: Implement cross-validation to improve model generalization.

Contributors
Charalambia Zerva (ics20117)
Maria-Anna Ioannidou (ics20067)
Alexandros Lemona (ics20103)
