---
title: 视觉SLAM十四讲笔记（二）——三维刚体运动
date: 2021-03-09 22:07:07
tags: VSLAM
---

## 旋转向量

三维空间内的坐标都可以用$R^{3}$表示。假设在线性空间内，我们找到了该空间的一组基($e_1$,
$e_2$, $e_3$),那么任意向量a在该基下有一坐标：
$$
a = 
\begin{bmatrix}
e_1, & e_2, & e_3
\end{bmatrix}
\begin{bmatrix}
a_1 \\\\
a_2 \\\\
a_3
\end{bmatrix}=a_1e_1+a_2e_2+a_3e_3.
$$

> 反对称矩阵
> $a \times b$ = $a$ ^ $b$ 
> $a$^ 为反对称矩阵（Skew-symmetric Matrix）。
> 该反对称符号一一映射。
> $$
> a\^{} =
\begin{bmatrix}
 0 & -a_3 & a_2\\\\
 a_3 & 0 & -a_1\\\\
 -a_2 & a_1 & 0
\end{bmatrix}
> $$

## 旋转向量和欧拉角

## 四元数

## 相似、仿射、射影变换
