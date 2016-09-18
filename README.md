# MNIST_NN
This repo is used to understand how different type of Neural Network works, and how to achitect a neural network. The mnist_cnn.py follows examples from keras.

Use `virtualenv` to create a new environment and use `pip install -r requirements.txt` to install all the dependencies required in this project.

This repo use `keras` to architect NNs and use `theano` as it's backend. Considering expensive computation, it is recommended to train the models on a GPU, using `THEANO_FLAGS=device=gpuX, floatX=float32 python xxx.py` where gpuX is the identity of your GPU.
