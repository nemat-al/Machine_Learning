## Machine_Learning
Tasks for Machine Learning Course in ITMO University.

### Index
1. [Classifiers](#classifiers)
2. [Optimization algorithms](#optimization_algorithms)
3. [Logistic regression method](#logistic_regression_method)
4. [Natural Language Processing](#natural-anguage-processing)
5. [CNN and Transfer Learning](#cnn_and_transfer_learning)

---------------------

### [Classifiers](https://github.com/Nemat-Allah-Aloush/Machine_Learning_Techinques/blob/main/Task_1.ipynb)
* The first task was to train, test and evaluate four different models.
The four different trained classifiers are:
1. Small decision tree
2. Deep decision tree
3. Random forest on small trees
4. Random forest on deep trees
* Evaluating each model individualy was done by calculating some metrics (precision;recall; accuracy; F1-score; log-loss;) and by ploting precision-recall 
and ROC curves for each model.
* The second task was to train a classifier that avoids Type II (False Negative) errors
and calculate different metrics to evaluate it. By avoiding Type II errors, it means that the recall for that algorithm should be greater than 0.95

---------------------

### [Optimization algorithms](https://github.com/Nemat-Allah-Aloush/Machine_Learning_Techinques/blob/main/Task_2_Optimization.ipynb)
* In this file two optimization algorithms were implemented:
1. Gradient Descent (GD) algorithm 
2. Adam's optimization algorithm 
for a function of two variables f(x,y).
* The two algorithms were applied on an arbitrary function and implement the search for its minimum.
* Finally the process of finding an extremum was illustrated in the form of a graph.

---------------------

### [logistic regression method](https://github.com/Nemat-Allah-Aloush/Machine_Learning_Techinques/blob/main/Task_3.ipynb)
Logistic regression method was implemented through three different optimization algorithms: gradient descent, stochastic gradient descent, and Adam algorithm. The three algorithms were built as modeled and trained for 5 different learning rates. Finally the performance of the three algorithms was compared

---------------------

### [Natural Language Processing](https://github.com/Nemat-Allah-Aloush/Machine_Learning_Techinques/blob/main/Task_4_NLP.ipynb)
*	The data analyzed is the story of Alice in Wonderland by Lewis Carroll from Project Gutenberg's [website](http://www.gutenberg.org/files/11/11-0.txt).
*	First of all necessary preprocessing tasks are performed on the text: converting to lower case, removing stop words, numbers / non-alphabetic characters, lemmatization.
*	The first task is to find Top 10 most important words (excluding the word 'Alice') from each chapter in the, in terms of TF-IDF metric.
Then trying to name each chapter according to the identified tokens?
*	The second task is to find the Top 10 most used verbs in sentences with Alice. And concluding what does alice do the most.

---------------------

### [CNN and Transfer Learning](https://github.com/Nemat-Allah-Aloush/Machine_Learning_Techinques/blob/main/Task_5_CNN_and_Transfer_Learning.ipynb)
The aim of this file is to distinguish dogs from cats first by Convolutional Neural Network and then by transfer Learning model using pre-trained VGG16-model weights from keras application.
