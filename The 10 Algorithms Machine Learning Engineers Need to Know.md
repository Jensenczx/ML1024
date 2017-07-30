### The 10 Algorithms Machine Learning Engineers Need to Know

#### Surpervised Learning

给定的数据是带有标签的，也就是给定数据的分类，比如给我们一堆狗的图片，但是会告诉我们每一张狗的图片是哪一种狗，我们要做的是根据数据抽离的属性，确定一个函数，然后不断地优化这个函数中的参数，最终得到一个模型（参数固定的函数），然后当再次给予数据的时候，通过这个函数的计算，就可以得到相应的分类结果。

从给定数据中挖掘出一个模式，然后将这个模式尽可能的逼近真实结果，同时保持一定的泛化能力。

1. Decision Tree 决策树
2. Naive Bayesian classification 朴素贝叶斯分类器
3. Ordinary Least Squares  Regression 最小二乘法
4. Logistic Regression 逻辑回归
5. Support Vector Machine 支持向量机
6. Ensemble Methods 集成方法

- 它们平均了单个模型的偏差：如果你将民主党的民意调查和共和党的民意调查在一起平均化，那么你将得到一个均衡的结果，不偏向任何一方。
- 它们减少了方差：一组模型的总体意见比其中任何一个模型的单一意见更加统一。在金融领域，这就是所谓的多元化，有许多股票的组合比一个单独的股票的不确定性更少，这也为什么你的模型在数据多的情况下会更好的原因。
- 它们不太可能过拟合：如果你有单个的模型没有过拟合，那么把这些模型的预测简单结合起来（平均、加权平均、逻辑回归），那么最后得到的模型也不会过拟合。

#### UnSurpervised Learning

给定的数据是不带有标签的，也就是这些数据属于什么类别，我们是不清楚的。常见的有聚类算法，给定一堆数据，让机器自己从中挖据特性。然后将数据根据各自的特性进行分类。

1. Clustering Algorithm 聚类算法
2. Principal Component Analysis 主成分分析
3. Singular Value Decomposition 奇异值分解
4. Independent Component Analysis 独立成分分析

#### Reinforcement Learning

#### Target

了解机器学习三大分支，并知道其中相关算法，对整体有个系统的认识。

#### Source Text

[机器学习工程师必知的十大算法](http://www.infoq.com/cn/articles/10-algorithms-machine-learning-engineers-need-to-know)



