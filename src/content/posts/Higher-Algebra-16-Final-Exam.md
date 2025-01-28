---
title: 2016 高等代数上期末考
published: 2024-12-31
description: 2016 高等代数上期末考 试题及答案
tags: [高等代数, 答案]
category: 数学
draft: false
---

[题目来源](https://github.com/tianyilt/ecust-CourseShare/blob/master/%E6%95%B0%E5%AD%A6%E5%AD%A6%E9%99%A2/%E5%BF%85%E4%BF%AE%E8%AF%BE%E7%A8%8B/%E5%A4%A71%E4%B8%8A_%E9%AB%98%E7%AD%89%E4%BB%A3%E6%95%B0%E4%B8%8A/%E8%80%83%E8%AF%95/%E6%9C%9F%E6%9C%AB/2016%E9%AB%98%E7%AD%89%E4%BB%A3%E6%95%B0%E6%9C%9F%E6%9C%AB%E5%8D%B7.jpg)

**建议使用电脑访问**

## 第一题
### 题目
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

### 答案
$$
\begin{align*}
(f(x), g(x)) &= x + 2 \,, \\
u(x) &= \frac12 x - \frac12 \,, \\
v(x) &= - \frac12 x^2 - \frac12 x + \frac32 \,.
\end{align*}
$$

### 解析
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

## 第二题
### 题目
将多项式 $x^8 - 1$ 分别在有理数域、实数域、复数域上因式分解.

### 答案
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

## 第三题
### 题目
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

### 答案
1. $0$
2. $(3 n - 2) (n - 2)^{n - 1}$

### 解析
1) 
   $$
   \begin{align*}
   \begin{vmatrix}
   a^2 & (a+1)^2 & (a+2)^2 & (a+3)^2 \\
   b^2 & (b+1)^2 & (b+2)^2 & (b+3)^2 \\
   c^2 & (c+1)^2 & (c+2)^2 & (c+3)^2 \\
   d^2 & (d+1)^2 & (d+2)^2 & (d+3)^2 
   \end{vmatrix}
   &\xlongequal{\text{c}_2-\text{c}_1, \text{c}_3-\text{c}_1, \text{c}_4-\text{c}_1}
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

## 第四题
### 题目
求线性方程组的通解：
$$
\begin{equation*}
\left\{
\begin{aligned}
    x_1 &- 2 x_2 + 3 x_3 - x_4 &= 1 \\
    3 x_1 &- 5 x_2 + 5 x_3 - 3 x_4 &= 2 \\
    2 x_1 &- 3 x_2 + 2 x_3 - 2 x_4 &= 1
\end{aligned}
\right.
\end{equation*} \,.
$$

### 答案
通解为
$$
\begin{pmatrix}
0 \\ -1 \\ 0 \\ 1
\end{pmatrix}
+ k_1 
\begin{pmatrix}
5 \\ 4 \\ 1 \\ 0
\end{pmatrix}
+ k_2
\begin{pmatrix}
1 \\ 0 \\ 0 \\ 1
\end{pmatrix} \,,
$$
其中 $k_1, k_2$ 为任意常数.

### 解析
$$
\overline{A} = 
\begin{pmatrix}
1 & -2 & 3 & -1 & 1 \\
3 & -5 & 5 & -3 & 2 \\
2 & -3 & 2 & -2 & 1
\end{pmatrix}
\rightarrow
\begin{pmatrix}
1 & -2 & 3 & -1 & 1 \\
0 & 1 & -4 & 0 & -1 \\
0 & 1 & -4 & 0 & -1
\end{pmatrix} \\
\rightarrow
\begin{pmatrix}
1 & -2 & 3 & -1 & 1 \\
0 & 1 & -4 & 0 & -1 \\
0 & 0 & 0 & 0 & 0
\end{pmatrix}
\rightarrow
\begin{pmatrix}
1 & 0 & -5 & -1 & -1 \\
0 & 1 & -4 & 0 & -1 \\
0 & 0 & 0 & 0 & 0
\end{pmatrix}
$$
所以同解方程组为
$$
\begin{equation*}
\left\{
\begin{aligned}
    x_1 &- 5 x_3 - x_4 &= -1 \\
    x_2 &- 4 x_3 &= -1
\end{aligned}
\right.
\end{equation*} \,.
$$
可得对应的齐次线性方程组的基础解系为
$$
\eta_1 =
\begin{pmatrix}
5 \\ 4 \\ 1 \\ 0
\end{pmatrix}
\,, \quad
\eta_2 =
\begin{pmatrix}
1 \\ 0 \\ 0 \\ 1
\end{pmatrix} \,,
$$
原方程组的一个特解为
$$
\beta =
\begin{pmatrix}
0 \\ -1 \\ 0 \\ 1
\end{pmatrix} \,,
$$
所以原方程组的通解为
$$
\beta + k_1 \eta_1 + k_2 \eta_2 \,,
$$
即
$$
\begin{pmatrix}
0 \\ -1 \\ 0 \\ 1
\end{pmatrix}
+ k_1
\begin{pmatrix}
5 \\ 4 \\ 1 \\ 0
\end{pmatrix}
+ k_2
\begin{pmatrix}
1 \\ 0 \\ 0 \\ 1
\end{pmatrix} \,,
$$
其中 $k_1, k_2$ 为任意常数.

## 第五题
### 题目
已知向量组 $\alpha_1, \alpha_2, \cdots, \alpha_r, \beta$ 的秩为 $r$，向量组 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma$ 的秩为 $r + 1$.

证明：
1) $\beta$ 能由 $\alpha_1, \alpha_2, \cdots, \alpha_r$ 唯一线性表出；
2) 向量组 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma - \beta$ 线性无关.

