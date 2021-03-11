# Greek-Parliament-Proceedings
In this notebook I will work with a dataset containing Greek Parliament proceedings, available at https://zenodo.org/record/2587904. I will perform Data Exploration, Classification with machine learning and Classification with a Neural Network

## Data Exploration

* Expore the dataset to get an overall idea of what it is about. Think about:

  * Speeches per party.
  
  * Speeches over time.
  
  * Speeches per party and time.
  
  * Speakers per party.
  
  * Etc.
  
* Your analysis can (and should) include tables and diagrams.
* ## Classification without Neural Networks

* Train at least two non-neural network algorithms to learn to classify a speech. The target variable should be the political party of the speaker.

* If a party does not have enough support (in the Machine Learning sense, i.e., too few speeches), you may excise it from the dataset if you detect that you cannot get results for it.

* You should split your data to training and testing datasets, try the different algorithms with cross validation on the training dataset, and find the best hyperparameters for the best algorithm. Note that parameters for bag of words and tf-idf construction can be very important.

* Report your scores; once you find the best algorithm and the best hyperparameters, report the score on the test data.

* To gauge the efficacy of the algorithm, report also the results of a baseline classifier, using, for instance, scikit-learn's [`DummyClassifier`](https://scikit-learn.org/stable/modules/generated/sklearn.dummy.DummyClassifier.html).
* ## Classification with a Neural Network

* Carry out classification, but this time using a neural network.
