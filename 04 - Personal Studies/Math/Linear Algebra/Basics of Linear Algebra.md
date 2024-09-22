
### Matrix Multiplication 

Recall that,
$$
\begin{align}

A \cdot B = \begin{bmatrix}
x_{1} & x_{2} & x_{3} \\
x_{4} & x_{5} & x_{6}
\end{bmatrix}
\begin{bmatrix}
y_{1} & y_{2} \\
y_{3} & y_{4} \\
y_{5} & y_{6}
\end{bmatrix}
\\ =
\begin{bmatrix}
x_{1}y_{1}+x_{2}y_{3}+x_{3}y_{5} & \dots \\
\dots & \dots
\end{bmatrix}

\end{align}
$$
And therefore,

$$
\text{matmul}(A, B)_{ij} = AB_{ij}=\sum_{r}A_{i,r}B_{r,j}
$$
where $ij$ is the position of the value in the resultant matrix, $i$ is the row in first matrix, $j$ is the column in the second matrix and $r$ is each element in each matrix.

---
### Linear Functions

Given that $f(x)$ is linear,
$$
\begin{aligned}
f(a+b) &= f(a) + f(b) \\ 
\\
f(\lambda A) &= \lambda f(a)
\end{aligned}
$$
