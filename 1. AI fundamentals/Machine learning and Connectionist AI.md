# Forms of AI: `Machine learning`

`Machine learning` is the field of study which focuses on computing systems `capable of learning from examples`, building hypotheses about the world based on those examples, and use such hypotheses as mathematical models to` make predictions` on or infer properties `of unseen data`

## Machine learning vs symbolic AI

- `Machine learning` can be viewed as a **“bottom-up” approach** to AI, where intelligence is built going `from particular to general` (model used to future inference/prediction).

- `Symbolic AI` is the dual of *Machine learning*, which is instead an inherently **“top-down” approach** to AI, where intelligence is built going `from general` (initial hypotheses, e.g., statements in the knowledge base), `to particular` (further conclusions, derived via reasoning on the initial hypotheses)

### Machine learning and artificial neural networks

There are **many different techniques** for building a **machine learning model**

Today’s most popular machine learning technique is `artificial neural network`

### Neural networks

>Neural networks are a machine learning technique that is inspired by the structure and function of biological neural networks in animal brains

- A neural network consists of connected units or `nodes` called artificial neurons, which loosely model the neurons in the brain. These are `connected by edges`, which model the synapses in the brain

- Each artificial neuron receives signals from connected neurons, then processes them and sends a signal to other connected neurons

- The **“signal” is simply a real number**, and the output of each neuron is computed by some non-linear function of the sum of its inputs, called the activation function

- The `strength` of the signal at each connection is determined `by a weight`, which `adjusts during the learning process` from the available examples
    - Therefore, the learning process (training) within a neural network consists of determining the right weigths to be assigned to every connection


#### Deep Learning
>The term deep learning refers to machine learning using many layers of simple, adjustable computing elements

In the context of neural networks, this corresponds to **having many layers of connected artificial neurons**

## Connectionist AI
>Neural networks are models that basically consist of interconnections among simple processing units (i.e., artificial neurons).

Is basically AI systems that use `artificial neural networks` as their underlying technology, in particular all said above is part of connectionist AI

`Pros`:

- ability to learn and adapt
- ability to handling uncertain or ambiguous information
- capability of handling large amount of data

`Cons`:

- **knowledge** is not symbolic (it is “encoded” into connections between neurons) thus **non-human-interpretable**
- the **output** outcomes are **non-human-interpretable**

---
Go to [INDEX](../README.md)