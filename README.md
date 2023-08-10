# 2023-stochastic-process-application
Coursework; Presentation

## Belief Propagation
Here's the materials which I found useful during preparations:

### Paper
- Understanding Belief Propagation: A good summary (perhaps the most comprehensive one) , but a little too broad, better learn in conjunction with tutorials listed below. The paper covers:

3 different graphical models (Bayesian network, MRF, and factor graph); conversions between each other
Free energy and three approximations
Compare BP with other algorithms (e.g., junction tree) 
- Neuronal message...: introduction for BP (based on Bethe approximation) & variational message passing (based on mean-field approximation) in the context of neuronal network; help you better understand the concept of "free energy"

### Tutorials
- UCLA tutorial: a good introduction to graphical graph(from simple to complex), and a numerical example(you can try it by hand) for no-loop BP process, which helps you understand the concepts of local evidence and message.

- CMU tutorial: more rigorous, including the most detailed proof (among all the materials I have read) for "fixed point of BP algorithm = minima of Bethe approximation"

### Implementation
A code example for BP: https://github.com/krashkov/Belief-Propagation/blob/master/4-ImplementationBP.ipynbLinks to an external site.


### P.S.

In fact I am still a little confused about the relationship between convergence of BP and Bethe approximation. Temporarily, I think that Bethe approximation serves as a theoretical foundation for the practicality of BP algorithm, i.e., as long as we can somehow speculate Bethe approximation has a minima, then we could feel confident to apply BP method. 

## Stochastic Gradient Langevin Dynamics
1. Understanding the Mathematical Concepts behind Langevin Dynamics: https://towardsdatascience.com/langevin-dynamics-29bbb9407b47
2. Bayesian Learning via Stochastic Gradient Langevin Dynamics(paper)
