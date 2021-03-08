# Denoising-autoencoder

The data being used to answer this question is the Fashion-MNIST data set. Due to the nature of this problem, only the data concerning images were used. This included 60,000 training images, which were split into a training and validation set, consisting of 50,000 and 10,000 images respectively, and 10,000 test images used as the test set.  

Experimentation done on this project:
 * Implement a denoising autoencoder with mean squared error loss for the Fashion-MNIST data.
 * Explore model variants with different layer sizes, depths, etc. to find what works wellon the validation set and describe the process through which you arrive at your finalmodel.
 * Train the final model to convergence on the training set using different optimisation algorithms. 
    * Adam performed the best of Stochastic Gradient Descent and Root Mean Square Prop.


Observations:

The model does well to produce the correct article of clothing, that is to say, if given a noisy image ofa t-shirt for example, it correctly reproduces an image of a t-shirt.On the other hand, the model seems to struggle in instances in which the item of clothing has detailsand patterns. The model struggles to recreate these logos and patterns, resulting in splotches of adarker or lighter colour in the place where they would be, although the model does get the placementcorrect.The model also seems to find reproducing the correct colour/hue difficult in general.
