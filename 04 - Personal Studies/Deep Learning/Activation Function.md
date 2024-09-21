hese are non-linear functions that convert the raw output of a perceptron into a desirable output. Different activation functions perform this conversion in different ways.

Activation functions are necessary for neural networks because, without them, the output of the model would simply be a linear function of the input. In other words, it wouldn’t be able to handle large volumes of complex data. Activation functions are an additional step in each forward propagation layer but a valuable one.

---
## Sigmoid Function

$$
g(z) = \sigma(z) = \frac{1}{1+e^{-z}}
$$
where ${\{ z \text{ } | \text{ } z \in \mathbb{R} \}}$ and ${\{ g(z) \text{ } | \text{ } 0 < g(z) < 1 \}}$.

This is one of most commonly used AFs for probabilistic determination.

---
## Rectified Linear Unit (ReLU)

$$
g(z) = \max(0, z)
$$
where ${\{ z \text{ } | \text{ } z \in \mathbb{R} \}}$.

This is one of most commonly used AFs for regression, since,
$$
g(z) = \begin{cases}
z & \text{if } z>0, \\
0 & \text{if } z \leq 0
\end{cases}
$$

