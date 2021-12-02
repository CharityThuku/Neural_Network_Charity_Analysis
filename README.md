# Neural_Network_Charity_Analysis
- The purpose of this project was to  use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.

# Results
**Data Processing**
- The columns EIN and NAME are identification information and have been removed from the input data.
- Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop

**Compiling, Training and Evaluating the Model**
- The  neural network model had 2 hidden layers. The first layer had 80 neurons, the second has 30 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."
- The model had an accuracy of 74% but after optimization went down to 72%.

# Summary
- The model ended up with the accuracy score of 72% after optimization. However, the deep learning neural network model did not reach the target of 75% accuracy. We could use a supervised machine learning model such as the Random Forest Classifier as it's an accurate model due to it's sufficient number of estimators and tree depth.
