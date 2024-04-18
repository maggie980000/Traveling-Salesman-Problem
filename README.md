The objective of the travelling salesman problem (TSP) is to find the shortest possible route that visits each city exactly once and returns to the origin city. 
Given a list of cities and the distances between each pair, this problem raises the question: "What is the optimal route?".

We conducted experiments with local search methods including nearest neighbor and $k$-opt methods, as well as meta-heuristic algorithms such as Tabu search, Simulated Annealing, Genetic Algorithm, Ant Colony Optimization and Cross Entropy method on att48 and berlin52 datasets.

We found that Cross Entropy method and Ant Colony Optimization can obtain good solutions for the TSP problem. In addition, it is observed that Genetic Algorithm with Ant Colony Optimization initialization is effective in further refining the solution to achieve the optimal total distance.
