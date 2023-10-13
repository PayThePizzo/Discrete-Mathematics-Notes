# Predicates and Quantified Statements 
> The symbolic analysis of predicates and quantified statements is called the predicate calculus

<br>

## Quantifiers
> Quantifiers allow us to introduce 


<br>

## Predicates
> Predicates are statements that can be either true or false, in their simplest definition

### Simple or Atomic Predicates - P
Atomic predicates are similar to the building block of the propositions we just
covered. 

> They merely express relations between objects or properties that can be true or false.

Plus they do not include variables, just complete sentences such as: $3 < 5$ (T)

### Atomic Predicates with Variables - P(x)
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

There are many different combinations as we can use logical connectives (including conditionals), this 
is where it becomes hard to assess validity and/or truth.

<br>

## Truth Set 
If $P(x)$ is a predicate and $x$ has domain $D$, the truth set of $P(x)$ is the 
set of all elements of $D$ that make $P(x)$ true when they are substituted for $x$. 

The truth set of $P(x)$ is denoted:

```math
\begin{align*}
    \{ x \in D \mid P(x) \}
\end{align*}
```

---

<br>

## Universal Statement - "For all"
Let $Q(x)$ be a predicate and $D$ the domain of $x$. 

A universal statement is a statement of the form:

```math 
\begin{align*}
    \forall x \in D \mid Q(x)
\end{align*}
```

**True or false?**
* It is defined to be true if, and only if, $Q(x)$ is true **for each individual** $x$ in $D$. 
* It is defined to be false if, and only if, $Q(x)$ is false for at least one $x$ in $D$. 
  * A value for $x$ for which $Q(x)$ is false is called a **counterexample** to the universal statement.

Basically it is an abbreviated version of the $\wedge$ as each element of the domain is considered and
the truth depends on whether the predicate is applicable to all of those elements.

### Method of Exhaustion
It consists of showing the truth of the predicate separately for each individual element of the domain. (The idea is to exhaust the possibilities before you exhaust yourself!) This method can, in theory, be used whenever the domain of the predicate variable is finite

## Existential Statement - "There exists" 
Let $Q(x)$ be a predicate and $D$ the domain of $x$. 

An existential statement is a statement of the form:

```math 
\begin{align*}
    \exists x \in D \mid Q(x)
\end{align*}
```

**True or false?**
* It is defined to be true if, and only if, $Q(x)$ is true for at least one $x$ in $D$ namely there is an **example** . 
* It is false if, and only if, $Q(x)$ is false for all $x$ in $D$.

Basically it is an abbreviated version of the $\vee$ as each element of the domain is considered and
the truth depends on whether the predicate is applicable to at least one of those elements.


## Universal Conditional Statement

A universal conditional statement is a statement of the form:  

```math 
\begin{align*}
    \forall x \text{, if } P(x)  \text{ then } Q(x)
\end{align*}
```

<br>

---

## Watch out for!

### Bound Variables and Scope
We say that the variable $x$ is **bound** by the quantifier
that controls it and that its scope begins when the quantifier introduces it and ends at the
end of the quantified statement.

### Implicit Quantification
Let $P(x)$ and $Q(x)$ be predicates and suppose the common domain of $x$ is $D$.

The notation $P(x) \Rightarrow Q(x)$ means that every element in the truth set of $P(x)$ is in the
truth set of $Q(x)$, or, equivalently, $\forall x, P(x) \Rightarrow Q(x)$.

The notation $P(x) \Longleftrightarrow Q(x)$ means that $P(x)$ and $Q(x)$ have identical truth sets, or,
equivalently, $\forall x, P(x) \Longleftrightarrow Q(x)$.

---

<br>

## Equivalent Forms of Universal and Existential Statements

### Negation of Universal Statements
The negation of a universal statement (“all are”) is logically equivalent to an
existential statement (“some are not” or “there is at least one that is not”).

The negation of a statement of the form $\forall x \in D \mid P(x)$ is logically equivalent to:

```math 
\begin{align*}
    \sim (\forall x \in D \mid P(x)) \equiv \exists x \in D \mid \sim P(x) \\
\end{align*}
```

### Negation of Existential Statements 
The negation of an existential statement (“some are”) is logically
equivalent to a universal statement (“none are” or “all are not”).

The negation of a statement of the form $\exists x \in D \mid P(x)$ is logically equivalent to:

```math 
\begin{align*}
    \sim (\exists x \in D \mid P(x)) \equiv \forall x \in D \mid \sim P(x) 
\end{align*}
```

### Negation of Universal Conditional Statements

```math 
\begin{align*}
    \sim (\forall x \text{, } P(x) \Rightarrow Q(x)) \equiv \exists x \mid \sim (P(x) \Rightarrow Q(x)) \\
    \sim (\forall x \text{, } P(x) \Rightarrow Q(x)) \equiv \exists x \mid (P(x) \wedge \sim Q(x))
\end{align*}
```

--- 

<br>

## Vacuous Truth of Universal Statements
In general, a statement of the form:

```math 
\begin{align*}
    \forall x \in D \text{, } P(x) \Rightarrow Q(x)
\end{align*}
```
is called **vacuously true** or true by default if, and only if, $P(x)$ is false for every $x$ in $D$.
In mathematics, the words in **general** signal that what is to follow is a generalization of
some aspect of the example that always holds true.



## Variants of Universal Conditional Statements


## Necessary and Sufficient Conditions, Only If