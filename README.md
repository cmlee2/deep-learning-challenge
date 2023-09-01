# deep-learning-challenge

Overview:

For this challenge, I was tasked with building a neural network that would be able to classify whether a company would be successfully funded by the fictional nonprofit foundation Alphabet soup. I received a dataset containing 34000 organizations that had received funding from the company over the years.

Results:

Data Preprocessing:

For this Dataset, our target variable was the IS_SUCCESSFUL column because we wanted to see whether the company would be funded. Our features included the variables APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL CONSIDERATIONS, and ASK_AMT. The columns EIN and NAME were dropped due to those columns being neither features or target variables.

Compiling, Training, and Evaluating Model

My first neural network contained 2 layers. The first layer had 8 Neurons, while the second layer had 5 neurons. When optimizing the model, I created neural network with 5 layers containing 26, 26, 11, 26 and 6 neurons respectively. Both of these models utilized a relu activation function. I was unable to achieve the 75% accuracy goal with my last model. To help tune the model, I imported Keras Tuner and ran 52 trials with varying epochs, layers, and nodes to find the best settings for my model.

Summary:

The model was very close to achieving the goal 75% accuracy, but was ultimately unable to reach the desired goal. Potential recommendations include adding additional layers or nodes to model. 