These are non-linear functions that convert the raw output of a perceptron into a desirable output. Different activation functions perform this conversion in different ways.

We need these because without them, the equation of a perceptron would simply be $\hat{y} = w_{0} + X^TW$, which is entirely linear. Since most tasks have complex relationships between inputs and outputs, they require a non-linear relationship between them. Activation functions provide that non-linearity.

---
### Sigmoid Function

$$
g(z) = \sigma(z) = \frac{1}{1+e^{-z}}
$$
where ${\{ z \text{ } | \text{ } z \in \mathbb{R} \}}$ and ${\{ g(z) \text{ } | \text{ } 0 < g(z) < 1 \}}$.

This is one of most commonly used AFs for probabilistic determination.

---
### Rectified Linear Unit (ReLU)

$$
g(z) = \max(0, z)
$$
where ${\{ z \text{ } | \text{ } z \in \mathbb{R} \}}$.

This is one of most commonly used AFs for linear regression, since,
$$
g(z) = \begin{cases}
z & \text{if } z>0, \\
0 & \text{if } z \leq 0
\end{cases}
$$

---
###  

