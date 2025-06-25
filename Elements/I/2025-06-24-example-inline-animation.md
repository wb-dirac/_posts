---
layout: post
title: 作正三角形（内联动画版本）
category: 欧式几何
tags: [几何作图,几何原本卷I,欧式几何,内联动画]
description: 演示如何在文章中嵌入内联动画的示例
has_main_animation: false
---

## 问题描述

设AB是给定的有限直线。

于是，要求在直线AB上作一个等边三角形。

## 解决步骤

### 步骤1：作第一个圆

以A为圆心、AB为距离作圆BCD；

{% include inline_animation.html name="circle-step1" caption="以A为圆心、AB为半径作圆" %}

根据[公设3]，我们可以以任意点为圆心、任意距离为半径作圆。

### 步骤2：作第二个圆

再以B为圆心、BA为距离作圆ACE；

{% include inline_animation.html name="circle-step2" width="400" height="300" caption="以B为圆心、BA为半径作圆" %}

同样根据[公设3]，我们作第二个圆。

### 步骤3：连接交点

从两圆的交点C到点A、点B连直线CA、CB。

{% include inline_animation.html name="connect-intersection" caption="连接交点C与A、B" %}

根据[公设1]，我们可以连接任意两点。

## 证明

现在，由于点A是圆CDB的圆心，所以AC等于AB。

[圆的定义]

又，由于点B是圆CAE的圆心，所以BC等于BA。

[圆的定义]

但已证明，CA也等于AB；

因此，直线CA、CB中的每一条都等于AB。

而等于同量的量也彼此相等；

[等量传递假设]

因此，CA也等于CB。

因此，三条直线CA、AB、BC彼此相等。

因此，三角形ABC是等边的；且它是在给定的有限直线AB上作的。

这就是所要作的。（Q.E.F.） 