# GIO
GIO (Gravitational Interactions Optimization) is a population-based metaheuristic capable of optimizing high-dimensional functions. 
The metaheuristic (initially conceived by Julio Barrera) was inspired by how bodies interact in Newtonian Physics.  
Each member of the population is seen as a point particle with a mass proportional to the value of the fitness function in the 
location it is found. Newton's laws of gravitation are used to produce attraction forces. 
Those forces move particles, which get attracted to the areas in the search space with the highest fitness function. 
All particles are affected by all other particles, moving little by little at each period. 
After a sufficient number of generations, particles may converge to the fitness function's optimum(a).  
The metaheuristic has been tested against GA, PSO, and DE, outperforming them specially at very high dimensional problems 
(500 to 1,000 dimensions). An article is on its way.

In this repository you will find a set of articles we have published about this new metaheuristic.
After our paper gets published, and it eventually will, we will provide implementations of the algorithm, along with the set of
benchmark functions with which it has been tested.
