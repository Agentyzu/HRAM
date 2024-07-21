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
# Additional Supplements
Only the main code is provided, the experiment is carried out by changing the parameters and observing the optimal results, the process of changing the parameters needs to be adjusted manually. By altering the parameter (denoted as $a$ in the `chromosome` file), we observe the variation of link load variance with different quantities of AUVs in the receiving layer. The result is shown in the firure. It is observed that at $\eta=0.4$, the load variance is minimized across various quantities of AUVs.

![figure](file:///C:/Users/Leona/AppData/Local/Temp/MicrosoftEdgeDownloads/4053fe14-f68f-46b2-a703-d6bace8f6631/Figure_1.pdf)

Due to the randomness of this experiment, experimental results in the paper are based on 500 rounds of randomly generated simulation scenarios, and the average of the experimental results is taken.
