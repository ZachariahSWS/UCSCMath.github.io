---
layout: default
title: Math 105A Homework 4
permalink: /Bob/105a/hw4
---

# [Math 105A](/Bob/105a) Homework 4

Please complete the following from the [textbook](/Bob/105a/lecture_notes_v2.pdf){: .internal-link }:

### 4.1.1
Prove the infinum version of theorem 36:

For a set $A$ that is bounded above, a number $\alpha$ equals $\sup A$ if and only if $\alpha$ is an upper bound of $A$, and for all $\varepsilon > 0$, there exists $x \in A$ such that $x > \alpha - \varepsilon$

### 4.1.2
Prove the infinum version of theorem 37:

Assume that $A$ is a set in the reals that is bounded above, let $\alpha = \sup A$ and assume
that $\alpha \notin A$. Then for any $\varepsilon > 0$ there is an infinite number of elements of $A$ contained within the interval $(\alpha - \varepsilon, \alpha)$

### 4.1.3
Prove that $c < 0$ case of Theorem 38:

For $A$ a bounded set of the reals, we have that

$$\sup(cA) = c \sup A,\quad \inf(cA) = c\inf(A)$$

for a real constant $c > 0$, and

$$\sup(cA) = c\inf(A),\quad \inf(cA) = c \sup A$$

for a real constant $c < 0$

### 4.2.1
Prove that a bounded monotonically decreasing sequence converges.

### 4.2.2
Let $A$ be a non-empty subset of $\mathbb R$ that is bounded above, then there exists a sequence $\{x_n\}$ with $x_n \in A$ for all $n \in \mathbb N$ with $\{x_n\} \rightarrow \sup A$

### 4.2.3
Define a sequence $\{a_n\}$ by $a_1 = \sqrt2$ and $a_{n+1} = \sqrt{2 + a_n}$

- Show that $a_n \leq 2$ for every $n$
- Show that $\{a_n\}$ is an increasing sequence. And then explain why $\{a_n\}$ converges.
- Show that $\lim_{n \rightarrow \infty} a_n = 2$

### 4.2.4
Let $k > 1$ be a constant, and define a sequence $\{a_n\}$ by $a_1 = 1$ and

$$a_{n+1} = \frac{k(1+a_n)}{k + a_n}$$

- Show that $\{a_n\}$ converges. (Either show the sequence is Cauchy or satisfies the conditions
in the monotone convergence theorem)
- Find $\lim_{n \rightarrow \infty}a_n$

### 4.2.5
From Rudin: fix $\alpha > 1$ and take $x_1 > \sqrt{\alpha}$ and define
$x_{n+1} = \frac{\alpha + x_n}{1 + x_n}$

- Prove that $x_1 > x_3 > x_5 > \dots$
- Prove that $x_2 < x_4 < x_6 < \dots$
- Find what $\{x_n\}$ converges to and prove your claim

### 4.2.6
For $x_1 > 0$ and $\alpha > 0$ define the sequence $\{x_n\}$ recursively by

$$x_{n+1} = \frac{p-1}{p}x_n + \frac{\alpha}{px_n^{p-1}}$$

where $p$ is a fixed positive integer. Prove what $\{x_n\}$ converges to.

Hint: Monotone Convergence theorem and the arithmetic mean vs geometric mean inequality will help here

### Additional Question

By quoting 3 things, explain how the Bolzano-Weierstrass Theorem implies
the Cauchy Completeness of $\mathbb R$. (i.e. Bolzano-Weierstrass is another equivalent form
of completeness when the AP is present)
