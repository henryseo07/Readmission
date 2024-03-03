# Access the hyperparameters

import pickle

# Load the pickle file
with open('path_to_your_file.pkl', 'rb') as file:
    data = pickle.load(file)

hyperparameters = data['hyperparameters']

