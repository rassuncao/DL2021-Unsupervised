# DL2021-Unsupervised
Python Notebooks to run the code examples of DL unsupervised algorithms for autoencoders, variational autoencoders, and GANs.  

These notebooks are meant to teach Keras with some unsupervised DL algorithms. The best sequence to use these notebooks is the following:

- Autoencoder_MLP_Sequential.ipynb: Building an autoencoder with MultiLayer Perceptron (MLP) using a Sequential Model in Keras
- Autoencoder_CNN_Sequential.ipynb: Same as above but using convolutional neural nets rather than MLP 
- Autoencoder_CNN_Functional.ipynb: Same as above but using the Functional Model in Keras
- Extreme_Autoencoder_CNN_Functional.ipynb: As above but using an extremely small code of dimension 2 and visualizaing the representation
- Autoencoder_Denoising.ipynb: A Functional Model for denosing autoencoder based on CNNs
- Variational_Autoencoder.ipynb: A Functional Model for VAEs based on CNNs. This is almost a copy of the Keras code for AVE that you can find in the documentation at https://blog.keras.io/building-autoencoders-in-keras.html 
- FirstGAN.ipynb: Building a first GAN to generate and save new MNIST images. Adapted from https://machinelearningmastery.com/how-to-develop-a-generative-adversarial-network-for-an-mnist-handwritten-digits-from-scratch-in-keras/  
