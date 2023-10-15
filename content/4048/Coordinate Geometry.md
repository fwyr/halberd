---
title: Coordinate Geometry
topic: "4048"
---
# Equations of a straight line
## Gradient-intercept form
The gradient, $m$, of a straight line joining $A(x_1, y_1)$ and $B(x_2, y_2)$ is given by rise over run, formally:
$$ 
m = \frac{y_2-y_1}{x_2-x_1}, \text{ where } x_1 \neq x_2 
$$
The equation of a straight line expressed in **gradient-intercept form**, with gradient $m$ and $y$-intercept $c$ is
$$ 
y = mx + c 
$$

## Gradient-point form
The equation of a line can also be expressed in **gradient-point form**.
$$
y-y_1 = m(x-x_1) 
$$

---
# Collinear points
Three or more points are **collinear** if all these points lie on the same line.
If points $A$, $B$, and $C$ are collinear, then
$$ 
m_{AB} = m_{AC} = m_{BC} 
$$

---
# Gradient of lines
## Parallel lines
If two lines $l_1$ and $l_2$ are parallel, $l_1\parallel l_2$, then $m_{l_1} = m_{l_2}$.
In other words, if two lines are parallel, the two lines have equal gradients.
## Perpendicular lines
Two lines $y=m_1x+c_1$ and $y=m_2x+c_2$ are perpendicular if $m_1\times m_2=-1$.
The equation relating the gradient of a line and the gradient of its perpendicular bisector is
$$ 
m_1 = -\frac{1}{m_2} 
$$

---
# Distance formula
The distance between any two given points $A(x_1, y_1)$ and $B(x_2, y_2)$ is given by
$$ 
AB=\sqrt{\left(x_2-x_1\right)^2 + \left(y_2-y_1\right)^2} 
$$
This formula is derived using Pythagoras’ Theorem, and is commonly referred to as Euclidean distance.

---

# Midpoint
The midpoint between any two given points $A(x_1, y_1)$ and $B(x_2, y_2)$ is given by
$$ 
\left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}\right) 
$$

---
# Perpendicular bisector
The perpendicular bisector of a line segment $AB$ is the line that
- is **perpendicular** to $AB$, and
- **bisects** $AB$ (passes through the midpoint)
Any point on the perpendicular bisector is equidistant from points $A$ and $B$.

---
# Area of a polygon
The area of a polygon with $n$ sides is defined as the following.
$$ 
a = \frac{1}{2}\begin{vmatrix} x_1 & x_2 & x_3 & \dots &x_n &x_1 \\ y_1&y_2&y_3&\dots&y_n&y_1 \end{vmatrix} 
$$

This represents $a = (x_1y_2 + x_2y_3 + \cdots + x_ny_1) - (x_2y_1 + x_3y_2 + \cdots + x_1y_n)$, where the coordinates are written in a **cyclic anti-clockwise** direction.
This is known as the [**shoelace method**](https://en.wikipedia.org/wiki/Shoelace_formula).

---
# Proof of quadrilaterals
The identity of a quadrilateral $ABCD$ can be proved by examining its properties.
The properties needed to be shown for each quadrilateral are:
- trapezium
    - one pair of opposite sides are parallel
- kite
    - two pairs of adjacent sides are equal, or
    - one diagonal is the perpendicular bisector of the other diagonal
- parallelogram
    - both pairs of opposite sides are parallel and equal, or
    - diagonals bisect each other
- rhombus
    - $ABCD$ is a parallelogram and all sides are equal, or
    - diagonals bisect each other and are perpendicular
- rectangle
    - $ABCD$ is a parallelogram and adjacent sides are perpendicular, or
    - diagonals bisect each other and are equal in length
- square
    - $ABCD$ is a rectangle and all sides are equal, or
    - diagonals bisect each other and are perpendicular and equal