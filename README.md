# Image multi-classification using transfer learning by pytorch and resnet

Implemented by pytorch in jupyternotebook, here I fine tune the last fully connected layer in Resnet50 and trained on Imagewoof dataset
using 20 epochs, using around 30 min GPU time on Google Colab, achieving the accuracy of 78 % (The state of art at the time of writing is 88.58%).[Ref 1] 

Then the results are evaluated and the class with the poorest prediction score is selectively visualized. 

Finally, Grad-Cam is used to visualize the 4th last hidden layer on the trained Resnet50 model on the poorest classified image to understand how the neural network process the image in that layer. 

## reference:

[1] The Imagewoof dataset leaderbroad can be found [here](https://github.com/fastai/imagenette).
[2] [Pytorch transfer learning tutorial](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html) 
[3] [Imformative post about Grad-Cam](https://glassboxmedicine.com/2020/05/29/grad-cam-visual-explanations-from-deep-networks/)




