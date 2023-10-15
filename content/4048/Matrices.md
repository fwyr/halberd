---
title: Matrices
topic: "4048"
---
# Definition of a matrix
A **matrix** is a rectangular arrangement of numbers into rows and columns.
$$
A = \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}
$$
The **order** of a matrix $A$ is $m \times n$ where it has $m$ rows and $n$ columns.
Each element/entry in the matrix has an address. $A_{pq}$ refers to the element occupying the $p$-th row and $q$-th column of matrix $A$.
## Null matrix
A **null matrix** is denoted by $O$ and has 0 for all elements.
For example,
$$
O=\begin{pmatrix}
0 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 0
\end{pmatrix}
$$

---
# Operations
## Addition & subtraction
Matrix addition and subtraction is possible if both matrices are of the **same order**.
$$
\begin{pmatrix} a & b & c \\ d & e & f \end{pmatrix} \pm \begin{pmatrix} g & h & i \\ j & k & l \end{pmatrix}
\begin{pmatrix} a\pm g & b\pm h & c\pm i \\ d\pm j & e\pm k & f\pm l \end{pmatrix}
$$
Matrix addition is both 
- **commutative**, as $A + B = B + A$; and
- **associative**, as $(A + B) + C = A + (B + C)$.

Matrix subtraction is **not** commutative nor associative.
## Scalar multiplication
For a matrix $A$ and a real number $k$, the matrix $kA$ is obtained by multiplying every element of $A$ by $k$.
$$
k \times \begin{pmatrix} a & b & c \\ d & e & f \end{pmatrix} = \begin{pmatrix} ka & kb & kc \\ kd & ke & kf \end{pmatrix} 
$$
## Matrix multiplication
Two matrices can only be multiplied if the **number of columns** in $A$ is **equal** to the **number of rows** in $B$. That is, considering matrices $A$ and $B$, $AB$ exists only if $A$ is of order $m\times n$ and $B$ is of order $n\times k$. The resulting product matrix is of order $m \times k$.
In $AB$, entry $a_{ij}$ is the sum of the products of corresponding elements in row $i$ of $A$ and column $j$ of $B$. 
$$
\begin{pmatrix} a & b & c \\ d & e & f \end{pmatrix} \times \begin{pmatrix} g & h \\ i & j \\ k & l \end{pmatrix}

\begin{pmatrix} ag+bi+ck & ah+bj+cl \\ dg+ei+fk & dh+ej+fl \end{pmatrix} 
$$
Matrix multiplication is **not commutative** (i.e. $AB \neq BA$) but it is **associative** (i.e. $(AB)C = A(BC)$).

---
# Identity matrix
The identity matrix $I$ is a square matrix, where all the elements in the **leading diagonal** are 1. All other elements not in the leading diagonal are 0.
$$
I = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}
$$
If I and A are square matrices of the same order, then
$$
IA = AI = A
$$

---
# Inverse matrices
With reference to real numbers, the **multiplicative inverse** of $a$ is a value that when multiplied by $a$ would return 1.
In other words, the multiplicative inverse of $a$ is said to be $a^{-1}$, as $a \times a^{-1} = 1$.
In a similar vein, the multiplicative inverse of matrix $A$ is $A^{-1}$, as $A \times A^{-1} = I$.
$$
A^{-1} = \frac1{ad-bc}\begin{pmatrix}d & -b \\ -c & a\end{pmatrix} 
$$
## Determinant
For a $2 \times 2$ matrix $A = \begin{pmatrix}a & b \\ c & d\end{pmatrix}$, the **determinant** of $A$, denoted by $\begin{vmatrix}a & b \\ c& d\end{vmatrix}$, or $\det A$, is given by $ad - bc$.
$$
\det\begin{pmatrix}a&b\\c&d\end{pmatrix}=\begin{vmatrix}a&b\\c&d\end{vmatrix}=ad-bc
$$
As such, we can define the inverse of matrices as follows.
$$
A^{-1} = \frac{1}{\det A}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}
$$

---
# Matrix equations
Given an equation involving two known matrices $A$ and $B$ and an unknown matrix $C$, we can find $C$ by using the inverses of $A$ and $B$.
For example, if $AC = B$, we can find $A^{-1}$. Multiplying $A^{-1}$ to the front of each side gives us $C = A^{-1}B$, and hence $C$ can be solved.
If $CB=A$, we can find $B^{-1}$ and multiply it to the back of each side, thus giving us $C = AB^{-1}$ and allowing $C$ to be solved.
## Simultaneous equations
Simultaneous equations can be solved easily using matrix algebra.
Given a set of simultaneous equations as shown below,
$$
\begin{cases} 3x - 4y = -27 \\ -2x + 5y = 25 \end{cases}
$$
we can express it as a matrix equation as shown below.
$$
\begin{pmatrix}3&-4\\-2&5\end{pmatrix}\begin{pmatrix}x\\y\end{pmatrix} = \begin{pmatrix}-27\\25\end{pmatrix}
$$
The matrix $\begin{pmatrix}3&-4\\-2&5\end{pmatrix}$ in this scenario is known as the **coefficient matrix**.
The pair of simultaneous equations is now expressed as a matrix equation is of the form
$$
AX = B \text{, where } A = \begin{pmatrix}3&-4\\-2&5\end{pmatrix}\text{, } X=\begin{pmatrix}x\\y\end{pmatrix}\text{, and } B =\begin{pmatrix}-27\\25\end{pmatrix}
$$
### Special cases
If the determinant of the coefficient matrix is equal to 0, the method fails. Further investigation is needed to determine whether the simultaneous equations have **no solution** or **infinite solutions**.