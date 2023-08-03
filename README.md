# deep-learning-challenge

# Overview

This analysis is used to determine the likelihood of success for each venture. The data contains demographics of organizations that have received prior funding.

# Results
In preprocessing, the EIN and Name columns were removed from the analysis because neither are relevant to the performance of the organization. The "Is successful" column is the target, as it gives a binary classifaction of the successfulness of the organization. And, the remaining columns were used as the features as they are descriptions of the performance. The Application type and Classification columns contained an excessive amount of unique values, these 2 columns were broken into to smaller buckets so that there were 10 or less unique values.

The intial model (located in Starter_Code.ipynb file) had an accuracy of 72%. I made a few more attempts to improve accuracy, in the first optimization model I increased the number of neurons in both the input and hidden layer and added another layer. This did not significantly improve the accuracy. In the second model optimization, I didn't change the neurons but instead changed the activation method for the hidden layers. Still no improvement in accuracy there. In the final attempt, I increased the epochs and the number of neurons.

# Summary
In summary, more optimization is needed in order for this to be a functional model in application forecasting.