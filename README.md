# TextToFloorGAN-Synthesizing-Architectural-Floor-Plans-using-GANs



## Table of Contents
1. [Objective](#objective)
2. [Dataset](#dataset)
3. [Models Used](#models-used)
4. [Training Results](#training-results)
5. [Generated Results](#generated-results)
6. [Try Yourself](#try-yourself)
7. [Literature Survey](#literature-survey)



## Objective
To create a fully function CGAN on Floor Plan Dataset; which can take input text from user and return the floor plan generation. Further understanding how Vanilla GAN work on the Floor Plan Dataset



## Dataset
https://aclanthology.org/2023.acl-long.820/

Picture of a sample Image from Dataset


![image](https://github.com/iamzayd/TextToFloorGAN-Synthesizing-Architectural-Floor-Plans-using-GANs/assets/91972048/77383ca5-8865-4912-8ef0-8aa20d405665)



## Models Used

CGAN - Text to Image

Vanilla GAN - Image Synthesis



## Training Results

CGAN




Vanilla GAN


![image](https://github.com/iamzayd/TextToFloorGAN-Synthesizing-Architectural-Floor-Plans-using-GANs/assets/91972048/28505873-e63b-4dcf-bb9e-fca11adb93b8)



## Generated Results

CGAN
Prompt - bathroom is in north side of the house, next to living room and common room, size of bathroom is 8 feet in width and 6 feet in length. common room is in north east corner of the house, next to living room, bathroom and master room, size of common room is 10 feet in width and 14 feet in length. kitchen is in west side of the house, next to living room, size of kitchen is 6 feet in width and 16 feet in length. living room is in west side of the house, next to master room, kitchen, bathroom and common room, size of living room is 348 sqft. master room is in south east corner of the house, next to living room and common room, size of master room is 12 feet in width and 14 feet in length.

ACTUAL:


![image](https://github.com/iamzayd/TextToFloorGAN-Synthesizing-Architectural-Floor-Plans-using-GANs/assets/91972048/648d8a38-df2a-41ad-8b5e-51eeae5e0363)



GENERATED:



![image](https://github.com/iamzayd/TextToFloorGAN-Synthesizing-Architectural-Floor-Plans-using-GANs/assets/91972048/9e775b00-edd3-4bf8-818e-d975fffb526a)


Vanilla GAN



## Try Yourself


1. Downlaod the dataset from https://aclanthology.org/2023.acl-long.820/

2. Run  ``` git clone https://github.com/iamzayd/TextToFloorGAN-Synthesizing-Architectural-Floor-Plans-using-GANs.git ```

3. Choose Files to run based on your choice  ``` <model_name>.ipynb ```



## Literature Survey

Generative Adversarial Networks (GANs):
"A Generative Adversarial Network" by Ian J. Goodfellow et al. (2014)


Conditional Generative Adversarial Networks (cGANs):
"Conditional Generative Adversarial Networks" by Mehdi Mirza and Simon Osindero (2014)


Conditional Variational Autoencoders with Generative Adversarial Networks (CVAE-GAN):
"CVAE-GAN: Fine-Grained Image Generation Through Asymmetric Training" by Jianwen Bao et al. (2017)


Deep Convolutional Generative Adversarial Networks (DCGANs):
"Deep Convolutional Generative Adversarial Networks" by Alec Radford et al. (2015)

