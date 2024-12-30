---
title: 2024 高等代数上期中考
published: 2024-11-10
description: 2024 高等代数上期中考 试题及答案
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
f(x) &= x^4 + x^3 + 2 x^2 + x + 1 \,, \\
g(x) &= 2 x^3 + x^2 + 2 x + 1 \,,
\end{align*}
$$
求 $(f(x), g(x))$，并求多项式 $u(x), v(x)$，使得
$$
(f(x), g(x)) = u(x)f(x) + v(x)g(x) \,.
$$

## 答案
$$
\begin{align*}
(f(x), g(x)) &= x ^ 2 + 1 \,, \\
u(x) &= \frac43 \,, \\
v(x) &= -\frac23 x - \frac13 \,.
\end{align*}
$$

## 解析
使用辗转相除法.

$$
f(x) = (\frac12 x + \frac14) g(x) + (\frac34 x^2 + \frac34) \,, \\
g(x) = (\frac83 x + \frac43) (\frac34 x^2 + \frac34) \,,
$$

因此
$$
(f(x), g(x)) = x ^ 2 + 1 \,.
$$
而
$$
\frac34 x^2 + \frac34 = f(x) - (\frac12 x + \frac14) g(x) \,,
$$
于是，令 $u(x) = \frac43, v(x) = -\frac23 x - \frac13$，就有
$$
(f(x), g(x)) = u(x)f(x) + v(x)g(x) \,.
$$

# 第二题
## 题目
1) 把 $x^4 + x^2 + 1$ 在实数域及复数域上做因式分解；
2) 把 $x^6 + 27$ 在实数域及复数域上做因式分解.

## 答案
1) 实数域：
   $$
   \begin{align*}
   x^4 + x^2 + 1 &= (x^2 + 1)^2 - x^2
                 &= (x^2 - x + 1) (x^2 + x + 1)
   \end{align*}
   $$
   复数域：
   $$
   x^4 + x^2 + 1 = (x - \frac12 - \frac{\sqrt3}{2} i) (x - \frac12 + \frac{\sqrt3}{2} i) (x + \frac12 - \frac{\sqrt3}{2} i) (x + \frac12 + \frac{\sqrt3}{2} i)
   $$
2) 实数域：
   $$
   \begin{align*}
   x^6 + 27 &= (x^2 + 3) (x^4 - 3 x^2 + 9)
            &= (x^2 + 3) (x^2 - 3 x + 3) (x^2 + 3 x + 3)
   \end{align*}
   $$
   复数域：
   $$
   x^6 + 27 = (x - \sqrt3 i) (x + \sqrt3 i) (x - \frac32 - \frac{\sqrt3}{2} i) (x - \frac32 + \frac{\sqrt3}{2} i) (x + \frac32 - \frac{\sqrt3}{2} i) (x + \frac32 + \frac{\sqrt3}{2} i)
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
判别 $\sum\limits_{i=0}^{p-1} (x+1)^i$ 是否在有理数域上不可约，这里 $p$ 为素数.

## 答案
$$
P(x) = \sum_{i = 0}^{p - 1} (x + 1)^i 
= \sum_{i = 0}^{p - 1} \sum_{k = 0}^{i} C_i^k x^k 
= \sum_{k = 0}^{p - 1} \sum_{i = k}^{p - 1} C_i^k x^k \,.
$$

对 $k = 0, 1, 2, \cdots, p - 2$，
$$
\sum_{i = k}^{p - 1} C_i^k = C_{p}^{k+1} = \frac{p!}{(k + 1)!(p - k - 1)!} \,,
$$
因为 $k + 1 \lt p, p - k - 1 \lt p$，所以 $p \mid \frac{p!}{(k + 1)!(p - k - 1)!}$.

质数 $p$ 满足 $p \nmid C_{p-1}^{p-1}, p \mid \sum\limits_{i = k}^{p - 1} C_i^k (k = 0, 1, 2, \cdots, p - 2)$ 且 $p^2 \nmid \sum\limits_{i = 0}^{p - 1} C_i^0$，根据艾森斯坦判别法，$P(x)$ 在有理数域上不可约.

# 第五题
## 题目
计算行列式的值：
$$
\begin{vmatrix}
5 & 1 & -2 & 1 \\
3 & 7 & -1 & 2 \\
9 & 10 & 1 & 10 \\
1 & 0 & -1 & 0
\end{vmatrix}
$$

## 答案
$100$

## 解析
$$
\begin{align*}
\begin{vmatrix}
5 & 1 & -2 & 1 \\
3 & 7 & -1 & 2 \\
9 & 10 & 1 & 10 \\
1 & 0 & -1 & 0
\end{vmatrix} &= 
-
\begin{vmatrix}
1 & 0 & -1 & 0 \\
3 & 7 & -1 & 2 \\
9 & 10 & 1 & 10 \\
5 & 1 & -2 & 1
\end{vmatrix} = 
-
\begin{vmatrix}
1 & 0 & -1 & 0 \\
0 & 7 & 2 & 2 \\
0 & 10 & 10 & 10 \\
0 & 1 & 3 & 1
\end{vmatrix} = 
\begin{vmatrix}
1 & 0 & -1 & 0 \\
0 & 1 & 3 & 1 \\
0 & 10 & 10 & 10 \\
0 & 7 & 2 & 2
\end{vmatrix} \\ &= 
\begin{vmatrix}
1 & 0 & -1 & 0 \\
0 & 1 & 3 & 1 \\
0 & 0 & -20 & 0 \\
0 & 0 & -19 & -5
\end{vmatrix} = 
\begin{vmatrix}
1 & 0 & -1 & 0 \\
0 & 1 & 3 & 1 \\
0 & 0 & -20 & 0 \\
0 & 0 & 0 & -5
\end{vmatrix} = 
100
\end{align*}
$$

# 第六题
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
