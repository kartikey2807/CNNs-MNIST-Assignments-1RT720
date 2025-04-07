# Introduction
**Problem**
* Classification
* MNIST dataset
* Using DNNs and CNNs
---

Applied the following **models**
* Deep Neural Net (with 2 hidden layers)
* CNN (3 pairs of Conv-ReLU layers)
* CNN with Residual connections
* CNN with Residual connections + Batch Normalization
* CNN with Residual connections + Batch Normalization + Dropout layer
---

**Observation:** ```ReLU(MaxPool(x)) = MaxPool(ReLU(x))```

---

**Results**
| Model | Test accuracy |
| :- | :- |
| DNN (2 hidden layers) | 97.70% |
| CNN | 98.59% |
| CNN with residual connections | 98.70% |
| CNN with residual connections + BN | 99.16% |
| CNN with residual connections + BN + Dropout| 99.28% |
