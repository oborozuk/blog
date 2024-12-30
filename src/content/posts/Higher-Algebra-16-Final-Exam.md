---
title: 2016 高等代数上期末考
published: 2024-12-30
description: 2016 高等代数上期末考 试题及答案
tags: [高等代数, 答案]
category: 数学
draft: true
---

[题目来源](https://github.com/tianyilt/ecust-CourseShare/blob/master/%E6%95%B0%E5%AD%A6%E5%AD%A6%E9%99%A2/%E5%BF%85%E4%BF%AE%E8%AF%BE%E7%A8%8B/%E5%A4%A71%E4%B8%8A_%E9%AB%98%E7%AD%89%E4%BB%A3%E6%95%B0%E4%B8%8A/%E8%80%83%E8%AF%95/%E6%9C%9F%E6%9C%AB/2016%E9%AB%98%E7%AD%89%E4%BB%A3%E6%95%B0%E6%9C%9F%E6%9C%AB%E5%8D%B7.jpg)
**建议使用电脑访问**

# 第一题
## 题目
对
$$
\begin{align*}
f(x) &= x^4 + 4 x^3 + 4 x^2 + x + 2 \,, \\
g(x) &= x^3 + 2 x^2 + x + 2 \,,
\end{align*}
$$
求 $(f(x), g(x))$，并求多项式 $u(x), v(x)$，使得
$$
(f(x), g(x)) = u(x)f(x) + v(x)g(x) \,.
$$

## 答案
$$
\begin{align*}
(f(x), g(x)) &= x + 2 \,, \\
u(x) &= \frac12 x - \frac12 \,, \\
v(x) &= - \frac12 x^2 - \frac12 x + \frac32 \,.
\end{align*}
$$

## 解析
使用辗转相除法.

$$
f(x) = (x + 2) g(x) + (- x^2 - 3 x - 2) \,, \\
g(x) = (1 - x) (- x^2 - 3 x - 2) + (2 x + 4) \,, \\
- x^2 - 3 x - 2 =  (- \frac12 x - \frac12)(2 x + 4) \,,
$$

因此
$$
(f(x), g(x)) = x + 2 \,.
$$
而
$$
\begin{align*}
2 x + 4 &= g(x) - (1 - x) (- x^2 - 3 x - 2) \\
&= g(x) - (1 - x) (f(x) - (x + 2) g(x)) \\
&= (x - 1) f(x) + (- x^2 - x + 3) g(x) \,,
\end{align*}
$$
于是，令 $u(x) = \frac12 x - \frac12, v(x) = - \frac12 x^2 - \frac12 x + \frac32$，就有
$$
(f(x), g(x)) = u(x)f(x) + v(x)g(x) \,.
$$

# 第二题
## 题目
将多项式 $x^8 - 1$ 分别在有理数域、实数域、复数域上因式分解.

## 答案
有理数域：
$$
x^8 - 1 = (x - 1)(x + 1)(x^2 + 1)(x^4 + 1)
$$
实数域：
$$
x^8 - 1 = (x - 1)(x + 1)(x^2 + 1)(x^2 - \sqrt2 x + 1)(x^2 + \sqrt2 x + 1)
$$
复数域：
$$
\begin{align*}
x^8 - 1 = &(x - 1)(x + 1)(x - i)(x + i)(x - \frac{\sqrt2}{2} - \frac{\sqrt2}{2} i) \cdot \\
&(x - \frac{\sqrt2}{2} + \frac{\sqrt2}{2} i) (x + \frac{\sqrt2}{2} - \frac{\sqrt2}{2} i) (x + \frac{\sqrt2}{2} + \frac{\sqrt2}{2} i)
\end{align*}
$$

# 第三题
## 题目
计算行列式的值：

1) 
   $$
   \begin{vmatrix}
   a^2 & (a+1)^2 & (a+2)^2 & (a+3)^2 \\
   b^2 & (b+1)^2 & (b+2)^2 & (b+3)^2 \\
   c^2 & (c+1)^2 & (c+2)^2 & (c+3)^2 \\
   d^2 & (d+1)^2 & (d+2)^2 & (d+3)^2 
   \end{vmatrix}
   $$
2) 
   $$
   \begin{vmatrix}
   2 & 2 & \cdots & 2 & 2 & n \\
   2 & 2 & \cdots & 2 & n & 2 \\
   2 & 2 & \cdots & n & 2 & 2 \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   n & 2 & \cdots & 2 & 2 & 2
   \end{vmatrix}
   $$

