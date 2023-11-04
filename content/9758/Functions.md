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
This can be determined by sketching the graph of $f$ and analysing the range of its $y$-axis.
## Even & odd functions
An **even** function $f$ is one such that $f(x) = f(-x)$ for all values of $x$. The graph of an even function is symmetrical about the $y$-axis.
An **odd** function $f$ is one such that $f(-x) = -f(x)$ for all values of $x$.  The graph of an odd function is symmetrical about the origin.
## Injective functions
A function is said to be **injective** (one-one) if no two elements in the given domain have the same image.
For any injective function $f$,
$$
\begin{gather}
\forall x_{1}, x_{2} \in D_{f}\text{, if } x_{1}\neq x_{2}\text{, then } f(x_{1}) \neq f(x_{2}) \\[8pt]
\implies\text{if } f(x_{1})=f(x_{2})\text{, then } x_{1}=x_{2}
\end{gather}
$$
Graphically, $f$ is injective if and only if every horizontal line $y=k$, $k\in\mathbb{R}_{f}$, cuts the graph of $f$ at **one and only one** point.
### Test for injective functions
The **horizontal line test** is a **graphical** method for testing whether a function is injective.
To prove that a function $f$ is injective, either,
- show that **every** horizontal line $y=b, b\in R_f$ cuts the graph of $y=f(x), \,x\in D_f$ **exactly once**, or
- show that **every** horizontal line $y=b, b\in R_f$ cuts the graph of $y =f(x), \,x\in D_f$ **at most once**.
To prove that a function $f$ is **not** injective,
- provide a counter-example — find **one** horizontal line such that it cuts the graph of $y=f(x),\, x\in D_{f}$

---
# Inverse functions
Let $f: X \mapsto Y$ be a function such that $f: x \mapsto y, x \in X$. Let $g: Y \mapsto X$ be a relation such that $x$ can be obtained from $g(y)$.
The relation $g$ is the **inverse of function** $f$. If $g$ is a function, then $g$ is called the **inverse function** represented by $f^{-1}$.
$$
f^{-1}(y) = x \Leftrightarrow y=f(x) \text{ for } x \in D_{f}
$$
The inverse function $f^{-1}$ exists if and only if the function $f$ is **injective**.
The domain of $f^{-1}$ is the range of $f$, and the range of $f^{-1}$ is the domain of $f$.
$$
\begin{gather*}
D_{f^{-1}} = R_{f} \\
R_{f^{-1}} = D_{f}
\end{gather*}
$$
## Graphical relationship
In general, if $(a, b)$ is a point on the curve $y=f(x)$, then $(b, a)$ is on the curve $y = f^{-1}(x)$ since $f(a) = b \Leftrightarrow f^{-1}(b) = a$.
Graphs of $f$ and $f^{-1}$ are **reflections** of each other **in the line** $y=x$.
## Finding the rule
We can obtain the rule of $f^{-1}$ as follows:
1. Let $y = f(x)$.
2. Make $x$ the subject of the formula in terms of $y$.
3. Replace $y$ on RHS by $x$.

---
# Composite functions
A composite function is such that an initial function $f$ is applied to an input $x$, and afterwards applying another function $g$ to this output.
We denote this as the following.
$$
gf(x) =g(f(x)), \, x\in D_{f}
$$
## Existence of composite functions
For arbitrary functions $f$ and $g$, not all "outputs" of $f$ can be used as "inputs" for $g$, as not all images of $f$ may be elements in the domain of $g$.
As such, for the composite function $gf$ to exist as a function, each $x\in D_f$ must have a unique image $f(x)$, and for each image $f(x)$, it has to have one and only one image under the rule of $g$.
Thus, for any given functions $f$ and $g$,
1. the composite function $gf$ **exists when**
$$
R_{f} \subseteq D_{g}
$$
2. $D_{gf} = D_f$
## Range of composite functions
There are two methods of determining the range of a composite function $gf$:
1. use the graphs of both $y = f(x)$ and $y = g(x)$ to first obtain $R_f$ and then $R_{gf}$
2. sketch the graph of $gf$.
## Composition of function & its inverse
If a function $f: x\mapsto y$, its inverse function $f^{-1}: y \mapsto x$. It is then clear that $f^{-1}f(x) = f^{-1}(f(x)) = x$. Similarly, we obtain $ff^{-1}(x) = f(f^{-1}(x)) = x$. The composition function $f^{-1}f$ of $ff^{-1}$ will map any element in $x$ in its domain **to itself**.
However, though composite functions $f^{-1}f$ and $ff^{-1}$ have the **same rule**, they may have **different domains** as $D_{f^{-1}f} = D_f$, whilst $D_{ff^{-1}}=D_{f^{-1}}$.
 


