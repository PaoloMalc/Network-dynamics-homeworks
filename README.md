# Network dynamics - Course Homeworks

This repository contains the solutions to the homework assignments for the "Network Dynamics" course, part of the MSc in Physics of Complex Systems at Politecnico di Torino.

The assignments explore various theoretical and computational aspects of network science, including flow optimization, game theory, and epidemiological models on graphs.

## Repository Contents

### Homework I: Network Flows and Centrality Measures

- **Flow Optimization and Minimum Cut**: Analysis of an o-d network to compute the minimum cut capacity ($C_U^*=5$) and optimize extra capacity distribution to maximize throughput.
    
- **Wardrop Equilibrium & Social Optimum**: Computation of the user optimal flow vector (Wardrop equilibrium) and the social optimum in networks with given delay functions, including the analysis of the Price of Anarchy (PoA).
    
- **Braess' Paradox**: Demonstration of Braess' paradox by adding a new link and computing optimal toll vectors (both with full and minimum support) to restore a unitary PoA.
    
- **Centrality Measures**: Implementation and comparison of various centrality metrics (Degree, Eigenvector, Katz, and PageRank/Bonacich) on a specific graph topology, highlighting the differences in node ranking based on network structure.
    

### Homework II: Dynamics and Epidemics on Graphs

- **Markov Chains and Relaxation Times**: Analysis of the convergence of standard and lazy dynamics on specific graphs (e.g., circulant graphs and Barbell graphs), including explicit calculation of the second largest eigenvalue $\lambda_2$ and relaxation times.
    
- **Stubborn Nodes Game**: A two-player game on a tree graph aiming to maximize the influence of stubborn nodes on the asymptotic average opinion (electrical network analogy).
    
- **French-DeGroot Dynamics**: Computation of the asymptotic consensus variance and optimization of self-loop weights to minimize it.
    
- **SIR Epidemic Model**: Estimation of the expected absorbing time bounds for an SI model on different topologies (grids and Barbell graphs) using the minimum conductance profile $\gamma(k)$.
    

### Homework III: Games on Networks and Erdos-Renyi Graphs

- **Quadratic Games**: Finding Nash equilibria and best response functions in a network game with utility $u_i(x) = -\frac{x_i^2}{2} + c_ix_i + \beta \sum_{j \neq i} W_{ij}x_jx_i$. Explores the relation between Nash equilibrium uniqueness ($\beta w_i < 1$) and Katz centrality.
    
- **Key Player Problem**: Identifying the node whose removal causes the largest reduction in total activity $y = \sum_{j} x_j^*$.
    
- **Coordination/Anti-coordination Games**: Analysis of asynchronous best response dynamics and pure-strategy Nash equilibria in mixed populations (V1 playing coordination, V2 playing anti-coordination) using continuous and discrete-time Markov chains.
    
- **Wardrop Equilibrium with Tolls**: A two-player game where link managers set tolls $\omega_i$ to maximize revenue based on the resulting Wardrop equilibrium flows.
    
- **SIR Model on Rings & Erdos-Renyi**: Calculation of the asymptotic distribution of recovered individuals in a 1D ring SIR model and the expected number of isolated k-stars in an $G(n,p)$ random graph.
