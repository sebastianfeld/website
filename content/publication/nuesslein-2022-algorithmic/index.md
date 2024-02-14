---
title: Algorithmic QUBO formulations for k-SAT and hamiltonian cycles
authors:
- Jonas Nuesslein
- Thomas Gabor
- Claudia Linnhoff-Popien
- Sebastian Feld
date: '2022-01-01'
publishDate: '2024-02-14T10:33:06.095055Z'
publication_types:
- manuscript
publication: '*23rd Genetic and Evolutionary Computation Conference (GECCO 2022)*'
abstract: Quadratic Unconstrained Binary Optimization (QUBO) can be seen as a generic
  language for optimization problems. QUBOs attract particular attention since they
  can be solved with quantum hardware, like quantum annealers or quantum gate computers
  running QAOA. In this paper, we present two novel QUBO formulations for k-SAT and
  Hamiltonian Cycles that scale significantly better than existing approaches. For
  k-SAT we reduce the growth of the QUBO matrix from O(k) to O(log(k)). For Hamiltonian
  Cycles the matrix no longer grows quadratically in the number of nodes, as currently,
  but linearly in the number of edges and logarithmically in the number of nodes.
  We present these two formulations not as mathematical expressions, as most QUBO
  formulations are, but as meta-algorithms that facilitate the design of more complex
  QUBO formulations and allow easy reuse in larger and more complex QUBO formulations.
links:
- name: URL
  url: https://dl.acm.org/doi/pdf/10.1145/3520304.3533952
---
