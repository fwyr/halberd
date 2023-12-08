---
title: Differentiation Techniques
topic: "9758"
---

# Limits
For a given function $f$, if $f(x)$ approaches a real number $L$ as $x$ **approaches** $a$, then $L$ is the **limit** of $f(x)$ as $x$ approaches $a$. 
$$
\lim_{ x \to a } f(x) = L
$$
If $f$ is defined at $x=a$ and $\lim_{ x \to a } f(x) = f(a)$, then $f$ is said to be **continuous** at $x=a$. If $f$ is continuous at every point on an interval $I$, $f$ is a continuous function on the interval $I$.

---
# First principle
Consider a curve with equation $y = f(x)$.
Let $A(x, y)$ and $B(x + \delta x, y + \delta y)$ be two points on the curve, where $\delta x$ represents a small increment in $x$. $\delta y$ is the corresponding small increment in $y$ due to $\delta x$.
It follows that $\delta y = f(x + \delta x) - f(x)$, and the gradient of the line $AB$ is given by $\frac{\delta y}{\delta x}$. As $B$ tends towards $A$, $\delta x$ tends towards 0 and the gradient of the line $AB$ becomes closer to the gradient of the curve at point $A$.
Hence, 
$$
\begin{align*}
\text{gradient of curve at A} &= \lim_{ \delta x \to 0 } \frac{\delta y}{\delta x} \\[5pt]
&= \lim_{ \delta x \to 0 } \frac{f(x+\delta x)-f(x)}{\delta x}
\end{align*}
$$
We denote $\lim_{ \delta x \to \infty } \frac{\delta y}{\delta x}$ as $\frac{dy}{dx}$. This is known as the **first derivative of** $f$ **with respect to x** at $x$. This is also denoted by $f'(x)$ or $\frac{d}{dx} f(x)$. 

>[!info] Derivative from First Principle
>Provided that the limit exists, the first derivative of $f(x)$ from first principles is
>$$
>\frac{dy}{dx} = f'(x) = \lim_{ \delta x \to 0 } \frac{f(x+\delta x) - f(x)}{\delta x} 
>$$

---
# Rules of differentiation
## Basic rule
Let $f$ and $g$ be two functions of $x$. We denote $\frac{d}{dx}f(x)$ and $\frac{d}{dx}g(x)$ to be $f'(x)$ and $g'(x)$ respectively.
The basic rule of differentiation are shown.
$$
\begin{align*}
\frac{d}{dx}\left[a\,f(x) \pm b\,g(x)\right] = a\,f'(x) \pm b\,g'(x)
\end{align*}
$$

## Power rule
For any value of $n$,
$$ 
\begin{align*} y &= x^n \\\\ \frac{dy}{dx} &= nx^{n-1} \end{align*} 
$$

## Chain rule
>[!info] Chain Rule
>If $y$ is a function of $u$, where $u$ is a function of $x$, then
>$$
>\frac{dy}{dx}=\frac{dy}{du}\times \frac{du}{dx}
>$$

In other words, 
$$ 
\frac{d}{dx} [f(g(x))] = f'(g(x)) \times g'(x) 
$$

## Product rule
>[!info] Product Rule
>Let $y = uv$ where $u$ and $v$ are both functions of $x$. Then,
>$$
>\frac{dy}{dx} = \frac{d}{dx}(uv) = u \frac{dv}{dx} + v \frac{du}{dx}
>$$ 

## Quotient rule
>[!info] Quotient Rule
>Let $y = \frac{u}{v}$ where $u$ and $v$ are both functions of $x$. Then,
>$$
>\frac{dy}{dx} = \frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \frac{du}{dx} - u frac{dv}{dx} }{v^2}
>$$

