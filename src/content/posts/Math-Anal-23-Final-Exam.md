---
title: 2023 数学分析上期末考
published: 2025-01-04
description: 2023 数学分析上期末考 试题及答案
tags: [数学分析, 答案]
category: 数学
draft: false
---

**建议使用电脑访问**

## 第一题
### 题目
叙述下列定理并解释其几何意义。

1) 连续函数的零点存在定理
2) 罗尔(Rolle) (中值) 定理

### 答案
1) 若 $f(x)$ 在 $[a, b]$ 上连续，且 $f(a)$ 与 $f(b)$ 异号，则存在 $\xi \in (a, b)$，使得 $f(\xi) = 0$ .
   
    几何意义：若函数在区间 $[a, b]$ 上连续，且在区间端点处函数值异号，则函数在区间内至少有一个零点.
2) 若 $f(x)$ 在 $[a, b]$ 上连续，在 $(a, b)$ 内可导，且 $f(a) = f(b)$，则存在 $\xi \in (a, b)$，使得 $f'(\xi) = 0$.

    几何意义：若函数在区间 $[a, b]$ 上连续，在区间内可导，且在区间端点处函数值相等，则函数在区间内至少有一个驻点.

## 第二题
### 题目
计算
1) $\lim\limits_{n \to + \infty} \frac{\sqrt{n + 1}}{[\sqrt{n} + 1]}$
2) $\lim\limits_{x \to 0^+} x^{ln(1 + x)}$
3) $\lim\limits_{x \to + \infty} \frac{\sqrt{x^2 + x} - \sqrt{x} cosx}{\sqrt{x^2 - 1} + \sqrt{x} sinx}$

### 答案
1) $\lim\limits_{n \to + \infty} \frac{\sqrt{n + 1}}{[\sqrt{n} + 1]} = \lim\limits_{n \to + \infty} \frac{\sqrt{n + 1}}{\sqrt{n}} = 1$
2) $\lim\limits_{x \to 0^+} x^{ln(1 + x)} = \lim\limits_{x \to 0^+} e^{ln(1 + x)lnx} = e^{\lim\limits_{x \to 0^+} xlnx} = e^{\lim\limits_{x \to 0^+} \frac{lnx}{\frac{1}{x}}} = e^{\lim\limits_{x \to 0^+} \frac{\frac{1}{x}}{-\frac{1}{x^2}}}= e^{\lim\limits_{x \to 0^+} -x} = 1$
3) 

## 第三题
### 题目
求 $x cosx − sin2x$ 的带皮亚诺 (Peano) 余项的 $n$ 次 Maclaurin 公式.

### 答案
