# IML_DecisionTree

## Description:

This project contains the ID3 Decision tree algorithm implementation by Daphne Demekas, Nasma Dasser, Constantin Eulenstein and Kevin Landert. The algorithm aims to predict the room in which a user is located based on seven WiFi signal strengths that are captured from the user's mobile phone. To train and test the algorithm, we use two separate "clean" and "noisy" datasets, both containing 2000 samples of seven continuous variables (signal strengths from seven emitters) and one categorical variable (the room in which the user is located).


## Folder structure:
* [data](https://github.com/Nasmasim/Decision-Trees/tree/main/data): all data files used in this project
    * [wifi_db](https://github.com/Nasmasim/Decision-Trees/tree/main/data/wifi_db): contains _clean_datatest.txt_ and _noisy_dataset.txt_
    * [testing_data](https://github.com/Nasmasim/Decision-Trees/tree/main/data/testing_data): contains examples of edge cases datasets
* [jupyter](https://github.com/Nasmasim/Decision-Trees/tree/main/jupyter): contains the Jupyter Notebook _DecisionTree_Notebook.ipnyb_ to open on Jupyter Lab
* [src](https://github.com/Nasmasim/Decision-Trees/tree/main/src): contains all python files
    * _DecisionTree.py_ the decision tree algorithm, evaluation, prediction and pruning
    * _utils.py_ utiliy functions for loading the data, calculating entropy, and plotting the confusion matrix
    * _validation.py_ function for the 10-fold cross validation 
* [tests](https://github.com/Nasmasim/Decision-Trees/tree/main/tests): contains anything corresponding to testing

## Requirements
IML_DecisionTree requires the following to run: 
* ```Python3```
* ```numpy ```
* ```matplotlib```

## Run instructions:

* This project can be run via the command line using the command ```python3 main.py``` . 
    * The code then runs on the two given inputs _clean_data.txt_ and _noisy_data.txt_. 
* To print individual trees and run the code with different data on **jupyter**
    1. Open the _DecisionTree_Notebook.ipnyb_ in the [jupyter](https://github.com/Nasmasim/Decision-Trees/tree/main/jupyter) folder
    2. Run the code
* You can also run the code with another dataset by
    1. Uploading new dataset in the [wifi_db](https://github.com/Nasmasim/Decision-Trees/tree/main/data/wifi_db) folder
    2. Changing the path to the new dataset in ```main.py```
## Credit
Daphne Demekas, Nasma Dasser, Constantin Eulenstein and Kevin Landert

