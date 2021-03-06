---
title: "[머신러닝] 몬테카를로 시뮬레이션(MCMC) 요약" 
categories:
  - machine-learning
tags:
  - machine-learning
use_math: true
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
sidebar:
  title: "AI Machine Learning"
  nav: sidebar-contents
---


# 몬테카를로 시뮬레이션(Markov Chain Monte Carlo Method) 요약

## 2. Simple Monte Carlo

### 2.1 Accuracy of simple Monte Carlo

몬테카를로의 목적은 표본평균을 이용해 모평균을 추정하는 것이다. 
우리는 우리가 알기 원하는 확률변수 $$Y$$의 평균을 $$\mu = E(Y)$$로 표현한다. 
그리고나서 $$Y$$의 분포에서 iid(Independent and Identically Distributed)를 만족하는 $$Y_1, \dots , Y_n$$을 생성한다. 
그리고 생성된 표본평균을 이용해 모평균을 $$\mu$$를 추정한다. 표본평균은 아래 식을 이용해 구한다. 

$$\hat{\mu}_n = \frac{1}{n}\sum_{i=1}^{n}Y_i$$

이떄 $$\hat{\mu}_n$$ 또한 확률변수이므로 평균과 분산을 갖는다. $$\hat{\mu}_n$$의 평균과 분산은 아래와 같이 구한다. 
<br />

$$E(\hat{\mu}_n) = \frac{1}{n}\sum_{i=1}^{n}E(Y_i) = \mu$$
<br />

$$Var(\hat{\mu}_n) = E((\hat{\mu}_n - \mu)^2) = \frac{\sigma^2}{n}$$
<br />

### 2.2 Error estimation

### 2.3 Safely computing the standard error

### 2.4 Estimating probabilities

### 2.5 Estimating quantiles

### 2.6 Random sample size

### 2.7 Estimating ratios

### 2.8 When Monte Carlo fails






