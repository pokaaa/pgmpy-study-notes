# pgmpy源码学习笔记

## 学习目标
 - 学习[pgmpy](https://github.com/pgmpy/pgmpy)的过程记录
 - 查找[pgmpy官方对应源码](https://github.com/pgmpy/pgmpy/tree/dev/pgmpy)，学习贝叶斯网络各部分知识的实现细节

## 学习来源
> **原笔记**源自：*[https://github.com/pgmpy/pgmpy/tree/dev/examples](https://github.com/pgmpy/pgmpy/tree/dev/examples)*.

## 我的笔记
> **我的学习笔记**以"""红色注释"""的形式添加在了**原笔记**的代码部分
>

## 目前已完成的源码学习
 - [创建贝叶斯网络](https://github.com/pokaaa/pgmpy-study-notes/blob/main/Creating%20a%20Discrete%20Bayesian%20Network.ipynb)
   - 创建：定义模型结构、CPD 
   - 基本运算：判断d-分隔/有向分隔、马尔可夫性 
 - [贝叶斯网络的推理问题](https://github.com/pokaaa/pgmpy-study-notes/blob/main/Inference%20in%20Discrete%20Bayesian%20Networks.ipynb)
   - 后验概率问题——变量消元算法
   - 最大后验假设（MAP）问题
 - 贝叶斯网络参数学习
   - 最大似然估计(MLE)
   - 贝叶斯估计
 - 贝叶斯网络结构学习
   - CH评分
   - 爬山法

