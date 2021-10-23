# END3.0-Session2.5

Sunny Manchanda

Write a neural network that a. can take 2 inputs:

an image from the MNIST dataset (say 5), and
a random number between 0 and 9, (say 7)
b. and gives 2 outputs:

the "number" that was represented by the MNIST image (predict 5), and
the "sum" of this number with the random number and the input image to the network (predict 5 + 7 = 12)
You can mix fully connected layers and convolution layers

You can use one-hot encoding to represent the random umber input as well as the "summed" output.

Your code MUST be - well documented (via readme file on github and comments in the code) - must mention the data representation - must mention your data generation strategy (basically the class/method you are using for random number generation) - must mention how you have combined the two inputs (basically which layer you are combining) - must mention how you are evaluating your results - must mention "what" results you finally got and how did you evaluate your results - must mention what loss function you picked and why!

Training MUST happen on the GPU

Accuracy is not really important for the SUM

Once done, upload the code with short trining logs in the readme file from colab to GitHub, and share the GitHub lik (public repository

Architecture

MNIST Image-->                    MLP               


                                                                --> Concatenate    --> CrossEntropy Loss --> Output


Random Number Generator-->RNG--> One Hot Encoding----->
