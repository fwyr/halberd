---
title: Applications of Differentiation
topic: "4049"
---
# Tangents & normals
## Tangents
Given a point $P(x_0, y_0)$ on a curve, the gradient of the tangent at P is equal to the tangent of the curve at P.
$$ 
\begin{align*} \frac{dy}{dx}\Big|_{x=x_0} &= f'(x_0) \\ &= m \end{align*} 
$$
Therefore, the **equation of the tangent** at $P(x_0, y_0)$ is
$$ 
y - y_0 = m(x-x_0) \text{ where } m = f'(x_0) 
$$

## Normals
The **normal** to a curve at point $P$ is the line that passes through the point and is perpendicular to the tangent at $P$.
Since the gradient of the tangent at $P = \frac{dy}{dx}\Big|_{x=x_0} = f'(x_0)$,
$$ 
\begin{align*} \text{gradient of normal} &= -1 \div \frac{dy}{dx}\Big|_{x=x_0} \\ &= -\frac{1}{f'(x_0)} \end{align*} 
$$
Hence, the **equation of the normal** to $P$ is
$$ 
y-y_0 = m(x-x_0) \text{ where } m = -\frac{1}{f'(x)} 
$$

---
# Increasing & decreasing functions
A function $y = f(x)$ is called an **increasing function** if the value of $y$ increases as $x$ increases, and called a **decreasing function** if the value of $y$ decreases as $x$ increases.
Let $f$ be a differentiable function on an interval between $a$ and $b$.

![[Pasted image 20231010125418.png|350]]
If $\frac{dy}{dx} > 0$ for all $x$ in $a < x< b$, the function is increasing in $a < x < b$.

![[Pasted image 20231010125440.png|342]]
If $\frac{dy}{dx} < 0$ for all $x$ in $a < x < b$, the function is decreasing in $a < x < b$.
>

Essentially,
$$ 
\frac{dy}{dx} = \begin{cases}
> 0, y \text{ is increasing} \\ < 0, y \text{ is decreasing } \\ \end{cases} 
$$

---
# Stationary points
A **stationary point** on the curve $y = f(x)$ is a point at which $\frac{dy}{dx} = 0$.
$$ 
\frac{dy}{dx} = 0 \text{ at } x=x_0 \implies (x_0, y_0) \text{ is a stationary point} 
$$
There are three types of stationary points: (1) maximum points, (2) minimum points, and (3) points of inflexion.
- Maximum points refer to “peaks”, where its $y$ value is greater than the points next to it.
- Minimum points refer to “valleys”, where its $y$ value is less than the points next to it.
- Points of inflexion are neither “peaks” nor “valleys”, but rather “flat surfaces”, where the $y$ value continually decreases or increases.
![[Pasted image 20231010130004.png|450]]
## First derivative test
The first derivative test uses $\frac{dy}{dx}$ to determine whether a stationary point is a maximum point, a minimum point, or a stationary point of inflexion. We observe whether the sign of $\frac{dy}{dx}$ when changing $x_0$ by some small value $\delta$.
Here, $x_{0}$ is a **maximum point** as the sign of $\frac{dy}{dx}$ changes from positive to negative.

|$x$|$(x_0)^-$|$x_0$|$(x_0)^+$|
|---|---|---|---|
|$\frac{dy}{dx}$|$+ve$|$0$|$-ve$|

Here, $x_{0}$ is a **minimum point** as the sign of $\frac{dy}{dx}$ changes from negative to positive.

|$x$|$(x_0)^-$|$x_0$|$(x_0)^+$|
|---|---|---|---|
|$\frac{dy}{dx}$|$-ve$|$0$|$+ve$|

Here, $x_{0}$ is a **stationary point of inflextion** as the left and right values of $\frac{dy}{dx}$ have the same sign.

| $x$             | $(x_0)^-$ | $x_0$ | $(x_0)^+$ |
| --------------- | --------- | ----- | --------- |
| $\frac{dy}{dx}$ | $+ve/-ve$ | $0$   | $+ve/-ve$ |

## Second derivative test
$$ 
\frac{d^2y}{dx^2} = \begin{cases} < 0,& (x_0, y_0) \text{ is a maximum point} \\[5pt] > 0,& (x_0, y_0) \text{ is a minimum point} \\[5pt] = 0,& \text{use the First Derivative Test} \end{cases}
$$
Across an interval, if the value of $\frac{dy}{dx}$ changes from negative to positive, i.e. the **second derivative** of $x$, $\frac{d^2y}{dx^2} > 0$, then the stationary point is a **minimum point**.
If $\frac{dy}{dx}$ changes from positive to negative, i.e. $\frac{d^2y}{dx^2} < 0$, then the stationary point is a **maximum point**.
Otherwise, if $\frac{d^2y}{dx^2} = 0$, use the first derivative test to determine the nature of the stationary point.

---
# Maxima & minima
For a function $y = f(x)$,
1. if $\frac{dy}{dx} = 0$ at $x = a$, then $f(a)$ is a **stationary value** of $y$;
2. if $\frac{dy}{dx} = 0$ only at $x = a$, and $\frac{d^2y}{dx^2} > 0$, then $f(a)$ is the **maximum value** of $y$;
3. if $\frac{dy}{dx} = 0$ only at $x = a$, and $\frac{d^2y}{dx^2}<0$, then $f(a)$ is the **minimum value** of $y$

By finding the **maximum** or the **minimum** of a function, we can solve some maximisation or minimisation problems.

---
# Rate of change
## Connected rates of change
Given two variables $x$ and $y$ related by the equation $y = f(x)$ and $x$ changes with time $t$, the rates of change $\frac{dx}{dt}$ and $\frac{dy}{dt}$,

$$ 
\frac{dy}{dt} = \frac{dy}{dx} \times \frac{dx}{dt} 
$$