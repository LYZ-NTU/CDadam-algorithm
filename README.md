# CDadam-algorithm
About the code of CDadam algorithm
This repository houses the implementation of the CDadam algorithm, an Adam variant that integrates central difference into gradient computation to address issues related to one-sided estimation errors in first-order (forward-difference) gradients, thereby potentially enhancing convergence.
# Contents
**Test Functions:**

rastrigin: Implements the Rastrigin function, a commonly used benchmark function in optimization tasks known for its multiple local minima, which poses a challenge for optimization algorithms.

testfunction1: A custom test function designed to evaluate the performance of the CDadam algorithm under specific characteristics.

testfunction_ackley: Contains the Ackley function, another well-known test function in optimization, featuring a complex landscape with a global minimum and many local minima.

**Equations:**

2D Helmholtz equation: Code for solving the 2D Helmholtz equation, which arises in various fields such as physics and engineering, particularly in wave propagation problems.

burgers equation: Implementation for solving the Burgers' equation, a fundamental partial differential equation that models fluid dynamics and exhibits nonlinear behavior.

heat equation: Code to solve the heat equation, describing the distribution of heat (or variation in temperature) in a given region over time.

navier_stokes equation: Contains the implementation for solving the Navier-Stokes equations, which are crucial in fluid mechanics for describing the motion of viscous fluid substances.

# Usage
To use the code, simply navigate to the respective directories for test functions or equations. Each file contains the necessary code to run experiments with the CDadam algorithm on the corresponding function or equation. You can modify parameters within the files to suit different experimental setups and observe how the CDadam algorithm performs under varying conditions.
# Dependencies
The code is implemented in [specify programming language, e.g., Python] and relies on common scientific computing libraries such as [list libraries like NumPy, SciPy, TensorFlow/PyTorch etc., if applicable]. Ensure these dependencies are installed before running the code.
