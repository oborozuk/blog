---
title: 2023 高等代数上期中考
published: 2024-11-01
description: 2023 高等代数上期中考 试题及答案
tags: [高等代数, 答案]
category: 数学
draft: false
---

**建议使用电脑访问**

# 第一题
## 题目
对
$$
\begin{align*}
f(x) &= x^4 + x^3 - 3 x^2 - 4 x - 1 \,, \\
g(x) &= x^3 + x^2 - x - 1 \,,
\end{align*}
$$
求 $(f(x), g(x))$，并求多项式 $u(x), v(x)$，使得
$$
(f(x), g(x)) = u(x)f(x) + v(x)g(x) \,.
$$

## 答案
$$
\begin{align*}
(f(x), g(x)) &= x + 1 \,, \\
u(x) &= - \frac23 x + \frac13 \,, \\
v(x) &= \frac23 x^2 - \frac13 x - \frac43 \,.
\end{align*}
$$

## 解析
使用辗转相除法.

$$
f(x) = x g(x) + (- 2 x^2 - 3 x - 1) \,, \\
g(x) = (- \frac12 x + \frac14) (-2 x^2 - 3 x - 1) + (- \frac34 x - \frac34) \,, \\
- 2 x^2 - 3 x - 1 = (\frac83 x + \frac43) (- \frac34 x - \frac34) \,,
$$

因此
$$
(f(x), g(x)) = x + 1 \,.
$$
而
$$
\begin{align*}
- \frac34 x - \frac34 &= g(x) - (- \frac12 x + \frac14) (f(x) - x g(x)) \\
&= (\frac12 x - \frac14) f(x) + (- \frac12 x^2 + \frac14 x + 1) g(x) \,,
\end{align*}
$$
于是，令 $u(x) = - \frac23 x + \frac13, v(x) = \frac23 x^2 - \frac13 x - \frac43$，就有
$$
(f(x), g(x)) = u(x)f(x) + v(x)g(x) \,.
$$

# 第二题
## 题目
把 $x^4 + 1$ 在实数域及复数域上做因式分解.

## 答案
$$
x^4 + 1 = (x^2 + \sqrt{2}x + 1)(x^2 - \sqrt{2}x + 1) \,.
$$

## 解析
$$
\begin{align*}
x^4 + 1 &= x^4+ 2 x^2  + 1 - 2 x^2 \\
&= (x^2 + 1)^2 - (\sqrt{2}x)^2 \\
&= (x^2 + \sqrt{2}x + 1)(x^2 - \sqrt{2}x + 1) \,.
\end{align*}
$$
# 第三题
## 题目
多项式 $m(x)$ 称为多项式 $f(x), g(x)$ 的一个最小公倍式，如果
1) $f(x) \mid m(x), g(x) \mid m(x)$，
2) $f(x), g(x)$ 的任一公倍式都是 $m(x)$ 的倍式.

我们以 $[f(x), g(x)]$ 表示首项系数是 $1$ 的那个最小公倍式，证明：如果 $f(x), g(x)$ 的首项系数都是 $1$，那么
$$
[f(x), g(x)] = \frac{f(x)g(x)}{(f(x), g(x))} \,.
$$

## 答案
因为
$$
\frac{f(x)g(x)}{(f(x), g(x))} = f(x)\frac{g(x)}{(f(x), g(x))} = g(x)\frac{f(x)}{(f(x), g(x))} \,,
$$
所以 $\frac{f(x)g(x)}{(f(x), g(x))}$ 是 $f(x), g(x)$ 的公倍式.

如果 $h(x)$ 是 $f(x), g(x)$ 的一个公倍式，那么
$$
f(x) \mid h(x), g(x) \mid h(x) \,,
$$
于是
$$
\frac{f(x)}{(f(x), g(x))} \mid \frac{h(x)}{(f(x), g(x))} , \quad
\frac{g(x)}{(f(x), g(x))} \mid \frac{h(x)}{(f(x), g(x))} \,.
$$
因为
$$
\left( \frac{f(x)}{(f(x), g(x))}, \frac{g(x)}{(f(x), g(x))} \right) = 1 \,,
$$
所以
$$
\frac{f(x)g(x)}{(f(x), g(x))} \mid \frac{h(x)}{(f(x), g(x))} \,, \\
\frac{f(x)g(x)}{(f(x), g(x))} \mid h(x) \,.
$$

