# Neural_Network_Charity_Analysis


## Analysis Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.\
We use the following methods for the analysis:
- preprocessing the data for the neural network model,
- compile, train and evaluate the model,
- optimize the model.
- 
## Results

Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing

# What variable(s) are considered the target(s) for your model?

  These predictions will be based on the 'IS_SUCCESSFUL' column in the provided data.

# What variable(s) are considered to be the features for your model?

  AFFILIATION
  APPLICATION_TYPE
  ASK_AMT
  CLASSIFICATION
  INCOME_AMT
  ORGANIZATION
  SPECIAL_CONSIDERATIONS
  STATUS
  USE_CASE

# What variable(s) are neither targets nor features, and should be removed from the input data?

The columns for "NAME" and "EIN" have no direct effect on the success/falure rate, and have been excluded from processing.

#  Compiling, Training, and Evaluating the Model

# How many neurons, layers, and activation functions did you select for your neural network model, and why?

Initial preparation for the Sequential Neural Network specified 43 input features, into three processing layers that began with 80 neurons and decreased to 30.


# Were you able to achieve the target model performance?

The target performance of 80% accuracy was not met (72.75%).


# What steps did you take to try and increase model performance?

i tried to add more layers and neurons, but the accurcy for three results was still 72`%

## Summary
The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.\
Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.
