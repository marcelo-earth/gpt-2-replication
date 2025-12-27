# Training LLMs

What do we need to train a LLM?

- Training set (or corpus): This can weigh hundreds of GBs.

For example, the training set for LLAMA-4 was 30 million of tokens, or 120,000,000,000,000 bytes, which is 109 TB of data.

The first step is to tokenize the data.

Training the model is the most expensive part of the process.

So far a GPU can't have hundreds of TBs of data, so we need to split the data into smaller chunks. So it can be loaded into a central computer providing loss function results, results, and now it's time to make backpropagation.

