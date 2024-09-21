Using [[Perceptrons]], we can construct simple neural networks that take inputs, pass them through some hidden layers and then produce outputs.

![[Pasted image 20240922020055.png | center]]

Since there's two sets of connects between nodes, there will be two sets of weights, the first being applied to the input, $x$ and the second being applied to the raw output, $z$, before the activation function, $g(z)$, is applied to obtain the output, $\hat{y}$.

$$
\\begin{in}

\end{in}
z_{i} = w_{0, i}^{(1)}+\sum_{j=1}^{m}x_{j}w_{j,i}^{(1)}
$$