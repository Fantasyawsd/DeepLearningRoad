# 计算机视觉 (Computer Vision)

本文档包含计算机视觉相关的深度学习内容，主要围绕卷积神经网络(CNN)及其在各个视觉任务中的应用。

## CNN概述

* [1. 一文看懂25个神经网络模型](https://blog.csdn.net/qq_35082030/article/details/73368962)
* [2. DNN概述论文：详解前馈、卷积和循环神经网络技术](https://zhuanlan.zhihu.com/p/29141828)
* [94页论文综述卷积神经网络：从基础技术到研究前景](https://zhuanlan.zhihu.com/p/35388569)

## 计算机视觉入门

* [CS231 李飞飞 已授权个人翻译笔记](https://zhuanlan.zhihu.com/p/21930884) && [视频](http://study.163.com/course/courseMain.htm?courseId=1003223001)
* [计算机视觉研究方向](https://mp.weixin.qq.com/s/WNkzfvYtEO5zJoe_-yAPow)

## 图像分类

### 发展史
* [从LeNet-5到DenseNet](https://zhuanlan.zhihu.com/p/31006686)      
* [深度学习笔记（十一）网络 Inception, Xception, MobileNet, ShuffeNet, ResNeXt, SqueezeNet, EfficientNet, MixConv](https://www.cnblogs.com/xuanyuyt/p/11329998.html)
* [CNN网络结构的发展](https://zhuanlan.zhihu.com/p/68411179)
* [Awesome - Image Classification：论文&&代码大全](https://github.com/weiaicunzai/awesome-image-classification)
* [pytorch-image-models](https://github.com/rwightman/pytorch-image-models)

### 经典网络详解
* [经典CNN模型LeNet解读](https://zhuanlan.zhihu.com/p/41736894)
* [机器学习进阶笔记之三 | 深入理解Alexnet](https://zhuanlan.zhihu.com/p/22659166)
* [一文读懂VGG网络](https://zhuanlan.zhihu.com/p/41423739)
* [Inception V1,V2,V3,V4 模型总结](https://zhuanlan.zhihu.com/p/52802896)
* [ResNet解析](https://blog.csdn.net/lanran2/article/details/79057994)
* [一文简述ResNet及其多种变体](https://zhuanlan.zhihu.com/p/35985680)
* [深入剖析MobileNet和它的变种（例如：ShuffleNet）为什么会变快？](https://zhuanlan.zhihu.com/p/158591662)
* [CNN模型之ShuffleNet](https://zhuanlan.zhihu.com/p/32304419)
* [ShuffleNet V2和四个网络架构设计准则](https://zhuanlan.zhihu.com/p/40980942)
* [ResNeXt 深入解读与模型实现](https://zhuanlan.zhihu.com/p/78019001)

### 注意力机制在CV中的应用
* [如何评价Momenta ImageNet 2017夺冠架构SENet?](https://www.zhihu.com/question/63460684)
* [CBAM：卷积块注意力模块](https://zhuanlan.zhihu.com/p/79419670) && [CBAM: Convolutional Block Attention Module](https://zhuanlan.zhihu.com/p/65529934)
* [SKNet——SENet孪生兄弟篇](https://zhuanlan.zhihu.com/p/59690223)
* [GCNet：当Non-local遇见SENet](https://zhuanlan.zhihu.com/p/64988633)

## 目标检测

### 发展史
- [深度学习之目标检测的前世今生（Mask R-CNN）](https://zhuanlan.zhihu.com/p/32830206)      
- [深度学习目标检测模型全面综述：Faster R-CNN、R-FCN和SSD](https://zhuanlan.zhihu.com/p/29434605)      
- [从RCNN到SSD，这应该是最全的一份目标检测算法盘点](https://zhuanlan.zhihu.com/p/36184131)    
- [目标检测算法综述三部曲](https://zhuanlan.zhihu.com/p/40047760)
  - [基于深度学习的目标检测算法综述（一）](https://zhuanlan.zhihu.com/p/40047760)
  - [基于深度学习的目标检测算法综述（二）](https://zhuanlan.zhihu.com/p/40020809)
  - [基于深度学习的目标检测算法综述（三）](https://zhuanlan.zhihu.com/p/40102001)
- [From RCNN to YOLOv3]()：[上](https://zhuanlan.zhihu.com/p/35724768)，[下](https://zhuanlan.zhihu.com/p/35731743)
- [后 R-CNN时代， Faster R-CNN、SSD、YOLO 各类变体统治下的目标检测综述：Faster R-CNN系列胜了吗？](https://zhuanlan.zhihu.com/p/38709522)
- [目标检测进化史](https://zhuanlan.zhihu.com/p/60590369)
- [CVPR2019目标检测方法进展综述](https://zhuanlan.zhihu.com/p/59376548)

### Anchor-Free目标检测
- [Anchor-Free目标检测算法](): [第一篇：arxiv2015_baidu_DenseBox](https://zhuanlan.zhihu.com/p/40221183)， [如何评价最新的anchor-free目标检测模型FoveaBox？](https://www.zhihu.com/question/319605567/answer/647844997), [FCOS: 最新的one-stage逐像素目标检测算法](https://zhuanlan.zhihu.com/p/61644900) && [最新的Anchor-Free目标检测模型FCOS，现已开源！](https://zhuanlan.zhihu.com/p/62198865) && [中科院牛津华为诺亚提出CenterNet，one-stage detector可达47AP，已开源！](https://zhuanlan.zhihu.com/p/62789701) && [AnchorFreeDetection](https://github.com/VCBE123/AnchorFreeDetection)
- [Anchor free深度学习的目标检测方法](https://zhuanlan.zhihu.com/p/64563186)
- [聊聊Anchor的"前世今生"（上）](https://zhuanlan.zhihu.com/p/63273342)&&[聊聊Anchor的"前世今生"（下）](https://zhuanlan.zhihu.com/p/68291859)

### 目标检测技术细节
* [目标检测的性能评价指标](https://zhuanlan.zhihu.com/p/70306015) && [NMS和计算mAP时的置信度阈值和IoU阈值 ](https://zhuanlan.zhihu.com/p/75348108) && [白话mAP](https://zhuanlan.zhihu.com/p/60834912) && [目标检测模型的评估指标mAP详解(附代码）](https://zhuanlan.zhihu.com/p/37910324)
* [深度学习中IU、IoU(Intersection over Union)](https://blog.csdn.net/iamoldpan/article/details/78799857)
* [Selective Search for Object Detection ](https://www.learnopencv.com/selective-search-for-object-detection-cpp-python/)[（译文）](https://blog.csdn.net/guoyunfei20/article/details/78723646)
* [Region Proposal Network(RPN)](https://zhuanlan.zhihu.com/p/106192020)
* [边框回归(Bounding Box Regression)详解](https://blog.csdn.net/zijin0802034/article/details/77685438)
* [NMS——非极大值抑制](https://blog.csdn.net/shuzfan/article/details/52711706) && [非极大值抑制NMS的python实现](https://zhuanlan.zhihu.com/p/128125301)

### 经典检测网络详解
* [将CNN引入目标检测的开山之作：R-CNN](https://zhuanlan.zhihu.com/p/23006190)
* [R-CNN论文详解](https://blog.csdn.net/u014696921/article/details/52824097)
* [深度学习（十八）基于R-CNN的物体检测](https://blog.csdn.net/hjimce/article/details/50187029)
* [Fast R-CNN](https://zhuanlan.zhihu.com/p/24780395)
* [深度学习（六十四）Faster R-CNN物体检测](https://blog.csdn.net/hjimce/article/details/73382553) && [你真的学会RoI Pooling了吗?](https://zhuanlan.zhihu.com/p/59692298)
* [目标检测论文阅读：Feature Pyramid Networks for Object Detection](https://zhuanlan.zhihu.com/p/36461718)
* [SSD](https://zhuanlan.zhihu.com/p/24954433)

### YOLO系列
* [YOLO](http://www.mamicode.com/info-detail-2314392.html) && [目标检测|YOLO原理与实现](https://zhuanlan.zhihu.com/p/32525231) && [图解YOLO](https://zhuanlan.zhihu.com/p/24916786) && [【论文解读】Yolo三部曲解读——Yolov1](https://zhuanlan.zhihu.com/p/70387154)
* [目标检测|YOLOv2原理与实现(附YOLOv3)](https://zhuanlan.zhihu.com/p/35325884?group_id=966229905398362112) && [YOLO2](https://zhuanlan.zhihu.com/p/25167153) && [【论文解读】Yolo三部曲解读——Yolov2](https://zhuanlan.zhihu.com/p/74540100)
* [<机器爱学习>YOLO v3深入理解](https://zhuanlan.zhihu.com/p/49556105) && [【论文解读】Yolo三部曲解读——Yolov3](https://zhuanlan.zhihu.com/p/76802514)
* [YOLOv4](https://zhuanlan.zhihu.com/p/138510087)

## 图像分割

### 概述
* [超像素、语义分割、实例分割、全景分割 傻傻分不清 ](https://zhuanlan.zhihu.com/p/50996404) && [语义分割、实例分割和全景分割的区别](https://blog.csdn.net/u013066730/article/details/103613154)
* [图像语义分割(Semantic segmentation) Survey](https://zhuanlan.zhihu.com/p/36801104)
* [干货 | 一文概览主要语义分割网络](https://blog.csdn.net/qq_20084101/article/details/80432960)
* [语义分割 发展综述](https://zhuanlan.zhihu.com/p/37618829)       
* [9102年了，语义分割的入坑指南和最新进展都是什么样的](https://zhuanlan.zhihu.com/p/76603228)
* [实例分割最新最全面综述：从Mask R-CNN到BlendMask](https://zhuanlan.zhihu.com/p/110132002)

### 经典分割网络
* [语义分割卷积神经网络快速入门](https://blog.csdn.net/qq_20084101/article/details/80455877)          
* [图像语义分割入门+FCN/U-Net网络解析](https://zhuanlan.zhihu.com/p/31428783) && [深入理解深度学习分割网络Ｕnet](https://blog.csdn.net/Formlsl/article/details/80373200)
* [Unet神经网络为什么会在医学图像分割表现好？](https://www.zhihu.com/question/269914775)
* [实例分割--Mask RCNN详解(ROI Align / Loss Function)](https://www.codetd.com/article/2554465) && [令人拍案称奇的Mask RCNN](https://zhuanlan.zhihu.com/p/37998710)

## 人脸相关技术

### 人脸识别
* [如何走近深度学习人脸识别？你需要这篇超长综述 | 附开源代码](https://zhuanlan.zhihu.com/p/35295839)    
* [人脸检测和识别算法综述]()      
    * [人脸检测算法综述 ](https://zhuanlan.zhihu.com/p/36621308)          
    * [人脸检测背景介绍和发展现状](https://zhuanlan.zhihu.com/p/32702868)
    * [人脸识别算法演化史](https://zhuanlan.zhihu.com/p/36416906)
    * [基于深度学习的人脸识别技术综述](https://zhuanlan.zhihu.com/p/24816781) && [如何走近深度学习人脸识别？你需要这篇超长综述](https://zhuanlan.zhihu.com/p/35295839) && [人脸识别损失函数综述（附开源实现）](https://zhuanlan.zhihu.com/p/51324547)

### 人脸关键点检测
* [【每周CV论文推荐】 初学深度学习人脸关键点检测必读文章](https://zhuanlan.zhihu.com/p/88344339)
* [从传统方法到深度学习，人脸关键点检测方法综述](https://mp.weixin.qq.com/s/CvdeV5xgUF0kStJQdRst0w)
* [人脸关键点检测综述](https://zhuanlan.zhihu.com/p/42968117)

## 图像超分辨率

* [深度学习图像超分辨率综述](https://zhuanlan.zhihu.com/p/57564211)
* [从SRCNN到EDSR，总结深度学习端到端超分辨率方法发展历程](https://zhuanlan.zhihu.com/p/31664818)

## 其他视觉任务

### 行人重识别
* [【CVPR2019正式公布】行人重识别论文](https://zhuanlan.zhihu.com/p/62843442)
* [2019 行人再识别年度进展回顾](https://zhuanlan.zhihu.com/p/64004977)

### 图像着色
* [Awesome-Image-Colorization](https://github.com/MarkMoHR/Awesome-Image-Colorization)

### 边检测
* [Awesome-Edge-Detection-Papers](https://github.com/MarkMoHR/Awesome-Edge-Detection-Papers)

### OCR与文本检测
* [2019CVPR文本检测综述](https://zhuanlan.zhihu.com/p/67319122)
* [OCR文字处理](https://zhuanlan.zhihu.com/p/65707543)
* [自然场景文本检测识别技术综述](https://mp.weixin.qq.com/s?__biz=MzU4MjQ3MDkwNA==&mid=2247485142&idx=1&sn=c0e01da30eb5e750be453eabe4be2bf4&chksm=fdb69b41cac11257ae22c7dac395e9651dab628fc35dd6d3c02d9566a8c7f5f2b56353d58a64&token=1065243837&lang=zh_CN#rd)

### 点云处理
* [awesome-point-cloud-analysis](https://zhuanlan.zhihu.com/p/65690433)

### 细粒度图像分类
* [超全深度学习细粒度图像分析：项目、综述、教程一网打尽](https://zhuanlan.zhihu.com/p/73542103)

### 图像检索
* 图像检索的十年[上](https://mp.weixin.qq.com/s/sM78DCOK3fuG2JrP2QaSZA)、[下](https://mp.weixin.qq.com/s/yzVMDEpwbXVS0y-CwWSBEA)

### 人群计数
* [人群计数](http://chuansong.me/n/443237851736), [1](https://www.cnblogs.com/wmr95/p/8134692.html), [2](https://blog.csdn.net/u011285477/article/details/51954989), [3](https://blog.csdn.net/qingqingdeaini/article/details/79922549)

## 轻量化模型

- [纵览轻量化卷积神经网络：SqueezeNet、MobileNet、ShuffleNet、Xception](https://zhuanlan.zhihu.com/p/32746221)   

## 卷积神经网络技术细节

### 卷积层
* [A Comprehensive Introduction to Different Types of Convolutions in Deep Learning](https://towardsdatascience.com/a-comprehensive-introduction-to-different-types-of-convolutions-in-deep-learning-669281e58215) && 翻译：[上](https://www.leiphone.com/news/201902/D2Mkv61w9IPq9qGh.html)、[下](https://www.leiphone.com/news/201902/biIqSBpehsaXFwpN.html?uniqueCode=OTEsp9649VqJfUcO)
* [卷积有多少种？一文读懂深度学习中的各种卷积](https://zhuanlan.zhihu.com/p/57575810)
* [卷积神经网络工作原理](https://www.zhihu.com/question/39022858)
* [一文读懂卷积神经网络中的1x1卷积核](https://zhuanlan.zhihu.com/p/40050371)

### 池化层
* [卷积神经网络中的各种池化操作](https://zhuanlan.zhihu.com/p/112216409)

### 注意力机制
* [深度学习中的注意力模型（2017版）](https://zhuanlan.zhihu.com/p/37601161)
* [计算机视觉中的注意力机制（推荐）](https://zhuanlan.zhihu.com/p/146130215) 
* [计算机视觉中的注意力机制](https://zhuanlan.zhihu.com/p/32928645)

### 特征融合
* [盘点目标检测中的特征融合技巧（根据YOLO v4总结）](https://zhuanlan.zhihu.com/p/141685352)
* [多尺度融合介绍](https://zhuanlan.zhihu.com/p/147820687)

## 实现与代码

* [PyTorch官方实现ResNet](https://github.com/pytorch/vision/blob/master/torchvision/models/resnet.py) && [pytorch_resnet_cifar10](https://github.com/akamaster/pytorch_resnet_cifar10)
* [目标检测-20种模型的原味代码汇总](https://zhuanlan.zhihu.com/p/37056927)     
* [TensorFlow Object Detection API 教程](https://blog.csdn.net/qq_36148847/article/details/79306762)
* [Pytorch-UNet](https://github.com/milesial/Pytorch-UNet)
* [segmentation_models.pytorch](https://github.com/qubvel/segmentation_models.pytorch)