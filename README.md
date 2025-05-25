Introduction

Using meta-learning for domain adaptation is a powerful approach to improving a model's ability to generalize across different data distributions. Instead of adapting a single model directly to a new domain, meta-learning teaches the model how to adapt efficiently by learning across multiple related domains.

MAML (Model-Agnostic Meta-Learning) is often one of the first choices for meta-learning in domain adaptation, especially when the goal is quick adaptation to new tasks or distributions.

What Makes Your Implementation MAML?

A CNN-based MAML retains the standard principles of Model-Agnostic Meta-Learning (MAML) but integrates convolutional neural networks (CNNs) as the base architecture for feature extraction and adaptation.


## Training Progress

Below is the meta loss recorded over each epoch during training:

### Epoch Loss Summary
| Epoch | Meta Loss |
|-------|----------|
| 1/5   | 5.1146   |
| 2/5   | 1.0626   |
| 3/5   | 0.6059   |
| 4/5   | 0.3681   |
| 5/5   | 0.2132   |

meta-loss is consistently decreasing, which suggests the model is effectively learning how to adapt across tasks. The sharp drop in the first couple of epochs indicates that SGD is optimizing well, and later epochs show steady convergence.

Meta-Test Accuracy: 0.9615
0.9615269895124678

