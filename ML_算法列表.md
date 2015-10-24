#ML算法列表

##详细版
[http://www.datasciencecentral.com/profiles/blogs/a-tour-of-machine-learning-algorithms-1](http://www.datasciencecentral.com/profiles/blogs/a-tour-of-machine-learning-algorithms-1)

##粗略版

###Regression(回归分析)

> Regression(回归分析)关心的是变量之间的关系。它应用的是统计方法，几个算法的例子包括：

* Ordinary Least Squares
* Logistic Regression
* Stepwise Regression
* Multivariate Adaptive Regression Splines (MARS)
* Locally Estimated Scatterplot Smoothing (LOESS)
* Instance-based Methods

###Instance based learning(基于实例的学习)

> (基于实例的学习)模拟了一个决策问题，所使用的实例或者例子是对模型非常重要的。这种方法对现有数据建立一个数据库然后把新数据加进去，再用一个相似性测量方法从而在数据库里找出一个最优匹配，进行一个预测。由于这个原因，这种方法也被称为胜者为王方法和基于内存的方法。现在关注的焦点在存储数据的表现形式和相似性测量方法。

* k-Nearest Neighbour (kNN)
* Learning Vector Quantization (LVQ)
* Self-Organizing Map (SOM)

###Regularization Methods

> 这是一个对其他方法的延伸（通常是回归方法），这个延伸对越简单的模型越有利，并且更擅长归纳。我在这里列出它是因为它的流行和强大。

* Ridge Regression
* Least Absolute Shrinkage and Selection Operator (LASSO)
* Elastic Net
* Decision Tree Learning

### Decision tree methods(决策树方法)
> 建立了一个根据数据中实际值决策的模型。决策树用来解决归纳和回归问题。

* Classification and Regression Tree (CART)
* Iterative Dichotomiser 3 (ID3)
* C4.5
* Chi-squared Automatic Interaction Detection (CHAID)
* Decision Stump
* Random Forest
* Multivariate Adaptive Regression Splines (MARS)
* Gradient Boosting Machines (GBM)

###Bayesian

> Bayesian method(贝叶斯方法)是在解决归类和回归问题中应用了贝叶斯定理的方法。

* Naive Bayes
* Averaged One-Dependence Estimators (AODE)
* Bayesian Belief Network (BBN)
* Kernel Methods

###Kernel Method(核方法)
>中最有名的是Support Vector Machines(支持向量机)。这种方法把输入数据映射到更高维度上，是的一些归类和回归问题更容易建模。

* Support Vector Machines (SVM)
* Radial Basis Function (RBF)
* Linear Discriminate Analysis (LDA)
* Clustering Methods

### Clustering(聚类)
> 本身就形容了问题和方法。聚类方法通常是由建模方式分类的。所有的聚类方法都是用统一的数据结构来组织数据，使得每组内有最多的共同点。

* K-Means
* Expectation Maximisation (EM)
* Association Rule Learning

### Association rule learning
> (联合规则学习)是用来对数据间提取规律的方法，通过这些规律可以发现巨量多维空间数据之间的联系，而这些重要的联系可以被组织拿来使用。

* Apriori algorithm
* Eclat algorithm
* Artificial Neural Networks

### Artificial Neural Networks(人工神经网络)

> 是从生物神经网络的结构和功能得到启发的。它属于模式匹配一类，经常被用于回归和分类问题，但是它存在上百个算法和变种组成。其中有一些是经典流行的算法（我把深度学习拿出来单独讲）：

* Perceptron
* Back-Propagation
* Hopfield Network
* Self-Organizing Map (SOM)
* Learning Vector Quantization (LVQ)
* Deep Learning

###Deep Learning

> (深度学习)方法是人工神经网络的一种现代的更新。相比传统的神经网络，它有更多更复杂的网络构成，许多方法都是关心半监督学习，这种学习的问题中有很大的数据，但是其中很少是被标记的数据。

* Restricted Boltzmann Machine (RBM)
* Deep Belief Networks (DBN)
* Convolutional Network
* Stacked Auto-encoders
* Dimensionality Reduction

###Dimensionality Reduction(维度缩减)
> 像聚类方法一样，追求和利用数据中的统一的结构，但是它用更少的信息来对数据做归纳和形容。这对于对数据进行可视化或者简化数据很有用。

* Principal Component Analysis (PCA)
* Partial Least Squares Regression (PLS)
* Sammon Mapping
* Multidimensional Scaling (MDS)
* Projection Pursuit

###Ensemble Methods

> Ensemble methods(组合方法)由许多小的模型组成，这些模型经过独立训练，做出独立的结论，最后组成一个总的预测。很多研究集中在使用什么模型以及这些模型怎么被组合起来。这是一个非常强大且流行的技术。

* Boosting
* Bootstrapped Aggregation (Bagging)
* AdaBoost
* Stacked Generalization (blending)
* Gradient Boosting Machines (GBM)
* Random Forest
