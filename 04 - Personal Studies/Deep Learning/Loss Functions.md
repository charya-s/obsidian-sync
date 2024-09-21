During training, loss functions are used to calculate the loss, $L$, between the produced output, $\hat{y}$ and the expected output, $y$.

$$
J(W) = \frac{1}{n}\sum_{i=1}^{n}{L(f(x^{(i)};W), y^{(i)})}
$$

where $J(W)$ is the total loss across the dataset, $n$ is the total number of datapoints, $L$ is the loss function, $f(x)


Various loss functions can be used depending on the application of the model. 