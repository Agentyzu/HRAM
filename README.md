# HRAM-HRAOA Algorithm
This is the main code for the paper "HRAM: Underwater Hierarchical Route Allocation Mechanism Based on Load Balancing" submited to ICOMIP 2024.
# Introduction
In the route allocation optimisation module of paper, the HRAM-HRAOA applies an improved adaptive genetic algorithm  to simulate the processes of natural selection, crossover and mutation to find a routing scheme that makes the load on network links more balanced.
# File Decription
*[] The [Alt](URL "chromosome") file defines some basic parameters, mainly including the attributes of the sensor source nodes, AUV nodes, as well as the selection relationship. In addition, there are some preliminary operations of the algorithm, including encoding, decoding, and the design of the fitness function.
*[] The [Alt](URL "GA") file is the main part of the algorithm, including operations such as selection, crossover, mutation, etc., which are iterated to achieve the the smallest loaded variance.
