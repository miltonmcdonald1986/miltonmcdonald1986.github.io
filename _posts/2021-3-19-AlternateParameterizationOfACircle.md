---
layout: post
mathjax: true
title: Alternate Parameterization of a Circle
---

The first quadrant of the unit circle is defined by the parametric functions
$$
\begin{align*}
x(u)&=\cos{u}\\
y(u)&=\sin{u}\quad 0\leq u\leq\frac{\pi}{2}.
\end{align*}
$$

The following image illustrates this parameterization.  Note that as $u$ increases from $u=0$ to $u=1$, the point $\left(x(u), y(u)\right)=\left(\cos{u}, \sin{u}\right)$ traverses the first quadrant of the unit circle.
<img src="\images\2021-03-19-08-34.gif">

We will show that by setting $t=\tan\left(u/2\right)$, one can derive the alternate representation
$$
\begin{align*}
x(t)&=\frac{1-t^2}{1+t^2}\\
y(t)&=\frac{2t}{1+t^2}\quad 0\leq t\leq 1.
\end{align*}
$$
