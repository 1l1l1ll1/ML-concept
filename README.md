# ML-concept
# 1、超参数定义
       机器学习模型中一般有两类参数：一类需要从数据中学习和估计得到，称为模型参数（Parameter）---即模型本身的参数。比如，线性回归直线的加权系数（斜率）及其偏差项（截距）都是
       模型参数。还有一类则是机器学习算法中的调优参数（tuning parameters），需要人为设定，称为超参数（Hyperparameter）。比如，正则化系数λ，决策树模型中树的深度。
## batch_size、epoch、iteration是深度学习中常见的几个超参数：

（1）batch_size：每批数据量的大小。DL通常用SGD的优化算法进行训练，也就是一次（1 个iteration）一起训练batchsize个样本，计算它们的平均损失函数值，来更新参数。

（2）iteration：1个iteration即迭代一次，也就是用batchsize个样本训练一次。

（3）epoch：1个epoch指用训练集中的全部样本训练一次，此时相当于batchsize 等于训练集的样本数。
# 2. ML WorkFlow
![image](https://user-images.githubusercontent.com/114986300/197780949-d0e56696-beac-4533-961f-6a284cf1fa0d.png)
### ps:![image](https://user-images.githubusercontent.com/114986300/197789954-4b115735-8cc6-470f-9e42-fb4bafe0c36d.png)
### ps:![image](https://user-images.githubusercontent.com/114986300/197790370-d31e1f36-ea75-43c4-9204-a00c7d0b39c0.png)  
注意enumerate返回值有两个,一个是序号，一个是数据（包含训练数据和标签）。在模型中。
