# TensorFlow
+ TensorFlow on Python 3.4

## Current Info.
+ Python : 3.43
+ TensorFlow : 0.10.0rc0

## Running Container
### Using Jupyter
+ docker run --name tensorflow -it -p 8888:8888 wall72/tensorflow
### Using Jupyter, TensorBoard
+ docker run --name tensorflow -it -p 8888:8888 -p 6006:6006 wall72/tensorflow
+ Run TensorBoard : #> tensorboard --logdir=./logs --host 0.0.0.0

## Reference
+ https://github.com/tensorflow/tensorflow
