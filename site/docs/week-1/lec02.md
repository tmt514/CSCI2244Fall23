# Lecture 2 - Discrete Probability Basics

!!! note "Agenda"

    1. Formally define (discrete) probability space for common random objects.
    2. Probability Axioms.
    3. The naïve ways of analyzing probability events.
    4. Probability Paradoxes II - The Monty Hall Problem

## Readings

* [Alvarez] Sections 2.1-2.2; 3.1-3.2.

## Important Terms/Notations

* Probability Space: $(\Omega, P)$
* Sample Space: $\Omega$
* Probability Mass Function (PMF): $P$
* (Discrete) Uniform Distribution: _equiprobable outcomes_
* Events: $E\subseteq \Omega$
* Independent Events: $P(E_1\cap E_2) = P(E_1)P(E_2)$
* Random Variables: $X: \Omega\to \mathbb{R}$
* Independent Random Variables: $P(X=x \land Y=y) = P(X=x)P(Y=y)$

## Probability Axioms

* **Non-negativity of probability**: For any event $E$ we have $P(E)\ge 0$.
* **Probability of the sample space**: $P(\Omega)=1$.
* **Countable additivity**: For any countable set of disjoint events $\{A_1, A_2, \ldots\}$ we have

$$\begin{cases}
P(\bigcup_{i=1}^n A_i) = \sum_{i=1}^{n} P(A_i) & \text{if the set has finitely many events,}\\
P(\bigcup_{i=1}^\infty A_i) = \sum_{i=1}^{\infty} P(A_i) & \text{if the set has countably infinite sets.}
\end{cases}
$$

## Naive (But Useful!) Ways of Analyzing Probability Events

* Enumerate the entire sample space.
    * Venn Diagrams
* Drawing trees for coincident independent events.

