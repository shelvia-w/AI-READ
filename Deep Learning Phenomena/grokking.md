## Topic: Grokking

A compiled list of grokking-related AI papers which I have read.

Last updated: 3 July 2024

### Icon description:

🥇 at least 200 citations (at the time of reading)

🥈 at least 100 citations (at the time of reading)

🥉 at least 50 citations (at the time of reading)

🏆 less than 50 citations (at the time of reading)

----

### Table of Contents:
- [Grokking Phenomenon](#grokking-phenomenon)
- [Phase Transitions](#phase-transitions)
- [Mechanistic Interpretability](#mechanistic-interpretability)

----

### Grokking Phenomenon

* 🥇 2022: [Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets](https://arxiv.org/pdf/2201.02177.pdf) ([Code](https://github.com/openai/grok)) <br>
This paper studied the generalization of neural networks on small algorithmically generated datasets, mainly in terms of data efficiency. In particular, they observed that in some situations, the validation accuracy begins to increase from chance level toward (almost) perfect generalization, long after the training accuracy reaches 100% (overfitting). They called this phenomenon “grokking”.

### Phase Transitions
* 🥉 2022: [Towards Understanding Grokking: An Effective Theory of Representation Learning](https://arxiv.org/pdf/2205.10343.pdf) ([Code](https://github.com/ejmichaud/grokking-squared)) <br>
This paper studied the grokking phenomenon using physics-inspired tools, namely effective theories and phase diagrams. They suggested that the observed generalization in algorithmic datasets is due to the network’s capability of learning good representation of the input embeddings. They also found that grokking occurs when the representation learning is significantly faster compared to the decoder learning. Therefore, with proper hyperparameter tuning (changing the learning rates and weight decay), it is possible to avoid grokking.
* 🏆 2022: [The Slingshot Mechanism: An Empirical Study of Adaptive Optimizers and the Grokking Phenomenon](https://openreview.net/pdf?id=lY1e0PNkSJ) <br>
This paper proposed that for grokking to occur with explicit regularization, the training dynamics must undergo a slingshot mechanism where the norm of the last layer weights exhibits cyclic behaviour (sharp phase transitions that alternate between rapid growth and plateaus) over the course of training. Furthermore, they found that by varying the epsilon parameter (the small constant added for numerical stability) of the Adam optimizer, one can control the appearance of the slingshot effects.

### Mechanistic Interpretability
* 🥇 2022 : [Progress Measures for Grokking via Mechanistic Interpretability](https://arxiv.org/pdf/2301.05217) ([Code](https://github.com/mechanistic-interpretability-grokking/progress-measures-paper)) <br>
