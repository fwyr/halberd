---
title: Integration
topic: "4049"
---
# Indefinite integrals
**Integration** is the reverse process of differentiation.
$$ 
\frac{d}{dx} F(x) = f(x) \implies \int f(x)\,dx = F(x) +c 
$$
where $c$ is an arbitrary constant.
## Notation
$$ 
\int f(x)\,dx = F(x) + c 
$$

In the above equation,
- $\int f(x)\,dx$ is the **indefinite** integral of $f$ with respect to $x$
    - the integral is said to be “indefinite” because $c$ is an arbitrary constant
- $f(x)$ is the **integrand**
- $F(x)$ is the **integral**
- $c$ is the arbitrary constant of integration

$\int$ and $dx$ **must both be written**, with the integrand placed between them. $dx$ is written to show that the integrand is integrated with respect to $x$.
## Basic rules of integration
The first basic rule shown below may indicate the usefulness of [[Partial Fractions|partial fractions]].
$$ 
\int \left[\,f(x) \pm g(x) \,\right] \,dx = \int f(x)\,dx \,\pm \int g(x)\,dx 
$$
$$ 
\int kf(x)\,dx = k\int f(x)\,dx \text{ where } k \neq 0 
$$
## Powers
$$ 
\int x^n\,dx = \left(\frac1{n+1}\right)x^{n+1} + c \text{ where } n \neq 1 
$$
$$ 
\int (ax+b)^n\,dx = \left(\frac1{a(n+1)}\right)(ax+b)^{n+1} + c \text{ where } n \neq 1 
$$

## Trigonometric functions
Given a wacky funny trigonometric function (for instance, $\sin x\cos x$ or $4\sin^3x$), the main idea is to make use of [[(08) Trigonometric Identities|trigonometric identities]] and [[(09) Further Trigonometry|further trigonometry]] to transform these equations solely in the forms of $\cos x$, $\sin x$, or $\sec^2 x$.
$$
\int\cos(ax+b)\,dx = \frac1{a}\sin(ax+b) + c 
$$
$$
\int\sin(ax+b)\,dx = -\frac1{a}\cos(ax+b) + c
$$
$$
 \int\sec^2(ax+b)\,dx = \frac1{a}\tan(ax+b) + c 
$$
## Exponential functions
$$
 \int e^{ax+b} \,dx = \frac1{a}e^{ax+b} + c 
$$
$$
 \int f'(x)\,e^{f(x)} \, dx = e^{f(x)} + c 
$$
## Logarithmic function
$$
 \int \frac{1}{ax+b}\,dx = \frac1{a} \ln|ax+b| + c 
$$
$$
 \int\frac{f'(x)}{f(x)} \, dx = \ln |f(x)| + c 
$$
It is important to note the following caveat.
$$
n \neq -1 \implies \int \frac1{(ax+b)^n} \,dx \neq \frac1{a}\ln\left|(ax+b)^n\right] + c 
$$

---
# Definite integrals
Consider two constants $a$ and $b$. Given that $\frac{d}{dx}F(x) = f(x)$, then
$$ 
\begin{align*} F(b) - F(a) &= \left[\,f(x)\,\right]_a^b \\ &= \int_a^b f(x) \, dx \end{align*} 
$$
The integral $\int_a^b f(x)\,dx$ is known as a **definite integral**.
## Indefinite vs. definite integrals
The indefinite integral $\int f(x)\,dx$ is a **function of** $x$**.**
The definite integral $\int_a^b f(x)\,dx$ is a **numerical value**.
$$ 
\int_a^bf(x)\,dx=\left[F(x)\right]_a^b = F(b) - F(a) 
$$
## Properties
$$ 
\int_a^af(x)\,dx = 0 
$$
$$ 
\int_a^bf(x)\,dx = -\int_b^af(x)\,dx 
$$
$$ 
\int_a^bf(x)\,dx + \int_b^cf(x)\,dx = \int_a^cf(x)\,dx 
$$