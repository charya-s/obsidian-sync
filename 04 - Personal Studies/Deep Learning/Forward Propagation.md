Using [[Perceptrons]], we can construct simple neural networks that take inputs, pass them through some hidden layers and then produce outputs. 

![[Pasted image 20240922020055.png | center]]

Since there's two sets of connections between nodes, there will be two calculations done in a chain, with the final output, $\hat{y}_{i}$ obtained using the values of $g(z)$ calculated in the hidden layer.

$$
\begin{align}
z_{i} = w_{0, i}^{(1)}+\sum_{j=1}^{m}x_{j}w_{j,i}^{(1)} \\
\hat{y}_{i} = g \left( w_{0, i}^{(2)}+\sum_{j=1}^{d_{1}}g(z_{j})w_{j,i}^{(2)} \right)
\end{align}
$$

where $d_{1}$ is the number of perceptrons in the hidden layer. 

**Note** that both equations above are actually the same basic perceptron equation, with the only difference being that for $\hat{y}$, we use the calculated values of $z$ as "inputs" in the place of $x$. As such, this equation can be applied for each perceptron in each layer for any number of layers until the final, output layer is calculated.