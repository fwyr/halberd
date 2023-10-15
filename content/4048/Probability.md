---
title: Probability
topic: "4048"
---
# Probability
**Probability** is a measure of the **chance** that an event will occur.
An **experiment** or **trial** is any course of action that generates a set of observable outcomes, and can be repeated under the same set of conditions (for example, tossing a coin).
An **outcome** of an experiment is the result which is obtained from the experiment. An outcome need not be numerical and may consist of more than one item of information. When an experiment is conducted at random, it means that all outcomes are equally likely. Equally likely outcomes are outcomes which have an equal chance of occurring.
The **sample space** or **possibility space** $S$ for an experiment is the [[(13) Set Theory|set]] of all possible outcomes of the experiment.
An **event** is a set of outcomes of an experiment satisfying a given condition. An event is a subset of the sample space. It may consist of a single outcome or several outcomes. Sure or definite events refer to events where the probability is 1, whereas impossible events refer to events where the probability is 0.

---
# Probability of single event
If the sample space $S$ consists of a finite number of equally likely outcomes, then the probability of an event $A$ occurring, denoted as $P(A)$, is defined as
$$
P(A) = \frac{\text{no. of elements in }A}{\text{no. of elements in }S} = \frac{n(A)}{n(S)} 
$$
## Probability laws
Let $S$ be the sample space and $A$ be a particular event.
We define $A'$ to be the **complement** of $A$, that is, the event in which $A$ does not occur.
The probability laws are
$$
\begin{gather*} 0 \leq P(A) \leq 1 \\ P(A\prime) = 1 - P(A) \end{gather*}
$$

---
# Diagrams
## Probability diagrams
To represent the sample space of a random event involving two stages in a systemic manner, a **possibility diagram** can be used.
### Non-numerical experiments
For example, tossing a coin provides a **non-numerical** situation concerning two stages of two outcomes.
A relevant possibility diagram is as shown.

| |Heads|Tails|
|---|---|---|
|Heads|⚫️|⚫️|
|Tails|⚫️|⚫️|

### Numerical experiments
In another example, rolling a 6-sided die twice gives us a **numerical** situation concerning two stages of six outcomes.
If we wanted to visualise all **possible sums** from the two die rolls, we can have a possibility diagram as shown.

|+|1|2|3|4|5|6|
|---|---|---|---|---|---|---|
|1|2|3|4|5|6|7|
|2|3|4|5|6|7|8|
|3|4|5|6|7|8|9|
|4|5|6|7|8|9|10|
|5|6|7|8|9|10|11|
|6|7|8|9|10|11|12|

It is worth noting that possibility diagrams are tedious to draw, and are also unsuitable in experiments with more than two sequences. Hence, possibility diagrams are infrequently used.
## ==Probability trees==
A probability tree helps to illustrate all possible events in an experiment consisting of two or more stages. The probability of each outcome is written on its branches, while the event is written on its nodes.

---
# Addition & multiplication of probabilities
## Mutually exclusive events
Two events $A$ and $B$ are said to be **mutually exclusive** if they **cannot occur simultaneously**.
In other words, $A$ and $B$ are mutually exclusive if $P(A\cap B) = 0$.
The **Addition Law of Probability** can be applied to mutually exclusive events.
$$
P(A\cup B)= P(A)+P(B)
$$
If events $A$ and $B$ are not mutually exclusive, the sets of sample spaces will intersect each other. In other words, events $A$ and $B$ are not mutually exclusive if $A$ and $B$ are not disjoint.
In this case, the probability of $A$ and $B$ occurring can be found as such.
$$
P(A\cup B) = P(A) + P(B) - P(A\cap B)
$$

## Independent events
Two events $A$ and $B$ are said to be **independent** if the occurrence of $A$ does not affect the occurrence of $B$.
The **Multiplication Law of Probability** can be applied to independent events. Given that the occurrence of A does not affect the occurrence of B, the probability of A and B occurring can be found as such.
$$
P(A\cap B) = P(A)\times P(B)
$$
