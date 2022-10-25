# ML-concept
# 1、超参数定义
       机器学习模型中一般有两类参数：一类需要从数据中学习和估计得到，称为模型参数（Parameter）---即模型本身的参数。比如，线性回归直线的加权系数（斜率）及其偏差项（截距）都是
       模型参数。还有一类则是机器学习算法中的调优参数（tuning parameters），需要人为设定，称为超参数（Hyperparameter）。比如，正则化系数λ，决策树模型中树的深度。
## batch_size、epoch、iteration是深度学习中常见的几个超参数：

（1）batch_size：每批数据量的大小。DL通常用SGD的优化算法进行训练，也就是一次（1 个iteration）一起训练batchsize个样本，计算它们的平均损失函数值，来更新参数。

（2）iteration：1个iteration即迭代一次，也就是用batchsize个样本训练一次。

（3）epoch：1个epoch指用训练集中的全部样本训练一次，此时相当于batchsize 等于训练集的样本数。
