# Conditional Statements 

When you make a logical inference or deduction, you reason from a hypothesis to a conclusion. Your aim is to be able to say, “If such and such is known, then something or other must be the case.”

Let $p$ and $q$ be statements. A sentence of the form “**If** $p$ **then** $q$” is denoted symbolically by $p \Rightarrow q$;
* $p$ is called the hypothesis 
* And $q$ is called the conclusion.

---

## Implication - IF THEN
If $p$ and $q$ are statement variables, the conditional of $q$ by $p$ is “If $p$ then $q$” or
“$p$ implies $q$” and is denoted $p \Rightarrow q$. It is false when $p$ is true and $q$ is false; otherwise it is true. We call $p$ the hypothesis

| $p$ | $q$ | $\sim p$ | $p \Rightarrow q$ | $(\sim p) \vee q$ | $(\sim q) \Rightarrow \sim p$ |
|-----|-----|----------|-------------------|-------------------|-------------------------------|
| T   | T   | F        | **T**             | **T**             | **T**                         |
| T   | F   | F        | **F**             | **F**             | **F**                         |
| F   | T   | T        | **T**             | **T**             | **T**                         |
| F   | F   | T        | **T**             | **T**             | **T**                         |

The only combination of circumstances in which you would call a conditional sentence false occurs when the hypothesis is true and the conclusion is false. In all other cases, you would not call the sentence false.

A conditional statement that is true by virtue of the fact that its hypothesis is false is often called **vacuously true** or true by default
* Thus the statement “If you show up for work  Monday morning, then you will get the job” is vacuously true if you do not show up for work Monday morning. 
* In general, **when the “if” part of an if-then statement is false, the statement as a whole is said to be true, regardless of whether the conclusion is true or false**.

#### Representation through OR - IF THEN becomes Either OR
We can convert statements of the king "Either $\sim p$ or $q$ in If-Then statements easily:

```math
p \Rightarrow q \equiv (\sim p) \vee q
```

#### Negation of a conditional statement - IF THEN using AND
The negation of “if p then q” is logically equivalent to “p and not q.”: 

```math
\sim(p \Rightarrow q) \equiv p \wedge (\sim q)
```

<br>

## Contrapositive
The contrapositive of a conditional statement of the form "if $p$ then $q$" is "if $\sim q$ then $\sim p$"

```math
\text{The contrapositive of } p \Rightarrow q \text{ is } \sim q \Rightarrow \sim p
```

## Converse
The converse of a conditional statement of the form "if $p$ then $q$" is "if $q$ then $p$"

```math
\text{The contrapositive of } p \Rightarrow q \text{ is } q \Rightarrow p
```

## Inverse
The inverse of a conditional statement of the form "if $p$ then $q$" is "if $\sim p$ then $\sim q$"

```math
\text{The contrapositive of } p \Rightarrow q \text{ is } \sim p \Rightarrow \sim q
```

### Logical Equivalences and Contrapositive, Converse, Inverse of a Conditional Statement 
We must remember that:
1. A conditional statement is logically equivalent to its contrapositive.
2. A conditional statement and its converse are not logically equivalent.
3. A conditional statement and its inverse are not logically equivalent.
4. The converse and the inverse of a conditional statement are logically equivalent to each other.

---

## ONLY IF 
To say “p only if q” means that p can take place only if q takes place also. That is, if
q does not take place, then p cannot take place. Another way to say this is that if p
occurs, then q must also occur (by the logical equivalence between a statement and its
contrapositive).

If p and q are statements, $p$ **only if** $q$ means 
* “if **not** $q$ then **not** $p$”
* or, equivalently, “if $p$ then $q$.”

## IFF - Biconditional
Given statement variables $p$ and $q$, the biconditional of $p$ and $q$ is “$p$ if, and only if,
$q$” and is denoted $p \Longleftrightarrow q$. 

It is true if both $p$ and $q$ have the same truth values and is
false if $p$ and $q$ have opposite truth values. 

The words if and only if are sometimesabbreviated **iff**.

| $p$ | $q$ | $p \Rightarrow q$ Sufficient | $q \Rightarrow p$ Necessary | $(p \Rightarrow q) \wedge (q \Rightarrow p)$ | $p \Leftrightarrow q$ |
|-----|-----|------------------------------|-----------------------------|----------------------------------------------|-----------------------|
| T   | T   | T                            | T                           | **T**                                        | **T**                 |
| T   | F   | F                            | T                           | **F**                                        | **F**                 |
| F   | T   | T                            | F                           | **F**                                        | **F**                 |
| F   | F   | T                            | T                           | **T**                                        | **T**                 |

### Necessary and Sufficient Conditions
If $r$ and $s$ are statements for a bidirectional conditional iff $r \Longleftrightarrow s$:
* "r is a **sufficient** condition for s" means "if $r$ then $s$" or $r \Rightarrow s$
  * In other words, to say “r is a sufficient condition for s” means that the occurrence of r 
  is sufficient to guarantee the occurrence of s. 
* "r is a **necessary** condition for s" means "if not $r$ then not $s$" which also means "if $s$ then $r$" or $s \Rightarrow r$
  * On the other hand, to say “r is a necessary condition for s” means that if r does not occur, 
  then s cannot occur either: The occurrence of r is necessary to obtain the occurrence of s. 
* Consequently, "r is a **necessary and sufficient** condition for s" means “$r$ **if, and only if,** $s$.”

In order to demonstrate $r \Longleftrightarrow s$ we need to demonstrate both the sufficient and the necessary conditions