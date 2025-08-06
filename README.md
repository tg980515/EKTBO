# EKTBO: Elite Knowledge Transfer within Lower-level Searches for Bilevel Optimization
This is the official implementation for the paper: [EKTBO: Elite Knowledge Transfer within Lower-level Searches for Bilevel Optimization](https://www.sciencedirect.com/science/article/pii/S221065022500255X), which was accepted by SWEVO. 
File structure
In total, three files are contained in the root directory:

EKTBO.m: The source code of EKTBO.


main.m: The code to launch the experiment.


BLEA_D: A folder containing all necessary files. Please note that it contains some files provided in BLEAQ2 and BLCMAES. So please cite the following paper if you decide to use the code formally: 

[1]A. Sinha, P. Malo, and K. Deb, “Evolutionary algorithm for bilevel optimization using approximations of the lower level optimal solution mapping,” European Journal of Operational Research, vol. 257, no. 2, pp. 395–411, Mar. 2017. 

[2]He X, Zhou Y, Chen Z. Evolutionary bilevel optimization based on covariance matrix adaptation[J]. IEEE Transactions on Evolutionary Computation, 2018, 23(2): 258-272.

# Citation
Please cite our paper if you find it useful in your research:

@article{LAI2025102097,
title = {Elite knowledge transfer within lower-level searches for bilevel optimization},
journal = {Swarm and Evolutionary Computation},
volume = {98},
pages = {102097},
year = {2025},
issn = {2210-6502},
doi = {https://doi.org/10.1016/j.swevo.2025.102097},
url = {https://www.sciencedirect.com/science/article/pii/S221065022500255X},
author = {Yutao Lai and Hai-Lin Liu and Yukai Xu and Lei Chen},
keywords = {Bilevel optimization, Evolutionary algorithm, Knowledge transfer, Gaussian distribution},
abstract = {Bilevel optimization problems pose significant challenges for evolutionary algorithms (EAs) due to their nested structure. This paper introduces an efficient evolutionary bilevel algorithm that leverages elite knowledge transfer to tackle these challenges. Firstly, this paper employs a biobjective source selection strategy to balance convergence quality with relevance to the target lower-level problem. Building on this, a multi-source elite knowledge transfer mechanism constructs an elite Gaussian distribution model from source lower-level solutions, facilitating efficient parameterized knowledge transfer to accelerate the optimization of the target lower-level problem. Additionally, an adaptive strategy for reducing the lower-level population size further enhances algorithmic efficiency. Evaluated on benchmark test suites and real-world problems, the proposed algorithm demonstrates superior efficiency and accuracy compared to state-of-the-art bilevel optimization algorithms, underscoring the effectiveness of the elite knowledge transfer and adaptive reduction strategies. The source code for EKTBO has been publicly released at the following link: https://github.com/tg980515/EKTBO}
}
# Acknowledgement
[BLCMAES](https://github.com/hxyokokok/BLCMAES)

[TLEA-CMAES](https://github.com/gdutcislab/TLEA-bilevel)

[BLEAQ2](https://github.com/msu-coinlab/BLEAQ2)
