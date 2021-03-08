# Denoising-autoencoder

The data being used to answer this question is the Fashion-MNIST data set. Due to the nature of this problem, only the data concerning images were used. This included 60,000 training images, which were split into a training and validation set, consisting of 50,000 and 10,000 images respectively, and 10,000 test images used as the test set.  

Experimentation done on this project:
 * Implement a denoising autoencoder with mean squared error loss for the Fashion-MNIST data.
 * Explore model variants with different layer sizes, depths, etc. to find what works wellon the validation set and describe the process through which you arrive at your finalmodel.
 * Train the final model to convergence on the training set using different optimisation algorithms. 
    * Adam performed the best of Stochastic Gradient Descent and Root Mean Square Prop.
