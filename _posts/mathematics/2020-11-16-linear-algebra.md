---
title: Basic Linear Algebra
date: 2020-11-16 12:42:00 +0100
categories: [Mathematics,Linear Algebra]
tags: [algebra]     # TAG names should always be lowercase
comments: true
math: true
---

> You cannot know too much Linear Algebra
>
> -- <cite>[Benedict Hyman Gross](https://boffosocko.com/2012/05/05/you-cannot-learn-too-much-linear-algebra/)</cite>

Prepostscript (PPS):  This post will be updated when more knowledge of linear algebra to understand other posts is needed.  

## Introduction:

You may have noticed that **Linear Algebra** is a term composed by _Linear_ + _Algebra_. So let's start by defining what is each of the two terms. An _algebra_ it's the union of a **set of objects** and a **set of rules** that applies to that objects. Etymologically the word _Algebra_ comes from the title of the book  [_Ilm al-jabr wa l-muqābala_](https://en.wikipedia.org/wiki/The_Compendious_Book_on_Calculation_by_Completion_and_Balancing), '_The Compendious Book on Calculation by Completion and Balancing_', by the Persian mathematician [al-Khwarizmi](https://en.wikipedia.org/wiki/Muhammad_ibn_Musa_al-Khwarizmi), also, the word _Algorithm_ derivates from his name, so you can imagine that he was an influential mathematician. The word _Linear_  refers to that what we are traying to solve using those set of objects and rules are **Linear systems**. Systems of equations where those equations are of first order, the maximum degree of the variables is equal to one, so in $\mathbb R^2$ (in the plane) we have straight lines, in $\mathbb R ^3$​  (in a space) we have a plane.

Those objects in our case, in ML, will be **vectors**, elements of $\mathbb R ^n$ (tuples of $n$ real numbers). For example, $v$ can be a vector of $\mathbb R ^2$ ($ v \in \mathbb R ^2$) with coordinates $v_1 = 42$ and $v_2 = 73$: 

$$ v  =  \begin{bmatrix} 42 \cr 73 \end{bmatrix}\in \mathbb R ^2 $$

We can represent a vector of $w \in \mathbb R^n$:

$$ w  =  \begin{bmatrix} w_1 \cr w_2 \cr . \cr . \cr . \cr w_n \end{bmatrix}\in \mathbb R ^n $$

And the **rules** or _axioms_ that apply to those vectors are the following:

Being $u, v, w$ vectors, and $a, b, 0$ and $1$ _scalars_ (elements of $\mathbb R$), then:

- (A1) $ u + (v + w) = (u + v) + w$
- (A2) $u + v = v + u$
- (A3) Exists a vector, called the zero vector, such that $v +0 = v$
- (A4) For every vector $v$ exists a vector $-v$ called the inverse
- (A5) $a(u+v) = au + av$
- (A6) $(a + b) v = av + bv$
- (A7) $ a(bv)  = (ab)v$
- (A8) Exist a scalar called the identity, and denoted as $1$, such as $1*v = v$

Mathematically those rules are important, since they are defining how vectors interact with themselves and with scalars. 

Now, specifically, we can define those operations on vectors of $\mathbb R^n$ .  For example, if $u, v \in \mathbb R^2$ and $a \in \mathbb R$, then:

$$ u + v = \begin{bmatrix} u_1 \cr u_2 \end{bmatrix} + \begin{bmatrix} v_1 \cr v_2 \end{bmatrix} = \begin{bmatrix} u_1 + v_1 \cr u_2+ v_2 \end{bmatrix} $$

$$ a * u = a * \begin{bmatrix} u_1 \cr u_2 \end{bmatrix} = \begin{bmatrix} a * u_1 \cr a * u_2 \end{bmatrix}$$



**References**:

- [Mathematics for machine learning](https://mml-book.github.io/) by Marc Peter Deisenroth, Aldo Faisal, and Cheng Soon Ong
- 3blue1brown's Linear Algebra [Videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