### 答案
1) 因为向量组 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma$ 的秩为 $r + 1$，所以向量组 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma$ 线性无关，于是 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma$ 线性无关.

   因为向量组 $\alpha_1, \alpha_2, \cdots, \alpha_r, \beta$ 的秩为 $r$， $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma$ 线性相关，所以 $\gamma$ 可以由这个向量组的极大线性无关组 $\alpha_1, \alpha_2, \cdots, \alpha_r$ 线性表出.

   假设 $\beta = k_1 \alpha_1 + k_2 \alpha_2 + \cdots + k_r \alpha_r = l_1 \alpha_1 + l_2 \alpha_2 + \cdots + l_r \alpha_r$（$k_1, k_2, \cdots, k_r$ 和 $l_1, l_2, \cdots, l_r$ 是两组不全相同的常数），则 $(k_1 - l_1) \alpha_1 + (k_2 - l_2) \alpha_2 + \cdots + (k_r - l_r) \alpha_r = 0$，即 $\alpha_1, \alpha_2, \cdots, \alpha_r$ 线性相关，这与 $\alpha_1, \alpha_2, \cdots, \alpha_r$ 线性无关矛盾，所以 $\beta$ 可以由 $\alpha_1, \alpha_2, \cdots, \alpha_r$ 唯一线性表出.
2) 假设向量组 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma - \beta$ 线性相关，则存在不全为 $0$ 的常数 $k_1, k_2, \cdots, k_r, k_{r+1}$ 使得 $k_1 \alpha_1 + k_2 \alpha_2 + \cdots + k_r \alpha_r + k_{r+1} (\gamma - \beta) = 0$.

   因为 $\alpha_1, \alpha_2, \cdots, \alpha_r, \beta$ 线性相关，设 $\beta = l_1 \alpha_1 + l_2 \alpha_2 + \cdots + l_r \alpha_r$，则 $k_1 \alpha_1 + k_2 \alpha_2 + \cdots + k_r \alpha_r + k_{r+1} (\gamma - l_1 \alpha_1 - l_2 \alpha_2 - \cdots - l_r \alpha_r) = 0$，即 $(k_1 - k_{r+1} l_1) \alpha_1 + (k_2 - k_{r+1} l_2) \alpha_2 + \cdots + (k_r - k_{r+1} l_r) \alpha_r + k_{r+1} \gamma = 0$.
   
   因为 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma$ 线性无关，所以 $k_1 - k_{r+1} l_1 = k_2 - k_{r+1} l_2 = \cdots = k_r - k_{r+1} l_r = k_{r+1} = 0$，即 $k_1 = k_2 = \cdots = k_r = k_{r+1} = 0$，这与 $k_1, k_2, \cdots, k_r, k_{r+1}$ 不全为 $0$ 矛盾，所以 $\alpha_1, \alpha_2, \cdots, \alpha_r, \gamma - \beta$ 线性无关.

## 第六题
### 题目
已知向量
$$
\alpha_1 = \begin{pmatrix}
1 \\ 0 \\ 1 \\ 0 \\ 1
\end{pmatrix},
\alpha_2 = \begin{pmatrix}
0 \\ 1 \\ 0 \\ 1 \\ 0
\end{pmatrix},
\alpha_3 = \begin{pmatrix}
2 \\ 1 \\ 2 \\ 1 \\ 2
\end{pmatrix},
\alpha_4 = \begin{pmatrix}
2 \\ 1 \\ 0 \\ 1 \\ 2
\end{pmatrix},
$$
求向量组的一个极大线性无关组，并用它表出剩下的向量.

### 答案
一个极大线性无关组为
$$
\alpha_1, \alpha_2, \alpha_4
$$
剩下的向量可以由这个极大线性无关组线性表出：
$$
\alpha_3 = 2 \alpha_1 + \alpha_2
$$

### 解析
$$
\begin{pmatrix}
1 & 0 & 2 & 2 \\
0 & 1 & 1 & 1 \\
1 & 0 & 2 & 0 \\
0 & 1 & 1 & 1 \\
1 & 0 & 2 & 2
\end{pmatrix}
\rightarrow
\begin{pmatrix}
1 & 0 & 2 & 2 \\
0 & 1 & 1 & 1 \\
0 & 0 & 0 & -2 \\
0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0
\end{pmatrix}
\rightarrow
\begin{pmatrix}
1 & 0 & 2 & 0 \\
0 & 1 & 1 & 0 \\
0 & 0 & 0 & 1 \\
0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0
\end{pmatrix}
$$

## 第七题
### 题目
已知 $M = \begin{pmatrix}A & B \\ C & D \end{pmatrix}$，且 $A$ 可逆，证明：
$$
r(M) = r(A) + r(D - CA^{-1}B) \,.
$$

### 答案
对 $M$ 做初等变换，得到
$$
\begin{pmatrix}A & B \\ C & D \end{pmatrix}
\rightarrow
\begin{pmatrix}A & O \\ C & D - CA^{-1}B \end{pmatrix}
\rightarrow
\begin{pmatrix}A & O \\ O & D - CA^{-1}B \end{pmatrix}
$$
所以 $r(M) = r(A) + r(D - CA^{-1}B)$.

## 第八题
### 题目
1) 已知 $A, B$ 为 $n$ 阶可逆矩阵，证明：$(AB)^* = B^* A^*$；
2) 若 $A, B$ 不全可逆，上述结论成立吗？（不需要写出证明）

### 答案
1) 
   因为 $A, B$ 可逆，所以 $|AB| = |A| |B| \neq 0$，所以 $AB$ 可逆.
   $$
   (AB)^* = |AB| (AB)^{-1} = |A| |B| B^{-1} A^{-1} = B^* A^* \,,
   $$
   所以 $(AB)^* = B^* A^*$.
2) 成立.
