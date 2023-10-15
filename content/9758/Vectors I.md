---
title: Vectors I
topic: "9758"
---
# Definition of vectors
**Scalars** are quantities that have magnitude but no associated direction.
**Vectors** ([[4048/Vectors|learnt previously]]) are quantities that have both **magnitude** and **direction**.
## Notation & geometrical representation
A vector, denoted by $\mathbf{a}$ (written as $\underset{\sim}{a}$), can be represented by a directed line segment $\overrightarrow{PQ}$, where
- the magnitude of $\mathbf{a}$ is the **length** of the line segment $PQ$, and
- the direction of $\mathbf{a}$ is the **direction** of the line segment from $P$ to $Q$
$P$ is the initial point and $Q$ is the terminal point. 
## Modulus of a vector
The **modulus** of a vector is its **magnitude**.
The modulus of $\mathbf{a}$ is $|\mathbf{a}|$.
## Negative vectors
The negative of a vector $\mathbf{a}$, denoted by $-\mathbf{a}$, has the same magnitude as $\mathbf{a}$ but the opposite direction.
Geometrically, if $\mathbf{a}$ is represented by $\overrightarrow{PQ}$, then $-\mathbf{a}$ is represented by $\overrightarrow{QP}$.
## Zero vectors
The **zero vector** (also known as a **null vector**), denoted by $\mathbf{0}$ or $\underset{\sim}{0}$, is the vector with zero magnitude and zero direction.
For any point $P$, $PP = \mathbf{0}$.
## Equal vectors
Two vectors $\mathbf{a}$ and $\mathbf{b}$ are said to be equal (i.e. $\mathbf{a}=\mathbf{b}$) if they have the **same** magnitude and the **same** direction.
## Parallel vectors
Consider two non-zero vectors $\mathbf{a}$ and $\mathbf{b}$. 
For some scalar $\lambda\in\mathbb{R}\setminus\{ 0 \}$, $\mathbf{a}$ is parallel to $\mathbf{b}$ (i.e. $\mathbf{a}\parallel\mathbf{b}$) if and only if $\mathbf{b}=\lambda \mathbf{a}$.
## Unit vectors
A unit vector is a vector with a magnitude of 1.
For any non-zero vector $\mathbf{a}$, the unit vector in the direction of $\mathbf{a}$ is denoted by $\mathbf{\hat{a}}$.
$$
\mathbf{\hat{a}}=\frac{1}{\lvert\mathbf{a}\rvert}\mathbf{a}
$$
Any vector $\mathbf{b}$ that is parallel and in the same direction as $\mathbf{a}$ can be written as $|\mathbf{b}|\mathbf{\hat{a}}$.
## Position & free vectors
There are two types of vectors — **position vectors** and **free vectors**.
A **position vector** is used to denote the location of a point. It defines the position of one point relative to another point.
A **free vector** (sometimes known as a **displacement vector**) is a vector with no associated position.

---
# Vector algebra
## Vector addition
Given two non-parallel vectors $\mathbf{a}$ and $\mathbf{b}$, the resultant vector of $\mathbf{a}+\mathbf{b}$ is as shown. This is known as the **triangle law of addition**.
![[Pasted image 20231010173352.png|350]]

Similarly, the addition of position vectors is such that, given three points $A$, $B$, and $C$,
$$
\overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC}
$$
Vector addition is **commutative** and **associative**.
Furthermore, for any vector $\mathbf{a}$, $\mathbf{a} + \mathbf{0} = \mathbf{0} + \mathbf{a} = \mathbf{a}$ and $\mathbf{a}+(-\mathbf{a})=(-\mathbf{a})+\mathbf{a}=\mathbf{0}$.
## Vector subtraction
The vector subtraction of $\mathbf{a}-\mathbf{b}$ is equivalent to the vector addition of $\mathbf{a}+(-\mathbf{b})$.
![[Pasted image 20231010173554.png|600]]
Any displacement vector can be written in terms of the position vectors of its end points.
$$
\overrightarrow{PQ} = \overrightarrow{OQ} - \overrightarrow{OP}
$$
## Scalar multiplication
Let $\mathbf{a}$ be a non-zero vector and $\lambda\in\mathbb{R}$ be a scalar.
The scalar multiple of $\mathbf{a}$ by $\lambda$, denoted by $\lambda \mathbf{a}$, is a vector whose direction depends on the sign of $\lambda$ as follows:
- if $\lambda>0$, then $\lambda \mathbf{a}$ and $\mathbf{a}$ are in the **same** direction
- if $\lambda=0$, then $\lambda \mathbf{a}$ is the zero vector (i.e. $\lambda \mathbf{a}=\mathbf{0}$)
- if $\lambda>0$, then $\lambda \mathbf{a}$ and $\mathbf{a}$ are in **opposite** directions
Let $m$ and $n$ be two scalar values and $\mathbf{a}$ and $\mathbf{b}$ be two vectors.
- $m\mathbf{a}=\mathbf{a}m$
- $(mn)\mathbf{a}=m(n\mathbf{a})=n(m\mathbf{a})$ — associative law of multiplication
- $(m+n)\mathbf{a}=m\mathbf{a}+n\mathbf{a}$ — distributive law of scalar addition
- $m(\mathbf{a}+\mathbf{b})=m\mathbf{a}+m\mathbf{b}$ — distributive law of vector addition

