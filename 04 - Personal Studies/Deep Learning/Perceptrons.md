### Single-Layer Perceptrons

This is the basic building block of neural networks. These are analogous to "neurons" in a brain.

![[Pasted image 20240922012434.png | center]]

Neural networks such as the one above use the following equation for forward propagation.
$$
\hat{y} = g \left(w_{0} + \sum_{j=1}^{m}{x_{j} w_{j}} \right) = g(z)
$$
Where $\hat{y}$ is the output of the perception, $g$ is the [[Activation Function]],  $w_{0}$ is the bias, $m$ is the total number of inputs, $x_{i}$ is the current input and $w_{i}$ is the weight of the current input.

The term $z$, which is a substitute term for the raw output of the perceptron before the application of the activation function, can be re-written in vector form as follows.
$$
\begin{split}

z = w_{0} + X^TW  \\ \\
\text{where} \hspace{0.5cm} X=\begin{bmatrix}
           x_{1} \\
           \vdots \\
           x_{m}
\end{bmatrix}
\text{ and }
W=\begin{bmatrix}
           w_{1} \\
           \vdots \\
           w_{m}
\end{bmatrix}

\end{split}
$$

---
### Multi-Layer Perceptrons

A neural network can have multiple outputs in each layer by placing multiple single-layer perceptrons in parallel.

![[Pasted image 20240922015008.png | center]]

The equation for the single-layer perceptron can be further expanded to allow for multi-layer perceptrons as follows.

$$
z_{i} = w_{0, i} + \sum_{j=1}^{m}{x_{j} w_{j,i}}
$$
where $z_{i}$ is the raw output of the $i\text{-th}$ perceptron.

Simple neural networks can be implemented manually in PyTorch as follows.

```python

```