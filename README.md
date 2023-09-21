# Machine Learning and Optimisation Demo

Date: 2023-09-23

## Overview

This code demonstrates the use of optimization techniques in machine learning using the `pyomo` libraries.

## Requirements

To set up the environment, execute the following:

```
!pip install -q pyomo amplpy pandas numpy scikit-learn
```

### Solvers
Ensure you have the following solvers installed:
- **Ipopt**: Used for solving continuous linear and non-linear optimization problems.
- **Bonmin**: A basic open-source solver for mixed integer non-linear programming.

These solvers are crucial for the optimization models used in this code.

## Contents

- **Initialization**: Setting up the AMPL environment and necessary modules (code for this section is commented out in the provided script).
- **Linear Regression with Pyomo**: This section demonstrates how to implement linear regression using the Pyomo library and compares its results with the `scikit-learn` library.
- **Ridge Regression with L2 Regularization**: This demonstrates the inclusion of L2 regularization in linear regression using Pyomo.
- **Sparse Robust Linear Regression**: This introduces a version of regression that enforces sparsity constraints.
  
## Running the Code

1. Ensure you have all the necessary libraries installed.
2. Load the provided Python script and run.
3. The script will display the regression coefficients for each model and will compare some results with the `scikit-learn` library.

## Data

The code primarily uses the diabetes dataset from the `scikit-learn` library.
