## master-research

# Root-finding Algorithms for Random Trees:
Theory and Simulations

We study the problem of finding the first vertex in a randomly generated tree. This problem
can be thought as finding the source of a rumor spread in a social network. We use
three different models for generating these networks, namely, S.I. model, Uniform and
Preferential attachment. We present different algorithms that spot the source and we
use some results about the ML (Maximum Likelihood) estimator to prove some of their
properties. These studied estimators are of two different types: For a given graph G, some
of them output single vertices as candidates for the source v R , and the others return sets
H of V (G) that satisfies that (i) with high probability v R is in H and (ii) the size of H is
independent of the size of the growing network G. For networks in which each node has
at most 3 neighbors, we show that the probability that the studied estimators find the
source goes above 1/4 as the graph grows. On the other hand, this probability goes to
0 for networks in which each node has at most two neighbors. We give lower bounds for
the size of the output set H by analyzing the behavior of the ML estimator in the case
where the studied network grows following uniform and preferential mechanisms. We do
simulations to test the performance of the presented estimators in three different tasks:
the first about single source finding in separate graphs, the second related to the size of
the output set H and the third one about an one against all tournament.

This repository contains both the theory and the scripts produced during my master's research. 

#
## Authors

* **Diego Baptista Theuerkauf** 
* ** Advisor: Dr. Roberto Imbuzeiro **
