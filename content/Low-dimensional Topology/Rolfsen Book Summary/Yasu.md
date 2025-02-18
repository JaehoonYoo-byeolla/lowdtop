---
title: 문방구 불량식품
draft: true
tags: 
aliases: 
permalink: /
description: 멘탈 터져서 갈아엎음
date: 2025-02-14
---
$S^{3}$이  Solid Torus $S^{1} \times D^{2}$ 두개로 분리가 된다~~는 사실은 매우 잘 알려진 사실이다~~.
하지만 분리가 되고 다시 붙일 때 어디가 떨어지고 어디가 붙는지는 매우 중요하다. $\partial D^{2} = S^{1}$ 을 고려해서 $S^{3}$을 분리하면 파란색 부분은 파란색 부분끼리, 빨간색부분은 빨간색 부분끼리 붙는다. 첫번째 그림에서는 $S^{3}$ 을 분리하는 정보, 또는 두 solid torus를 붙여 $S^{3}$를 만드는 정보이다.[^1]
![[public/Untitled/S3surgery.jpeg]]


다음 그림은 붙이는 정보를 바꾼 것이다. $S^{1}$은 $S^{1}$끼리, $D^{2}$는 $D^{2}$의 boundary끼리. 이 정보를 토대로 붙이면 $S^{1} \times S^{2}$를 얻을 수 잇다. 
![[public/Untitled/s1s2.jpeg|picture]]

그렇다면 다음과 같은 생각을 해볼 수 있다.
> $S^{3}$에서 solid torus를 잘라내어 solid torus를 붙이는 정보를 다르게 하면 다른 3차원 다양체를 얻을 수 있지 않을까?

[[Dehn Surgery]]가 그 답을 준다.

왼쪽의 그림에서 빨간색을 torus의 meridian 파란색을 longitude라고 하자.[^2][^3]
# Dehn Surgery on unknot
[[(Dehn) surgery to unknot|Dehn Surgery]]의 아이디어는 위의 예시와 비슷하다. 위 그림들처럼 $S^{3}$에서 왼쪽의 solid torus를 잘라내고, meridian을 새로운 meridian과 longitude에 맞게 torus를 변형한다. 예를 들어 다음같은 형태로도 변형할 수 있다.
![[public/Untitled/trefoildsolid.jpeg]]

이 빨간선을 원래 잘라낸 정보인 왼쪽의 빨간선에 맞춰 다시 붙여 새로운 3 차원 다양체를 얻는다. 

이러한 행위 자체를 Dehn Surgery라고 한다.


[^1]: ~~왜인지는 $S^{3}=\partial D^{4}$를 잘 생각해보자~~ 

[^2]: [[Knots in the Solid Torus]] 만들다가 멘탈 터져서 대충 적습니다. 조만간에 as를..

[^3]:  Meridian은 solid torus에서 unique up to ambienty isotopy of solid torus.
