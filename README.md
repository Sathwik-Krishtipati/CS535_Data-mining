# Data-mining

#### The following projects were in collaboration with Teresa Chu, Kaushal Thakar, Kishore Kumar Basam, Vikas Kiran Nadikuda for the CS 535 Data mining course

### TOPIC 2 : Image Generation with Probabilistic Diffusion Models
 

Reference paper:
Denoising Diffusion Probabilistic Models (DDPM) : https://hojonathanho.github.io/diffusion/
 
Reference codes:
https://github.com/lucidrains/denoising-diffusion-pytorch

https://github.com/hojonathanho/diffusion

https://github.com/pesser/pytorch_diffusion

 
Problem 1: What is the problem that the paper aims to solve, and why is this problem important or interesting? Answer this question in two sentences. 
 
Problem 2: Implement DDPM and test it on 2-dimensional Swiss roll data. You should output Fig.3 of the blog intro 2. 

Problem 3: Test DDPM on the mixture of 8 Gaussians and 25 Gaussians respectively. These Gaussians can be either identical or with different parameters at your choice. You should output figures like those in Problem 2. 

Problem 4: Test DDPM on MNIST dataset. Visualize the denoising process (You should output a figure like Fig. 6 in the paper).
 
Problem 5: Perform an interpolation experiment with your trained model from Problem 4 (You should output a figure like Fig. 8 in the paper).


 
### TOPIC 3: Image Classification with Normalizing Flows
 
 
Reference papers: 
[1]Density estimation using Real NVP: https://arxiv.org/abs/1605.08803

[2]Semi-Supervised Learning with Normalizing Flows: https://arxiv.org/abs/1912.13025
 
Reference code: 

https://github.com/chrischute/real-nvp

https://github.com/izmailovpavel/flowgmm


 
Problem 1: Use Real NVP to model the density for the 2-dimensional two-moon, circles, and pinwheel datasets, respectively. You need to output the samples generated from your trained model. You can use code 1 as a library. 
 
Problem 2: Use Real NVP to do classification on the two-moon, circles, and pinwheel datasets, respectively. You should output figures similar to those in this notebook demo. 
Note: the paper [2] is performing semi-supervised learning, while you are required to do supervised learning where all labels of the data points are available.

Problem 3: Use Real NVP to do classification on MNIST dataset. Report the prediction accuracy. 
 
Problem 4: Interpolate the latent space to generate pictures between “2” and “9”. 
 
Problem 5: Use Real NVP to do classification on CIFAR10 dataset. Report the prediction accuracy.
 
Problem 6: Interpolate the latent space to generate pictures between “cat” and “dog”.