---
# Vectors in two dimensions
Any vector parallel to the 2-dimensional $x$-$y$ plane can also be represented in terms of components in the directions of the $x$ and $y$-axes.
In general, the two-dimensional position vector $\overrightarrow{OP}$ of a point $P$ with coordinates ($x$, $y$) is
$$
\overrightarrow{OP} = \begin{pmatrix}x\\y\end{pmatrix} \implies \left\lvert\overrightarrow{OP}\right\rvert = \sqrt{ x^{2}+y^{2} }
$$
We can also write $\overrightarrow{OP}=a\mathbf{i}+b\mathbf{j}$, where $\mathbf{i}$ and $\mathbf{j}$ are vectors of magnitude 1 in the $x$ and $y$ directions respectively.
$$
\begin{align*}
\mathbf{i}&=\begin{pmatrix}
1 \\
0
\end{pmatrix} &
\mathbf{j}&=\begin{pmatrix}
0 \\
1
\end{pmatrix}
\end{align*}
$$

---
# Vectors in three dimensions
Vectors can also be described in terms of components in the directions of the $x$, $y$, and $z$-axes.
In general, the three-dimensional position vector $\overrightarrow{OQ}$ of a point $Q$ with coordinates ($x$, $y$, $z$) is
$$
\overrightarrow{OQ} = \begin{pmatrix}x\\y\\z\end{pmatrix}\implies\left\lvert\overrightarrow{OQ}\right\rvert=\sqrt{ x^{2}+y^{2}+z^{2} }

$$
We can also write $\overrightarrow{OQ}=a\mathbf{i}+b\mathbf{j}+c\mathbf{k}$, where $\mathbf{i}$, $\mathbf{j}$ and $\mathbf{k}$ are vectors of magnitude 1 in the $x$, $y$, and $z$ directions respectively.

$$
\begin{align*}
\mathbf{i}&=\begin{pmatrix}
1 \\
0 \\
0
\end{pmatrix} &
\mathbf{j}&=\begin{pmatrix}
0 \\
1 \\
0
\end{pmatrix} &
\mathbf{k} &= \begin{pmatrix}
0 \\
0 \\
1
\end{pmatrix}
\end{align*}
$$

For 3-dimensional vectors, given vectors $\mathbf{a}$ and $\mathbf{b}$,
$$
\mathbf{a}\pm \mathbf{b}=\begin{pmatrix}
x_{1}  \\
y_{1}  \\
z_{1} \\
\end{pmatrix} \pm
\begin{pmatrix}
x_{2}  \\
y_{2}  \\
z_{2} \\
\end{pmatrix} =
\begin{pmatrix}
x_{1} \pm x_{2}  \\
y_{1} \pm y_{2}  \\
z_{1} \pm z_{2} \\
\end{pmatrix}
$$
The distance between two points $A(x_1, y_1, z_1)$ and $B(x_2, y_2, z_2)$ is given by the magnitude of $\overrightarrow{AB}$, denoted by $\left\lvert\overrightarrow{AB}\right\rvert$ or $AB$.
Since $\overrightarrow{AB}=\overrightarrow{OB}-\overrightarrow{OA}=\begin{pmatrix}x_2 - x_1 \\y_2 - y_1 \\z_2 - z_1\end{pmatrix}$,
$$
\left\lvert\overrightarrow{AB}\right\rvert = \sqrt{ (x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2} +(z_{2}-z_{1})^{2}}
$$

---
# Collinearity
>[!info] Collinearity Theorem
>Three points $A$, $B$, and $C$ are **collinear** (i.e. lie on a straight line) if and only if
> $$
>\overrightarrow{AB}=\lambda \overrightarrow{AC}\text{, where } \lambda\in\mathbb{R}\setminus \{ 0 \}
>$$
> In other words, $A$, $B$, and $C$ are colllinear if $AB$ is parallel to $AC$ with a common point $A$.

