# 优化与训练 (Optimization and Training)

本文档包含深度学习中的优化算法、正则化技术、训练技巧等内容。

## 优化算法

* [优化算法纵览](http://fa.bianp.net/teaching/2018/eecs227at/)
* [从梯度下降到Adam](https://zhuanlan.zhihu.com/p/27449596)
* [从梯度下降到拟牛顿法：盘点训练神经网络的五大学习算法](https://zhuanlan.zhihu.com/p/25703402)
* [最优化算法系列（math）](https://blog.csdn.net/chunyun0716/article/category/6188191/2)
* [神经网络的优化及训练](https://zhuanlan.zhihu.com/p/36050743)
* [梯度下降优化算法纵览](http://ruder.io/optimizing-gradient-descent/), [1](https://blog.csdn.net/qq_23269761/article/details/80901411), [2](https://www.cnblogs.com/guoyaohua/p/8542554.html), [几种优化算法的比较（BGD、SGD、Adam、RMSPROP）](https://blog.csdn.net/qq_32172681/article/details/100979476)
* [BFGS](https://blog.csdn.net/philosophyatmath/article/details/70173128)

## 正则化技术

* [正则化技术总结](https://zhuanlan.zhihu.com/p/35429054?group_id=966442942538444800)
  * [史上最全面的正则化技术总结与分析--part1](https://zhuanlan.zhihu.com/p/35429054?group_id=966442942538444800)
  * [史上最全面的正则化技术总结与分析--part2](https://zhuanlan.zhihu.com/p/35432128?group_id=966443101011738624)

### L1/L2正则化
* [L1正则化与L2正则化](https://zhuanlan.zhihu.com/p/35356992) && [深入理解L1、L2正则化](https://zhuanlan.zhihu.com/p/29360425) && [L2正则=Weight Decay？并不是这样](https://zhuanlan.zhihu.com/p/40814046) && [都9102年了，别再用Adam + L2 regularization](https://zhuanlan.zhihu.com/p/63982470)
* [为什么weight decay能够防止过拟合](https://www.zhihu.com/question/65626362)

### Dropout
* [Dropout](https://arxiv.org/pdf/1207.0580.pdf), [1](https://blog.csdn.net/stdcoutzyx/article/details/49022443), [2](https://blog.csdn.net/hjimce/article/details/50413257), [3](https://blog.csdn.net/shuzfan/article/details/50580915)，[系列解读Dropout](https://blog.csdn.net/shuzfan/article/details/50580915)

### 批归一化与变体
* [Batch Normalization（BN）]():[1 ](https://zhuanlan.zhihu.com/p/26702482),[2 ](https://blog.csdn.net/hjimce/article/details/50866313),[3 ](https://bbs.cvmart.net/topics/576),[4 ](https://blog.csdn.net/edogawachia/article/details/80040456), [5](https://zhuanlan.zhihu.com/p/38176412), [6](https://www.zhihu.com/question/38102762), [7](https://zhuanlan.zhihu.com/p/52132614)
* [详解深度学习中的Normalization，不只是BN](https://zhuanlan.zhihu.com/p/33173246) && [如何区分并记住常见的几种 Normalization 算法](https://zhuanlan.zhihu.com/p/69659844)
* [FAIR何恺明等人提出组归一化：替代批归一化，不受批量大小限制](https://zhuanlan.zhihu.com/p/34858971)
* [Coursera吴恩达《优化深度神经网络》课程笔记（3）-- 超参数调试、Batch正则化和编程框架](https://zhuanlan.zhihu.com/p/30922689)

### 其他正则化技术
* [谱归一化（Spectral Normalization）的理解](https://blog.csdn.net/StreamRock/article/details/83590347)，[常见向量范数和矩阵范数](https://blog.csdn.net/left_la/article/details/9159949)，[谱范数正则（Spectral Norm Regularization）的理解](https://blog.csdn.net/StreamRock/article/details/83539937)
* [机器学习里的黑色艺术：normalization, standardization, regularization](https://zhuanlan.zhihu.com/p/29974820) && [数据标准化/归一化normalization](https://blog.csdn.net/pipisorry/article/details/52247379) && [特征工程中的「归一化」有什么作用？](https://www.zhihu.com/question/20455227)

## 梯度问题

* [神经网络训练中的梯度消失与梯度爆炸](https://zhuanlan.zhihu.com/p/25631496)
* [梯度消失和梯度爆炸问题详解](https://www.jianshu.com/p/3f35e555d5ba)
* [详解深度学习中的梯度消失、爆炸原因及其解决方法](https://zhuanlan.zhihu.com/p/33006526) && [神经网络梯度消失和梯度爆炸及解决办法](https://blog.csdn.net/program_developer/article/details/80032376)
* [LSTM系列的梯度问题](https://zhuanlan.zhihu.com/p/36101196)
* [详解残差块为何有助于解决梯度弥散问题](https://zhuanlan.zhihu.com/p/28124810)
* [浅谈神经网络中的梯度爆炸问题](https://zhuanlan.zhihu.com/p/32154263)

## 损失函数

### 交叉熵损失
* [为什么选用交叉熵而不是MSE](https://zhuanlan.zhihu.com/p/61944055) &&[为什么使用交叉熵作为损失函数](https://zhuanlan.zhihu.com/p/63731947) &&[二元分类为什么不能用MSE做为损失函数？](http://sofasofa.io/forum_main_post.php?postid=1001792)&& [为什么平方损失函数不适用分类问题？](https://www.zhihu.com/question/319865092)
* [交叉熵代价函数（作用及公式推导）](https://blog.csdn.net/u014313009/article/details/51043064) && [交叉熵损失的来源、说明、求导与pytorch实现](https://zhuanlan.zhihu.com/p/67782576) && [Softmax函数与交叉熵](https://zhuanlan.zhihu.com/p/27223959) && [极大似然估计与最小化交叉熵损失或者KL散度为什么等价](https://zhuanlan.zhihu.com/p/84764177)

### Focal Loss
* [何恺明大神的「Focal Loss」，如何更好地理解？](https://zhuanlan.zhihu.com/p/32423092) && [FocalLoss 对样本不平衡的权重调节和减低损失值](https://zhuanlan.zhihu.com/p/82148525) && [focal_loss 多类别和二分类 Pytorch代码实现](https://blog.csdn.net/qq_33278884/article/details/91572173) && [多分类focal loss及其tensorflow实现](https://blog.csdn.net/qq_39012149/article/details/96184383)
* [堪比Focal Loss！解决目标检测中样本不平衡的无采样方法](https://zhuanlan.zhihu.com/p/93658728)

### 其他损失函数
* [激活函数/损失函数汇总](https://zhuanlan.zhihu.com/p/30385380)
* [机器学习中常见的损失函数及其应用场景](https://blog.csdn.net/zuolixiangfisher/article/details/88649110) && [PyTorch的十八个损失函数](https://zhuanlan.zhihu.com/p/61379965)
* [深度度量学习中的损失函数](https://zhuanlan.zhihu.com/p/82199561)
* [损失函数整理](https://zhuanlan.zhihu.com/p/35027284)
* [目标检测回归损失函数简介：SmoothL1/IoU/GIoU/DIoU/CIoU Loss](https://zhuanlan.zhihu.com/p/104236411)

## Softmax详解

**Softmax**：[详解softmax函数以及相关求导过程](https://zhuanlan.zhihu.com/p/25723112)  &&  [softmax的log似然代价函数（公式求导）](https://blog.csdn.net/u014313009/article/details/51045303) && [【技术综述】一文道尽softmax loss及其变种](https://zhuanlan.zhihu.com/p/34044634)
* [从最优化的角度看待Softmax损失函数](https://zhuanlan.zhihu.com/p/45014864)  && [Softmax理解之二分类与多分类](https://zhuanlan.zhihu.com/p/45368976) && [Softmax理解之Smooth程度控制](https://zhuanlan.zhihu.com/p/49939159) && [Softmax理解之margin](https://zhuanlan.zhihu.com/p/52108088)

## 权重初始化

* [神经网络中的权重初始化一览：从基础到Kaiming](https://zhuanlan.zhihu.com/p/62850258)
* [深度学习中常见的权重初始化方法](https://zhuanlan.zhihu.com/p/138064188)
* [深度学习中神经网络的几种权重初始化方法](https://blog.csdn.net/u012328159/article/details/80025785)
* [谈谈神经网络权重为什么不能初始化为0](https://zhuanlan.zhihu.com/p/75879624)
* [神经网络中的偏置（bias）究竟有这么用？](https://www.zhihu.com/question/305340182)
* [深度学习里面的偏置为什么不加正则？](https://www.zhihu.com/question/66894061)

## 学习率与衰减

* [权重衰减（weight decay）与学习率衰减（learning rate decay）](https://zhuanlan.zhihu.com/p/38709373) && [pytorch必须掌握的的4种学习率衰减策略](https://zhuanlan.zhihu.com/p/93624972)
* [机器学习：如何找到最优学习率](https://blog.csdn.net/whut_ldz/article/details/78882871)及[实现](https://github.com/L1aoXingyu/torchlib)
* [神经网络中 warmup 策略为什么有效](https://www.zhihu.com/question/338066667)

## 评估指标

* [通俗讲解查全率和查准率](https://zhuanlan.zhihu.com/p/35888543) && [全面梳理：准确率,精确率,召回率,查准率,查全率,假阳性,真阳性,PRC,ROC,AUC,F1](https://zhuanlan.zhihu.com/p/34079183) && [机器学习之类别不平衡问题 (1) —— 各种评估指标](https://zhuanlan.zhihu.com/p/34473430) && [机器学习之类别不平衡问题 (2) —— ROC和PR曲线](https://zhuanlan.zhihu.com/p/34655990) && [AUC详解与python实现](https://zhuanlan.zhihu.com/p/84035782) && [微平均和宏平均](https://zhuanlan.zhihu.com/p/78628437)  && [机器学习中的性能度量](https://zhuanlan.zhihu.com/p/74980268) && [精确率、召回率、F1 值、ROC、AUC 各自的优缺点是什么](https://www.zhihu.com/question/30643044)

## 信息论基础

* [机器学习各种熵](https://zhuanlan.zhihu.com/p/35423404)
* [距离和相似性度量](https://zhuanlan.zhihu.com/p/27305237)

## 数据处理与平衡

* [不平衡数据集处理方法](): [其一](https://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/), [其二](https://www.zhihu.com/question/285824343), [其三](https://blog.csdn.net/songhk0209/article/details/71484469) && [Awesome Imbalanced Learning](https://github.com/ZhiningLiu1998/awesome-imbalanced-learning) && [Class-balanced-loss-pytorch](https://github.com/vandit15/Class-balanced-loss-pytorch)
* [目标检测正负样本区分策略和平衡策略总结(一)](https://zhuanlan.zhihu.com/p/138824387) && [目标检测正负样本区分策略和平衡策略总结(二)](https://zhuanlan.zhihu.com/p/138828372) && [目标检测正负样本区分策略和平衡策略总结(三）](https://zhuanlan.zhihu.com/p/144659734)

## Bias-Variance Trade-off

* [为什么说bagging是减少variance，而boosting是减少bias?](https://www.zhihu.com/question/26760839)