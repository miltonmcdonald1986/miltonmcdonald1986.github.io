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
To simplify $(\cos{\arctan{t}})$, we must find the cosine of the angle whose tangent is $t$.  We construct a right triangle that satisfies the condition $\tan{\theta}=t$.  By definition of tangent ($\tan{\theta}=\mbox{opposite}/\mbox{hypotenuse})$, the right triangle shown in the figure below satisfies the condition.  
<img src="\images\2021-03-19-13-01.png">  
The Pythagorean Theorem gives  
  
$$
h^2=1^2+t^2\quad\Leftrightarrow\quad h=\sqrt{1+t^2},
$$  

so that  

$$
\begin{align*}
\cos{\theta}&=\frac{1}{h}\\
&=\frac{1}{\sqrt{1+t^2}}
\end{align*}
$$  

</details>   
