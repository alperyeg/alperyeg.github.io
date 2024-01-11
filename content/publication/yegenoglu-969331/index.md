---
title: Gradient-free optimization of artificial and biological networks using learning
  to learn
authors:
- Alper Yegenoglu
date: '2023-01-01'
publishDate: '2023-12-03T15:51:56.772197Z'
publication_types:
- thesis
publication: '*Forschungszentrum Jülich GmbH, Zentralbibliothek, Verlag*'
doi: 10.18154/RWTH-2023-09115
featured: true
image:
  caption: "Image credit: **Vecteezy**"
  focal_point: ""
  preview_only: false
links:
- name: URL
  url: https://publications.rwth-aachen.de/record/969331
abstract: Understanding human intelligence, learning, decision-making, and memory has long been a pursuit in neuroscience. While our brain consists of networks of neurons, how these networks are trained for specific tasks remains unclear. In the field of machine learning and artificial intelligence, gradient descent and backpropagation are commonly used to optimize neural networks. However, applying these methods to biological spiking networks (SNNs) is challenging due to the binary communication scheme via spikes. 
In my research, I propose gradient-free optimization techniques for artificial and biological neural networks. I utilize metaheuristics like genetic algorithms and the ensemble Kalman Filter (EnKF) to optimize network parameters and train them for specific tasks. This optimization is integrated into the concept of learning to learn (L2L), which involves a two-loop optimization procedure. The inner loop trains the algorithm or network on a set of tasks, while the outer loop optimizes the hyperparameters and parameters.
Initially, I apply the EnKF to a convolutional neural network, achieving high accuracy in digit classification. Then, I extend this optimization approach to a spiking reservoir network using the Python-based L2L-framework. By analyzing connection weights and the EnKF's covariance matrix, I gain insights into the optimization process.
I further enhance the optimization by integrating the EnKF into the inner loop and updating hyperparameters using a genetic algorithm. This automated approach suggests alternative configurations, eliminating the need for manual parameter tuning. Additionally, I present a simulation where SNNs guide an ant colony in food foraging, resulting in emergent self-coordination and self-organization. I employ correlation analysis methods to understand the ants' behavior.
Through my work, I demonstrate the effectiveness of gradient-free optimization techniques in learning to learn. I showcase their application in optimizing both biological and artificial neural networks.
---
