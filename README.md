# SVM-Classifier
This Python script is designed to predict stroke diagnoses using a Support Vector Machine (SVM) classifier, integrating key data science libraries. The script begins by importing necessary libraries, such as Pandas for data manipulation, NumPy for numerical operations, scikit-learn for machine learning tasks, and Matplotlib for visualization.

The process commences with loading a preprocessed stroke dataset, Transformed_Stroke_Data.csv. The dataset undergoes a selection process focusing on numeric columns, aligning with the SVM classifier's requirements. The target variable for prediction is identified as 'Diagnosis'.

The dataset is then split into features (X) and the target (y), followed by dividing it into training and testing sets using scikit-learn's train_test_split function. This ensures a robust evaluation of the model's performance.

An SVM classifier with a linear kernel is initialized and trained on the training data. Post-training, the classifier is used to predict stroke outcomes on the test set. Additionally, the script calculates probabilities to construct a Receiver Operating Characteristic (ROC) curve, an essential tool for evaluating the performance of binary classifiers.

The script concludes by generating a classification report, providing detailed performance metrics like precision, recall, and f1-score for the classes 'No Stroke' and 'Stroke'. Moreover, it features a plotted ROC curve, visually representing the model's diagnostic ability by showcasing the trade-off between the True Positive Rate and False Positive Rate, along with the Area Under Curve (AUC) metric.

This script is ideal for medical diagnostic projects, particularly in stroke prediction, leveraging the precision and effectiveness of SVM for classification tasks, combined with the analytical power of Pandas, NumPy, scikit-learn, and Matplotlib.
