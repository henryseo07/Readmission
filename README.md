# Readmission

To access the hyperparameters of the model, use code below:

import pickle

### Load the pickle file
with open('path_to_your_file.pkl', 'rb') as file:
    data = pickle.load(file)

### Access the hyperparameters

hyperparameters = data['hyperparameters']


### Learning Curves are in the Folder
