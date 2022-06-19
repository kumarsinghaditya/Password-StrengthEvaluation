# Password-StrengthEvaluation

Evaluate the strength of your entered password in one go!

To ensure diversity, assurance and correctness of our results, we output the strength of the passcode using different Machine Learning models and also have extended the project to apply deep learning to it by using an ANN.

The machine learning models are trained and dumped into joblib files to avoid recomputing the same function repetitively which ulitmately saves a lot of time.

The models used are:

1) Logistic Regression
2) Naive Bayes
3) Decision Tree
3) Multi Layer Perceptron Network (ANN)

# Installation

• To run the project, clone the project into your PC/Mac:

      git clone https://github.com/kumarsinghaditya/Password-StrengthEvaluation.git
    
• Note: If the version mismatches, the joblib files might fail to be dumped and would not load. In that case, try training the models and overwrite the joblib files.

      python DecisionTree.py
      python LogisticRegression.py
      python NaiveBayes.py
      python NeuralNetwork.py
