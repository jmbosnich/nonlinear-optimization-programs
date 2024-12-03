# nonlinear-optimization-programs
Implementation of algorithms to solve constrained and unconstrained optimization problems. 

The first file `unconstrained_quadratic_programming` is an unconstrained nonlinear optimization solver with the following user-defined options:
- three different search direction methods
  1. steepest descent
  2. Newton's method
  3. Hessian modification
- three different line search methods
  1. Armijo backtracking
  2. two variations of Goldstein's line search
 
The second file `constrained_quadratic_programming` is an inequality-constrained nonlinear optimization solver using the active-set method.

Note: I wrote these programs for the nonlinear optimization course IEMS 450-2 at Northwestern University.
