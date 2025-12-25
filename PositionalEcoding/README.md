# Introduction to Positional Encoding

Let's go from the start. We have an input.

"Hello, how are you?"

This in **Input Embedding** is transformed into a vector of numbers.

```
[0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0]
[0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0]
[0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0]
```

Now, so far with recurrent neural networks, we have been able to capture the order of the words because we have been able to pass the previous word to the next one.

But with **transformers**, we need to capture the order of the words without having to pass the previous word to the next one.