---
# Non-parallel vectors
## Equal non-parallel vectors
Consider two non-zero and non-parallel vectors $\mathbf{a}$ and $\mathbf{b}$.
If $\lambda \mathbf{a} = \mu \mathbf{b}$ for some scalars $\lambda,\mu\in\mathbb{R}$, then $\lambda=\mu=0$.
## Linear combinations
Consider two non-zero and non-parallel vectors $\mathbf{a}$ and $\mathbf{b}$.
Any vector $\mathbf{c}$ that is **coplanar** with (i.e. lies in the same plane as) $\mathbf{a}$ and $\mathbf{b}$ can be expressed as a **unique** linear combination of $\mathbf{a}$ and $\mathbf{b}$.
In other words, there exists a unique combination of $\alpha,\beta\in\mathbb{R}$ such that $\mathbf{c}=\alpha \mathbf{a}+\beta \mathbf{b}$.
If $\mathbf{a}$ and $\mathbf{b}$ are non-zero and non-parallel coplanar vectors such that $\alpha \mathbf{a}+\beta \mathbf{b}=\lambda \mathbf{a}+\mu \mathbf{b}$, then $\alpha=\lambda$ and $\beta=\mu$.

---
# Ratio theorem
>[!info] Ratio Theorem
>Considering the following triangle, $\overrightarrow{OA}$ and $\overrightarrow{OB}$ are two non-zero position vectors and $P$ is a point that divides $AB$ in the ratio $\lambda:\mu$.
>![[Pasted image 20231010180454.png|350]]
>Let $\mathbf{a}=\overrightarrow{OA}$, $\mathbf{b}=\overrightarrow{OB}$, and $\mathbf{p}=\overrightarrow{OP}$. The **ratio theorem** states that
>$$
>\mathbf{p}=\frac{\mu \mathbf{a}+\lambda \mathbf{b}}{\lambda+\mu}
>$$

---
# Scalar product
>[!info] Scalar Product
>![[Pasted image 20231010181620.png|500]]
>The **scalar product** (also known as the **dot product**) of two vectors $\mathbf{a}$ and $\mathbf{b}$ is defined as
>$$
>\mathbf{a}\cdot \mathbf{b}=|\mathbf{a}| |\mathbf{b}|\cos \theta
>$$
>where $\theta$ is the angle between $\mathbf{a}$ and $\mathbf{b}$ and $0º\leq\theta\leq 180º$.
>The scalar product takes two vectors and generates a scalar quantity

## Properties of scalar product
Given three non-zero vectors $\mathbf{a}$, $\mathbf{b}$, and $\mathbf{c}$, with $\theta$ being the angle between $\mathbf{a}$ and $\mathbf{b}$, and a scalar $\lambda\in\mathbb{R}\setminus \{ 0 \}$,
- $\mathbf{a}\cdot \mathbf{b}=\mathbf{b}\cdot\mathbf{a}$ — commutative
- $\lambda(\mathbf{a}\cdot\mathbf{b})=(\lambda \mathbf{a})\cdot \mathbf{b}=\mathbf{a}\cdot(\lambda \mathbf{b})$ — associative
- $\mathbf{a}\cdot(\mathbf{b}\pm \mathbf{c}) = (\mathbf{a}\cdot \mathbf{b})\pm(\mathbf{a}\cdot \mathbf{c})$ — distributive
- $\mathbf{a}\cdot \mathbf{b} >0$ if $0º<\theta<90º$ and $\mathbf{a}\cdot \mathbf{b}<0$ if $90º<\theta<180º$
	- $|\mathbf{a}\cdot \mathbf{b}|=|\mathbf{a}| |\mathbf{b}|$ if and only if $\mathbf{a}$ and $\mathbf{b}$ are parallel to each other
	- $\mathbf{a}\cdot \mathbf{b}=0$ if and only if $\mathbf{a}$ and $\mathbf{b}$ are perpendicular to each other
- $\mathbf{a}\cdot \mathbf{a}=|\mathbf{a}|^{2}$
## 3-dimensional scalar product
Given two vectors $\mathbf{a}=\begin{pmatrix}a_{1} \\a_{2} \\a_{3}\end{pmatrix}$ and $\mathbf{b}=\begin{pmatrix}b_{1} \\b_{2} \\b_{3}\end{pmatrix}$,
$$
\mathbf{a}\cdot \mathbf{b} =a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3}
$$

