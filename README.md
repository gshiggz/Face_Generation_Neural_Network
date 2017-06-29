# Face_Generation_Neural_Network
This Network Uses Generative Adversarial Networks (GANs) to generate original images of faces. This is accomplished by combining
two Convolutional Neural Networks (CNNs) against each other. One is designated as the discriminator model which discriminates if 
an image is real or fake via a CNN. The other is designated as the generator model which will take a random vector and upsample through 
a transposed CNN. This model was trained on the MNIST and CelebA datasets on a Floydhub GPU cloud instance in Python and Tesorflow.
