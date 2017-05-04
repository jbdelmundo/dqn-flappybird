# Keras-FlappyBird

Python based agent that learns to play Flappy bird

A single 200 lines of python code to demostrate DQN with Keras



![](animation1.gif)

-# Installation Dependencies:
-* Python 2.7
-* Keras 1.0
-* Tensorflow 1.0+
-* pygame
-* scikit-image
-* scipy and numpy


If you want to run the original pre-trained network,
-```
-python qlearn_orig.py
-```


If you want to train the network from beginning, delete the model.h5 and run
-```
-python qlearn.py -m "Train
-```

Reference:
Please read the following blog for details
https://yanpanlau.github.io/2016/07/10/FlappyBird-Keras.html