>[!example] Example — Scalar products in 3-dimensional space.
>Given $\mathbf{a}=\begin{pmatrix}1 \\2 \\1 \end{pmatrix}$ and $\mathbf{b}=\begin{pmatrix}2 \\3 \\-1 \end{pmatrix}$, find $(3\mathbf{a}-\mathbf{b})\cdot(2\mathbf{a}+\mathbf{b})$
>$$
>\begin{align*}
>(3\mathbf{a}-\mathbf{b})\cdot(2\mathbf{a}+\mathbf{b}) &= \left[3\begin{pmatrix}
>1\\2\\1
>\end{pmatrix}-\begin{pmatrix}
>2\\3\\-1
>\end{pmatrix}\right]\cdot
>\left[2\begin{pmatrix}
>1\\2\\1
>\end{pmatrix}+\begin{pmatrix}
>2\\3\\-1
>\end{pmatrix}\right] \\[5pt]
>&=\begin{pmatrix}
>1\\3\\4
>\end{pmatrix}\cdot \begin{pmatrix}
>4\\7\\1
>\end{pmatrix} \\[5pt]
>&=(1)(4)+(3)(7)+(4)(1) \\[5pt]
>&=29
>\end{align*}
>$$
>$\therefore (3\mathbf{a}-\mathbf{b})\cdot(2\mathbf{a}+\mathbf{b}) =29$

## Applications of scalar products
### Angle between two vectors
Since $\mathbf{a}\cdot \mathbf{b} = |\mathbf{a}| |\mathbf{b}| \cos \theta$, the angle between $\mathbf{a}$ and $\mathbf{b}$ is represented as
$$
\theta=\cos^{-1}\left(\frac{\mathbf{a}\cdot \mathbf{b}}{|\mathbf{a}| |\mathbf{b}|}\right)
$$
If $\mathbf{a}\cdot\mathbf{b} > 0$, $\theta$ is acute. If $\mathbf{a}\cdot \mathbf{b}<0$, $\theta$ is obtuse.
### Direction cosines
The **direction cosines** of a given vector $\mathbf{a}$ are the respective cosines of the angles between the vector and the **three coordinate axes**. Equivalently, they are the $x$, $y$, and $z$ components of the unit vector $\mathbf{\hat{a}}$.
The direction cosines are:
$$
\begin{gather*}
\cos \theta_{x}=\frac{\mathbf{a}\cdot\mathbf{i}}{|\mathbf{a}| |\mathbf{i}|} & 
\cos \theta_{y}=\frac{\mathbf{a}\cdot\mathbf{j}}{|\mathbf{a}| |\mathbf{j}|} &
\cos \theta_{z}=\frac{\mathbf{a}\cdot\mathbf{k}}{|\mathbf{a}| |\mathbf{k}|} 
\end{gather*}
$$
Note that $\cos ^{2}\theta_{x}+\cos ^{2}\theta_{y}+\cos ^{2}\theta_{z}=1$.
### Length of projection
Let $\mathbf{a}$ and $\mathbf{b}$ be two non-parallel vectors as shown below.
![[Pasted image 20231010231547.png|250]]
$PQ$ is known as the **length of projection** of $\mathbf{a}$ on $\mathbf{b}$.
$$
PQ=|\mathbf{a}\cdot \mathbf{\hat{b}}|
$$
$\overrightarrow{PQ}$ is known as the **projection** of $\mathbf{a}$ on $\mathbf{b}$, which is a component of $\mathbf{a}$ parallel to $\mathbf{b}$.
$$
\overrightarrow{PQ}=(\mathbf{a}\cdot \mathbf{\hat{b}})\mathbf{\hat{b}}
$$
$\overrightarrow{QR}$ is known as the component of $\mathbf{a}$ perpendicular to $\mathbf{b}$.
$$
\overrightarrow{QR}=\mathbf{a}-(\mathbf{a}\cdot \mathbf{\hat{b}})\mathbf{\hat{b}}
$$

==add example? refer to RI Vector I Example 15.==

---
# Vector product
>[!info] Vector Product
>The **vector product** (also known as the **cross product**) of two vectors $\mathbf{a}$ and $\mathbf{b}$ is defined as
>$$
>\mathbf{a}\times \mathbf{b}=(|\mathbf{a}| |\mathbf{b}| \sin\theta)\mathbf{n}
>$$
>where $\theta$ is the angle between $\mathbf{a}$ and $\mathbf{b}$, and $\mathbf{n}$ is the unit vector that is perpendicular to both vectors (as determined by the right-hand rule).

