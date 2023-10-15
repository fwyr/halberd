---
title: Differentiation
topic: "4049"
---
# First principle of differentiation
## Gradient function
The gradient of a straight line is given by
$$ 
m = \frac{y_2-y_1}{x_2-x_1} 
$$
**Differentiation** allows us to find the gradient of a tangent line at any point through a numerical approach instead of a graphical approach.
Consider any function.
A **secant line** is a straight line joining two points on a curve. The gradient of the tangent line at $(x, y)$ can be found with the gradient of the secant line. By continually decreasing $h$ and moving the second point nearer to the first point, the gradient of the secant line will approach the gradient of the tangent line.

![[Pasted image 20231010124051.png|500]]

Suppose $y = x^2$. Given two points $(x, y)$ and $(x+\delta x, y+\delta y)$, we can derive the following.

$$ 
\begin{align*} y + \delta y &= (x + \delta x)^2 \\ \delta y &= (x+\delta x)^2 - y \\ \delta y &= (x+dx)^2 - x^2 \\ \end{align*} 
$$

Continuing,

$$ 
\begin{align*} \frac{\delta y}{\delta x} &= \frac{(x+dx)^2 - x^2}{\delta x} \\ \frac{\delta y}{\delta x} &= \frac{x^2 + 2x\delta x + \delta x^2 - x^2}{\delta x} \\ \therefore \frac{\delta y}{\delta x} &= 2x + \delta x \end{align*}
 $$

To find the gradient of the tangent, we find the limit of this gradient $\frac{\delta y}{\delta x}$. 
By letting $\delta x \rightarrow 0$,
$$
\lim_{\delta x→0} \frac{\delta y}{\delta x} =2x+0 =2x
$$
The notation $\lim_{\delta x→0} \frac{\delta y}{\delta x}$ is denoted by $\frac{dy}{dx}$ or $f’(x)$. This is called the **first derivative of $y$ with respect to $x$**. The gradient of the curve at $x = a$ is denoted as $\frac{dy}{dx}\Big|_{x=a}$ or $f’(a)$.

|Form|Gradient function|Gradient at $x = a$|
|---|---|---|
|$y = x^2$|$\frac{dy}{dx}$|$\frac{dy}{dx}\Big\lvert_{x=a}$|
|$f(x) = x^2$|$f’(x)$|$f’(a)$|

## Sum and difference
Given that $f(x)$, $g(x)$, and $h(x)$ are functions, and $\alpha$ is a constant,
$$ 
\begin{align*} f(x) = g(x) \pm h(x) &\implies f'(x) = g'(x) \pm h'(x) \\ f(x) = \alpha \times g(x) &\implies f'(x) = \alpha \times g'(x) \end{align*}
$$

---
# Rules of differentiation
## Power rule
For any value of $n$,
$$ 
\begin{align*} y &= x^n \\\\ \frac{dy}{dx} &= nx^{n-1} \end{align*} 
$$
## Chain rule
If $f(x)$ and $g(x)$ are functions, then
$$ 
\frac{d}{dx} [f(g(x))] = f'(g(x)) \times g'(x)
 $$

## Product rule
If $y = uv$ where $u$ and $v$ are functions of $x$, then
$$ 
\frac{d}{dx}(uv) = \frac{du}{dx}\times v + u \times \frac{dv}{dx} 
$$

## Quotient rule
If $y = \frac{u}{v}$ where $u$ and $v$ are functions of $x$, then
$$ 
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{\frac{du}{dx}\times v - u\times\frac{dv}{dx}}{v^2} 
$$

---
# Trigonometric functions
The first derivatives of each trigonometric function is as shown.
$$ 
\frac{d}{dx}\left(\sin x\right) = \cos x 
$$
$$ 
\frac{d}{dx}\left(\cos x\right) = - \sin x 
$$
$$ 
\frac{d}{dx}\left(\tan x \right) = \sec^2 x 
$$
For expressions in the form of $f(g(x))$ where $f(x)$ is a trigonometric function, remember to apply the chain rule.
For example,
$$
 \frac{d}{dx}\left(\sin(f(x))\right) = \cos (f(x)) \times f'(x)
  $$

---
# Exponential and logarithmic functions
The first derivative of $e$ to the power of $x$ is $e^x$.
$$ 
\frac{d}{dx} (e^x) = e^x 
$$
With the chain rule,
$$ 
\frac{d}{dx}\left[e^{f(x)}\right] = e^{f(x)} \times f'(x) 
$$
The first derivative of $\ln x$ is $\frac{1}{x}$.
$$ 
\frac{d}{dx}(\ln x) = \frac{1}{x} 
$$
With the chain rule,
$$ 
\frac{d}{dx}\left[\ln(f(x))\right] = \frac{1}{f(x)} \times f'(x) 
$$




