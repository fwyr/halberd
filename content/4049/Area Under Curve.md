---
title: Area Under Curve
topic: "4049"
---

# Area bounded by $x$-axis
## Above the $x$-axis
Consider the diagram which shows the region $A$ bounded by the curve $y=f(x)$, the $x$-axis, and the lines $x=a$ and $x=b$.
![[Pasted image 20231015160954.png|400]]
This region is **above** the $x$-axis. Using integration, we can find the area of region $A$ to be
$$
\text{area of region A} = \int^b_{a} f(x) \, dx 
$$
## Below the $x$-axis
Consider the diagram which shows the region $B$ bounded by the curve $y=f(x)$, the $x$-axis, and the lines $x=a$ and $x=b$.
![[Pasted image 20231015161114.png|400]]
This region is **below** the $x$-axis. The area of region $B$ is hence given by
$$
\text{area of region B} = -\int_a^bf(x)\,dx = \int_b^af(x)\,dx = \left\lvert\int_a^bf(x)\,dx\right\lvert
$$
## Generalisation
The area, highlighted in green below, is enclosed by the curve $y=f(x)$ and the $x$-axis, with parts both **above** and **below** the $x$-axis.
![[Pasted image 20231015161353.png|400]]
As such, the total area enclosed by the curve $y=f(x)$, and the lines $x=a$ to $x=c$ is
$$
\text{shaded area} = \int_a^bf(x)\,dx - \int_b^cf(x)\,dx = \int_a^bf(x)\,dx + \int_c^bf(x)\,dx
$$

---
# Area bounded by $y$-axis
If the curve of $x = f(y) ≥ 0$ between $y =a$ to $y = b$, then the area enclosed by the curve, the $y$-axis, and the lines $y = a$ and $y = b$ is given by
![[Pasted image 20231015161550.png|200]]
$$ 
\text{area} = \int_a^bf(y)\,dy
$$
If the curve of $x = f(y) ≤ 0$ between $y = a$ to $y = b$, then the area enclosed by the curve, the $y$-axis, and the lines $y = a$ to $y=b$ is given by
![[Pasted image 20231015161651.png|200]]
$$
\text{area} = -\int_a^bf(y)\,dy
$$

For the combined case, the total area enclosed by the curve, the $y$-axis, and the lines $y=a$ to $y=b$ is given by

![[Pasted image 20231015161938.png|200]]
$$
\text{area} = \int_a^bf(y)\,dy - \int_b^cf(y)\,dy
$$

---
# Area bounded by two graphs
In general, the area $A$ bounded by two curves $y = f(x)$ and $y = g(x)$, where $f(x) ≥ g(x)$, is given by
$$
\text{area of region A} = \int_a^bf(x)\,dx-\int_a^bg(x)\,dx = \int_a^b[f(x)-g(x)]\,dx 
$$
![[Pasted image 20231015162120.png|350]]
By observation, we see that the function of the single integral is written as an expression of the function of the top curve and that of the bottom curve with respect to the enclosed and the axis.