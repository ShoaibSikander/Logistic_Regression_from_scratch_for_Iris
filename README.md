# Logistic_Regression_from_scratch_for_Iris

This repositry implements Logistic Regression Classifier from scratch Python. Coding stuff has been provided in two files, one of which is Jupyter Notebook File and the other one is Python File. Jupyter Notebook explains each step briefly whereas no explanation has been provided in Python File. The reason is that it is exactly the same program as in Jupyter Notebook with the only difference that commands intended for explanation are not included in Python File.
The reknown Iris Dataset has been used in the program which contains three classes of flowers with four features each. The classes are 'Iris-Setosa', 'Iris-Versicolor' and 'Iris-Virginica' whereas features are 'Sepal Length', 'Sepal Width', 'Petal Length' and 'Petal Width'. Since Logistic Regression is a Binary Classifier which uses 'One-Vs-Rest' approach therefore, for the sake of simplicity, one of the class 'Iris-Virginica' has been removed. Therefore dataset limits to 100 samples with 50 samples of 'Iris-Setosa' and 'Iris-Versicolor' each. After shuffling, 90% of data has been used for Training and 10% for Testing. Measuring Test Accuracy, provides a result of 100% which is not suprising due to simplicity of dataset.
After scratch Python implementation, Logistic Regression Classifier has been implemented using Scikit-Learn Library. Same amount of data for training and testing provides Test Accuracy of 100%. Getting same Test Accuracy using both methods proves correctness of scratch Python Implementation.
