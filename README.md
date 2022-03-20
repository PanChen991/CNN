# CNN

# Exercise 2 - CNN

## Objective

In this exercise, you will use the Keras API to create a first CNN.


## Details

Using the Keras API, you have to create a small convolutional neural networks using less than 15 layers, containing
at least one convolutional layer, one pooling layer and one dense (fully connected layer). You can find a list of the different
layers available [here](https://www.tensorflow.org/api_docs/python/tf/keras/layers).

You should experiment with different designs (number of layers, types of pooling, filter sizes, number of fully connected layers, number of neurons).

You will need to feed the image directory to `training.py` (`GTSRB/Final_Training/Images/`) with `-d`, and can view the final metrics visualization in the Desktop.

## Tips

A good starting point for small networks is LeNet5. You will find many existing implementations online.

Don't forget the basic structure of a convnet: convolutional layer, activation and pooling.

You can use the [`summary`](https://www.tensorflow.org/api_docs/python/tf/keras/Model#summary) method of the Keras model API to print the description of your model.


##result
![CNN_result](https://user-images.githubusercontent.com/94951202/159158944-e2821383-c54e-40fa-872c-b4e73eb8614e.png)
