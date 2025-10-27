# Forms of AI: `Neuro-symbolic AI`

A continuing `challenge` for AI is to bring the **symbolic AI** and **connectionist AI** paradigms `together`
> This is the main goal of the so called “neuro-symbolic AI”

**Symbolic AI** and **Connectionist AI** represent two distinct yet complementary approaches to AI, with their own pros and cons

- `Symbolic AI` systems allow us to string together long chains of reasoning and to take advantage of the expressive power of structured representations
    - tasks that require explicit knowledge, logical reasoning, and interpretability.

- `Connectionist AI` systems can adapt to unseen situations and recognize patterns even in the face of noise and uncertainty
    - pattern recognition, adaptive learning, and handling large amounts of data

### Benefits

- By `combining learning and reasoning`, these systems could potentially understand and interact with the world in a way that is much closer to how humans do

### Applications in self driving cars
A `neuro-Symbolic AI` system in this context would use:

- a `neural network` to learn to **recognize objects** from data (images from the car’s cameras)
- a `symbolic AI` system to **reason** about these objects and **make  decisions** according to traffic **rules**.

### Approaches
Neuro-symbolic AI methods can be classified in `two main categories`:

1. Methods that `“inject” symbolic knowledge into neural networks`
    - Methods of this kind compress structured symbolic knowledge and produce representations of such a knowledge that are suitable to be processed by neural networks. The compressed, neural-networkprocessable knowledge can be integrate with neural patterns, in order to have neural networks operate by exploiting the resulting integrated neural patterns

2. Methods that `“incorporate” neural patterns into symbolic knowledge`
    - Method of this kind extract information from neural patterns to allow for mapping to structured symbolic knowledge (lifting) and perform symbolic reasoning over a knowledge that is augmented by neural patterns

![](./img/Neuro-symbolic%20AI%20methods.png)


---
Go to [INDEX](../README.md)