## Trigonometric functions
The basic derivatives for trigonometric functions are shown, where $x$ is measured in **radians**.
$$
\begin{align*}
\frac{d}{dx}\sin x &= \cos x \\[5pt]
\frac{d}{dx}\cos x &= -\sin x \\[5pt]
\frac{d}{dx}\tan x &= \sec^2 x \\[5pt]
\frac{d}{dx}\sec x &= \sec x\tan x \\[5pt]
\frac{d}{dx} \csc x &= -\csc x\cot x \\[5pt]
\frac{d}{dx}\cot x&= -\csc^2x
\end{align*}
$$
Generally, the chain rule applies as well. For example,
$$
\frac{d}{dx}\sin f(x) = \cos f(x) \times f'(x)
$$

## Inverse trigonometric functions
The basic derivatives for inverse trigonometric functions are shown.
$$
\begin{align*}
\frac{d}{dx} \sin^{-1} x &= \frac{1}{\sqrt{ 1-x^2 }},&\, |x|<1 \\[5pt]
\frac{d}{dx} \cos^{-1} x &= -\frac{1}{\sqrt{ 1-x^2 }},&\,|x|<1 \\[5pt]
\frac{d}{dx} \tan^{-1} x &= \frac{1}{1+x^2},&\,x\in\mathbb{R}
\end{align*}
$$

## Exponential and logarithmic functions
The basic derivatives for exponential and logarithmic functions are shown.
$$
\begin{align*}
\frac{d}{dx}e^x &= e^x \\[5pt]
\frac{d}{dx}a^x &= a^x\ln a \\[5pt]
\frac{d}{dx}\ln x &= \frac{1}{x} \\[5pt]
\frac{d}{dx}\log_{a}x &= \frac{d}{dx}\left(  \frac{\ln x}{\ln a} \right) = \frac{1}{x\ln a}
\end{align*}
$$

---

# Higher order derivatives
Let $y = f(x)$.
The **first derivative** of $y$ with respect to $x$, denoted $\frac{dy}{dx}$, is obtained by differentiating $y$ with respect to $x$.
The **second derivative** of $y$ with respect to $x$, denoted $\frac{d^2y}{dx^2}$, is obtained by differentiating $\frac{dy}{dx}$ with respect to $x$.
In general, the **$n$th** derivative of $y$ with respect to $x$ is denoted by $\frac{d^ny}{dx^n}$, where
$$
\frac{d^ny}{dx^n} = \frac{d}{dx}\left( \frac{d^{n-1}y}{dx^{n-1}} \right) \text{ for } n \in {\mathbb{Z}^+ }
$$

---
# Implicit differentiation
An **explicit** function is an equation where $y$ is defined entirely in terms of $x$. Examples of explicit functions include $y = 4x+1$ and $y = x+\frac{1}{x}$.
An **implicit** function is an equation involving $x$ and $y$, where $y$ is not entirely in terms of $x$ and thus cannot be expressed in the form of $y = f(x)$. Examples of implicit functions include $y = 4xy - 10$ and $y = \frac{8}{x} + 3y^3$.
When differentiating an implicit function with terms involving $y$ with respect to $x$, we need to apply the [[Differentiation Techniques#Chain rule|chain rule]], since we assume that $y$ is defined implicitly as a function of $x$.
To differentiate a function $f(y)$ with respect to $x$, we use the chain rule to obtain
$$
\frac{d}{dx}f(y) = \left[ \frac{d}{dy} f(y) \right] \times \frac{dy}{dx}
$$  

>[!example] Implicit differentiation.
>Given that $x^2 + y^3 = xy^2$, find $\frac{dy}{dx}$.
>$$
>\begin{align*}
>\frac{d}{dx}(x^2+y^3) &= \frac{d}{dx}(xy^2) \\[5pt]
>2x + 3y^2 \frac{dy}{dx} &= x\times 2y \frac{dy}{dx}+y^2 \\[5pt]
>(3y^2 - 2xy) \frac{dy}{dx} &= y^2 - 2x \\[5pt]
>\therefore \frac{dy}{dx} &= \frac{y^2-2x}{3y^2-2xy}
>\end{align*}
>$$




