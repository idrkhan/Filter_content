# Filter_content
Data is created from a bollywood song by converting video into frames, it is seperated into parts val(which contains intimate scenes that has to be filtered) ie. the data on which the model was trained.
And the other part consist of the test ie. for testing the model. Test data was unseen to the model at the time of training.
Model was built using a convolution nueral network for binary classification between adult content and normal content.
For optimisation of the model RMSprop was used.
For improving accuracy, data and epochs should be increased.
