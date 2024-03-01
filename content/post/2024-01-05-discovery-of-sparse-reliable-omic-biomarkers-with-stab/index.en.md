---
title: Discovery of sparse, reliable omic biomarkers with Stabl
author: Huahui Ren
date: '2024-01-05'
slug: discovery-of-sparse-reliable-omic-biomarkers-with-stab
categories:
  - academic
tags:
  - Tools
authors: [huahui]
doi: ''
publishDate: '2024-01-05T14:33:58+08:00'
publication_types:
  - '0'
publication: ''
publication_short: ''
abstract: ''
summary: ''
featured: no
url_pdf: ~
url_code: ~
url_dataset: ~
url_poster: ~
url_project: ~
url_slides: ~
url_source: ~
url_video: ~
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
slides: ''
---


![](images/featured.png)

### 简介
***
本研究是斯坦福大学团队于2024发表在NBT。该研究开发了一款叫[Stabl](https://github.com/gregbellan/Stabl)的工具，Stabl适用于小样本、多组学、高维度数据集中的临床生物标记物发现。


### 背景
***
近年来，由于多组学的兴起，在具有小样本的临床研究中会产生大量的临床变量(**P>>n**)。在面临这种问题的时候，我们要保证使用的统计方法具有可预测型(**predictivity**)、稀疏性（**sparsity**,这里和我们通常理解的稀疏性不同，是指少量有代表性的生物标记）和可靠性（**reliability**）。

针对高维数据特征筛选的问题，我们通常使用的基于正则化一类的方法（lasso，elastic net）和基于这类方法的加强的版本（adaptive lasso, sparsegroup lasso）。针对于多组学的问题，近年来使用数据融合（data fusion，不是特别清楚这类方法，[有空学习一下](https://www.pnas.org/doi/10.1073/pnas.2202113119)）是一种选择。但是对于小样本的临床研究来说，往往小的扰动就会使这些方法筛选出不同的特征组合。

另外一些考虑了稳定性的方法，往往通常是通过设置先验的筛选阈值和降低假阳性率来达到的。这类方法使建模与特征选择分成两个不同的模块，可能不是很好的选择。

**Stabl**方法是基于一个有监督的机器学习框架，通过在训练阶段讲原始数据加入噪音，确定信噪音比的阈值，然后再决定是否把变量纳入到预测模型中。（**原文**：Stabl combines noise injection into the original data, determination of a data-driven signal-to-noise threshold and integration of the selected features into a predictive model）

### 主要结果
***




### 结论
***


#### 参考

1. Hédou J, Marić I, Bellan G, et al. Discovery of sparse, reliable omic biomarkers with Stabl. Nat Biotechnol. Published online January 2, 2024.



