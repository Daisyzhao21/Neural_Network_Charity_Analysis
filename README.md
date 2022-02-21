Neural Network Charity Analysis 
===============================

### Overview

The purpose is this project is to predict loan risk by using Machine Learning to analyze a dataset of more than 34,000 organizations that have received funding from Alphabet Soup over the years.

### Results
#### 1. Data Preprocessing:


- What variable(s) are considered the target(s) for your model?

	'IS_SUCCESSFUL'is the target column. 

- What variable(s) are neither targets nor features, and should be removed from the input data?

	'EIN' and 'NAME' column are dropped.

- What variable(s) are considered to be the features for your model?

	After 'EIN' and 'NAME' columns are dropped, all the other columns are considered to be the features in the  model.

#### 2. Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

	Two-layers, network model with 10 and 5 neurons. A sigmoid activation function is used throughout hidden and output layers.
  ![](https://raw.githubusercontent.com/Daisyzhao21/Neural_Network_Charity_Analysis/main/1.png)

- Were you able to achieve the target model performance?
```
Training Loss: 0.5495;  Accuracy: 0.7334
Test Loss: 0.560 Accuracy: 0.72396
```
Even the best model upon tuning the hyper-parameters was unable to achieve the target model performance. 0.72396 is a satisfied performance.

- What steps did you take to try and increase model performance?

	To improve the accuracy from the initial model with varying degree of success.
 
### Conclusion

A simple two-layer Neural Network Model will predict results with satisfying accuracy. However, the model performance only achieved 72.396% accuracy even upon changing the hyperparameters, such as activation function, number of layers and number of neurons. The combination of several optimization techniques improved the accuracy slightly, but met with diminishing returns for the additional effort. To improved accuracy, it is suggested to explore other machine learning methods such as Logistic regression or Support-vector machine. 
