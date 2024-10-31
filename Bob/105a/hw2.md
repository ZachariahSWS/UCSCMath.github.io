---
layout: default
title: Math 105A Homework 2
permalink: /Bob/105a/hw2
---

# [Math 105A](/Bob/105a) Homework 2

Please complete the following from the [textbook](/Bob/105a/lecture_notes_v2.pdf){: .internal-link }:

- Section 2.1 - #1-2
- Section 2.2 - #1-8
- Section 2.3 - #1-4

## Transcribed Questions

### 2.1.1
Find what the following sequences converge to and prove they indeed converge to your claimed value.
- $\{x_n\} = \{ 3+\frac{(-1)^n}{2n} \}$
- $\{x_n\} = \{ \frac{2n-5}{5n+7} \}$
- $\{x_n\} = \{ \frac{2n^2+3n}{n+n^2} \}$
- $\{x_n\} = \{ \frac1{n^2} + \frac2{n^2} + \dots + \frac{n}{n^2} \}$

### 2.1.2
Let $h > 0$ be fixed. Prove (either by induction or using the binomial theorem) that
$$(1+h)^n \geq 1 + nh, \quad n = 1,2,\dots$$
Deduce that, if $0 < r < 1$, then $\lim_{n \rightarrow \infty}r^n = 0$. \[Hint: explain why you can write $r = \frac1{1+h}$ for some $h > 0$.\]

### 2.2.1
Prove or disprove with counterexample the following variation of Theorem 11: Given two sequences $\{x_n\}$ and $\{y_n\}$ that are convergent with $x_n \rightarrow x$ and $y_n \rightarrow y$, if $x_n > y_n \forall n \in \mathbb{N}$, then $x > y$.

### 2.2.2
Prove both parts of Lemma 12:
- Suppose for two sequences $\{a_n\}$ and $\{b_n\}$ that $0 \leq b_n \leq a_n$ is true for all $n \in \mathbb N$
  If $a_n \rightarrow 0$, $b_n \rightarrow 0$
- For sequences $\{a_n\}, \{b_n\}$ and $\{c_n\}$ with the property that $a_n \leq b_n \leq c_n \ \forall n \in \mathbb N$, if $\{a_n\}$ and $\{c_n\}$ are both convergent with $\lim_{n \rightarrow \infty} a_n = L = \lim_{n \rightarrow \infty} c_n$, then $\{b_n\}$ is convergent with $\lim_{n \rightarrow \infty} b_n = L$

### 2.2.3
Conjecture the value of the following and provide a proof of its convergence (if it does?)
$$\lim_{n \rightarrow \infty} \sqrt{n^2 + 6n} - n$$
Hint: Finding a lower bound on a term in a denominator give an upper bound on its reciprocal, i.e. $f(x) > M$ means $\frac1{f(x)} < \frac1M$

### 2.2.4
- Suppose that the sequence $\{x_n\}$ is bounded and that $y_n \rightarrow 0$. Prove that $\{x_ny_n\}$ converges to $0$.
- Give an example in which $y_n \rightarrow 0$, and $x_ny_n$ does not converge to 0.

### 2.2.5
- Suppose that $x_n \rightarrow x$, and define $y_n$ to be the sequence given by

$$y_n = \frac{x_1 + x_2 + \dots + x_n}{n} = \frac1n \sum_{k=1}^n x_k$$

  i.e. the arithmetic mean of the first $n$ terms. Show that $y_n \rightarrow x$
- Let $\{x_n\} = \{(-1)^n\}$. We know that $x_n$ diverges, but show that $y_n$ in this instance converges.

### 2.2.6
- Prove that if $\{x_n\}$ converges to $L$, then $\{\|x_n\|\}$ converges to $\|L\|$
- Is there converse always true? (is it always the case that if $\{\|x_n\|\}$ converges then $\{x_n\}$ converges?)

### 2.2.7
A polynomial with rational coefficients $p(x)$ is given by
$$p(x) = a_nx^n + a_{n-1}x^{n-1} + \dots + a_1x + a_0, \ \ a_0,a_1,a_2,\dots,a_n \in \mathbb Q$$
and a rational function $R(x)$ is a fraction of two polynomials with rational coefficients, i.e. $R(x) = \frac{p(x)}{q(x)}$
- Using induction on the degree of the polynomial and the algebraic limit laws proven in this section, prove why if $x_n \rightarrow x$, then $p(x_n) \rightarrow p(x)$ for any polynomial $p(x)$ with rational coefficients.
- What requirements would need to be placed on the sequence $\{x_n\}$ to guarantee that $R(x_n) \rightarrow R(x)$ if $x_n \rightarrow x$ and $R(x)$ is some rational function.

### 2.2.8
Provide a direct proof of iii) in Theorem 14 using the definition of convergence (an $\varepsilon - N$ argument) without using i) or ii) from the algebraic limit rules.
i)
ii)
iii) If $b \neq 0, \exists N \in \mathbb N$ such that for $n > N, b_n \neq 0$
Also it then follows that $\frac{1}{b_n} \rightarrow \frac1b$ and $\frac{a_n}{b_n} \rightarrow \frac{a}b$

### 2.3.1
Consider the sequence $u_n = (-1)^n$. Write out the first 5 terms of the subsequence $\{u_{3k+1}\}_{k \geq 1}$

### 2.3.2
For the sequence $\{x_n\} = \{\sin(\frac{n\pi}4) + \frac1n\}$, please write out in simplified form, the following subsequences.
- $\{x_{4n}\}$
- $\{x_{4n+1}\}$
- $\{x_{4n+2}\}$
- $\{x_{4n+3}\}$

Which of these subsequences converge? Which diverge?

### 2.3.3
- Suppose a subsequence $u_n$ is such that $\lim_{k\rightarrow \infty} u_{2k} = L \in \mathbb Q$ and $\lim_{k \rightarrow \infty} u_{2k+1} = L$. Prove that $\lim_{k \rightarrow \infty} u_k = L$.
- Prove or disprove. If a sequence is such that $\lim_{k \rightarrow \infty} u_{3k} = Ln \in \mathbb Q$ and $\lim_{k \rightarrow \infty} u_{3k+1} = L$, does this imply that $\lim_{n \rightarrow \infty} u_n = L$?

### 2.3.4
Given a subsequence $\{x_n\}$, say you have $M$ distinct subsequences of $\{x_n\}$ in that none of the terms of the subsequences overlap.
Call $A_k$ the indices of subsequence $k$. If every one of these distinct $M$ subsequences converge to the same value $L$, what condition is required of

$$\bigcup_{k=1}^M A_k$$

to guarantee the original sequence $\{x_n\}$ converges to $L$.
