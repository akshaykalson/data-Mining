Image Classification Using Machine Learning Models

This Python script demonstrates image classification using machine learning models such as Support Vector Machines (SVM), Decision Trees, and Random Forests. The classification task is performed on features extracted from images, and the performance of each model is evaluated using confusion matrices.

Description
The script carries out the following steps:

Data Loading and Preprocessing: Load the dataset containing images and their corresponding classes. Merge the dataset with features extracted using edge histograms. Split the data into training and testing sets.

Model Training: Initialize and train three different classifiers: SVM, Decision Tree, and Random Forest.

Hyperparameter Tuning: Fine-tune the hyperparameters of the SVM classifier using grid search and cross-validation.

Model Evaluation: Evaluate the performance of each trained model on the test set. Generate confusion matrices to visualize classification results.

Confusion Matrix Export: Export the confusion matrices to CSV files for further analysis.

Usage
Ensure you have Python installed on your system.

Install the required dependencies by running:

pip install pandas scikit-learn
Run the Python script:

python image_classification.py
After execution, you can find the confusion matrices saved as CSV files in the same directory:
svm_confusion_matrix.csv
dt_confusion_matrix.csv
rf_confusion_matrix.csv
Requirements
Python 3.x
pandas
scikit-learn

Note
Make sure to replace the paths to your dataset files (EdgeHistogram.csv and Images.csv ) before running the script.

Contact
For any inquiries, please contact akshay.kalson@b-tu.de

Acknowledgments
This script was created as part of Data Mining course.