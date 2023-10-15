---
title: Partial Fractions
topic: "4049"
---
# Algebraic fractions
For two [[Polynomials|polynomials]] $f(x)$ and $g(x)$, the ratio $\frac{f(x)}{g(x)}$ is called a **rational expression** or **algebraic fraction**.
If the degree of the numerator $f(x)$ is **less than** the degree of the denominator $g(x)$, the fraction $\frac{f(x)}{g(x)}$ is said to be **proper**; otherwise, it is **improper**.

---
# Proper algebraic fractions
## Expression
To express a **proper algebraic fraction** $\frac{f(x)}{g(x)}$ in partial fractions, we factorise the denominator $g(x)$ completely and write down the forms of partial fractions.
If the denominator $g(x)$ has a linear factor $(ax+b)$, the partial fractions are

$$ 
\frac{f(x)}{g(x)} = \frac{A}{(ax+b)} + \frac{B}{Q(x)} 
$$

If the denominator $g(x)$ has a repeated linear factor $(ax+b)^n$, the partial fractions are
$$ 
\frac{f(x)}{g(x)} = \frac{A}{(ax+b)} + \frac{B}{(ax+b)^n} + \frac{C}{Q(x)} 
$$
If the denominator $g(x)$ has a quadratic factor $ax^2+bx+c$ that cannot be factorised, the partial fractions are
$$ 
\frac{f(x)}{g(x)} = \frac{Ax+B}{ax^2+bx+c} + \frac{C}{Q(x)}
 $$
## Solving
To solve for $A$, $B$, and $C$, multiply the entire equation by $g(x)$.
Thereafter, by comparison of the coefficients of the $x$ terms and the constant term, deduce the values of $A$, $B$, and $C$.
Inspection can also be used to eliminate certain factors to isolate the $A$, $B$, and $C$ terms.
### Cover-up rule
The cover-up rule only works for linear factors and the highest power term of a repeated linear factor.

>[!example] Example — Cover-up rule.
>Consider the following equation:
>$$
> \frac{3x+1}{(x+5)(x-2)} = \frac{A}{x+5} + \frac{B}{x-2} 
>$$
>To calculate the value of $A$, we equate its denominator to 0 and substitute that value of $x$ into the proper fraction. In the proper fraction, we have to “cover up” the factor which is in the denominator of $A$.
>To illustrate, the denominator of $A$ is $(x+5)$. Hence, we let $x = -5$ to equate its denominator to 0.
>After which, we “cover up” $(x+5)$ in the proper algebraic fraction and substitute $x = -5$ throughout.
>$$ 
>\begin{align*} A = \frac{3(-5)+1}{(-5)-2} = 2 \end{align*}
> $$
>The denominator of $B$ is $(x-2)$, hence we substitute $x=2$ and “cover up” $(x-2)$ in the proper algebraic fraction.
>$$ 
>B = \frac{3(2)+1}{(2)+5} = 1 
>$$
>Therefore, we get
>$$ 
>\frac{3x+1}{(x+5)(x-2)} = \frac{2}{x+5} + \frac{1}{x-2} 
>$$

---
# Improper algebraic fractions
An improper algebraic fraction must be first reduced to a **sum of a polynomial and a proper fraction**. This can be done by either splitting the numerator or using [[Polynomials#Long division|long division of polynomials]].
## Equal degrees
Consider the algebraic fraction $\frac{x^2+1}{x^2-x-2}$.
The goal is to get a constant multiple of the denominator as part of the numerator, by adding or subtracting terms.
$$ 
\begin{align*} \frac{x^2+1}{x^2-x-2} &= \frac{(x^2-x-2)+(x+3)}{x^2-x-2} \\ &= \frac{x^2-x-2}{x^2-x-2} + \frac{x+3}{x^2-x-2} \\ &= 1 + \frac{x+3}{x^2-x-2} \end{align*} 
$$
The proper fraction can then be solved.
Essentially, when the degree of $f(x)$ is equal to the degree of $g(x)$, we can always write
$$ 
f(x) = k\times g(x) + r(x) 
$$
where $k$ is a constant, and $r(x)$ is a polynomial such as the degree of $r(x)$ is always less than $g(x)$.
By doing so, we obtain
$$ 
\frac{f(x)}{g(x)} = \frac{k\times g(x)+r(x)}{g(x)} = k+\frac{r(x)}{g(x)} 
$$
where $\frac{r(x)}{g(x)}$ is a proper algebraic fraction.
## Greater degrees
We consider the case where the degree of $f(x)$ is greater than the degree of $g(x)$.
$$ 
\begin{align*} \frac{x^3-1}{2x-x^2} &= \frac{-x(2x-x^2) + 2x^2-1}{2x-x^2} \\ &= -x + \frac{2x^2-1}{2x-x^2} \end{align*} 
$$
Since $\frac{2x^2-1}{2x-x^2}$ is still an improper fraction, we continue splitting the fraction.
$$ 
\begin{align*} \frac{x^3-1}{2x-x^2} &= -x + \frac{2x^2-1}{2x-x^2} \\ &= -x -\frac{2(2x-x^2)}{2x-x^2} + \frac{4x-1}{2x-x^2} \\ &= -x-2 + \frac{4x-1}{2x-x^2} \end{align*} 
$$
Long division? What’s that? Anyway, moving on.
In general, given that the degree of $f(x)$ is greater than the degree of $g(x)$, the result can be stated as
$$ 
f(x) = g(x) \times q(x) + r(x) 
$$
which indicates that we obtain the form
$$ 
\frac{f(x)}{g(x)} = q(x) + \frac{r(x)}{g(x)} 
$$
where $\frac{r(x)}{g(x)}$ is a proper algebraic fraction.