又因 $f(x), g(x)$ 首项系数为 $1$，所以 $\frac{f(x)g(x)}{(f(x), g(x))} $ 的首项系数也为 $1$. 根据定义，
$$
[f(x), g(x)] = \frac{f(x)g(x)}{(f(x), g(x))} \,.
$$

# 第四题
## 题目
计算行列式的值：
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

## 答案
$$
d_n = (1 + (-1)^{n-1} \prod_{i=1}^n \frac1{a_i}) \prod_{1 \le i \lt j \le n}(a_j - a_i) \,.
$$

## 解析
拆分为两个行列式，利用范德蒙德行列式的结果.

# 第五题
## 题目
求向量组
$$
\alpha_1 = \begin{pmatrix}
2 \\ 1 \\ 4 \\ 3
\end{pmatrix},
\alpha_2 = \begin{pmatrix}
-1 \\ 1 \\ -6 \\ 6
\end{pmatrix},
\alpha_3 = \begin{pmatrix}
-1 \\ -2 \\ 2 \\ -9
\end{pmatrix},
\alpha_4 = \begin{pmatrix}
1 \\ 1 \\ -2 \\ 7
\end{pmatrix},
\alpha_5 = \begin{pmatrix}
2 \\ 4 \\ 4 \\ 9
\end{pmatrix}
$$
的一个极大线性无关组，并把其余向量用这个极大无关组线性表出.

## 答案
一个极大线性无关组是：  
$$
\alpha_1, \alpha_2, \alpha_4
$$
其他向量可以表示为这三个向量的线性组合：
$$
\alpha_3 = -\alpha_1 - \alpha_2, \quad \alpha_5 = 4 \alpha_1 + 3 \alpha_2 - 3 \alpha_4
$$

## 解析
$$
\begin{pmatrix}
2 & -1 & -1 & 1 & 2 \\
1 & 1 & -2 & 1 & 4 \\
4 & -6 & 2 & -2 & 4 \\
3 & 6 & -9 & 7 & 9
\end{pmatrix} \rightarrow
\begin{pmatrix}
1 & 0 & -1 & 0 & 4 \\
0 & 1 & -1 & 0 & 3 \\
0 & 0 & 0 & 1 & -3 \\
0 & 0 & 0 & 0 & 0
\end{pmatrix} \,.
$$

# 第六题（补充题）
## 题目
求多项式
$$
f(x) = x^4 + 4 x^3 + 4 x^2 + 1
$$
在实数范围内的因式分解.

## 答案
$$
\begin{align*}
f(x) = &(x^2 + (\sqrt{2 + 2 \sqrt2} + 2) x + \sqrt{2 + 2 \sqrt2} + \sqrt2 + 1) \cdot \\
&(x^2 - (\sqrt{2 + 2 \sqrt2} - 2) x - \sqrt{2 + 2 \sqrt2} + \sqrt2 + 1) \,.
\end{align*}
$$

## 解析
$$
\begin{align*}
f(x - 1) &= x^4 - 2 x^2 + 2 \\
&= (x^4 - 2 \sqrt2 x^2 + 2) - (2 - 2 \sqrt2) x^2 \\
&= (x^2 - \sqrt2)^2 - (\sqrt{(2 - 2 \sqrt2)}x)^2 \\
&= (x^2 - (\sqrt{(2 - 2 \sqrt2)}x - \sqrt2) (x^2 + (\sqrt{(2 - 2 \sqrt2)}x - \sqrt2) \,.
\end{align*}
$$
所以
$$
\begin{alignat*}{2}
f(x) &= &&((x + 1)^2 - (\sqrt{(2 - 2 \sqrt2)}(x + 1) - \sqrt2)((x + 1)^2 + (\sqrt{(2 - 2 \sqrt2)}(x + 1) - \sqrt2) \\
&= &&(x^2 + (\sqrt{2 + 2 \sqrt2} + 2) x + \sqrt{2 + 2 \sqrt2} + \sqrt2 + 1) \cdot \\
& &&(x^2 - (\sqrt{2 + 2 \sqrt2} - 2) x - \sqrt{2 + 2 \sqrt2} + \sqrt2 + 1) \,.
\end{alignat*}
$$
（还需验证不可约，此处略.）
