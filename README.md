# Convolution Neural Nets
* Classification on the MNIST Dataset
* using dropout and skip connections
* Implemented CNNs with *skip connections* / *BatchNorm* / *dropout*
* **Insight:** `ReLU(MaxPool(x)) = MaxPool(ReLU(x))`
---
**Results**
| Model | Test accuracy |
| :- | :- |
| Neural Nets (2 hidden layers) | 97.70% |
| CNN + skip connection | 98.70% |
| CNN + skip connection + BN | 99.16% |
| CNN + skip connection + BN + Dropout| 99.28% |
