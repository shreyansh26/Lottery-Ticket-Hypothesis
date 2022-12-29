# The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qiBwqVGF2t0gn_QosayJA9XuI0RWEvqC?usp=sharing]
[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)] (https://www.kaggle.com/code/shreyansh2626/lottery-ticket-hypothesis)

A re-implementation of the paper [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/abs/1803.03635v5) by Jonathan Frankle and Michael Carbin. This implementation focuses only on applying the hypothesis to Fully Connected networks on MNIST (Section 2 of the paper). It can however be extended to other datasets and architectures.

All the plots and the code can be found in the Jupyter notebook. The notebook however has been run on only 5 epochs and 5 pruning iterations since it was done on a Colab. A larger-scale experiment was run on Kaggle Notebooks with 200 epochs and 6 pruning iterations. This is the [link to the notebook](https://www.kaggle.com/code/shreyansh2626/lottery-ticket-hypothesis).