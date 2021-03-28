# venture_funding_with_deep_learning
Using deep neural networks to predict whether or not startups are attractive investments
--
# Usage
This project uses deep learning to predict startup success. To do so, the data is prepared for use in the neural network. First, the data is read into a dataframe and split according to the various columns. Then, the data is converted with binary classification for use in the model. Once this is complete, we initialize the model (the Sequential instance is used) and fit it with the data. The initial model uses 2 hidden layers with the relu activation and the sigmoid activation for the output. The model is compiled with the binary_crossentropy loss function, the adam optomizer and the accuracy metric. This is then optimized with changes to the number of hidden layers and numbers of hidden layers. Finally, the model is saved for future use.
--
# Technologies
The application is written in Jupyter lab using Python. The following packages are used: Pandas, Tensorflow, Keras (Dense and Sequential), and Sklearn (train_test_split, StandardScaler, and OneHotEncoder)
--
# Contributor
Billy Scolinos billyscolinos1@gmail.com
