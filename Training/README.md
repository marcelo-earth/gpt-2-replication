# Training LLMs

What do we need to train a LLM?

- Training set (or corpus): This can weigh hundreds of GBs.

For example, the training set for LLAMA-4 was 30 million of tokens, or 120,000,000,000,000 bytes, which is 109 TB of data.

The first step is to tokenize the data.

Training the model is the most expensive part of the process.

So far a GPU can't have hundreds of TBs of data, so we need to split the data into smaller chunks. So it can be loaded into a central computer providing loss function results, results, and now it's time to make backpropagation.

Now there is a phase of post-training. Once we trained the model we got a model that is able to generate text. But it's general. Now we can make it specialized for a specific task. We can make a fine-tuning process. This only takes a few hours, and you need less data.

Now let's go with **RLHF (Reinforcement Learning from Human Feedback)**.

You requiere thousands of humans in order to make it work.

RLHF but unsupervised can also be an option. DeepSeek made it work without any human feedback with GRPO (Group Relative Policy Optimization). 

> DeepSeek-R1, GRPO was first introduced in DeepSeekMath, an LLM fine-tuned for advanced mathematical reasoning. GRPO was originally designed to improve efficiency in fine-tuning, and it has proven to be a cost-effective and versatile method embraced by the community.

