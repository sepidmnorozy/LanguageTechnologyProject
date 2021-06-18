# LanguageTechnologyProject

This project consists of three files: 
-bert.ipynb
-ff.ipynb
-data_distribution.ipynb

Along with a folder for the datafiles, containing:
-X_test.pickle
-X_train.pickle
-y_test.pickle
-y_train.pickle

The data_distribution file can be run to analyse the train and test set, giving an overview of the distribution of labels and of sentence length (after tokenization). It also contains information on the different data sources.

The bert.ipynb file is the code for training and testing the BERT Transformer model on the data. It will require having the data in a folder, but no further dependencies. Running the entire file will train the model for a specified number of epochs, save the model weights, and then test the model on the test set. It will print a confusion matrix and the misclassifications. 

The ff.ipynb file is the code for training and testing the feedforward neural network model on the data. It will require having the data in a folder, but no further dependencies. Running the entire file will train the model for a specified number of epochs, save the model weights, and then test the model on the test set. It will print a confusion matrix and the misclassifications.
