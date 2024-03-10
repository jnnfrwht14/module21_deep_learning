# module21_deep_learning

# Overview of the analysis: 
The goal of this analysis was to create a model that was able to identify applicants for funding with the best chance of success in their venture if selected by Alphabet Soup.

# Results:

## Data Preprocessing

* What variable(s) are the target(s) for your model? 'IS_SUCCESSFUL'
* What variable(s) are the features for your model? 'IS_SUCCESSFUL'
* What variable(s) should be removed from the input data because they are neither targets nor features? 'EIN', 'NAME', 'SPECIAL_CONSIDERATIONS', AFFILIATION', 'USE_CASE'

## Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why? I used 18 neurons and incremented down. I added five layers for this neural network model. I used both ReLu and sigmoid since the data reflects 0,1 for IS_SUCCESSFUL.
* Were you able to achieve the target model performance? No. The closest I was able to get was 0.7321 accuracy.
* What steps did you take in your attempts to increase model performance? Removed data from the DF, changed neurons, layers and activation fucntions as well as changed the number of epochs.

##Summary: I ran over 40 models but kept seven. I tried a variety of models - varied the number of nodes and input features and activation. I wasn't able to reach 75%, and realized that removing some of the columns from the data decreased the accuracy. If the first ten epochs didn't reach 72 or higher, then the overall model was not going to reach 73. I would recommend removing outliers in the 'INCOME_AMT' and "ASK_AMT" to reduce noise. 


![attempt7](https://github.com/jnnfrwht14/module21_deep_learning/assets/144621532/cc1b225f-c53b-4800-9458-534ab9979b52)

H5 help:
https://www.tensorflow.org/guide/keras/serialization_and_saving