## 答案
1. $0$
2. $(3 n - 2) (n - 2)^{n - 1}$

## 解析
1) 
   $$
   \begin{align*}
   \begin{vmatrix}
   a^2 & (a+1)^2 & (a+2)^2 & (a+3)^2 \\
   b^2 & (b+1)^2 & (b+2)^2 & (b+3)^2 \\
   c^2 & (c+1)^2 & (c+2)^2 & (c+3)^2 \\
   d^2 & (d+1)^2 & (d+2)^2 & (d+3)^2 
   \end{vmatrix}
   &\xlongequal{\text{c}_2-\text{c}_1, \text{c}_3-\text{c}_1, c_4-\text{c}_1}
   \begin{vmatrix}
   a^2 & 2a+1 & 4a+4 & 6a+9 \\
   b^2 & 2b+1 & 4b+4 & 6b+9 \\
   c^2 & 2c+1 & 4c+4 & 6c+9 \\
   d^2 & 2d+1 & 4d+4 & 6d+9 
   \end{vmatrix} \\
   &\xlongequal{\text{c}_3+3\text{c}_2, \text{c}_3-3\text{c}_1}
   \begin{vmatrix}
   a^2 & 2a+1 & 4a+4 & 0 \\
   b^2 & 2b+1 & 4b+4 & 0 \\
   c^2 & 2c+1 & 4c+4 & 0 \\
   d^2 & 2d+1 & 4d+4 & 0 
   \end{vmatrix} = 0
   \end{align*}
   $$
2) 
   $$
   \begin{align*}
   \begin{vmatrix}
   2 & 2 & \cdots & 2 & 2 & n \\
   2 & 2 & \cdots & 2 & n & 2 \\
   2 & 2 & \cdots & n & 2 & 2 \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   n & 2 & \cdots & 2 & 2 & 2
   \end{vmatrix} 
   &= \begin{vmatrix}
   2 & 2 & \cdots & 2 & 2 & 2(n-1)+n \\
   2 & 2 & \cdots & 2 & n & 2(n-1)+n \\
   2 & 2 & \cdots & n & 2 & 2(n-1)+n \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   n & 2 & \cdots & 2 & 2 & 2(n-1)+n
   \end{vmatrix} \\
   &= (3n-2)^n
   \begin{vmatrix}
   2 & 2 & \cdots & 2 & 2 & 1 \\
   2 & 2 & \cdots & 2 & n & 1 \\
   2 & 2 & \cdots & n & 2 & 1 \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   n & 2 & \cdots & 2 & 2 & 1
   \end{vmatrix} \\
   &= (3n-2)^n
   \begin{vmatrix}
   0 & 0 & \cdots & 0 & 0 & 1 \\
   0 & 0 & \cdots & 0 & n-2 & 1 \\
   0 & 0 & \cdots & n-2 & 0 & 1 \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   \vdots & \vdots &  & \vdots & \vdots & \vdots \\
   n-2 & 0 & \cdots & 0 & 0 & 1
   \end{vmatrix} \\
   &\xlongequal{\text{按第一行展开}} (-1)^{n+1} (3n-2)^n 
   \begin{vmatrix}
   0 & 0 & \cdots & 0 & n-2 \\
   0 & 0 & \cdots & n-2 & 0 \\
   \vdots & \vdots &  & \vdots & \vdots \\
   \vdots & \vdots &  & \vdots & \vdots \\
   n-2 & 0 & \cdots & 0 & 0
   \end{vmatrix}_{n-1} \\
   &= (-1)^{n + 1} (3n - 2)^n \cdot (-1)^{\frac{(n-1)(n-2)}{2}} (n - 2)^{n - 1} \\
   &= (3n - 2)^n (n - 2)^{n - 1}
   \end{align*}
   $$

# 第四题
## 题目
求线性方程组的通解：
$$
\left\{
\begin{array}{l}
    x_1 - 2 x_2 + 3 x_3 -   x_4 = 1 \\
  3 x_1 - 5 x_2 + 5 x_3 - 3 x_4 = 2 \\
  2 x_1 - 3 x_2 + 2 x_3 - 2 x_4 = 1
\end{array}
\right.
$$
## 答案

# 第五题
## 题目

## 答案

## 解析

# 第六题
## 题目

## 答案

## 解析
