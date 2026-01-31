# Solving-2-Domination-Problem-in-Graphs-using-Quantum-Computing

The classical domination problem in graph theory involves
finding a minimum subset of vertices such that every vertex
not in this subset is adjacent to at least one vertex within it.
The 2-domination problem extends this concept by requiring
every vertex outside the dominating set to be adjacent to at
least two vertices in the set, providing enhanced reliability and
redundancy.
The 2-domination problem has been proven to be NP-hard
even for restricted graph classes. Classical approaches typically 
employ branch-and-bound techniques, greedy algorithms,
and metaheuristics, but these methods become computationally
infeasible for larger graphs.


This research provides you - 
A quantum computing approach to solving the 2-
domination problem in graphs is presented in this paper. We
formulate the problem as a Quadratic Unconstrained Binary Optimization (QUBO) problem, 
convert it to an Ising Hamiltonian,
and implement a solution using the Quantum Approximate Optimization 
Algorithm (QAOA). The 2-domination problem requires
finding a minimum subset of vertices such that every vertex not
in the subset is adjacent to at least two vertices from the subset,
providing enhanced reliability in various network applications.
Our approach demonstrates the potential of quantum algorithms
for solving complex combinatorial optimization problems. We
present experimental results on 3-vertex path graph, 4-vertex cy-
cle graph, 6-vertex star graph and 10-vertex Petersen graph and
discuss scalability challenges. The implementation leverages the
PennyLane quantum computing framework and shows promising
results for this NP-hard optimization problem.
