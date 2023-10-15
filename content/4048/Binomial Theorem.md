---
title: Binomial Theorem
topic: "4048"
---
# Expansion of binomials
The **binomial theorem** states that the expansion of a binomial $(a+b)^n$ can be expressed as 

$$
a^n + {n\choose1}a^{n-1}b + {n\choose2}a^{n-2}b^2 + \cdots + {n\choose n-1}ab^{n-1} + b^n
$$

Given a binomial $(a+b)^n$, there are some notable properties:
- there are $n+1$ terms in the expansion
- within each term, the sum of powers of $a$ and $b$ are equal to $n$
- the powers of $a$ are decreasing whereas the powers of $b$ are increasing
## Alternative expressions
The binomial expansion of $(a+b)^n$ could also be expressed as
$$
\begin{align*} (a+b)^n &= \sum_{i=0}^{n}{n\choose i}a^{n-i}b^i \end{align*}
$$
This is true for all values of $a$ and $b$ when $n > 0$.

---
# Combination
The binomial coefficient $n\choose r$ is defined as the following.
$$
{n \choose r} = \frac{n!}{(n-r)!r!} = \frac{n\times(n-1)\times\cdots\times(n-r+1)}{r\times(r-1)\times\cdots\times1}
$$

---
# General term
In the expansion of $(a+b)^n$, the general term ${n\choose r}a^{n-r}b^r$ is the general term, denoted as $T_{r+1}$.

$$
T_{r+1} = {n \choose r}a^{n-r}b^r
$$

## Finding a specific term
Given a binomial expression $(a+b)^n$ which includes the variable $x$, we can make use of the general term to find the power of $x$ in relation to $r$, where $r\in\mathbb{Z^+}$.
In other words, using the general term, we can transform it into
$$
T_{r+1} = {n\choose r}kx^{a}
$$
where $k$ is a constant, and $a$ is an expression only involving constants and/or $r$.

>[!example]
>Find the $x^4$ term in the binomial expression of $(3x+\frac{2}{x^2})^{10}$.
>The general term is as follows.
>$$
>T_{r+1} = {10 \choose r}(3x)^{10-r}\left(\frac{2}{x^2}\right)^r
>$$
>This can be rewritten into
>$$
>\begin{align*} T_{r+1} &= {10\choose r}(3)^{10-r}(2)^r \times x^{-2r+10-r} \\ &= {10\choose r}\left(3^{10-r}\times 2^r\right)\left(x^{10-3r}\right) \end{align*}
>$$
>Hence, we show that for the term $T_{r+1}$, the power of $x$ will always be $10-3r$.
>Finding the $x^4$-term, we set $10-3r=4\implies r=2$.
>$$
>\begin{align*} T_3 &= {10\choose 2}\left(3^{10-2}\times2^2\right)\left(x^{10-3\times2}\right) \\ &= {10\choose 2}\left(3^8\times2^2\right)\left(x^4\right) \\ &= 1\,180\,980x^4 \end{align*}
>$$
>$\therefore$ The $x^4$ term is $1\,180\,980x^4$.


