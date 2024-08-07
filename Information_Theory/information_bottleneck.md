## Topic: Information Bottleneck

A compiled list of information bottleneck-related papers which I have read.

Last updated: 21 July 2024

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

* 💥 2019 : [Markov Information Bottleneck to Improve Information Flow in Stochastic Neural Networks](https://www.mdpi.com/1099-4300/21/10/976) <br>

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

* 🥉 2022 : [On Information Plane Analyses of Neural Network Classifiers - A Review](https://arxiv.org/pdf/2003.09671) <br>
This paper consolidated and reviewed all the findings related to information plane analysis of deep neural networks. They argued that the compression phase observed in the plane could be related to the geometrical clustering of the latent representations. Furthermore, they noted that the results obtained by using different mutual information estimators are often not directly comparable.

* 💥 2021 : [Information Flows of Diverse Autoencoders](https://arxiv.org/pdf/2102.07402) <br>
This paper studied the information plane in the context of various autoencoders. They observed compression in some autoencoders, and the effect is amplified when the hidden layers are regularized to encourage sparsity. They also found no connection between compression and generalization.

* 💥 2020 : [Understanding Learning Dynamics of Binary Neural Networks via Information Bottleneck](https://arxiv.org/pdf/2006.07522) <br>
This paper studied the learning dynamics of binary neural networks using the information plane. They found that in this setting, the fitting phase and the compression phase happen simultaneously rather than consecutively.

* 💥 2020 : [Information-Bottleneck under Mean Field Initialization](https://people.maths.ox.ac.uk/tanner/papers/AbTa_InfBott_mean_field_ICML.pdf) <br>
This paper studied the information plane analysis when using different mutual information (MI) estimators (replica, KDE, EDGE) under the mean field (MF) initialization. They observed that under MF initialization, the MI is maximized in most layers. In the information plane, the MI estimates are closely concentrated and high accuracy is rapidly obtained with training.

* 🥉 2020 : [Understanding Convolutional Neural Networks with Information Theory](https://arxiv.org/pdf/1804.06537) <br>
This paper proposed to study the information plane in convolutional neural networks using the multivariate extension of the matrix-based Rényi α-entropy functional. They argued that for convolutional layers, the quantity that we need to measure is the multivariate mutual information between a variable and a group of variables (different feature maps). They also suggested to check the data processing inequality beforehand in order to validate the correctness of the estimator used. Using the partial information decomposition framework, they introduced three information-theoretic quantities to analyze the synergy and redundancy in convolutional layer representations.

* 💥 2020 : [On the Information Plane of Autoencoders](https://arxiv.org/pdf/2005.07783) <br>
This paper derived theoretical convergence of each layer of autoencoders in the information plane. The theory predicts that ideal autoencoders with a large bottleneck layer size do not compress input information, whereas a small size causes compression only in the encoder layers.

* 🥉 2019 : [Understanding Autoencoders with Information Theoretic Concepts](https://arxiv.org/pdf/1804.00057) <br>
This paper proposed to study the learning dynamics of stacked autoencoders (SAEs) using the information plane. They suggested three fundamental properties associated with the layer-wise information flow and intrinsic dimensionality of the bottleneck layer in SAEs.

* 💥 2019 : [Inverting Supervised Representations with Autoregressive Neural Density Models](https://arxiv.org/pdf/1806.00400) <br>
This paper proposed a method for estimating the mutual information between a model’s
inputs and its intermediate representations based on autoregressive density estimation. They observed information compression even for ReLU networks, and showed that compression in network layers has an important role in a model’s generalization performance.

* 🥉 2019 : [Estimating Information Flow in Deep Neural Networks](https://arxiv.org/pdf/1810.05728) <br>
This paper proposed a stochastic DNN framework to avoid the problems arising from deterministic function. This is done by adding i.i.d. Gaussian noise to the output of each hidden layer. They argued that the compression observed in the information plane during training is due to the clustering of the hidden representations. They also presented some evidence to show that compression and generalization may not be causally related.

* 💥 2019 : [Adaptive Estimators Show Information Compression in Deep Neural Networks](https://arxiv.org/pdf/1902.09037) <br>
This paper proposed adaptive way for estimating mutual information for the information plane analysis. 

* 2019 : [Utilizing Information Bottleneck to Evaluate the Capability of Deep Neural Networks for Image Classification](https://www.mdpi.com/1099-4300/21/5/456#B15-entropy-21-00456) <br>
This paper is an extended version of the 

* 🥈 2018 : [On the Information Bottleneck Theory of Deep Learning](https://openreview.net/pdf?id=ry_WPG-A-) ([Code](https://github.com/artemyk/ibsgd)) <br>
This paper challenged some of the claims made by the previous paper (Shwartz-Ziv & Tishby, 2017). In particular, they showed that compression is mainly observed when double-sided saturating nonlinearities are used. They also found no direct connection between compression and generalization. Furthermore, they observed that compression phase is still observed when full batch gradient descent was used. Finally, they argued that compression is a concurrent phase with the fitting process rather than a subsequent one.

* 2018 : [Evaluating Capability of Deep Neural Networks for Image Classification via Information Plane](https://openaccess.thecvf.com/content_ECCV_2018/papers/Hao_Cheng_Evaluating_Capability_of_ECCV_2018_paper.pdf) <br>


* 🥇 2017 : [Opening the Black Box of Deep Neural Networks via Information](https://arxiv.org/pdf/1703.00810) ([Code](https://github.com/ravidziv/IDNNs)) <br>
This paper proposed using the information plane to study the learning dynamics of deep neural networks with stochastic gradient descent optimization. They found two different phases: the initial empirical risk minimization phase, followed by the representation compression phase. They also argued that the optimality of a layer can be explained by the IB bounds.
