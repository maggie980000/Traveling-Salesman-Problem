The objective of the travelling salesman problem (TSP) is to find the shortest possible route that visits each city exactly once and returns to the origin city. 
Given a list of cities and the distances between each pair, this problem raises the question: "What is the optimal route?".

We conducted experiments with local search methods, such as the nearest neighbor and $k$-opt methods, as well as metaheuristic algorithms including Tabu search, Simulated Annealing, nature-inspired Genetic Algorithm, Ant Colony Optimization, and the population-based Cross Entropy method derived from statistics rigor. These experiments were carried out on the att48 and berlin52 datasets.

Our observations demonstrate that local search heuristics (3-opt), a population-based method driven by statistical rigor (Cross Entropy), and nature-inspired swarm intelligence metaheuristic methods (Ant Colony Optimization) excel in obtaining good solutions for the TSP. Furthermore, the results of our experiments indicate that nature-inspired metaheuristic algorithms are more effective in further refining the solution, ultimately achieving the optimal total distance when compared to local search methods.
