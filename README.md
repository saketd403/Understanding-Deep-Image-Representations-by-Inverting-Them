# Understanding-Deep-Image-Representations-by-Inverting-Them

Reconstructing the content of image based on paper "Understanding Deep Image Representations by Inverting Them"
by Mehandran and Veldadi (https://arxiv.org/pdf/1412.0035.pdf).

This paper illustrates how can the image be reconstructed using feature maps(feature detectors) of convolutional layers.It is understood that the higher layers retain less of the details of the image and so it is difficult to reconstruct those. The reason for this is higher layers focus more on complex and discriminative features.

This repository provides two ipython notebooks. We have used pretrained VGG19 for one notebook while we used  a pretrained  convolutional network provided as seperate file for second notebook.VGG19 model is able to reconstruct complex 3D images while the other model is pretrained on MNIST dataset and is able to reconstruct handwritten digits.

Please refer the notebooks for code and reconstructed images.
