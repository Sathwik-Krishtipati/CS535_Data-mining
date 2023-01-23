# Data-mining

Topic 2: Image Generation with Probabilistic Diffusion Models
 
Introduction:
1.	DDPM - Diffusion Models Beat GANs on Image Synthesis (Machine Learning Research Paper Explained)
2.	What are Diffusion Models?
 
Paper:
[1]Denoising Diffusion Probabilistic Models (DDPM)
 
Reference code: code1 or code2 or code3
 
Problem 1: What is the problem that the paper aims to solve, and why is this problem important or interesting? Answer this question in two sentences. (5 points)
 
Problem 2: Implement DDPM and test it on 2-dimensional Swiss roll data. You should output Fig.3 of the blog intro 2. (20 points)
 
Problem 3: Test DDPM on the mixture of 8 Gaussians and 25 Gaussians respectively. These Gaussians can be either identical or with different parameters at your choice. You should output figures like those in Problem 2. (30 points)
 
Problem 4: Test DDPM on MNIST dataset. Visualize the denoising process (You should output a figure like Fig. 6 in the paper).  (30 points)
 
Problem 5: Perform an interpolation experiment with your trained model from Problem 4 (You should output a figure like Fig. 8 in the paper). (35 points)
 
Topic 3: Image Classification with Normalizing Flows
 
Introduction:
1.	L3 Flow Models -- CS294-158-SP20 Deep Unsupervised Learning -- UC Berkeley -- Spring 2020
2.	Flow-based Deep Generative Models
 
Papers: 
[1]Density estimation using Real NVP
[2]Semi-Supervised Learning with Normalizing Flows
 
Reference code: code 1 and code2
 
Problem 1: Use Real NVP to model the density for the 2-dimensional two-moon, circles, and pinwheel datasets, respectively. You need to output the samples generated from your trained model. You can use code 1 as a library. (20 points)
 
Problem 2: Use Real NVP to do classification on the two-moon, circles, and pinwheel datasets, respectively. You should output figures similar to those in this notebook demo. 
Note: the paper [2] is performing semi-supervised learning, while you are required to do supervised learning where all labels of the data points are available. (30 points)
 
Problem 3: Use Real NVP to do classification on MNIST dataset. Report the prediction accuracy. (30 points)
 
Problem 4: Interpolate the latent space to generate pictures between “2” and “9”. (30 points)
 
Problem 5: Use Real NVP to do classification on CIFAR10 dataset. Report the prediction accuracy. (30 points)
 
Problem 6: Interpolate the latent space to generate pictures between “cat” and “dog”. (30 points)
