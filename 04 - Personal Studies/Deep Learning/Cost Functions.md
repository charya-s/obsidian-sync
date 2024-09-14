There are many types of cost functions that calculate the error between the expected output $y$ and the predicted output $\hat{y}$.


## Squared Error
$$
J(w,b) = \sum_{i=1}^{m} (\hat{y}^{(i)} - y^{(i)})
$$
This is most commonly used for [[Regression]] models.


## Mean Squared Error

$$
J(w,b) = \frac{\sum_{i=1}^{m} (\hat{y}^{(i)} - y^{(i)})}{m}
$$
This is most commonly used for [[Regression]] models.

## Binary Cross Entropy
$$
J(w,b) = \begin{cases}
  -y \log (p)      & \text{if $y=1$}\\
  -(1-y) \log (1-p) & \text{if $y=0$}
 \end{cases}
$$
