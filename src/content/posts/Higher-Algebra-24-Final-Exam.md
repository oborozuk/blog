---
title: 2024 高等代数上期末考
published: 2025-01-06
description: 2024 高等代数上期末考 试题及答案
tags: [高等代数, 答案]
category: 数学
draft: false
---

**建议使用电脑访问**

## 第一题
### 题目
求多项式 $u(x), v(x)$，使
$$
(f(x), g(x)) = u(x)f(x) + v(x)g(x) \,,
$$
这里
$$
\begin{align*}
f(x) &= x^4 + 2 x^3 - x^2- 4 x - 2 \,, \\
g(x) &= x^4 + x^3 - x^2 - 2 x - 2 \,.
\end{align*}
$$

### 答案
$$
\begin{align*}
(f(x), g(x)) &= x + 2 \,, \\
u(x) &= - x - 1 \,, \\
v(x) &= x + 2 \,.
\end{align*}
$$

## 第二题
### 题目
将多项式 $x^4 + 4$ 分别在实数域和复数域上做因式分解.

### 答案
实数域：
$$
x^4 + 4 = (x^2 - 2x + 2) (x^2 + 2x + 2)
$$
复数域：
$$
x^4 + 4 = (x + 1 + i) (x - 1 + i) (x + 1 - i) (x - 1 - i)
$$

## 第三题
### 题目
计算行列式的值：

1) 
   $$
   \begin{vmatrix}
   a & b & c & d \\
   a & a+b & a+b+c & a+b+c+d \\
   a & 2a+b & 3a+2b+c & 4a+3b+2c+d \\
   a & 3a+b & 6a+3b+c & 10a+6b+3c+d
   \end{vmatrix}
   $$
2) 
   $$
   d_n = \begin{vmatrix}
   1 & a_1 & a_1^2 & \cdots & a_1^{n-2} & a_1^{n-1}+\frac{1}{a_1} \\
   1 & a_2 & a_2^2 & \cdots & a_2^{n-2} & a_2^{n-1}+\frac{1}{a_2} \\
   1 & a_3 & a_3^2 & \cdots & a_3^{n-2} & a_3^{n-1}+\frac{1}{a_3} \\
   \vdots & \vdots & \vdots & \ddots & \vdots & \vdots \\
   1 & a_{n-1} & a_{n-1}^2 & \cdots & a_{n-1}^{n-2} & a_{n-1}^{n-1}+\frac{1}{a_{n-1}} \\
   1 & a_n & a_n^2 & \cdots & a_n^{n-2} & a_n^{n-1}+\frac{1}{a_n} \\
   \end{vmatrix}
   $$

### 答案
1. $a^4$
2. 
   $$
   d_n = (1 + (-1)^{n-1} \prod_{i=1}^n \frac1{a_i}) \prod_{1 \le i \lt j \le n}(a_j - a_i) \,.
   $$
   
## 第四题
### 题目
$$
f(x) = a_0 + a_1 x + a_2 x^2 + a_3 x^3 \,.
$$
已知 $f(-1) = 0, f(1) = 6, f(2) = 21, f(3) = 52$，求 $f(x)$.

### 答案
$$
f(x) = 1 + 2 x + 2 x^2 + x^3 \,.
$$

## 第五题
### 题目
求向量组
$$
\alpha_1 = \begin{pmatrix}
1 \\ -1 \\ 2 \\ 4
\end{pmatrix},
\alpha_2 = \begin{pmatrix}
0 \\ 3 \\ 1 \\ 2
\end{pmatrix},
\alpha_3 = \begin{pmatrix}
3 \\ 0 \\ 7 \\ 14
\end{pmatrix},
\alpha_4 = \begin{pmatrix}
1 \\ -1 \\ 2 \\ 0
\end{pmatrix},
\alpha_5 = \begin{pmatrix}
2 \\ 1 \\ 5 \\ 6
\end{pmatrix},
$$
的秩和一个极大线性无关组，并用它表出剩下的向量.

### 答案
秩为 $4$，
一个极大线性无关组为
$$
\alpha_1, \alpha_2, \alpha_4, \alpha_5
$$
剩下的向量可以由这个极大线性无关组线性表出：
$$
\alpha_3 = 3 \alpha_1 + \alpha_2
$$

## 第六题
### 题目
解矩阵方程：
$$
\begin{pmatrix}
2 & 2 & 3 \\
1 & -1 & 0 \\
1 & 2 & -1
\end{pmatrix}
X = \begin{pmatrix}
1 & -1 & 1 \\
1 & 1 & 0 \\
2 & 1 & 1
\end{pmatrix}
$$

### 答案
$$
X = \begin{pmatrix}
-9 & -8 & -2 \\
-10 & -9 & -2 \\
13 & 11 & 3
\end{pmatrix}
$$

## 第七题
### 题目
已知向量组 $\alpha_1, \alpha_2, \cdots, \alpha_s; \beta_1, \beta_2, \cdots, \beta_t; \alpha_1, \alpha_2, \cdots, \alpha_s, \beta_1, \beta_2, \cdots, \beta_t$ 的秩分别为 $r_1, r_2, r_3$.

证明：
$$
max\{r_1, r_2\} \le r_3 \le r_1 + r_2 \,.
$$

### 答案
略.

## 第八题
### 题目
1) 已知 $A, B$ 为 $n$ 阶可逆矩阵，证明：$(AB)^* = B^* A^*$；
2) 设 $P(i,j), P(i, j(c)), P(i(c))$ （$c \neq 0$）为三种初等矩阵，证明：
   $$
   P(i,j) = P(j(-1))P(i,j(1))P(j,i(-1))P(i,j(1)) \,.
   $$

### 答案
1) 
   因为 $A, B$ 可逆，所以 $|AB| = |A| |B| \neq 0$，所以 $AB$ 可逆.
   $$
   (AB)^* = |AB| (AB)^{-1} = |A| |B| B^{-1} A^{-1} = B^* A^* \,,
   $$
   所以 $(AB)^* = B^* A^*$.
1) 略.
