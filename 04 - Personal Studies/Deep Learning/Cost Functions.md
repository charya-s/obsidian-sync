There are many types of cost functions that calculate the error between the expected output $y$ and the predicted output $\hat{y}$.

---
## Squared Error
$$
J(w,b) = \sum_{i=1}^{m} (\hat{y}^{(i)} - y^{(i)})^2
$$
This is most commonly used for [[Regression]] models.

---
## Mean Squared Error

$$
J(w,b) = \frac{1}{2m}\sum_{i=1}^{m} (\hat{y}^{(i)} - y^{(i)})^2
$$
This is most commonly used for [[Regression]] models.

---
## Root Mean Squared Error
$$
J(w,b) = \sqrt{\frac{1}{m}\sum_{i=1}^{m} (\hat{y}^{(i)} - y^{(i)})^2}
$$
This is most commonly used for [[Classification]] models.

---

## Binary Cross Entropy
$$
J(w,b) = \begin{cases}
  -y \log (p)      & \text{if $y=1$}\\
  -(1-y) \log (1-p) & \text{if $y=0$}
 \end{cases}
$$
This is most commonly used for [[Classification]] models.