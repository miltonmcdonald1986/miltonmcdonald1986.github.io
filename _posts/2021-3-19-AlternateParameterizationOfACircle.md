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

To show this, let $t=\tan{u/2}$.  Then $u=2\arctan{t}$.

<details style="color:#d33682;"><summary markdown='span'><small>Click here for details.</small></summary>

We have  

$$
\begin{align*}
t&=\tan{u/2}&\Leftrightarrow\\
u/2&=\arctan{t} &\Leftrightarrow\\
u&=2\arctan{t}&
\end{align*}
$$  

</details>  
  
  
Thus we can write  

$$
\begin{align*}
\cos{u}&=\cos\left({2\arctan{t}}\right)&\\
&=2\cos^2(\arctan{t}) - 1&(1)\\
&=2\left(\frac{1}{\sqrt{1+t^2}}\right)^2-1&(2)\\
&=2\left(\frac{1}{1+t^2}\right)-1&\\
&=\frac{2-(1+t^2)}{1+t^2}&\\
&=\frac{1-t^2}{1+t^2}&
\end{align*}
$$  
  
<details style="color:#228B22;"><summary markdown='span'><small>Click here for details of (1).</small></summary>

One of the double angle formulas for cosine is  

$$
\cos(2\theta)=2\cos^2\theta-1.
$$  

Setting $\theta=\arctan{t}$ gives $\cos{2\arctan{t}}=2\cos^2{\arctan{t}}-1$.

</details>  
  
<details style="color:#d33682;"><summary markdown='span'><small>Click here for details of (2).</small></summary>

We have  

$$
\begin{align*}
t&=\tan{u/2}&\Leftrightarrow\\
u/2&=\arctan{t} &\Leftrightarrow\\
u&=2\arctan{t}&
\end{align*}
$$  

</details>  

where the last line was found by applying the standard double angle formula for cosine.  The last expression can be simplified further by considering the right triangle, pictured below.  The angle $\arctan{t}$ is the angle whose tangent is $t$, as shown in the figure.  The Pythagorean Theorem gives the hypotenuse to be $\sqrt{1+t^2}$, and we have $\cos{\arctan{t}}=1/\sqrt$1+t^2}$.
<img src="\images\2019-03-19-09-42.png">  
