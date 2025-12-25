---
title: SDE
description: 这是一个副标题
date: 2025-11-29
slug: 随机微分方程
image: helena-hertz-wWZzXlDpMog-unsplash.jpg
categories:
    - Test
    - 测试
---

## 正文测试

&nbsp;&nbsp;&nbsp;&nbsp;本文主要参考港中深的暑期班讲义和Bernt的入门级教材，本人才疏学浅，也非概率或金融方向，内容仅供参考。
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;我们要研究如何求解以下形式的方程
$$ \dfrac{dX}{dt} = b(t,X_t) + \sigma(t,X_t)\cdot B_t
$$
其中b和$\sigma$是给定的函数。我们先考虑一维情况
<br/>
对于连续的鞅, 我们有如下重要的不等式(不加证明)。

>**Theorem(Doob's martingale inequality)**
<br/>
如果$M_t$是一个鞅, 使得$t \rightarrow M_t$是几乎处处连续的, 则对于任意的$p\geq 1$, $T\geq 0$和所有$\lambda> 0$ 
>$$P[\sup_{o\leq t\leq T} \lvert M_t\rvert\geq \lambda]\leq\dfrac{1}{\lambda^p}\cdot E[\lvert M_T\rvert^p]$$
我们将使用这个不等式证明, Ito积分
$$ \int_{0}^{t} f(s,\omega)\, dB_s $$ 
可以被选择成连续的依赖$t$. 
>**Theorem**
<br/>
令$f \in \nu(0,T)$, 则存在一个关于t连续版本的积分
>$$ \int_{0}^{t} f(s,\omega)\, dB_s; \quad 0\leq t\leq T. $$
>即存在一个概率空间$(\Omega,\mathcal{F},P)$上的t-连续随机过程$J_t$, 使得
>$$ P[J_t = \int_{0}^{t}f\,dB] = 1 \quad \text{for all} \,\,\,t,0\leq t\leq T $$

