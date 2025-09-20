# GAN-Monet-Paintings-Generator

In this project, I build a Generative Adversarial Network (GAN) to transform any picture into a Monet-style painting.

How does a GAN work?
A GAN is composed of two neural networks trained together in opposition:

- The Generator takes an input image and transforms it to imitate Monet’s artistic style, creating a synthetic "painting."

- The Discriminator tries to distinguish between real Monet paintings and the generator’s creations.

Through this adversarial process, the generator improves at producing images that capture Monet’s style, while the discriminator becomes better at spotting fakes—pushing the generator to create increasingly convincing Monet-like artworks.

files : 

monet_paintings : file containing 300 images of Monet's artwork 
photos : file containing 7038 pictures ready to be transformed into fake Monet paintings 

image_processing.py : taking the image datasets as inputs and converting images to tensors ready for machine learning 
models.py : building the Generator and Discriminator model classes 
train.py : training the models with adversion process and returning the fake painting  
