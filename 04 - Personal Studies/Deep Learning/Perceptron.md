This is the basic building block of neural networks. These are analogous to "neurons" in a brain.

![[Pasted image 20240922012434.png | center]]

Neural networks such as the one above use the following equation for forward propagation.
$$
\hat{y} = g \left(w_{0} + \sum_{i=1}^{m}{x_{i} w_{i}} \right)
$$
Where $\hat{y}$ is the output of the perception, $g$ is the [[Activation Function]],  $w_{0}$ is the bias, $m$ is the total number of inputs, $x_{i}$ is the current input and $w_{i}$ is the weight of the current input.

This equation can be re-written in vector form as follows.
$$
\begin{split}

\hat{y} = g(w_{0} + X^TW)  \\ \\
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



