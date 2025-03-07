---
title:
  Emergent communication enhances foraging behavior in evolved swarms controlled
  by spiking neural networks
authors:
  - Cristian Jimenez Romero
  - Alper Yegenoglu
  - Aarón Pérez Martı́n
  - Sandra Diaz-Pier
  - Abigail Morrison
date: "2023-12-01"
publishDate: "2023-12-14T13:48:26.820056Z"
publication_types:
  - article-journal
publication: "*Swarm Intelligence*"
doi: 10.1007/s11721-023-00231-6
featured: true
image:
  caption: "An ant colony steered by spiking neural networks is foraging for food"
  focal_point: ""
  preview_only: false
abstract: Social insects such as ants and termites communicate via pheromones which allow them to coordinate their activity and solve complex tasks as a swarm, e.g. foraging for food or finding their way back to the nest. This behavior was shaped through evolutionary processes over millions of years. In computational models, self-coordination in swarms has been implemented using probabilistic or pre-defined simple action rules to shape the decision of each agent and the collective behavior. However, manual tuned decision rules may limit the emergent behavior of the swarm. In this work we investigate the emergence of self-coordination and communication in evolved swarms without defining any explicit rule. For this purpose, we evolve a swarm of agents representing an ant colony. We use an evolutionary algorithm to optimize a spiking neural network (SNN) which serves as an artificial brain to control the behavior of each agent. The goal of the evolved colony is to find optimal ways to forage for food and return it to the nest in the shortest amount of time. In the evolutionary phase, the ants are able to learn to collaborate by depositing pheromone near food piles and near the nest to guide other ants. The pheromone usage is not manually encoded into the network; instead, this behavior is established through the optimization procedure. We observe that pheromone-based communication enables the ants to perform better in comparison to colonies where communication via pheromone did not emerge. Furthermore, we assess the foraging performance of the ant colonies by comparing the SNN-based model to a multi-agent rule-based system. Our results show that the SNN-based model can efficiently complete the foraging task in a short amount of time. Our approach illustrates that even in the absence of pre-defined rules, self-coordination via pheromone emerges as a result of the network optimization. This work serves as a proof of concept for the possibility of creating complex applications utilizing SNNs as underlying architectures for multi-agent interactions where communication and self-coordination is desired.
summary: We show how a multi-agent system (ant colony) steered by Spiking Neural Networks establishes self-organization while foraging for food. We evolve the networks using a genetic algorithm and learning to learn. Our results depict emergent behavior, which we investigate.
url_code: "https://github.com/Meta-optimization/emergent_communication_in_agents/tree/main"
links:
  - name: URL
    url: https://doi.org/10.1007/s11721-023-00231-6
tags:
  - selected
  - swarm intelligence
  - mult-agent based modelling
  - spiking neural networks
  - neural networks
  - optimization
  - meta-learning
  - L2L
---
