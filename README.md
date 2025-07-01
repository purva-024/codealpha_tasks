# codealpha_tasks

Task 1: Iris Flower Classification

Use measurements of Iris flowers (setosa, versicolor, virginica) as input data.
● Train a machine learning model to classify the species based on these measurements.
● Use libraries like Scikit-learn for easy dataset access and model building.
● Evaluate the model’s accuracy and performance using test data.
● Understand basic classification concepts in machine learning.
_________________________________________________________________________________________________________________________________________________________________________________________

**Title: Iris Flower Classification**

The Iris Flower Classification dataset (also known as the Iris dataset or Fisher’s Iris dataset) includes four input features (independent variables) used to classify the flowers into three species.
This project uses the classic Iris dataset to classify flowers into three species: Setosa, Versicolor, and Virginica, based on their sepal and petal measurements. 
_________________________________________________________________________________________________________________________________________________________________________________________

**Features**:

* Uses Scikit-learn to load the Iris dataset and train models.
* Classification based on 4 features:
  * Sepal Length (cm)
  * Sepal Width (cm)
  * Petal Length (cm)
  * Petal Width (cm)
* Splits dataset into training and test sets.
* Displays model accuracy, confusion matrix, and classification report.
________________________________________________________________________________________________________________________________________________________________________________

* The data was successfully split into training (80%) and testing (20%) sets, resulting in 120 training samples and 30 testing samples.
* A Logistic Regression model was trained on the training data.
* The trained Logistic Regression model achieved perfect scores (1.0000) for accuracy, precision, recall, and F1-score on the test set.
* The confusion matrix showed that the model correctly classified all 30 instances in the test set across the three Iris species (10 setosa, 9 versicolor, and 11 virginica).
* The classification report confirmed the perfect precision, recall, and F1-score of 1.00 for each individual class (setosa, versicolor, and virginica).
_______________________________________________________________________________________________________________________________________________________________________________

**Output**:
* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score
