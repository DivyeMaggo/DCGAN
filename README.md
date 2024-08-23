# DCGAN
![image](https://github.com/user-attachments/assets/53b17464-047c-42d3-941c-f8ff4d38f067)

A DCGAN is essentially an extension of the basic GAN model, but with a specific use of convolutional layers in the discriminator and convolutional-transpose layers in the generator. This architecture was first introduced by Radford et al. in the paper titled Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks.

Improvements in Deep Convolutional Generative Adversarial Networks (DCGANs) typically focus on enhancing stability, training efficiency, and output quality. Here are some key advancements concisely summarized:

1. Replace pooling layers with strided convolutions in the discriminator and with fractional-strided convolutions in the generator.

2. Apply batch normalization in both the generator and the discriminator.

3. Eliminate fully connected hidden layers in deeper architectures.

4. Utilize ReLU activation for all layers in the generator, except for the output layer, which uses Tanh.

5. Employ LeakyReLU activation for all layers in the discriminator.

These improvements collectively help DCGANs generate more realistic images and improve the overall performance of the model.

I reimplemented DCGAN on cifar-10 dataset taking reference from [https://github.com/pytorch/tutorials/blob/main/beginner_source/dcgan_faces_tutorial.py.](https://github.com/Ksuryateja/DCGAN-CIFAR10-pytorch)

Best output, along with generator and discriminator loss:





![image](https://github.com/user-attachments/assets/06011fa5-5901-440d-850c-69f3049eacad)
![image](https://github.com/user-attachments/assets/2f2a86be-65e8-494c-9dfe-660e4c5e764a)




![image](https://github.com/user-attachments/assets/65416ff3-9194-4c13-b2a8-1e8ad1d25ac8)
