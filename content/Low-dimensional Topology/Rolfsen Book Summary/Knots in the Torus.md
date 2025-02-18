---
title: Knots in the Torus
draft: false
tags:
  - Torus
  - Torus_knot
  - meridian
  - longitude
aliases: 
permalink: /
description: asdf
date: 2025-02-19
---
>[!warning]
 >It is different with the ***[[Knots in the Solid Torus]]***. 

---
# Knot types of $\mathbb{S}^{1}$ in $\mathbb{T}^{2}$
This is a spoiler of this page.

There are only two knot types of $S^{1} \subset T^{2}$[^1]. 
The one is the $J$ separates $T^{2}$, which is null-homotopic in the torus[^2], we call it as **inessential** . 

The other one is the $M$, which is not null-homotopic, we call it as **essential**.[^11]

![[Two knot types in the torus.png]][^3][^4]
---
# Longitude-Meridian Basis
We know that $\pi_{1}\left(T^{2}\right)=H_{1}\left(T^{2}\right)= \mathbb{Z} \oplus \mathbb{Z}$. 
From the universal covering, we can easily can get those generators can be matched to the longitude and meridian generators.

Well, we need a formal definition of the meridian and longitude. However, the following arguments seem quite reasonable. Let's define $\left(e^{i\theta}, 1\right)$ is longitude, and $\left(1, e^{i\phi}\right)$ is the meridian.[^5]

Since the fundamental group is an abelian group. Let's take the basis for each, longitude to $\left(1, 0\right)$ and meridian to $\left(0,1\right)$. Then we can like the loop as $\left(a, b\right)$. I am going to use as a homologically and fundamental group wise back and forth.

## Lift it!
### Universal Cover
Well known fact! The $\mathbb{R}^{2} = \mathbb{C}$ is the universal cover of the $\mathbb{T}^{2}$. Then we can make a correspondence to $x$-axis to longitude and $y$-axis to meridian. From this argument, we can write a loop presentation simply.
> In $\left(a, b\right)$, $a=b=0$ or $\text{gcd}\left(a,b\right)=1$. 

### Another covering space
We have another covering space $\mathbb{C}\setminus\left\{0\right\}$ with a map $q:\mathbb{C}\setminus\left\{0\right\} \to \mathbb{T}^{2}$ such that $q\left(re^{i \theta}\right)=\left(e^{i \text{ln}r}, e^{i\theta}\right)$. 

Using this covering map, we can prove the following statement. 
>If two disjoint knot $K$ and $K^{\prime}$ are disjoint knots of class $\left(0,\pm 1\right)$[^6], then there is an ambient isotopy of $T^{2}$ taking $K$ to $K^{\prime}$.

Also,
> If the knot $K$ is of class $\left(0, \pm1\right)$ and intersect the meridian $M$ transversally in a finite number of points. Then $K$ and $M$ are ambient isotopic in $\mathbb{T}^{2}$.

These imply that ==any two knots in $T^{2}$ of class $\left(0, \pm1\right)$, are ambient isotopic in $T{^2}$. ==[^7]

>[!Theorem]
>So, there is the only isotopy class of a meridian, i.e. meridian is unique up to isotopy.

---
# We can make $\left(a,b\right)$ to $\left(0,d\right)$
Now, we know that there is the only isotopy class of the meridian. It means it is important.[^8] 

There are two **twists** which are self-homeomorphism of $\mathbb{T}^{2}$.
$$h_{L}\left(e^{i\theta}, e^{i\phi}\right) = \left(e^{i\left(\theta + \phi\right)}, e^{i\phi}\right)$$
and 

$$h_{M}\left(e^{i\theta}, e^{i\phi}\right) = \left(e^{i\theta}, e^{\left(\theta + \phi\right)}\right)$$

Those are ''longitudinal twist'' and ''meridinal twist''. The name **twists** seem fair.

These induces the isomorphism, more preciesely automorphism, of $\pi_{1}\left(\mathbb{T}^{2}\right)$. 


$$
h_{L_{\ast}} =
\begin{bmatrix}
1 & 0\\
1 & 1
\end{bmatrix}
, \quad
h_{M_{\ast}}=
\begin{bmatrix}
1 & 1\\
0 & 1
\end{bmatrix}.
$$



$$h_{L_{\ast}} \ h_{M_{\ast}} \in \text{Aut}\left(\pi_{1}\left(\mathbb{T}^{2}\right), \mathbb{Z}\right)=GL\left(2, \mathbb{Z}\right).$$
Using these twists, we can twist a longitude $\left(1, 0\right)$ to the meridian $\left(0,1\right)$.[^9][^10]

>[!Theorem]
>So, we can find a group homomorphism $h: \mathbb{T}^{2} \to \mathbb{T}^{2}$, which is compositie of twists, satisfying $h_{\ast}\left(a,b\right) = \left(0, d\right)$. Moreover, $d = \pm\left(\text{gcd}\left(a,b\right)\right)$ unless $a=b=0$.

>[!Corollary]
>Through these two theorems, for any knot $K\subset \mathbb{T}^{2}$ of class is not $\left(0,0\right)$, there is a homeomorphism $h:\mathbb{T}^{2} \to \mathbb{T}^{2}$ such that $h\left(K\right) = M$, the standard meridian.

---
# Trace of the standard meridian
Finally, we can prove the [[Knots in the Torus#Knot types of $ mathbb{S} {1}$ in $ mathbb{T} {2}$|first part]].
All the essential knot can be transformed to the standard meridian which is unique up to ambient isotopy. 

Also, the standard meridian does not separate the torus. So, essential knots do not separate the torus, the other one does.

So, there are only two types of knot in the torus, they are essential and inessential.

---
---

[^1]: Up to homeomorphism

[^2]: Not a solid torus.

[^3]: Figure from the Rolfsen Knots and Links

[^4]: This is just an example, $M$ could be the other shape.

[^5]: In non-mathematically, seems like meridian is the meridian and the other one is longitude.

[^6]: It is a homologically.

[^7]: I skipped a lot of proofs. However, the conclusion is, if it seems like, then it is.

[^8]: ~~If it were not, we do not care.~~

[^9]: Remark : It is not a swap. (1,0) -> (1, 1) -> (1-1, 1) = (0,1). Because of the continuity of $h$.

[^10]: So, it is a good chance link between [Dehn Twist](https://en.wikipedia.org/wiki/Dehn_twist) to the meridian with [[Mapping Class Group]]. 

[^11]: This will be important part to the [[Satellite Knot]].
