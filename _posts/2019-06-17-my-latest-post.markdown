---
layout: post
title:  "My latest post"
date:   2019-06-16 11:40:20
published: true
categories: Miscellaneous
---

This is my latest post with some math that hopefully displays nicely. 
$$
\begin{align}\label{eqn}
  \phi(x,y) &= \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right) = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  &=(x_1, \ldots, x_n) \left( \begin{array}{ccc} \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \nonumber\\
      \vdots & \ddots & \vdots \\\nonumber
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\\nonumber
      \vdots \\\nonumber
      y_n
    \end{array} \right). 
\end{align}
$$

We can reference equations (\ref{eqn}) as usual. You can also use
\\[ f(x) = x^2 \\]

for displays. This is some inline math: \\( f(x) = \sum\limits_{n = 1}^\infty \frac{x^n}{n!} \\). 