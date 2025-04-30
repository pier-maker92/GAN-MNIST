# GAN-MNIST
A step-by-step [Colab notebook](https://colab.research.google.com/drive/1SQ2TnrzOZ4OgUDCz3t8IAhoNdmlTYh_K#scrollTo=uLFtBKUDVQcv) that shows how to generate, steer, and invert handwritten digits with three progressively richer models:

- Unconditional DC-GAN – learns the data distribution and produces random digits.

- Conditional GAN (cGAN) – adds class labels so you can ask for any specific numeral (0-9).

- Encoder / Inference Net – maps a real image back to its latent vector z, enabling reconstructions and latent-space editing.


