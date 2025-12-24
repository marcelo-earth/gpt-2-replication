# GPT-2-Replication Model

Now with Pytorch and CUDA

Let's start with the basics, from this very simple equation:

```
output = (weight × input) + bias
```

This equation is the core of a perceptron, a simple artificial neuron that can be used to solve problems like classification and regression.

## My Questions & Answers

**How do we know, during training, that the model has reached a local minimum? Gradient descent is often described as a way to find the lowest point in a landscape of hills, but what happens if different people train the same neural network? Could it be that one of them ends up “better positioned” simply because their starting point led them to a much lower region than the others?**

1. We do "know" local minimum only if:
- _Loss function suddenly drops_
- Gradient is close to 0
- Model starts overfitting

2. The initial point matters a lot

3. Local minimums are not "bad"

**Is Adam better than SGD? It looks like it is, but I think I'm missing something.**

Adam converges faster than SGD.


