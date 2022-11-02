# DC-GAN
Generating MNIST Digit Dataset using Deep Convolutional Generative Adversarial Network

## GAN
> In a machine learning (ML) model called a generative adversarial network (GAN), two neural networks fight with one another to make predictions that are more correct. GANs generally operate unsupervised and learn through cooperative zero-sum games.

## Components that make up a GAN :

- The generator gains the ability to provide credible data. The created instances serve as the discriminator's negative training examples.
The discriminator gains the ability to discern real data from bogus data generated by the generator. The generator is punished by the discriminator when it generates improbable outcomes.
- The discriminator quickly learns to recognise the evident bogus data produced by the generator when training first starts.

<img src="https://eugenie.ai/wp-content/uploads/2021/08/Screenshot-2021-08-10-at-5.32.25-PM.png" width="500" height="200"/>

#### The MNIST Dataset containing digits handwritten in numerous free styles

<img src="https://miro.medium.com/max/584/1*2lSjt9YKJn9sxK7DSeGDyw.jpeg" width="400" height="300"/>
  
#### Included the dataset using the following code-
` (X_train, y_train), (X_test, y_test) = mnist.load_data() `

A GAN built with generator of
` 
