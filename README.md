# Steepest Descent Method for Optimization

## Project Overview
This project focuses on the implementation and analysis of the steepest descent method for finding minima of two well-known mathematical functions: **Rosenbrock's function** and **Himmelblau's function**. The steepest descent method is a widely-used optimization algorithm that iteratively moves towards the direction of the negative gradient to find the local minima of a function. 

The report provides valuable insights into the behavior and performance of the steepest descent method in the context of optimization problems, contributing to a better understanding of its application and effectiveness.

## Introduction
### Abstract
The project explores the implementation and effectiveness of the steepest descent algorithm in optimizing the Rosenbrock and Himmelblau functions. By employing the method iteratively, we analyze how the algorithm navigates the function landscape and approaches local minima. Key focuses include the impact of step size on convergence and the comparative performance of different step size strategies.

## Key Findings
- The implementation of a variable step size has shown to be particularly effective for Himmelblau’s function, resulting in better performance compared to a constant step size.
- Sensitivity to step size is critical; excessively large step sizes hinder convergence.
- The integration of the **Goldstein-Armijo algorithm** consistently yields improved results compared to the **Wolfe-Powell algorithm**, confirming its efficiency in optimizing both functions.
- Starting the algorithm from the point (0,0) significantly expedites the convergence process. Despite Himmelblau’s function having four global minimizers, all simulations converged to the singular minimizer at (3,2).

## Conclusion
The exploration of the Steepest Descent algorithm for optimizing both Rosenbrock’s and Himmelblau’s functions has provided valuable insights into its efficacy. Our findings demonstrate the importance of step size and the advantages of utilizing adaptive step strategies, particularly the Goldstein-Armijo algorithm. This project contributes to a comprehensive understanding of the Steepest Descent method's practical applications in solving complex optimization tasks.

## Future Work
Future improvements may include:

- Exploring additional optimization algorithms for comparative analysis.
- Testing the algorithm on other complex functions to assess its versatility.
- Enhancing visualization tools to better illustrate the optimization process.
## Author
This project was created as part of my Master’s Year 1 coursework by Kanupriya Jain and Alice Devilder. If you have any questions, feedback, or suggestions for improvement, please feel free to reach out!
