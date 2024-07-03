## Topic: Grokking

A compiled list of grokking-related AI papers which I have read.

Last updated: 22 April 2024

### Icon description:

🥇 at least 1k citations (at the time of reading)

🥈 at least 500 citations (at the time of reading)

🥉 at least 50 citations (at the time of reading)

⭐ less than 50 citations (at the time of reading)

----

### Grokking Phenomena

* 🥉 2022: [Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets](https://arxiv.org/pdf/2201.02177.pdf) <br>
This paper studied the generalization of neural networks on small algorithmically generated datasets, mainly in terms of data efficiency. In particular, they observed that in some situations, the validation accuracy begins to increase from chance level toward (almost) perfect generalization, long after the training accuracy reaches 100% (overfitting). They called this phenomenon “grokking”.
* 🥉 2022: [Towards Understanding Grokking: An Effective Theory of Representation Learning](https://arxiv.org/pdf/2205.10343.pdf) <br>
This paper’s aim is to study the grokking phenomenon using physics-inspired tools, namely effective theories and phase diagrams. They suggested that the observed generalization in algorithmic datasets is due to the network’s capability of learning good representation of the input embeddings. They also found that grokking occurs when the representation learning is significantly faster compared to the decoder learning. Therefore, with proper hyperparameter tuning (changing the learning rates and weight decay), it is possible to avoid grokking.