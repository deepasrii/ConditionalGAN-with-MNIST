# ConditionalGAN-with-MNIST

Generative Adversarial Networks (GANs) let us generate novel image data, video data, or audio data from a random input. Typically, the random input is sampled from a normal distribution, before going through a series of transformations that turn it into something plausible (image, video, audio, etc.).

However, a simple DCGAN doesn't let us control the appearance (e.g. class) of the samples we're generating. For instance, with a GAN that generates MNIST handwritten digits, a simple DCGAN wouldn't let us choose the class of digits we're generating. To be able to control what we generate, we need to condition the GAN output on a semantic input, such as the class of an image.

Here, Training a GAN conditioned on class labels to generate handwritten digits.

