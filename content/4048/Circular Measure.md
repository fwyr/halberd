---
title: Circular Measure
topic: "4048"
---
# Arcs,  sectors & segments
Considering the following figure,

![[Pasted image 20231009194105.png|250]]

The length of arc $APB$ is given by

$$ 
\frac{x\degree}{360\degree}\times2\pi r 
$$

The area of sector $OAPB$ is given by

$$ 
\frac{x\degree}{360\degree}\times\pi r^2 
$$

The area of minor segment $APB$ is given by the area of sector $OAPB$ minus the area of triangle $OAB$.

$$ 
\frac{x\degree}{360\degree}\times\pi r^2 - \frac12r^2\sin{x\degree} 
$$

---
# Arc length
The arc length $s$ is given by the product of the size of the angle $\theta$ and the radius $r$ of the circle.
$$
s = r\times \theta \text{ (rad)}
$$
The angle subtended at the centre of a circle by an arc equal in length to the radius of the circle is defined as [[(07) Trigonometric Functions#Radians|one radian]].
In general, in a circle of radius $r$ cm, an arc of $s$ cm will subtend an angle of $\frac{s}{r}$ radians at the centre of the circle.
In other words, the size of the angle, in radians, is given by the ratio of the arc length $s$ to the radius $r$.
$$
\begin{align*} \theta\text{ (rad) } &= \frac{s}{r} \\[8pt] s &= \theta\text{ (rad) } \times r \end{align*} 
$$

---
# Area of a sector
The area of a sector is
$$
A = \frac{1}{2}r^2\theta =rs
$$
where $\theta$ is in radians.
The ratio of the area of a sector to the area of the circle is equal to the ratio of the angle subtended by the arc of the sector to the angle of a complete revolution.
$$
\begin{align*} \text{area of a sector OAPB} &= \frac{\theta}{2\pi}\times\pi r^2 \\[8pt] &= \frac12r^2\theta \end{align*}
$$
Therefore, the area of a sector is $A = \frac12r^2\theta = \frac12rs$, where $\theta$ is in radians.

---
# Area of a segment
For a circle of radius $r$,
$$
\begin{align*} \text{area of segment APB} &= \text{area of a sector AOBP} - \text{area of} \triangle{OAB} \\[8pt] &= \frac12r^2\theta - \frac12r^2\sin\theta \\[8pt] &= \frac12r^2\left(\theta-\sin\theta\right) \\ \end{align*}
$$
where $\theta$ is in radians.