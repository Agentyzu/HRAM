# HRAM-HRAOA Algorithm
This is the main code for the paper "HRAM: Underwater Hierarchical Route Allocation Mechanism Based on Load Balancing" submited to ICOMIP 2024.
# Introduction
In the route allocation optimisation module of paper, the HRAM-HRAOA applies an improved adaptive genetic algorithm  to simulate the processes of natural selection, crossover and mutation to find a routing scheme that makes the load on network links more balanced.
# File Decription
* The `chromosome` file defines some basic parameters, mainly including the attributes of the sensor source nodes, AUV nodes, as well as the selection relationship. In addition, there are some preliminary operations of the algorithm, including encoding, decoding, and the design of the fitness function.
* The `GA` file is the main part of the algorithm, including operations such as selection, crossover, mutation, etc., which are iterated to achieve the the smallest loaded variance.
# Installation and Configuration
When installing Python, which can be directly downloaded from the official Python website, it is advisable to add Python to the environment variables during the installation process to avoid separate configurations later.

`PyCharm` is a comprehensive integrated development environment (IDE) tailored for Python programming. It offers robust features for code completion, debugging, testing, and version control.
