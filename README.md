# R Bug: Unexpected NA Propagation

This repository demonstrates a common issue in R programming involving the propagation of `NA` (Not Available) values during calculations.  When performing operations on vectors containing `NA` values, the result often also contains `NA` values, even if other parts of the calculation are valid.

The `bug.R` file contains a simple example of this issue.  The `bugSolution.R` file provides a solution demonstrating how to handle these missing values using functions like `is.na()` and potentially imputation techniques.