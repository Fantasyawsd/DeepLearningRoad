# 自然语言处理 (Natural Language Processing)

本文档包含自然语言处理相关的深度学习内容，主要围绕循环神经网络(RNN)、Transformer及其在NLP任务中的应用。

## NLP入门

* [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/index.html)
* [NLP上手教程](https://github.com/FudanNLP/nlp-beginner)
* [NLP入门推荐书目（2019版）](https://zhuanlan.zhihu.com/p/58874484)

## 循环神经网络(RNN)

### 发展史
* [从90年代的SRNN开始，纵览循环神经网络27年的研究进展](https://zhuanlan.zhihu.com/p/32668465)       

### RNN基础教程
* [Awesome-Chinese-NLP](https://github.com/crownpku/Awesome-Chinese-NLP)
* [nlp-pytorch-zh](https://github.com/apachecn/nlp-pytorch-zh)
* [完全图解RNN、RNN变体、Seq2Seq、Attention机制](https://zhuanlan.zhihu.com/p/28054589)
* [循环神经网络(RNN, Recurrent Neural Networks)介绍](https://blog.csdn.net/heyongluoyao8/article/details/48636251)
* [RNN以及LSTM的介绍和公式梳理](https://blog.csdn.net/Dark_Scope/article/details/47056361)

### LSTM详解
* [（译）理解长短期记忆(LSTM) 神经网络](https://zhuanlan.zhihu.com/p/24018768)
* [ 一文读懂LSTM和RNN](https://zhuanlan.zhihu.com/p/35878575?group_id=970350175025385472)
* [探索LSTM：基本概念到内部结构](https://zhuanlan.zhihu.com/p/27345523)
* [ 翻译：深入理解LSTM系列](https://blog.csdn.net/matrix_space/article/details/53374040)                      
* [深入理解 LSTM 网络 (一)](https://blog.csdn.net/matrix_space/article/details/53374040)
* [深入理解 LSTM 网络 (二)](https://blog.csdn.net/matrix_space/article/details/53376870)
* [LSTM](https://zhuanlan.zhihu.com/p/32085405)
* [深度学习其五 循环神经网络](https://zybuluo.com/hanbingtao/note/541458)                      
* [用循环神经网络进行文件无损压缩：斯坦福大学提出DeepZip](https://zhuanlan.zhihu.com/p/32582764)         

### 吴恩达序列建模课程
* [Coursera吴恩达《序列模型》课程笔记（1）-- 循环神经网络（RNN）](https://zhuanlan.zhihu.com/p/34309635)
* [Coursera吴恩达《序列模型》课程笔记（2）-- NLP & Word Embeddings](https://zhuanlan.zhihu.com/p/34975871)
* [Coursera吴恩达《序列模型》课程笔记（3）-- Sequence models & Attention mechanism](https://zhuanlan.zhihu.com/p/35532553)

## 词向量与嵌入

### Word2Vec
#### 原理
- [NLP 秒懂词向量Word2vec的本质](https://zhuanlan.zhihu.com/p/26306795)
- [一篇通俗易懂的word2vec](https://zhuanlan.zhihu.com/p/35500923)
- [YJango的Word Embedding--介绍](https://zhuanlan.zhihu.com/p/27830489)
- [nlp中的词向量对比：word2vec/glove/fastText/elmo/GPT/bert](https://zhuanlan.zhihu.com/p/56382372)
- [词嵌入（word2vec）](https://zh.diveintodeeplearning.org/chapter_natural-language-processing/word2vec.html)
- [谈谈谷歌word2vec的原理](https://blog.csdn.net/wangyangzhizhou/article/details/77073023)
- [Word2Vec中为什么使用负采样？](https://zhuanlan.zhihu.com/p/67117737)

#### 训练词向量
- [练习-word2vec](https://zhuanlan.zhihu.com/p/29200034)
- [word2vec方法的实现和应用](https://zhuanlan.zhihu.com/p/31886824)
- [自然语言处理入门 word2vec 使用tensorflow自己训练词向量](https://blog.csdn.net/wzdjsgf/article/details/79541492)
- [使用tensorflow实现word2vec中文词向量的训练](https://zhuanlan.zhihu.com/p/28979653)
- [如何用TensorFlow训练词向量](https://blog.csdn.net/wangyangzhizhou/article/details/77530479?locationNum=1&fps=1)

### 其他词向量技术
* [基于word2vec训练词向量(一)](https://zhuanlan.zhihu.com/p/35648927)
* [基于word2vec训练词向量(二)](https://zhuanlan.zhihu.com/p/35889385)
* [万物皆Embedding，从经典的word2vec到深度学习基本操作item2vec](https://zhuanlan.zhihu.com/p/53194407)

## Transformer与注意力机制

### 自注意力机制
* [自然语言处理中的自注意力机制（Self-Attention Mechanism）](https://zhuanlan.zhihu.com/p/35041012)    
* [自然语言处理中注意力机制综述](https://zhuanlan.zhihu.com/p/54491016)
* [深度学习中的注意力模型（2017版）](https://zhuanlan.zhihu.com/p/37601161)
* [Attention Model（mechanism） 的 套路](https://blog.csdn.net/bvl10101111/article/details/78470716)
* [NLP中的Attention Mechanism](https://zhuanlan.zhihu.com/p/31547842)

### Transformer详解
* [聊聊 Transformer](https://zhuanlan.zhihu.com/p/47812375)
* [基于Transform的机器翻译系统](https://zhuanlan.zhihu.com/p/144825330)
* [Transformer中的Attention](https://mp.weixin.qq.com/s/k8PdZAld2ANVoekuyQxI3w)

## 深度强化学习
* [CS234: Reinforcement Learning](http://web.stanford.edu/class/cs234/index.html)

## NLP实现与代码

### 推荐教程
* [推荐：nlp-tutorial](https://github.com/graykode/nlp-tutorial)
* [nlp-tutorial](https://github.com/lyeoni/nlp-tutorial)

### TensorFlow实现
* [tensorflow中RNNcell源码分析以及自定义RNNCell的方法](https://blog.csdn.net/liuchonge/article/details/78405185?locationNum=8&fps=1)     
* [TensorFlow中RNN实现的正确打开方式](https://zhuanlan.zhihu.com/p/28196873)      
* [TensorFlow RNN 代码](https://zhuanlan.zhihu.com/p/27906426)
* [Tensorflow实现的深度NLP模型集锦](https://zhuanlan.zhihu.com/p/67031035)
* [用tensorflow LSTM如何预测股票价格](https://zhuanlan.zhihu.com/p/33186759)
* [TensorFlow的多层LSTM实践](https://zhuanlan.zhihu.com/p/29797089)
* [《安娜卡列尼娜》文本生成——利用TensorFlow构建LSTM模型](https://zhuanlan.zhihu.com/p/27087310)

## NLP数据集

* [自然语言处理（NLP）数据集](https://zhuanlan.zhihu.com/p/35423943)
* [全唐诗(43030首)](https://pan.baidu.com/s/1o7QlUhO)
* [ACL 2018资源：100+ 预训练的中文词向量](https://zhuanlan.zhihu.com/p/36835964)
* [预训练中文词向量](https://github.com/Embedding/Chinese-Word-Vectors)
* [自然语言处理常见数据集、论文最全整理分享](https://zhuanlan.zhihu.com/p/56144877)
* [语义分析数据集-MSRA](https://github.com/msra-nlc/MSParS)