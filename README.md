# Handwritten-digits-classifier

This is a personal project that I carried out in order to apply the knowledge I acquired through the online book ["Neural Networks and Deep Learning"](http://neuralnetworksanddeeplearning.com/index.html), by Michael Nielsen.


You can check the jupyter notebook I've written on my repo [here](https://github.com/eliottjoulot/Handwritten-digits-classifier/blob/master/Network.ipynb).

You will need a very basic understanding of neural networks to understand what is going on in the code. If you don't, I highly recommend you watch [this series of videos](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi).

You will also need mathematical background on linear algebra, and most importantly be familiar with gradient descent. If you're not, I have written a <a href="../assets/pdf/neural_networks.pdf">short summary of the mathematical concepts</a> we will use in this project.

<br>

**Our goal is to recognize handwritten digits within the MNIST dataset, the "hello world" of neural networks.**

This digits are rendered on a 28 by 28 pixel grid, each pixel containing a grey-scale value between 0 and 1.
Those pixels are what determine the activation of 784 neurons in the input layer of the network.

<br>