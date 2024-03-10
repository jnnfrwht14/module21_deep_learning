# module21_deep_learning

# Overview of the analysis: 
The goal of this analysis was to create a model that was able to identify applicants for funding with the best chance of success in their venture if selected by Alphabet Soup.

# Results:

## Data Preprocessing

* What variable(s) are the target(s) for your model? 'IS_SUCCESSFUL'
* What variable(s) are the features for your model?
* What variable(s) should be removed from the input data because they are neither targets nor features? 'EIN', 'NAME', 'SPECIAL_CONSIDERATIONS', AFFILIATION', 'USE_CASE'

## Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why? I used 18 neurons and incremented down. I added five layers for thie neural network model. I used both ReLu and sigmoid since the data reflects 0,1 for IS_SUCCESSFUL.
* Were you able to achieve the target model performance? No. The closest I was able to get was 0.7321 accuracy.
* What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