The right-hand rule states if the fingers of your right hand curl in the direction of a rotation (through an angle of less than 180º) from $\mathbf{a}$ to $\mathbf{b}$, then your thumb would point in the direction of $\mathbf{a}\times \mathbf{b}$ or $\mathbf{n}$.
![[Pasted image 20231011105942.png|200]]
$\mathbf{a}\times \mathbf{b}$ gives a vector that is **perpendicular** to $\mathbf{a}$ and $\mathbf{b}$. 
If $\mathbf{a}=\mathbf{0}$ or $\theta=0º$, then $\mathbf{a}\times \mathbf{b} = \mathbf{0}$.
## Properties of vector product
Given three non-zero vectors $\mathbf{a}$, $\mathbf{b}$, and $\mathbf{c}$, with $\theta$ being the angle between $\mathbf{a}$ and $\mathbf{b}$, and a scalar $\lambda\in\mathbb{R}\setminus \{ 0 \}$,
- $\mathbf{a}\times \mathbf{b}=-(\mathbf{b}\times \mathbf{a})$ — **anti**-commutative 
- $\lambda(\mathbf{a}\times \mathbf{b})=(\lambda \mathbf{a})\times \mathbf{b=\mathbf{a\times(\lambda \mathbf{b})}}$ — associative
- $\mathbf{a}\times (\mathbf{b}\pm \mathbf{c})=(\mathbf{a}\times \mathbf{b})\pm(\mathbf{a}\times \mathbf{c})$ — distributive
- $|\mathbf{a}\times \mathbf{b}|=|\mathbf{b}\times \mathbf{a}|=|\mathbf{a}| |\mathbf{b}| \lvert\sin{\theta}\rvert \leq|\mathbf{a}| |\mathbf{b}|$
- $\mathbf{a}$ is **parallel** to $\mathbf{b}$ if and only if $\mathbf{a}\times \mathbf{b}=\mathbf{0}$
	- in particular, $\mathbf{a}\times \mathbf{a}=\mathbf{0}$
- $\mathbf{a}$ is **perpendicular** to $\mathbf{b}$ if and only if $|\mathbf{a}\times \mathbf{b}|=|\mathbf{a}| |\mathbf{b}|$
	- in particular, $\mathbf{i}\times\mathbf{j}=\mathbf{k}$, $\mathbf{j}\times\mathbf{k}=\mathbf{i}$, and $\mathbf{k}\times\mathbf{i}=\mathbf{j}$
## 3-dimensional vector product
Given two vectors $\mathbf{a}=\begin{pmatrix}a_{1} \\a_{2} \\a_{3}\end{pmatrix}$ and $\mathbf{b}=\begin{pmatrix}b_{1} \\b_{2} \\b_{3}\end{pmatrix}$,
$$
\mathbf{a}\times \mathbf{b}=\begin{pmatrix}
a_{1}\\a_{2}\\a_{3}\\
\end{pmatrix}\times \begin{pmatrix}
b_{1} \\
b_{2}  \\
b_{3}  \\
\end{pmatrix}=
\begin{pmatrix}
a_{2}b_{3}-a_{3}b_{2} \\
a_{3}b_{1}-a_{1}b_{3} \\
a_{1}b_{2}-a_{2}b_{1}
\end{pmatrix}
$$
## Applications of vector product
### Area of triangle
The area of a triangle $\triangle ABC$ is given by
$$
\text{area of triangle ABC} = \frac{1}{2}\left|\overrightarrow{AB}\times \overrightarrow{AC}\right|
$$
### Area of parallelogram
The area of a parallelogram $ABCD$ is given by
$$
\text{area of parallelogram ABCD} =\left|\overrightarrow{AB}\times \overrightarrow{AD}\right|
$$
### Lengths of right-angled triangles
Let $\mathbf{a}$ and $\mathbf{b}$ be two non-parallel vectors as shown below.
![[Pasted image 20231010231547.png|250]]
From the scalar product's application on the [[9758/Vectors I#Length of projection|length of projection]], $PQ=\left|\mathbf{a}\cdot \mathbf{\hat{b}}\right|$.
We can infer that
$$
\begin{align*}
QR&=\left|\overrightarrow{PR}\right|\sin \theta \\[5pt]
&= \frac{\left|\overrightarrow{OA}\times\mathbf{b}\right|}{|\mathbf{b}|} \\[8pt]
&= \frac{|\mathbf{a}\times\mathbf{b}|}{\mathbf{b}} \\[5pt]
&= \left|\mathbf{a}\times \mathbf{\hat{b}}\right|
\end{align*}
$$
Summarising, in a right-angled triangle $\triangle PQR$,
- length of projection of $\mathbf{a}$ onto $\mathbf{b} = PQ = \left|\mathbf{a}\times \mathbf{\hat{b}}\right|$
- perpendicular distance from $R$ to $PQ = QR = \left|\mathbf{a}\times \mathbf{\hat{b}}\right|$ 

