---
title: Set Theory
topic: "4048"
---
# Set notation
A set is a **collection** or **group** of well-defined objects. Each of the objects in the set is called a member or an element of the set.
Sets are commonly denoted by **capital** letters, with elements of a set being enclosed in curly brackets.
Consider set $A$, the set of even numbers between 1 and 9. $A$ can thus be defined by:
1. describing the set in words
	- $A$ is the set of even numbers between 1 and 9
2. listing the elements within curly brackets
	- $A = \{2,4,6,8\}$
3. describing the elements using the [set-builder notation](https://en.wikipedia.org/wiki/Set-builder_notation)
	- $A = \{x : x \text{ is an even number between 1 and 9}\}$
	- $A = \{2x : 1 \leq x \leq 4 \text{ and } x \text{ is an integer}\}$
## Notable sets
**Special symbols** are used to represent the various special sets of numbers in mathematics.

| Set of...             | Symbol         | Representation                                                                 |
| --------------------- | -------------- | ------------------------------------------------------------------------------ |
| Natural numbers       | $\mathbb{N}$   | $\{1,2,3,4,\dots\}$                                                            |
| Integers              | $\mathbb{Z}$   | $\{\dots,-3,-2,-1,0,1,2,3,\dots\}$                                             |
| Rational numbers      | $\mathbb{Q}$   | $\{x:x=\frac{p}{q}\text{, where }q\neq0\text{ and }p, q\text{ are integers}\}$ |
| Real numbers          | $\mathbb{R}$   |                                                                                |
| Positive integers     | $\mathbb{Z}^+$ | $\{1,2,3,4,\dots\}$                                                            |
| Negative integers     | $\mathbb{Z}^-$ | $\{\dots,-4,-3,-2,-1\}$                                                        |
| Positive real numbers | $\mathbb{R}^+$               |                                                                                |

In set notation, $\in$ and $\notin$ is used to represent that an element is/is not within a set.
For example, $1 \in \{1, 2, 3, 4\}$, whereas $5 \notin \{1, 2, 3, 4\}$.

---
# Types of sets
There are multiple types of sets:
- **equal sets**
	- two sets are said to be **equal** if they contain **exactly** the same elements
- **finite & infinite sets**
	- a set is said to be **finite** it we can list **all** the elements in it; conversely, a set is said to be **infinite** if it is **not possible** to list all elements in it.
	- for example, $\{1,2,3\}$ is a finite set, whereas $\mathbb{Z}$ is an infinite set.
- **null sets**
	- a null set is a set that has **no elements**; denoted by $\varnothing$ or $\{  \}$
- **disjoint sets**
	- two sets are said to be **disjoint** if they have **no common elements**
## Subsets
If **every** element in $B$ is also an element of $A$, then $B$ is a **subset** of $A$. This is represented by the notation $B \subset A$.
If $B$ is a subset of $A$, but $B \neq A$, then $B$ is a **proper subset** of $A$. This is represented by the notation $B \subseteq A$.

| Symbol          | Meaning                     |
| --------------- | --------------------------- |
| $\subset$       | is a subset of              |
| $\not\subset$   | is not a subset of          |
| $\subseteq$     | is a proper subset of       |
| $\not\subseteq$ | is not a proper subset of   |
| $\supset$       | is a superset of            |
| $\not\supset$   | is not a superset of        |
| $\supseteq$     | is a proper superset of     |
| $\not\supseteq$ | is not a proper superset of |

## Universal sets & complements
The **universal set** is the set which contains **all the elements** being considered in the question. It is denoted by $\xi$.
The **complement** of $A$ is the set that contains all the elements in $\xi$ which are **not elements** of $A$. It is denoted as $A'$.

---
# Venn diagrams
A **Venn diagram** is a visual tool composed of two or more closed loops, used to show relationships between different sets of items
In a Venn diagram, the universal set is represented by a rectangle whereas other sets are represented by closed loops. The label of the set is written close to and outside the corresponding loop.
The **common elements** for both sets are placed within the **overlapping** part of the loops representing the two sets.
## Intersection
Denoted by $A \cap B$, the intersection of sets $A$ and $B$ is the set of all elements which are **common** to both sets.
## Union
Denoted by $A\cup B$, the union of sets $A$ and $B$ is the set of **all** the elements which are in $A$, $B$, or both.