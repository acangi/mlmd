---
title: Random Quantum Neural Networks (RQNN) for Noisy Image Recognition
authors:
- Debanjan Konar
- Erol Gelenbe
- Soham Bhandary
- Aditya Das Sarma
- Attila Cangi
date: '2022-03-01'
publishDate: '2024-04-17T10:25:47.449981Z'
publication_types:
- article-journal
abstract: Classical Random Neural Networks (RNNs) have demonstrated effective applications
  in decision making, signal processing, and image recognition tasks. However, their
  implementation has been limited to deterministic digital systems that output probability
  distributions in lieu of stochastic behaviors of random spiking signals. We introduce
  the novel class of supervised Random Quantum Neural Networks (RQNNs) with a robust
  training strategy to better exploit the random nature of the spiking RNN. The proposed
  RQNN employs hybrid classical-quantum algorithms with superposition state and amplitude
  encoding features, inspired by quantum information theory and the brain's spatial-temporal
  stochastic spiking property of neuron information encoding. We have extensively
  validated our proposed RQNN model, relying on hybrid classical-quantum algorithms
  via the PennyLane Quantum simulator with a limited number of emphqubits. Experiments
  on the MNIST, FashionMNIST, and KMNIST datasets demonstrate that the proposed RQNN
  model achieves an average classification accuracy of $94.9%$. Additionally, the
  experimental findings illustrate the proposed RQNN's effectiveness and resilience
  in noisy settings, with enhanced image classification accuracy when compared to
  the classical counterparts (RNNs), classical Spiking Neural Networks (SNNs), and
  the classical convolutional neural network (AlexNet). Furthermore, the RQNN can
  deal with noise, which is useful for various applications, including computer vision
  in NISQ devices. The PyTorch code (this https URL) is made available on GitHub to
  reproduce the results reported in this manuscript.
url_pdf: https://arxiv.org/pdf/2203.01764.pdf
---
