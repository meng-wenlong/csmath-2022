# CSMATH-2022

## About this course
This mathematics course is designed for the first year Ph.D. students of computer science and related areas. The course focuses on the methodologies, technologies, mathematics and algorithms currently needed by people. We are trying our best to give novice of this area an introduction of mathematics with intuitive explanation, clear concepts as well as vivid application examples. The course consists of basic statistical learning, non-linear optimization, partial differential equations and applied function analysis.

## 有关本课程
本课程是为计算机及相关专业的博士生新生开设的一门数学课程。本课程教授在计算机科学和信息处理研究领域相关的数学方法论、技术、概念以及基本算法。试图以数学的直观引导，清晰的概念解释，生动的应用实例，为学生开始进入这些领域的研究提供一个数学知识的导引。

本课程的主要教学内容包括多元统计方法初步，非线性优化求解技术，偏微分方程以及应用泛函方法等四个单元。多元统计方法单元，从统计的角度，对计算机科学中如计算机视觉和模式识别等领域中的非确定性建模方法进行考察。非线性优化单元讲述主流非线性优化方法及其相关特性比较。偏微分方程单元，着重于介绍level-set方法，椭圆方程和 Poisson方程的求解理论以及相应应用与实现。应用泛函分析部分，简要阐述泛函基本概念、基于泛函和变分方法的数学建模思想，并以工程的实际问题为例进行案例分析。


## Instructors
+ [Dr. Hongxin Zhang](http://www.cad.zju.edu.cn/home/zhx/), the spring semester, [his weibo](https://weibo.com/kull/)
+ [Dr. Ming Li](http://www.cad.zju.edu.cn/liming), the summer semester 
+ [Dr. Yubo Tao](http://www.cad.zju.edu.cn/home/ybtao/), the summer semester

## TA
Hongjia Wu, Shi Dong and Shanchen Zou

## Classroom & Time
+ Room 107, Cao Guang Biao West Building, Yuquan Campus, Zhejiang University
+ Tuesday, 18:30-21:30

## Schedule
|  No. |   Topic             |     Date     |                  Slides                                   |   Homework              |
|:----:|:-------------------:|:------------:|:---------------------------------------------------------:|:-----------------------:|
| ---  |   ---               |  ---         |  The spring semester                                      |   ---                   |
|  01  |  Introduction       |  2022.02.22  |  [Introduction](pdf/csmath-00-introduction.pdf)           |   [HW01](hw/hw01.md)    |
|      |                     |              |  [Why data driven](pdf/csmath-01-data-driven.pdf)         |                         |
|      |                     |              |  [Point estimation](pdf/csmath-01-point_estimation.pdf)   |                         |
|      |                     |              |  [Additional reading](https://engineering.purdue.edu/kak/Trinity.pdf)  |            |
|  02  |  Component Analysis |  2022.03.01  |  [SVD and X-PCA](pdf/csmath-02-component_analysis-2022.pdf)  |  [HW02](hw/hw02.md)  |
|  03  |  Clustering         |  2022.03.08  |  [Clustering](pdf/csmath-03-distance_and_similarity.pdf)  |   [HW03](hw/hw03.md)    |
|  04  |  Graphical Models   |  2022.03.15  |  [Graphical Models](pdf/csmath-04-graphical_models.pdf)   |                         |
| ---  |   ---               |  ---         |  ---                                                      |   ---                   |
|      |  Additional Topics  |              |  [Naive Bayes classifier](pdf/ML2007-naive_bayes_classification.pdf)   |            |
|      |                     |              |  [Support Vector Machines](pdf/ML2007-SVM.pdf)            |                         |
|      |                     |              |  [Decision tree](pdf/ML2007-decision_tree.pdf)            |                         |
|      |                     |              |  [Boosting](pdf/ML2007-boosting.pdf)                      |                         |
|      |                     |              |  [Kalman Filter](pdf/ML2007-kalman_filter.pdf)            |                         |
|      |                     |              |  [Old course](http://www.cad.zju.edu.cn/home/zhx/ML/index_2007.html)   |            |
| ---  |   ---               |  ---         |  ---                                                      |   ---                   |
|  05  |  Linear Programming |  2022.03.22  |  [LP-1](pdf/csmath-05-linear_programming.pdf)             |                         |
|      |                     |              |  [English version](pdf/csmath-05-linear_programming_en.pdf)       |                 |
|  06  |  Linear Programming |  2022.03.29  |  [LP-2](pdf/csmath-06-linear_programming_and_dual_methods.pdf)    |                 |
|      |                     |              |  [English version](pdf/csmath-06-linear_programming_and_dual_methods_en.pdf)    |   |
|  07  |  Non-Linear         |  2022.04.12  |  [NP-1](pdf/csmath-07-nonlinear.pdf)                      |   [HW04](hw/hw04.md)    |
|  08  |  Non-Linear         |  2022.04.12  |  [NP-2](pdf/csmath-08-nonlinear_and_qp.pdf)               |   [HW05](hw/hw05.md)    |


## Homework and the Course Paper
Please hand out your 1 [course paper](coursepaper/README.md) and [5 selected homework](hw/README.md) (or exercises) by 2022-06-01. 

All homework and exercises must be implemented in Python and/or with TensorFlow (optionally) 

## Content

### Courselet on Multivariate Analysis
The study of learning from data is commercially and scientifically important. This one month short course is designed to give first year Ph.D. students a thorough grounding in the methodologies, technologies, mathematics and algorithms currently needed by people who do research in learning and data mining or who may need to apply learning or data mining techniques to a target problem. The topics of the course draw from classical statistics, from machine learning, from data mining, from Bayesian statistics and from statistical algorithmics.

Students entering the class should have a pre-existing working knowledge of probability, statistics and algorithms, though the class has been designed to allow students with a strong numerate background to catch up and fully participate.

#### Text books
+ [Pattern Recognition and Machine Learning](http://research.microsoft.com/en-us/um/people/cmbishop/prml/)
+ [Pattern Classification, 2nd ed](http://www.rii.ricoh.com/~stork/DHS.html)
+ [The Elements of Statistical Learning: Data Mining, Inference, and Prediction. Second Edition, 2009.](http://www-stat.stanford.edu/~tibs/ElemStatLearn/)

#### Reference website
+ [Stanford machine Learning course](http://www.stanford.edu/class/cs229/)


### Courselet on Optimization
Optimization methods, both linear and non-linear ones, are important mathematical techniques for computer science. This one month short course is designed to give first year Ph.D. students a thorough grounding in the methodologies, technologies, mathematics and algorithms currently needed by people who are doing research related to linear and non-linear optimization. The topics of the course draw mainly from linear programming, quadratic programming and nonlinear optimization.

Students entering the class should have a pre-existing working knowledge of fundamental mathematics and algorithms, though the class has been designed to allow students with a strong numerate background to catch up and fully participate.

## Copyright
2005-2022 Copyright By Dr. Hongxin Zhang AT Zhejiang University

浙江大学 2005-2022 版权所有，如需转载或引用本课程相关内容，请与作者联系。

You can also visit my weibo: https://weibo.com/kull
