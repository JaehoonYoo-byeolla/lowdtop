---
title: Unknot surgery
draft: true
tags:
  - Surgery
  - Max_Dehn
  - Dehn
  - Mapping_Class_Group
  - MCG
  - Heegaard
aliases: 
permalink: /
description: Dehn Surgery to unknow
date: 2025-02-14
---
 Let's start with the review of basic ~~Algebraic Topology~~.

# Introduction
 $\mathbb{S}^{3}$ and $\mathbb{S}^{2} \times \mathbb{S}^{1}$ are two solid tori
We can decompose $S^{3}$ as two solid tori.

$$\mathbb{S}^{3} = \partial D^{4} = D^{2}\times \mathbb{S}^{1} \sqcup \mathbb{S}^{1}\times D^{2}= U \sqcup V$$

Denote the first solid torus as $U$ and the other one as $V$. 
Let's view in the reverse way. We can get $\mathbb{S}^{3}$ through gluing two solid tori. 

However, we also can get 
$$\mathbb{S}^{2} \times \mathbb{S}^{1} = D^{2} \times \mathbb{S}^{1} \cup D^{2}\times \mathbb{S}^{1}.$$

%% We need to clarify the attaching maps. To make more precise, let's write in the following ways.

$$\mathbb{S}^{3} = \partial D^{4} = D_{11}^{2}\times \mathbb{S}_{11}^{1} \cup \mathbb{S}_{12}^{1}\times D_{12}^{2}= D_{11}^{2}\times \partial D_{12} \sqcup \partial D_{11}^{1}\times D_{12}^{2}$$
 and 
$$\mathbb{S}^{1} \times \mathbb{S}^{2} = D^{2}_{21}\times \mathbb{S}^{1}_{21} \cup \mathbb{S}^{1}_{22} \times D^{2}_{22}.$$

 %%
So, we need to clarify the attaching maps.

# Using Framed Link
If we use the [[Knots in the Solid Torus|framed link]], we can easily distinguish them. Let's consider the framed unknot $K\subset \mathbb{S}^{3}$. 
Since it is a framed unknot, which has a meridian and preferred longitude. 

Let's think the core of $U$ and $V$, as tubular neighborhoods of the framed unknots.
$$\mathbb{S}^{3} = \partial D^{4} = D_{11}^{2}\times \mathbb{S}_{11}^{1} \cup \mathbb{S}_{12}^{1}\times D_{12}^{2}= D_{11}^{2}\times \partial D_{12} \sqcup \partial D_{11}^{1}\times D_{12}^{2}= U \sqcup V$$
We can cut $\mathbb{S}^{3}$ along $U$ then can get $V$, which means $\mathbb{S}^{3}  \setminus U=V$.

Let change the view point. To get $S^{3}$, we are gluing $U$ to $V$. So it is enough to determine how to glue the meridian $\mu$ of $U$ to longitude $l$ and meridian $m$ of $V$.
More specifically, $a$ times to $l$, $b$ times to $m$. Using universal cover argument, we can denote as a tuple $\left(a,b\right)$^[1] such as $a=b=0$ or gcd$\left(a,b\right)=1$. 

Define the ***surgery coefficient*** as $a/b \in \mathbb{Q} \cup \left\{\infty\right\}$. 

So, if the surgery coefficient is $\infty$, it means gluing $U$ exactly same as the decomposition of $S^{3}$.
On the other hand, if the surgery coefficient 0, attach meridian to the longitude of $V$.

# Appendix
More generally we called the [Dehn Surgery](https://en.wikipedia.org/wiki/Dehn_surgery)

[1]: The first coordinate means longitude and the other one is meridian.
