## Topic: Information Bottleneck

A compiled list of information bottleneck-related papers which I have read.

Last updated: 4 July 2024

### Icon description:

🥇 at least 1k citations (at the time of reading)

🥈 at least 500 citations (at the time of reading)

🥉 at least 50 citations (at the time of reading)

💥 less than 50 citations (at the time of reading)

----

### Table of Contents:
- [Information Bottleneck Objective](#information-bottleneck-objective)
- [Information Plane Analysis of Deep Neural Networks](#information-plane-analysis-of-deep-neural-networks)
----

### Information Bottleneck Objective

* 💥 2023 : [How Does Information Bottleneck Help Deep Learning?](https://arxiv.org/pdf/2305.18887) ([Code](https://github.com/xu-ji/information-bottleneck))<br>

* 🥉 2020 : [The Information Bottleneck Problem and Its Applications in Machine Learning](https://arxiv.org/pdf/2004.14941) <br>

* 💥 2020 : [The Dual Information Bottleneck](https://arxiv.org/pdf/2006.04641) <br>

* 💥 2019 : [Information Bottleneck and its Applications in Deep Learning](https://arxiv.org/pdf/1904.03743) <br>

* 💥 2019 : [Learnability for the Information Bottleneck](https://arxiv.org/pdf/1907.07331) <br>

* 🥉 2018 : [Learning Representation for Neural Network-Based Classification Using Information Bottleneck Principle](https://arxiv.org/pdf/1802.09766) <br>

* 🥉 2018 : [Caveats for Information Bottleneck in Deterministic Scenarios](https://arxiv.org/pdf/1808.07593) ([Code](https://github.com/artemyk/ibcurve)) <br>
This paper studied the information bottleneck (IB) objective in the deterministic settings which reveal several interesting observations. In particular, they found that the IB curve cannot be explored by varying the Lagrangian parameter in this case. Instead, they proposed an alternative objective called the squared-IB Lagrangian which can be used to explore the IB curve.

* 🥉 2017 : [Nonlinear Information Bottleneck](https://arxiv.org/pdf/1705.02436) ([Code](https://github.com/artemyk/nonlinearIB)) <br>
This paper proposed an approximation to the Information Bottleneck (IB) objective that considers nonlinear encoding and decoding maps. They used the variational lower bound for the prediction term and non-parametric upper bound for the compression term.

* 🥇 2016 : [Deep Variational Information Bottleneck](https://arxiv.org/pdf/1612.00410) <br>
This paper proposed a variational approximation to the Information Bottleneck (IB) objective, which can be parameterized using neural network. The approximation was done by considering the lower bound on the IB objective using variational inference. They showed that the variational IB objective improves generalization performance and adversarial robustness.

* 🥇 2015: [Deep Learning and the Information Bottleneck Principle](https://arxiv.org/pdf/1503.02406) <br>
This paper proposed to analyze the deep neural networks (DNNs) using the Information Bottleneck (IB) method. This was by visualizing the information curve, which plots the mutual information between the layers and the input and output variables. They applied the IB method to quantify the efficiency/optimality of the internal representations of the hidden layers in the DNNs.

* 🥉 2010: [Learning and Generalization with the Information Bottleneck](https://www.cs.huji.ac.il/labs/learning/Papers/ibgen.pdf) <br>
This paper studied the learning theoretic properties of the Information Bottleneck (IB) method. They proved several finite bounds that showed that the IB method can generalize quite using the plug-in estimates, even with sample sizes much smaller than the ones required for reliable estimation of joint distribution. They also argued that in the supervised learning setting, the IB method can be used to study the performance-complexity trade-off.

* 🥉 2002: [The Information Bottleneck: Theory and Applications](https://www.cs.huji.ac.il/labs/learning/Theses/Slonim_PhD.pdf) <br>
This is Noam Slonim's thesis which provides a comprehensive review of the Information Bottleneck method along with its multivariate extension.

* 🥉 2001: [Multivariate Information Bottleneck](https://arxiv.org/pdf/1301.2270) <br>
This paper extended the orignal Information Bottleneck method to multivariate cases.

* 🥇 2000: [The Information Bottleneck Method](https://arxiv.org/pdf/physics/0004057) <br>
This paper proposed the Information Bottleneck method to study the concept of relevant information quantitatively. It studies the trade-off between compression and prediction to find the concise representations for an input random variable that contain as much relevant information as possible for an output variable.

### Information Plane Analysis of Deep Neural Networks

* 🥉 2022 : [On Information Plane Analyses of Neural Network Classifiers - A Review](https://arxiv.org/pdf/2003.09671)

* 🥈 2018 : [On the Information Bottleneck Theory of Deep Learning](https://openreview.net/pdf?id=ry_WPG-A-) ([Code](https://github.com/artemyk/ibsgd)) <br>
This paper challenged some of the claims made by the previous paper (Shwartz-Ziv & Tishby, 2017). In particular, they showed that compression is mainly observed when double-sided saturating nonlinearities are used. They also found no direct connection between compression and generalization. Furthermore, they observed that compression phase is still observed when full batch gradient descent was used. Finally, they argued that compression is a concurrent phase with the fitting process rather than a subsequent one.

* 🥇 2017 : [Opening the Black Box of Deep Neural Networks via Information](https://arxiv.org/pdf/1703.00810) ([Code](https://github.com/ravidziv/IDNNs)) <br>
This paper proposed using the information plane to study the learning dynamics of deep neural networks with stochastic gradient descent optimization. They found two different phases: the initial empirical risk minimization phase, followed by the representation compression phase. They also argued that the optimality of a layer can be explained by the IB bounds.