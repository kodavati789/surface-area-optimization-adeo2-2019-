Optimization of surfacearea

A Heuristics problem to build an approximation algorithm for finding the largest rectangle inside a non-convex polygon.

The components of the problem are: 
* The polygon: the constrained search space; 
* The rectangle: the solution of the problem; 
* Feasibility (is the rectangle inscribed in the polygon?): A constrained problem; 
* The area of the rectangle: the evaluation function; 
* Problem of maximization.. 
  * In this case we maximize the Area
  * To maximize Area we optimize two points or 4 coordinates and an angle for rotation


The performance of all heuristic algorithms influenced by the search space structure. Consequently, the design of an efficient algorithm needs to exploit, implicitly or explicitly, some features of the search space. For many heuristics, especially local searches, the complexity of the algorithm is very strongly influenced by the asperity of the local structures of local optima

 Algorithms
|Taboo Search|Particle Swarm Optimisation|
|---|---|
|The main objective of the algorithm is to discourage the search process from visiting configurations in some space regions that are already considered as explored.|The PSO algorithm employs a swarm of particles, which traverse a multidimensional search space to seek out optima. Each particle is a potential solution and is influenced by experiences of its neighbors as well as itself.|

 

