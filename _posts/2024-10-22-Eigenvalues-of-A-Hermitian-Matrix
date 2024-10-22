---
layout: post
title: Eigenvalues of A Hermitian Matrix
date: 2024-10-22 21:00:00-0400
description: An application of majorization. 
tags: theory
categories: Matrix Analysis
type: blog
related_posts: false
toc:
  beginning: true
---


# Majorization
Majorization is a concept used to evaluate the degree of "equality" between two vectors. 
**Definition 1.1** (Majorization): Given `$$x,y\in\mathbb{R}^n$$`, we say `$$x$$` is majorized by `$$y$$` if
$$
\begin{equation}
        \left\{
            \begin{array}{cl}
                \sum_{i=1}^k x_i^{\downarrow}\leq\sum_{i=1}^k y_i^{\downarrow}\,, & \quad k=1,\ldots, n-1\,, \\
                \sum_{i=1}^n x_i^{\downarrow}\leq\sum_{i=1}^n y_i^{\downarrow}\,, & 
            \end{array}
        \right.
    \end{equation}
$$
where `$$x_i^{\downarrow}$$` and `$$y_i^{\downarrow}$$` represent the `$$i$$`-th elements of the non-increasing rearrangement of `$$x$$` and `$$y$$`, respectively.

This blog introduces the [@Marshall2011Inequalities]
This theme supports rendering beautiful math in inline and display modes using [MathJax 3](https://www.mathjax.org/) engine. You just need to surround your math expression with `$$`, like `$$ E = mc^2 $$`. If you leave it inside a paragraph, it will produce an inline expression, just like $$ E = mc^2 $$.

# Diagonal Elements and Eigenvalues of a Hermitian Matrix
To use display mode, again surround your expression with `$$` and place it as a separate paragraph. Here is an example:

# Eigenvalues of a Hermitian Matrix
$$
\sum_{k=1}^\infty |\langle x, e_k \rangle|^2 \leq \|x\|^2
$$

You can also use `\begin{equation}...\end{equation}` instead of `$$` for display mode math.
MathJax will automatically number equations:

\begin{equation}
\label{eq:cauchy-schwarz}
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
\end{equation}

and by adding `\label{...}` inside the equation environment, we can now refer to the equation using `\eqref`.

Note that MathJax 3 is [a major re-write of MathJax](https://docs.mathjax.org/en/latest/upgrading/whats-new-3.0.html) that brought a significant improvement to the loading and rendering speed, which is now [on par with KaTeX](http://www.intmath.com/cg5/katex-mathjax-comparison.php).

### References
- Horn, R. A., Johnson, C. R. (1990). Matrix Analysis. Cambridge University Press. ISBN: 0521386322
- Marshall, A. W., Olkin, I.,, Arnold, B. C. (2011). Inequalities: Theory of Majorization and its Applications (Vol. 143). Springer.
