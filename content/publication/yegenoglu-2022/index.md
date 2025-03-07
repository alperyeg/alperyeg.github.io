---
title: "Exploring Parameter and Hyper-Parameter Spaces of Neuroscience Models on High Performance Computers With Learning to Learn"
authors:
  - Alper Yegenoglu
  - Anand Subramoney
  - Thorsten Hater
  - Cristian Jimenez-Romero
  - Wouter Klijn
  - Aaron Pérez Martín
  - Michiel van der Vlag
  - Michael Herty
  - Abigail Morrison
  - Sandra Diaz-Pier
date: "2022-05-07"
publishDate: "2022-05-27"
publication_types:
  - article-journal
publication: "*Frontiers in Computational Neuroscience*"
doi: 10.3389/fncom.2022.885207
image:
  caption: "Two loop concept of L2L."
  focal_point: ""
  preview_only: false
url_code: "https://github.com/Meta-optimization/L2L/tree/frontiers_submission"
abstract: Neuroscience models commonly have a high number of degrees of freedom and only specific regions within the parameter space are able to produce dynamics of interest. This makes the development of tools and strategies to efficiently find these regions of high importance to advance brain research. Exploring the high dimensional parameter space using numerical simulations has been a frequently used technique in the last years in many areas of computational neuroscience. Today, high performance computing (HPC) can provide a powerful infrastructure to speed up explorations and increase our general understanding of the behavior of the model in reasonable times. Learning to learn (L2L) is a well-known concept in machine learning (ML) and a specific method for acquiring constraints to improve learning performance. This concept can be decomposed into a two loop optimization process where the target of optimization can consist of any program such as an artificial neural network, a spiking network, a single cell model, or a whole brain simulation. In this work, we present L2L as an easy to use and flexible framework to perform parameter and hyper-parameter space exploration of neuroscience models on HPC infrastructure. Learning to learn is an implementation of the L2L concept written in Python. This open-source software allows several instances of an optimization target to be executed with different parameters in an embarrassingly parallel fashion on HPC. L2L provides a set of built-in optimizer algorithms, which make adaptive and efficient exploration of parameter spaces possible. Different from other optimization toolboxes, L2L provides maximum flexibility for the way the optimization target can be executed. In this paper, we show a variety of examples of neuroscience models being optimized within the L2L framework to execute different types of tasks. The tasks used to illustrate the concept go from reproducing empirical data to learning how to solve a problem in a dynamic environment. We particularly focus on simulations with models ranging from the single cell to the whole brain and using a variety of simulation engines like NEST, Arbor, TVB, OpenAIGym, and NetLogo.
featured: true
tags:
  - selected
---
