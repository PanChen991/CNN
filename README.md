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


##model summary 
Model: "sequential"
input_shape = (32,32,3)
conv2d (Conv2D)              (None, 30, 30, 6)         168       
max_pooling2d (MaxPooling2D) (None, 15, 15, 6)         0         
conv2d_1 (Conv2D)            (None, 13, 13, 16)        880       
max_pooling2d_1 (MaxPooling2 (None, 6, 6, 16)          0         
flatten (Flatten)            (None, 576)               0         
dense (Dense)                (None, 120)               69240     
dense_1 (Dense)              (None, 84)                10164     
dense_2 (Dense)              (None, 43)                3655      

##result

![CNN_result](https://user-images.githubusercontent.com/94951202/159159254-3cad5cee-4819-4351-95fc-652309eccaff.png)
