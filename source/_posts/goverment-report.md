---
title: 国务院工作报告分析
date: 2018-01-02 10:10:42
tags: R语言 文本挖掘 政府工作报告
toc: TRUE
---

突然来了一个紧急任务，我的毕业论文要开始写了，我打算把这个小项目改写成毕业论文，两个图像识别的模型先放一放。

## 准备工作
### 获取数据
政府工作报告[百度网盘地址](https://pan.baidu.com/s/1hs0CpgC) 密码:i667

### 代码说明
为了我的毕业论文的保密性，此项目的代码我暂时不挂出来，我尝试着把它写成一个像论文的东东。

## 摘要

## 引言

## 主题模型确定精神变迁话题线

### 数据的收集与整理
自新中国成立以来，国务院并非每年都发布政府工作汇报。从1950年开始，应该每年都有一次政
府工作汇报，但是1953年之前，政府处于初创，百废待兴，更重要的是人民代表大会还没有成立，政府结构和程序还处于摸索阶段，
所以这段时间政府并没有成型的工作汇报文本。另外1961-1963年国家经历的所谓的三年自然灾害，政府工作会议因此无法正常举行，
1965-1977年，国务院仅在1975年由国务院总理周恩来发布过一次工作汇报，这一阶段一共发生了十年动乱的文革，76年和77年毛周朱
相继去世，政府工作处于非正常时期，因此也没进行政府工作汇报。
  

### 选择统计量
主题模型主要以以下三个统计量为基础来进行统计和建模过程，词频（TF）
#### TF
TF 是英语单词 Term Frequency的缩写，用中文可以表达为词频，和字面上的意思一样，这个统计量的作用就统计每个词在文档中出现的频率。
数学公式为：
#### IDF
IDF既 Inverse Document Frequency，中文翻译为逆文档频率，概括来讲， IDF反应了一个词在所有文本中出现的频率，如果一个词在很多的文本中出现，那么它的IDF值应该低。
比如在两会的开始，主讲人经常会说“各位代表”这样的敬语，那“各位代表”这个词在语料库中的IDF就非常低。
#### TF-IDF
### 主题模型简介

### 参数估计

#### Gibbs抽样

#### 确定主题数

## 用层次聚类分析政府报告相似度

### 聚类分析方法概论

### 数据预处理-选择变量

### 文章之间的距离计算方法

### 确定聚类数量

## 政府各个时期精神面貌关键词展示

## 参考文献