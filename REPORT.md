# deep-learning-challenge

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.
The report should contain the following:
Overview of the analysis: Explain the purpose of this analysis.
Results: Using bulleted lists and images to support your answers, address the following questions:
Data Preprocessing
1. What variable(s) are the target(s) for your model?
* The target variable is the 'IS_SUCCESSFUL' column from application_df
2. What variable(s) are the features for your model?
* The feature variables are every other column from application_df other than 'IS_SUCCESSFUL' column 
3. What variable(s) should be removed from the input data because they are neither targets nor features?
* Both 'EIN' and 'NAME' columns were dropped/removed, because they were neither targets nor features for the dataset.
Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
* In the first attempt, I used 9 hidden_nodes_layer and relu as activation function and later on tried adding more hidden layer and change activation function to tanh
2. Were you able to achieve the target model performance?
* The 75% model accuracy target was not achieved even after changing activation function or adding hidden layers did not make much difference and we are still at 72% accuracy 
3. What steps did you take in your attempts to increase model performance?
 I increased the number of layers, eliminated more columns, added extra hidden nodes, and changed the activation functions for each layer in an effort to improve the model's accuracy.


Summary: The deep learning model achieved approximately 72% accuracy in predicting the classification problem. To improve prediction accuracy, a model that better correlates input and output data is recommended. This could be accomplished through further data preprocessing and cleanup, experimenting with different activation functions, and iterative optimization of the model.


