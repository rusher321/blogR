---
title: 大预言模型和宏基因组应用
author: Huahui Ren
date: '2024-05-29'
slug: ''
categories:
  - 技术
tags:
  - microbiome
subtitle: ''
summary: '大预言模型学习历程'
authors: []
lastmod: '2024-05-29T11:27:43+08:00'
featured: no
draft: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

最近在学习大语言模型的基础和在宏基因组中的应用，在这里总结下自己学习的内容和资料。

## **大语言模型基础**

1. **理解Transformer**
   
    1.1  Transformer是大语言的基础，基于这篇[**博客**](https://prvnsmpth.github.io/animated-transformer/)首先学习下Transformer是什么。
    
    1.2  Token: 在Transformer模型中，“tokens”是指模型输入的基本单位，通常是文本中的单词、子词或字符。在Transformer的上下文中，文本会被分割成一系列token，并且每个token都会被转换成一个向量表示。在处理序列数据时，tokens是构成输入序列的基本单位，它们在模型中被依次处理，用于捕捉序列中的语言结构和语义信息。
    
    1.3 Embeddings: 
    
    1.4 

2. **Hugingface 学习**

    1.1 [Hugging Face](https://huggingface.co/learn/nlp-course/chapter1/2?fw=pt)
    
    1.2 Xxx
    
    1.3 Xxx

3. **下游任务**

    3.1 Biomes classification
    
    宿主表型/疾病预测/多分类任务 
    [Multi-label classification](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/BERT/Fine_tuning_BERT_(and_friends)_for_multi_label_text_classification.ipynb#scrollTo=cMlebJ83LRYG)
    
    3.2 Token classification
    
    Contextual taxon embedding in different biomes/phenotypes
    (可以作为一个section，子标题)leverage language model to annotation ecological niche of microbe universe
    
    对应NLP任务: Named Entity Recognition (NER)，比如区分苹果（公司） 和 苹果（水果）
    
    Ref：[token_classification Notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/token_classification.ipynb#scrollTo=EUG8Gp6ugbNG)
    
    3.3 在新cohort 的 self-supervised learning (风格迁移)
    1. pretrained model + 无标签的自然群人的自监督微调 + 小样本的表型预测微调
    
    菌群干预、扰动
    1. 参考geneformer，调整物种的rank，看输出层的全局embedding及其他物种embedding.
    2. 生成式任务也可以考虑使用GPT等框架。


## **宏基因组应用相关文献**

1. 

2. 

3.