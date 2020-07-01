# final-priject-image_harmonization
this is a final project for course of Machine Learning

##Image Composition <br/>
Goal-1: generates a composite image by extracting the foreground of one image and pasting it on the background of another image. <br/>
Goal-2: adjusts the appearances of the foreground region to make it compatible with the new background.<br/>
Goal-3: learns the mapping between an input image and an output image.<br/>

![avatar](./Picture1.png)
<br/>

##GAN<br/>
Structure: Generator G and Discriminator D, where generator is used to generate fake image and discriminator aims to identify real and fake images.<br/>
![avatar](./Picture2.png)
<br/>

##Experiment<br/>
1.Dataset: including 4 sub-dataset<br/>
![avatar](./Picture3.png)
<br/>

2.toolset：<br/>
Linux<br/>
Python 3<br/>
Pytorch 1.2<br/>
NVIDIA GPU 1080 Ti<br/>

3.Training：<br/>
Image resize 256x256 <br/>
Trade-off parameter ℷ = 0.01<br/>
LeakyReLU  activate function convolution layers<br/>
Adam optimizer<br/>
0.002 learning rate<br/>
evaluation metric – MSE<br/>




