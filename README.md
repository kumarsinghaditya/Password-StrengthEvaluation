# Password-StrengthEvaluation

Evaluate the strength of your entered password in one go!


<img width="868" alt="102" src="https://user-images.githubusercontent.com/92226347/174485965-bd411c20-9208-479a-bfb9-20b3bfe20262.png">


To ensure diversity, assurance and correctness of our results, the strength of the passcode is depicted using different Machine Learning models and also, it is extended by applying deep learning to it by using ANN.

The machine learning models are trained and dumped into joblib files to avoid recomputing the same function repetitively which ulitmately saves a lot of time.

The models used to predict results are:

1) Logistic Regression
2) Naive Bayes
3) Decision Tree
3) Multi Layer Perceptron Network (ANN)


To provide a comparitive analysis over the strength of the password, machine learning as well as standard rules for rating password are also used so as to generate a Password Metric score simultaneosly.


<img width="868" alt="102" src="https://user-images.githubusercontent.com/92226347/174485864-c645b129-5808-44b9-9cb4-a5af88f8a280.png">


# Installation

• To run the project, clone the project into your PC/Mac:

      git clone https://github.com/kumarsinghaditya/Password-StrengthEvaluation.git
    
• To run the project:
      
      python nordpass.py

• Runs the website in the development mode.

      Open http://172.17.60.117:4000/ to view in your browser after successfully compiling the project.

• Note: If the version mismatches, the joblib files might fail to be dumped and would not load. In that case, try training the models and overwrite the joblib files.

      python DecisionTree.py
      python LogisticRegression.py
      python NaiveBayes.py
      python NeuralNetwork.py
