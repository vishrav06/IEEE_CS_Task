# IEEE_CS_Task
This repo stores the colab file where I performed the task for core member selection.

### Level 1

I used pandas to read the datset.
Did some basic analysis of the dataset.
Then I removed the labels from the dataset.
Once I was done with analyzing the structure of the image, I went on to display it.

I used matplotlib.pyplot to display 5 random samples for each label.

To conclude the EDA, I looked at the pixel distribution vaalues for the entire dataset and also for specific datapoints.



### Level 2

Firstly I normalized the dataset.
Then I created a multinomial Logistic Regression model using sklearn and trained the model.
The model had a test accurracy of 84.9%, precision of 0.89, and recall of 0.89.

Later I used SHAP to explain the model predictions giving the most important features for each class.
I also plotted feature importance to get the most important feature overall.



### Level 3

Here I started by creating a model using artificial neural network.
The architecture had one input layer, 2 hidden layers with relu activation, and one output layer with softmax activation.
The optimizer I used was Adam and loss was categorical cross entropy.
I used callbacks including early stopping and learning rate scheduler for efficient training.
After training, the accuracy of the model was 88.88% and the precision and recall were 0.89.
