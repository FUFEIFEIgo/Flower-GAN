# Flower-GAN
#### The method for Chinese art painting of flowers synthesis.
### Introduction of Flower-GAN System
##### The Flower-GAN system is divided into training and testing stages. The training stage includes two steps, 1) Training the attention network, generator and discriminator together. The aim of attention network is to obtain the attention map of the input images. When the performance of attention network is improved, we stop the training of this network. Finally, inputting the synthesized image to discriminator to judge directly. 2) Training the generator and discriminator. Different from step 1), finally, inputting the masked synthesized image to discriminator to judge. The testing stage, inputting the the prepared test images to generator framework to synthesize.

![image](https://github.com/FUFEIFEIgo/Flower-GAN/blob/master/step1.png)
![image](https://github.com/FUFEIFEIgo/Flower-GAN/blob/master/step2.png)
