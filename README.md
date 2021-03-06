# ENAS-Keras
Keras implementation of [Efficient Neural Architecture Search](https://arxiv.org/abs/1802.03268)

# STILL DEVELOPING
- ALMOST DONE: CNN micro search implementation (now testing)
- TODO: RNN cell search
- TODO: CNN macro search

# Prerequisites
- Python 3.6+
- Keras 2.1.5+
- Tensorflow 1.0.1+

## Recommended
- GPU

# Micro search
Run either ENAS_Keras_CIFAR10.py or ENAS_Keras_CIFAR10.ipynb on Jupyter Notebook to micro search CNN cells using [Cifar10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset.
Run either ENAS_Keras_MNIST.py or ENAS_Keras_MNIST.ipynb on Jupyter Notebook to micro search CNN cells using MNIST dataset.

# Files

```
.
├── ENAS_Keras_CIFAR10.ipynb
├── ENAS_Keras_CIFAR10.py
├── ENAS_Keras_MNIST.ipynb
├── ENAS_Keras_MNIST.py
├── ENAS.py
├── __init__.py
└── src
    ├── child_network_micro_search.py
    ├── controller_network.py
    ├── __init__.py
    ├── keras_utils.py
    └── utils.py
```

# Other implementations
- [Tensorflow](https://github.com/melodyguan/enas)
- [Pytorch](https://github.com/carpedm20/ENAS-pytorch)

# Reference
- [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578)
- [Learning Transferable Architectures for Scalable Image Recognition](https://arxiv.org/abs/1707.07012)
- [Efficient Neural Architecture Search via Parameter Sharing](https://arxiv.org/abs/1802.03268)
