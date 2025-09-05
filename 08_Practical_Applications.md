# 实战应用 (Practical Applications)

本文档包含深度学习的实际应用、比赛经验、训练技巧等实用内容。

## 炼丹术士那些事

### 调参经验
* [训练的神经网络不工作？一文带你跨过这37个坑](https://blog.csdn.net/jiandanjinxin/article/details/77190687)
* [Deep Learning 之 训练过程中出现NaN问题](https://blog.csdn.net/BVL10101111/article/details/76086344)
* [神经网络训练trick](https://zhuanlan.zhihu.com/p/59918821)
* [你有哪些deep learning（rnn、cnn）调参的经验？](https://www.zhihu.com/question/41631631)
* [GAN的一些小trick](https://zhuanlan.zhihu.com/p/27725664)
* [深度学习与计算机视觉系列(8)_神经网络训练与注意点](https://blog.csdn.net/han_xiaoyang/article/details/50521064)
* [神经网络训练loss不下降原因集合](https://blog.csdn.net/liuweiyuxiang/article/details/80856991) && [ loss不下降的解决方法](https://blog.csdn.net/zongza/article/details/89185852)
* [深度学习：欠拟合问题的几种解决方案](https://blog.csdn.net/u014038273/article/details/84108688) &&[过拟合和欠拟合问题](https://blog.csdn.net/mzpmzk/article/details/79741682)

### 调参技巧进阶
* [同一个神经网络使用不同激活函数的表达能力是否一致](https://www.zhihu.com/question/41841299)
* [论文笔记之数据增广：mixup](https://blog.csdn.net/ly244855983/article/details/78938667#%E8%AE%A8%E8%AE%BA)
* [避坑指南：数据科学家新手常犯的13个错误](https://zhuanlan.zhihu.com/p/44331706)	
* [大卷积核还是小卷积核?]() [1](https://www.jianshu.com/p/d75375dd7ebd), [2](https://blog.csdn.net/kuangtun9713/article/details/79475457)	
* [模型可解释性差？你考虑了各种不确定性了吗？](https://baijiahao.baidu.com/s?id=1608193373391996908)

### 模型可视化与解释
* [凭什么相信CNN的结果?--可视化](https://bindog.github.io/blog/2018/02/10/model-explanation/)				
  * [凭什么相信你，我的CNN模型？（篇一：CAM和Grad-CAM)](https://bindog.github.io/blog/2018/02/10/model-explanation/) && [pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam) && [Grad-CAM-tensorflow](https://github.com/insikk/Grad-CAM-tensorflow) && [grad-cam.tensorflow](https://github.com/Ankush96/grad-cam.tensorflow) && [cnn_visualization](https://github.com/js-fan/mxnet/tree/d2b802e2d2af3dae5b4ac941354602630d2ef1c7/example/cnn_visualization)
  * [凭什么相信你，我的CNN模型？（篇二：万金油LIME)](http://bindog.github.io/blog/2018/02/11/model-explanation-2/)
  * [论文笔记:Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://www.jianshu.com/p/294ad9ae2e50)

### 炼丹笔记系列
* [炼丹笔记系列]()
  * [炼丹笔记一：样本不平衡问题](https://zhuanlan.zhihu.com/p/56882616)
  * [炼丹笔记二：数据清洗](https://zhuanlan.zhihu.com/p/56022212)
  * [炼丹笔记三：数据增强](https://zhuanlan.zhihu.com/p/56139575)
  * [炼丹笔记四：小样本问题](https://zhuanlan.zhihu.com/p/56365469)
  * [炼丹笔记五：数据标注](https://zhuanlan.zhihu.com/p/56443169)
  * [炼丹笔记六 : 调参技巧](https://zhuanlan.zhihu.com/p/56745640)
  * [炼丹笔记七：卷积神经网络模型设计](https://zhuanlan.zhihu.com/p/57738934)

## 竞赛实战

### Kaggle基础知识
* [Kaggle实战]()
  * 常用算法：
    * Feature Engineering：continue variable && categorical variable
    * Classic machine learning algorithm：LR, KNN, SVM, Random Forest, GBDT(XGBoost&&LightGBM), Factorization Machine, Field-aware Factorization Machine, Neural Network
    * Cross validation, model selection：grid search, random search, hyper-opt
    * Ensemble learning
  * [kaggle竞赛宝典第一章-竞赛框架篇！:star:](https://mp.weixin.qq.com/s/EGiFG6u9BYr1aBdq0a0wIQ)
  * [Kaggle 项目实战（教程） = 文档 + 代码 + 视频](https://github.com/apachecn/kaggle)
  * [Kaggle入门系列：（一）机器学习环境搭建](https://zhuanlan.zhihu.com/p/29086448) && [Kaggle入门系列：（二）Kaggle简介](https://zhuanlan.zhihu.com/p/29417603) && [Kaggle入门系列（三）Titanic初试身手](https://zhuanlan.zhihu.com/p/29086614)
  * [从 0 到 1 走进 Kaggle](https://zhuanlan.zhihu.com/p/61660061) 
  * [Kaggle 入门指南](https://zhuanlan.zhihu.com/p/25742261) 

### Kaggle策略与技巧
  * [一个框架解决几乎所有机器学习问题](https://zhuanlan.zhihu.com/p/61657532) && [Approaching (Almost) Any Machine Learning Problem | Abhishek Thakur](http://blog.kaggle.com/2016/07/21/approaching-almost-any-machine-learning-problem-abhishek-thakur/)
  * [分分钟带你杀入Kaggle Top 1%](https://zhuanlan.zhihu.com/p/27424282)
  * [如何达到Kaggle竞赛top 2%？这里有一篇特征探索经验帖](https://zhuanlan.zhihu.com/p/48758045) 
  * [如何在 Kaggle 首战中进入前 10%？](https://zhuanlan.zhihu.com/p/27486736)
  * [Kaggle 首战 Top 2%, APTOS 2019 复盘总结 + 机器学习竞赛通用流程归纳](http://bbs.cvmart.net/topics/1717)
  * [kaggle的riiid比赛里关于数据处理时间空间优化的笔记](https://zhuanlan.zhihu.com/p/344388290)

### 大数据竞赛
* [大数据&机器学习相关竞赛推荐](https://blog.csdn.net/weixin_33739541/article/details/87565983)

## 刷排行榜的小技巧

* [Kaggle 六大比赛最全面解析（上）](https://www.leiphone.com/news/201803/XBjvQriKTyTMPLcz.html)
* [Kaggle 六大比赛最全面解析（下）](https://www.leiphone.com/news/201803/chz1DNHqgVWNEm5t.html)

### 图像分类竞赛技巧

* [炼丹笔记三：数据增强](https://zhuanlan.zhihu.com/p/56139575) && [数据增强(Data Augmentation)](https://zhuanlan.zhihu.com/p/41679153)
* [【技术综述】 深度学习中的数据增强（上）](https://zhuanlan.zhihu.com/p/38345420) && [【技术综述】深度学习中的数据增强（下）](https://zhuanlan.zhihu.com/p/38437739)
* [深度学习数据增广技术一览](https://zhuanlan.zhihu.com/p/144921458)
* [《Bag of Tricks for Image Classification with CNN》](https://zhuanlan.zhihu.com/p/53324148)&& [pdf](https://arxiv.org/pdf/1812.01187.pdf)
* [深度神经网络模型训练中的最新tricks总结【原理与代码汇总】](https://zhuanlan.zhihu.com/p/66080948) && [神经网络训练trick](https://zhuanlan.zhihu.com/p/59918821)

### Kaggle图像分类解决方案
* [Kaggle解决方案分享]()
  * [从0上手Kaggle图像分类挑战：冠军解决方案详解](https://www.itcodemonkey.com/article/4898.html)
  * [Kaggle 冰山图像分类大赛近日落幕，看冠军团队方案有何亮点](https://www.leiphone.com/news/201803/u40cjEZWArBfFaBm.html)
  * [【Kaggle冠军分享】图像识别和分类竞赛，数据增强及优化算法](https://mp.weixin.qq.com/s/_S8EBBJ-u9g_fHp7I3ChMQ?)
  * [识别座头鲸，Kaggle竞赛第一名解决方案解读](https://zhuanlan.zhihu.com/p/58496385)
  * [kaggle 首战拿金牌总结](https://zhuanlan.zhihu.com/p/60953933)
  * [16岁高中生夺冠Kaggle地标检索挑战赛！而且竟然是Kaggle老兵](https://zhuanlan.zhihu.com/p/37522227)
  * [6次Kaggle计算机视觉类比赛赛后感](https://zhuanlan.zhihu.com/p/37663895)
  * [Kaggle首战斩获第三-卫星图像识别](https://zhuanlan.zhihu.com/p/63275166)

### 目标检测竞赛技巧

* ensemble
* deformable
* sync bn
* ms train/test
* [目标检测任务的优化策略tricks](https://zhuanlan.zhihu.com/p/56792817)
* [目标检测小tricks--样本不均衡处理](https://zhuanlan.zhihu.com/p/60612064)
* [汇总|目标检测中的数据增强、backbone、head、neck、损失函数](https://zhuanlan.zhihu.com/p/137769687)
* [目标检测算法中的常见trick](https://zhuanlan.zhihu.com/p/39262769)
* [Bag of Freebies —— 提升目标检测模型性能的免费tricks](https://zhuanlan.zhihu.com/p/141878389)
* [目标检测比赛中的tricks（已更新更多代码解析）](https://zhuanlan.zhihu.com/p/102817180)

### 医学影像竞赛
* [Kaggle：肺癌自动诊断系统3D Deep Leaky Noisy-or Network 论文阅读](https://www.jianshu.com/p/50158f8daf0d)
* [干货|大神教你如何参加kaggle比赛——根据CT扫描图预测肺癌](https://yq.aliyun.com/articles/89312)