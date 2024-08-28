---
aliases:
  - Converse
  - Contrapositive
  - Biconditional
source: https://mfleck.cs.illinois.edu/building-blocks/version-1.3/logic.pdf
---
# Conditional Statements: Biconditional, Converse, Contrapositive,

## Conditional
- Represented as "if $p$, then $q$" or "$p \rightarrow q$"
	- Can think of as-> if $p$ is `true`, then whatever comes next is some bool value. This makes the statement itself true
	- If $p$ is `false` however, then it does not have the power of say
		- so the statement of `false` to `true` is not good (is `false`)
		- and, the statement of `false` to `false`, the statement itself, is `true`
$$
\begin{array}{|c|c|c|}
\hline
p & q & q \rightarrow p \\
\hline
T & T & T \\
T & F & T \\
F & T & F \\
F & F & T \\
\hline
\end{array}
$$

#### Relation
- *statement*: If it’s below zero, my car won’t start
- *converse*: If my car won’t start, it’s below zero
- *contrapositive*: If my car will start, then it’s not below zero.

### Biconditional
- Represented as $p ↔ q$
- A biconditional statement $p \leftrightarrow q$ is `true` if both $p$ and $q$ are either `true` or `false`. The truth table for a biconditional statement is as follows:

### Converse
- Converse of this is $q \rightarrow p$, and it is *NOT* the same\

### Contrapositive
- The contrapositive of $p → q$ is formed by swapping the roles of $p$ and $q$ and negating both of them to get $¬q → ¬p$
- Unlike the [[Conditional Statement|Converse]], contrapositive is equivalent to the original statement
