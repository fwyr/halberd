---
title: Functions
topic: "9758"
---
# Relations 
A **relation** from a given set $A$ to a given set $B$ is a rule for connecting elements in $A$ (inputs) to elements in $B$ (outputs).

Set $A$ is known as the **domain** and set $B$ is known as the **codomain** of the relation.

Relations include **one-to-one** relations, **many-to-one** relations, and **one-to-many** relations.

---
# Functions
A **function** $f: X \mapsto Y$ is a relation which maps **each** element $x\in X$, to **only** one element $y\in Y$. Here, $y$ is said to be the **image** of $x$.
A function $f$ can be expressed algebraically as

$$
f: x\mapsto f(x),\, x\in X
$$

where $f(x)$ is the **rule** of the function $f$.

The set $X$ is the **domain** of the function $f$, denoted by $D_f$, and the set $Y$ is called the **codomain** of $f$.

## Range
Consider a function $f$ with domain $D_f$.

The range of $f$, denoted by $R_f$, is the set of images $\{ f(x) \}$, where $x\in D_f$.

## Even & odd functions
An **even** function $f$ is one such that $f(x) = f(-x)$ for all values of $x$. The graph of an even function is symmetrical about the $y$-axis.

An **odd** function $f$ is one such that $f(-x) = -f(x)$ for all values of $x$.  The graph of an odd function is symmetrical about the origin.

## Injective functions
A function is said to be **injective** (one-one) if no two elements in the given domain have the same image.

For any injective function $f$,
$$
\begin{gather*}
\forall x_{1}, x_{2} \in D_{f}\text{, if } x_{1}\neq x_{2}\text{, then } f(x_{1}) \neq f(x_{2}) \\[5pt]
\implies\text{if } f(x_{1})=f(x_{2})\text{, then } x_{1}=x_{2}
\end{gather*}
$$
Graphically, $f$ is injective if and only if every horizontal line $y=k$, $k\in\mathbb{R}_{f}$, cuts the graph of $f$ at **one and only one** point.

---
# Inverse functions
Let $f: X \mapsto Y$ be a function such that $f: x \mapsto y, x \in X$. Let $g: Y \mapsto X$ be a relation such that $x$ can be obtained from $g(y)$.
The relation $g$ is the **inverse of function** $f$. If $g$ is a function, then $g$ is called the **inverse function** represented by $f^{-1}$.
The inverse function $f^{-1}$ exists if and only if the function $f$ is **injective**.
The domain of $f^{-1}$ is the range of $f$, and the range of $f^{-1}$ is the domain of $f$.