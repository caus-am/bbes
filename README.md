# bbes
Branch-and-Bound Equivalence Search

## Overview
Branch-and-Bound Equivalence Search is an algorithm for structure
learning of Bayesian Networks. It is similar to Greedy Equivalence
Search (Chickering, 2002) in that it searches over entire Markov
equivalence classes rather than over individual graphs, but it uses
the branch-and-bound search strategy to ensure the optimal equivalence
class is found.

For details, please see the following paper:

> Thijs van Ommen, Learning Bayesian Networks by Branching on
> Constraints, Proceedings of the Ninth International Conference on
> Probabilistic Graphical Models ([PGM 2018](https://pgm2018.utia.cas.cz)), 2018.

Note that this implementation is a proof-of-concept and has not been
optimized.
