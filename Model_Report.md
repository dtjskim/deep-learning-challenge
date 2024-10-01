Overview of the analysis: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Results: Using bulleted lists and images to support your answers, address the following questions:

*Data Preprocessing*

1.  What variable(s) are the target(s) for your model?
- The target variable is the 'IS_SUCCESSFUL' column from application_df

2.  What variable(s) are the features for your model?
- The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe

3.  What variable(s) should be removed from the input data because they are neither targets nor features?
- Both 'EIN' and 'NAME' columns were dropped/removed, because they were neither targets nor features for the dataset.


*Compiling, Training, and Evaluating the Model*

1.  How many neurons, layers, and activation functions did you select for your neural network model, and why?
- In the first attempt, i used 10 hidden_nodes_layer1 and 5 hidden_nodes_layer2, this was just a intial guess to see the result. 

2.  Were you able to achieve the target model performance?
- No, best accuracyI've achieved is around 73%

3.  What steps did you take in your attempts to increase model performance?
- I added more layers, removed more columns, added additional hidden nodes, and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

In this exercise, my best model had around 73% accuracy in predicting the classification problem. I think using a model with greater correlation between input and output would yield higher accuracy. I believe this could be achieved by doing additional data cleanup as well as by using a model with different activation functions and iterating until higher accuracy is reached. 


