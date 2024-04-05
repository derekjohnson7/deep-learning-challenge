# deep-learning-challenge

##Machine Learning Model for Predicting IS_SUCCESSFUL
#Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME: Identification columns
APPLICATION_TYPE: Alphabet Soup application type
AFFILIATION: Affiliated sector of industry
CLASSIFICATION: Government organization classification
USE_CASE: Use case for funding
ORGANIZATION: Organization type
STATUS: Active status
INCOME_AMT: Income classification
SPECIAL_CONSIDERATIONS: Special considerations for application
ASK_AMT: Funding amount requested
IS_SUCCESSFUL: Was the money used effectively


##Model Architecture
Input Features: The model uses all columns from the application_df dataset except for the IS_SUCCESSFUL column as input features.
Neural Network Structure:
Number of Input Features: 116
Number of Neurons in First Hidden Layer: 80
Number of Neurons in Second Hidden Layer: 30
Activation Functions: ReLU for both hidden layers, Sigmoid for the output layer
Total Parameters: 11,821
##Model Training and Performance
Loss: 0.5581
Accuracy: 72.72%
Training Dataset: The model was trained on the training dataset (X_train_scaled, y_train).
Evaluation: The model performance was evaluated on the training dataset.
##Next Steps
Model Evaluation: Evaluate the model on the test dataset (X_test_scaled, y_test) to assess its generalization performance.
Hyperparameter Tuning: Consider tuning hyperparameters (e.g., learning rate, batch size, number of epochs) or adjusting the model architecture to potentially improve performance.
