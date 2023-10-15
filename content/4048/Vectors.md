---
title: Vectors
topic: "4048"
---
# Definition of vectors
**Vectors** are represented graphically by a **directed line segment**, with **direction** and **magnitude**.
Such vectors can be written as $\begin{pmatrix}x\\y\end{pmatrix}$, $\overrightarrow{AB}$, or $\mathbf{a}$ (which is handwritten as $\underset{\sim}{a}$). 
The magnitude of a vector $\overrightarrow{AB}$ is represented by $\left|\overrightarrow{AB}\right|$. 
## Position & free vectors
**Position vectors**, or **fixed vectors**, are vectors with a **fixed starting position**, as opposed to **free vectors** with no specific location in space.

---
# Vector algebra
Two vectors are **equal** if they have the same **magnitude** and **direction**. In other words, if $\overrightarrow{AB} \parallel \overrightarrow{CD}$ and $\left|\overrightarrow{AB}\right| = \left|\overrightarrow{CD}\right|$, then $\overrightarrow{AB} = \overrightarrow{CD}$.
If two vectors $\overrightarrow{AB}$ and $\overrightarrow{CD}$ have the **same magnitude** but **opposite direction**, they are negative vectors; $\overrightarrow{AB} = -\overrightarrow{CD}$ and $\overrightarrow{CD} = -\overrightarrow{AB}$.  In particular, for any vector $\overrightarrow{AB}$, $\overrightarrow{AB}=-\overrightarrow{BA}$.
A zero vector, or null vector, is a vector with **zero magnitude** and no directional property. It is usually denoted by $\overrightarrow{O}$ or $\mathbf{0}$. If $\left|\overrightarrow{AB}\right| = 0$, then $\overrightarrow{AB} = \overrightarrow{O}$.

---
# Operations on vectors
## Addition
Two vectors can be added either by using the triangle law, parallelogram law, or the polygon law.
For any three vectors, $\mathbf{a}, \mathbf{b}$ and $\mathbf{c}$, the following properties hold true.
1. associative property — $(\mathbf{a} + \mathbf{b})+\mathbf{c}=\mathbf{a}+(\mathbf{b}+\mathbf{c})$
2. commutative property — $\mathbf{a}+\mathbf{b}=\mathbf{b}+\mathbf{a}$
3. additive identity property — $\mathbf{a}+\mathbf{0}=\mathbf{0}+\mathbf{a}$
4. additive inverse property — $\mathbf{a}+(-\mathbf{a}) = (-\mathbf{a})+\mathbf{a} =\mathbf{0}$
## Subtraction
The subtraction of two vectors $\overrightarrow{AB}$ and $\overrightarrow{CD}$ is simply the vector addition of vectors $\overrightarrow{AB}$ and $-\overrightarrow{CD}$.
## Scalar multiplication
Let $\mathbf{a}$ and $\mathbf{b}$ be two vectors, and let $m$ and $n$ be scalars.
The following properties hold true:
1. $m\mathbf{a}$ is a vector.
2. commutative property — $m(n\mathbf{a}) = n(m\mathbf{a})$
3. distributive property — $m(\mathbf{a}+\mathbf{b}) = m\mathbf{a}+m\mathbf{b}$

---
# Parallel vectors
Two non-zero vectors, $\overrightarrow{AB}$ and $\overrightarrow{CD}$, are said to be **parallel** if and only if $\overrightarrow{AB}$ can be expressed as a scalar multiple of $\overrightarrow{CD}$.
$$
\overrightarrow{AB} \parallel \overrightarrow{CD} \Longleftrightarrow \overrightarrow{AB} = k\,\overrightarrow{CD},\,k\in\mathbb{R},\,k\neq0
$$
## Collinear points
If three points $A$, $B$, and $C$ are **collinear**, then $AB$ and $AC$ are parallel. Hence, $\overrightarrow{AB} = k\,\overrightarrow{CD}$.
Conversely, if $\overrightarrow{AB} = k\,\overrightarrow{CD}$, then
- $\overrightarrow{AB}$ is parallel to $\overrightarrow{AC}$, and
- $AB$ and $AC$ share a common point $A$.

This implies that $A$, $B$, and $C$ must lie on the same line, hence they are collinear.
$$
A, B, C \text{ are collinear} \Longleftrightarrow \overrightarrow{AB} =k\,\overrightarrow{AC},\,k\in\mathbb{R},\,k\neq 0
$$
## Unit vectors
A **unit vector** is a vector with a magnitude of 1 unit, $\lvert \mathbf{x} \rvert = 1$.
The unit vector in the direction of vector $\mathbf{v}$ is denoted by $\mathbf{\hat{v}}$.
$$
\mathbf{\hat{v}} = \frac{1}{|\mathbf{v}|}\mathbf{v}
$$

---
# Vectors in two dimensions
For a position vector $\overrightarrow{OA}$, we call it the **position vector** of $A$ with respect to the **reference point** $O$, commonly referred to as the origin.
Unit vectors $\mathbf{i}$ and $\mathbf{j}$ are parallel to the $x$-axis and $y$-axis respectively.
$$
\begin{gather*} \mathbf{i} = \begin{pmatrix}1\\0\end{pmatrix}, & \mathbf{j} = \begin{pmatrix}0\\1\end{pmatrix} \end{gather*}
$$
Given a point $P = (a, b)$,
$$
\overrightarrow{OP} = a\mathbf{i} + b\mathbf{j} = \begin{pmatrix}a\\b\end{pmatrix}
$$
The magnitude of $\overrightarrow{OP}$ is $\sqrt{a^2 + b^2}$.
For vectors in 2 dimensions,

$$
\begin{align*} \begin{pmatrix}a\\b\end{pmatrix} = \begin{pmatrix}c\\d\end{pmatrix} &\Longleftrightarrow a=c \text{ and } b=d \\\\ \mathbf{0} &= \begin{pmatrix}0\\0\end{pmatrix} \\\\ \mathbf{a}\pm \mathbf{b} &= \begin{pmatrix}x_a\\y_a\end{pmatrix} \pm \begin{pmatrix}x_b\\y_b\end{pmatrix} \\ &= \begin{pmatrix}x_a \pm x_b\\y_a\pm y_b\end{pmatrix}\\\\ k\mathbf{a} &= k\begin{pmatrix}x\\y\end{pmatrix} \\ &= \begin{pmatrix}kx\\ky\end{pmatrix} \end{align*}
$$