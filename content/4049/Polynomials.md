---
title: Polynomials
topic: "4049"
---
# Polynomials
A **polynomial** in variable $x$ involves a sum of terms, each of the form $ax^n$, where $n$ is a **non-negative integer** and $a$ is a **real number**.
The **degree** of a polynomial in $x$ is its highest power of $x$.
Each term of a polynomial is in the form $ax^n$. The constant $a$ is called the **coefficient** of $x^n$. Coefficients are real numbers which can be of any sign.
Polynomials are commonly denoted as $P(x)$, $f(x)$, $g(x)$, etc.

---
# Identities
**Identities** are mathematical statements that are true for all real values of the variable(s) involved.
For example, $x(x+2) = (x+1)^2 -1$ is an identity.
To find unknown coefficients in an identity, we can
- equate coefficients of like powers of $x$ through inspection
- substitute suitable values of $x$
## Inspection
The process of inspection will be demonstrated by means of an example.

>[!example] Example — Solving by inspection.
>Given that $2x^3 - 5x^2 - 2x = (x-3)(ax^2-1) + (bx-3)(x+2) +c$ for all real values of $x$, find the values of constants $a$, $b$, and $c$.
>Comparing coefficients of $x^3$ terms,
>$$ 
>\begin{align*} 2 &= a \end{align*} 
>$$
>Comparing coefficients of $x^2$ terms
>$$ 
>\begin{align*} -5 &= -3a + b \\ b &= 1 \end{align*} 
>$$
>Comparing constant terms,
>$$ 
>\begin{align*} 0 &= 3 - 6 + c \\ c &= 3 \end{align*} 
>$$
>$\therefore a = 2, b = 1,$ and $c = 3$.

## Substitution
We can solve the previous exaple using substitution as well.

>[!example] Example — Solving by substitution.
>Given that $2x^3 - 5x^2 - 2x = (x-3)(ax^2-1) + (bx-3)(x+2) +c$ for all real values of $x$, find the values of constants $a$, $b$, and $c$.
>Substituting $x = 0$
>$$ 
>\begin{align*}0&=3-6+c\\c&=3\end{align*} 
>$$
>Substituting $x=3$,
>$$ 
>\begin{align*} 2(3)^3-5(3)^2-2(3)&=0+(3b-3)(3+2)+c\\ b&=1 \end{align*} 
>$$
>Substituting $x=-2$,
>$$
>\begin{align*} 2(-2)^3-5(-2)^2-2(-2)&=(-2-3)(4a-1)+0+c\\ a&=2 \end{align*} 
>$$
>$\therefore a = 2, b = 1,$ and $c = 3$.

---
# Long division
The **Division Algorithm** states that $\text{dividend} = \text{divisor} \times \text{quotient} + \text{remainder.}$
The order of the remainder is always **at least** **one degree less** than that of the divisor.

---
# Remainder theorem
>[!info] Remainder Theorem
>The **remainder theorem** states that when a polynomial $P(x)$ is divided by a linear divisor $(ax-b)$, the remainder is $P\left(\frac{b}{a}\right)$, where $a\neq 0$.

In particular, when $P(x)$ is divided by $(x-b)$, the remainder is $P(b)$.

---
# Factor theorem
>[!info] Factor Theorem
>The **factor theorem** states that if $(ax+b)$ is the factor of a polynomial $P(x)$, then $P\left(\frac{b}{a}\right) = 0$, and vice versa.

In particular, $(x-b)$ is a factor of $P(x) \Leftrightarrow P(\frac{b}{a})=0$.

---
# Cubic equations
To solve a cubic equation,
- define the polynomial as $f(x)$
- find a linear factor $(x-k)$ of $f(x)$ using the Factor Theorem by trial-and-error
- factorise $f(x)$ as $(x-k)(ax^2+bx+c)$ after using inspection coupled with comparing coefficients of like terms
- further factorise the quadratic factor $ax^2+bx+c$ if possible
- using the factorised form of $f(x)$, solve the equation $f(x)=0$ using the zero product property.

Note that sometimes, cubic expressions may involve the addition or subtraction of cubes.
The sum and differences of cubes can be used to factorise such cubic expressions.

$$
\begin{align*} a^3+b^3 &= (a+b)(a^2-ab+b^2)\\ a^3-b^3 &= (a-b)(a^2+ab+b^2) \end{align*} 
$$