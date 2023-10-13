# Predicates and Quantified Statements 
> The symbolic analysis of predicates and quantified statements is called the predicate calculus

## Quantifiers
> Quantifiers allow us to introduce 

<br>

## Predicates
> Predicates are statements that can be either true or false, in their simplest definition

### Simple or Atomic Predicates $P$
Atomic predicates are similar to the building block of the propositions we just
covered. 

> They merely express relations between objects or properties that can be true or false.

Plus they do not include variables, just complete sentences such as: $3 < 5$ (T)

### Atomic Predicates with Variables $P(x)$
> They are sentences that express a relationship between a finite number of objects, possibly specified through variables.
> When the variables are interpreted through a *domain* or *universe*, predicates become statements and can take up a truth value.

So we can evaluate their validity and truth only after we choose the variables and their domains. 

Example: $x \text{ is a prime number }$, $x \in \mathbb{N}$ is the domain

#### Domain or Universe
> The domain or universe of a predicate variable is the set of all values that may be 
> substituted in place of the variable.

### Compound Predicates
> Compound predicates are obtained through the introduction of quantifiers and logical connectives

Example: 

---

<br>

## Truth Set of $P(x)$
If $P(x)$ is a predicate and $x$ has domain $D$, the truth set of $P(x)$ is the 
set of all elements of $D$ that make $P(x)$ true when they are substituted for $x$. 

The truth set of $P(x)$ is denoted:

```math
\begin{align*}
    \{ x \in D \mid P(x) \}
\end{align*}
```