import pickle

# Load the pickle file
with open('path_to_your_file.pkl', 'rb') as file:
    data = pickle.load(file)

# Access the hyperparameters
# This depends on how your data is structured.
# For example, if your data is a dictionary and hyperparameters are stored under the key 'hyperparameters':
hyperparameters = data['hyperparameters']

# Now you can use the hyperparameters variable as needed
