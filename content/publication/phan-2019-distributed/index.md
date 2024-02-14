---
title: Distributed Policy Iteration for Scalable Approximation of Cooperative Multi-Agent
  Policies (Extended Abstract)
authors:
- Thomy Phan
- Kyrill Schmid
- Lenz Belzner
- Thomas Gabor
- Sebastian Feld
- Claudia Linnhoff-Popien
date: '2019-05-01'
publishDate: '2024-02-14T10:33:06.227616Z'
publication_types:
- paper-conference
publication: '*18th International Conference on Autonomous Agents and MultiAgent Systems
  (AAMAS 2019)*'
abstract: Decision making in multi-agent systems (MAS) is a great challenge due to
  enormous state and joint action spaces as well as uncertainty, making centralized
  control generally infeasible. Decentralized control offers better scalability and
  robustness but requires mechanisms to coordinate on joint tasks and to avoid conflicts.
  Common approaches to learn decentralized policies for cooperative MAS suffer from
  non-stationarity and lacking credit assignment, which can lead to unstable and uncoordinated
  behavior in complex environments. In this paper, we propose Strong Emergent Policy
  approximation (STEP), a scalable approach to learn strong decentralized policies
  for cooperative MAS with a distributed variant of policy iteration. For that, we
  use function approximation to learn from action recommendations of a decentralized
  multi-agent planning algorithm. STEP combines decentralized multi-agent planning
  with centralized learning, only requiring a generative model for distributed black
  box optimization. We experimentally evaluate STEP in two challenging and stochastic
  domains with large state and joint action spaces and show that STEP is able to learn
  stronger policies than standard multi-agent reinforcement learning algorithms, when
  combining multi-agent open-loop planning with centralized function approximation.
  The learned policies can be reintegrated into the multi-agent planning process to
  further improve performance.
url_pdf: http://www.ifaamas.org/Proceedings/aamas2019/pdfs/p2162.pdf
---
