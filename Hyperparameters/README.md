# Access the hyperparameters
## For all models except ANN
from joblib import load

# Replace 'path_to_your_model.pkl' with the actual path to your saved model file
model = load('path_to_your_model.pkl')

print(model.get_params())
