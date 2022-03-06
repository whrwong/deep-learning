# Deep Learning 

## Purpose of this analysis:
Predict whether or not applicants for charity funding will be successful.

Data Preprocessing

What variable(s) are considered the target(s) for your model?
- the IS_SUCCESSFUL variable
What variable(s) are considered to be the features for your model?
- the rest of the variables
What variable(s) are neither targets nor features, and should be removed from the input data?
- ID variables, EIN and NAME


Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The first model contained 5,741 neurons or params, two hidden layers, and one output layer. The activation functions selected were relu and sigmoid. 
- The second model contained 6,351 neurons or params, three hidden layers, and one output layer. The activation functions selected were relu and sigmoid.
Were you able to achieve the target model performance?
- No, we were short by a few percent.
What steps did you take to try and increase model performance?
- I tried filtering the STATUS and SPECIAL_CONSIDERATIONS columns and dropping them. 

