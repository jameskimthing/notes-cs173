# Logical Equivalence
- Two (simple or compound) propositions $p$ and $q$ are logically equivalent if they are `true` for exactly the same input values
- The shorthand notation for this is $p ≡ q$
	- ex: $p → q$ is *logically equivalent* to $¬p ∨ q$
	- ex: $p ∧ ¬p ≡ F$
- In mathematics, the equal operator $=$ can only be applied to objects such as numbers

## Some useful logical equivalences
(the next 2 are called *De Morgan's Law*)
- $¬(p ∧ q) ≡ ¬p ∨ ¬q$
- $¬(p ∨ q) ≡ ¬p ∧ ¬q$
- $p ∧ ¬p ≡ F$
- $p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)$
- $p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)$
- $p → q ≡ ¬p∨q$
- $¬(∀x, P(x)) ≡ ∃x, ¬P(x)$ (check out [[Quantifiers]] if not sure what these are)
