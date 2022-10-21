# MLP_Adversarial_Examples
Training a multilayer perceptron to classify cats and dogs and implementing fast gradient sign attack to generate adversarial examples to "fool" the network.

Libraries to install; torch, torchvision.

The first part of the code builds a convolutional neural network which is trained on a balanced dataset of 2000 images for each class; cats and dogs. 

The second part of the code generates adversarial examples using fast gradient sign attack.  The attack is executed at varying degrees of perturbation(noise).

The third part of the code visualizes the adversarial examples along with it's misclassified labels and degree of perturbation.


NB: While on cpu, my jupyter terminal was terminated when i implemented the visualization script. I think this may be due to insufficient RAM. If you experience same issue,
I would running the whole script on google colab.

