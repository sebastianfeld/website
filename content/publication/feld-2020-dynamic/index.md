---
title: The Dynamic Time Warping Distance Measure as QUBO Formulation
authors:
- Sebastian Feld
- Christoph Roch
- Thomas Gabor
- Michelle To
- Claudia Linnhoff-Popien
date: '2020-05-01'
publishDate: '2024-02-14T10:33:06.185503Z'
publication_types:
- paper-conference
publication: '*5th International Conference on Computer and Communication Systems
  (ICCCS 2020)*'
doi: 10.1109/ICCCS49078.2020.9118469
abstract: Dynamic Time Warping (DTW) is a representative of a distance measure that
  is able to calculate the distance between two time series. It is often used for
  the recognition of handwriting or spoken language. The metaheuristic Quantum Annealing
  (QA) can be used to solve combinatorial optimization problems. Similar to Simulated
  Annealing it seeks to find a global minimum of a target function. In order to use
  specialized QA hardware, the problem to be optimized needs to be translated into
  a Quadratic Unconstrained Binary Optimization (QUBO) problem. With this paper we
  investigate whether it is possible to transfer the DTW distance measure into a QUBO
  formulation. The motivation behind is the hope on an accelerated execution once
  the QA hardware scales up and the aspiration of gaining benefits due to quantum
  effects that are not given in the classical calculation. In principle, we find that
  it is possible to transform DTW into a QUBO formulation suitable for executing on
  QA hardware. Also, the algorithm returns not only the minimum total distance between
  two sequences, but also the corresponding warping path. However, there are several
  difficulties that make a manual intervention necessary.
---
