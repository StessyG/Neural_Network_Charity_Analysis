# Neural_Network_Charity_Analysis
# Overview of the analysis: Explain the purpose of this analysis.

Alphabet Soup raised and donates money 
The purpose of this analysis is to use a mathematical data driven solution to help Alphabet Soup predict which organizations are worth donating to, and which are too high-risk. The analysis focuses on designing and training a deep learning neural network.
During the analysis, we created a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

# Results: Using bulleted lists and images to support your answers, address the following questions.

1. Data Preprocessing

- The variables that were considered in this model: "STATUS", "ASK_AMT", "APPLICATION_TYPE", "CLASSIFICATION', "USE_CASE", "ORGANIZATION", and "INCOME_AMT".                   2

- The dependent variable is "IS SUCCESSFUL" since the goal is to determine the applications that will be successful.

- Two variables were removed during the analysis: "EIN" and "NAME".

2. Compiling, Training, and Evaluating the Model

- For the neural network model, 2 hidden layers were used; first one with 80 neurons, and the second one with 30 neurons. The relu activation function was applied for the hidden layers, while the sigmoid activation function was applied for the output layer.
The activation functions were set as follow because the sigmoid function performes best in binary classification problems, while the relu function is mostly used for non linear relationships in datasets.

- The target model performance was not achieved. The model accuracy was 0.66, while the model loss was 0.74.


![image1](https://github.com/StessyG/Neural_Network_Charity_Analysis/blob/514aadf7a4643f7b6572cb191fb8ffaec85bbe9a/Resources/images/image1_nm.png)


- To increase the model performance and the predictive accuracy, three different attempts were made:

- First attempt: The activation function of hidden layers was changed
    - 2 hidden layers
    - 80 neurons(first layer), 30 neurons(second layer) and 20 neurons(third layer)
    - Used relu and sigmoid activation functions for the hidden layers and sigmoid activation function for the output layer

![image2](https://github.com/StessyG/Neural_Network_Charity_Analysis/blob/514aadf7a4643f7b6572cb191fb8ffaec85bbe9a/Resources/images/image2_nm.png)

- Second attempt: Additional hidden layers were added 
    - 3 hidden layers
    - 80 neurons(first layer), 30 neurons(second layer) and 20 neurons(third layer)
    - Used relu and sigmoid activation functions for the hidden layers and sigmoid activation function for the output layer
    
    
![image3](https://github.com/StessyG/Neural_Network_Charity_Analysis/blob/514aadf7a4643f7b6572cb191fb8ffaec85bbe9a/Resources/images/image3_nm.png)

- Third attempt: Additional neurons were added to hidden layers
    - 2 hidden layers
    - 90 neurons(first layer) and 55 neurons(second layer)
    - Used relu activation function for the hidden layers and sigmoid activation function for the output layer


![image4](https://github.com/StessyG/Neural_Network_Charity_Analysis/blob/514aadf7a4643f7b6572cb191fb8ffaec85bbe9a/Resources/images/image4_nm.png)



# Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

