# modelling-simulation
Python implementations of numerical methods and modeling


## Fixed Point

A fixed point of a function \( f(x) \) is a value \( x^* \) such that:

$$
f(x^*) = x^*
$$

Fixed Point Iteration Method

Idea: Start from an initial guess \( x_0 \) and repeatedly apply the iteration:

$$
x_{n+1} = g(x_n)
$$

Banach Fixed Point Theorem

If:

- The function \( g(x) \) is a contraction mapping (Lipschitz constant \( 0 < k < 1 \)),
- The domain is a complete metric space,

then:

- There exists exactly one fixed point.
- Iteration will converge to that fixed point for any initial guess \( x_0 \).

Convergence Condition

A practical check for convergence: \( |g'(x)| < 1 \) near the fixed point.

