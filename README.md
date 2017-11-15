# MNIST IMAGE RECOG

This jupyter notebook consists of a neural network that detects MNIST dataset.

## Tech
* [Jupyter notebook](http://jupyter.org/) - an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.
* [TensorFlow](https://www.tensorflow.org/) - A neural network open source library.
* [TFLearn](http://tflearn.org/) - A easy to use framework that is put over the tensorflow library

## Get it started

  1) Git clone the folder to your computer
  2) Run the jupyternote book. ( make sure you have either Anaconda or virtual env running jupyternotebook )
  3) Run each block of code to see what happens at each step.
  
# Break down
The MNIST dataset is called. TF learn is used to build a simple neural network.
> Training the model

`sh
model.fit(trainX, trainY, validation_set=0.1, show_metric=True, batch_size=100, n_epoch=8)
`

- TrainX is the Labels.
- TrainY is the Features.
- Validation_set means that how much of the Training set is used to validate the model.

### Thats it
The following steps above creates a simple neural network.

-Farhana
