# Logical Equivalence

---

## Logical Connectives

Summary of most used logical connectives

| **Priority** | **Name**      | **Known As**   | **Symbol**                | **Logically Equivalent to**                     |
|--------------|---------------|----------------|---------------------------|-------------------------------------------------|
| _1_          | Negation      | NOT            | $\urcorner p$ or $\sim p$ |                                                 |
| _2_          | Conjunction   | AND            | $p \wedge q$              |                                                 |
| _3_          | Disjunction   | OR (Inclusive) | $p \vee q$                |                                                 |
| _4_          | Conditional   | IF..THEN..     | $p \Rightarrow q$         | $(\sim p) \vee q$ and $(\sim q ) \Rightarrow p$ |
| _5_          | Biconditional | IF AND ONLY IF | $p \Longleftrightarrow q$ | $(p \Rightarrow q) \wedge (q \Rightarrow p)$    |

### NOT
> If $p$ is a statement variable, the negation of $p$ is “not $p$” or “It is not the case that $p$”
> and is denoted $\urcorner p$. It has opposite truth value from $p$: if $p$ is true, $\urcorner p$ is false; if $p$ is
> false, $\urcorner p$ is true.

| $p$ | $\urcorner p$ |
|-----|---------------|
|  T  |       F       |
|  F  |       T       |


### AND
> If $p$ and $q$ are statement variables, the conjunction of $p$ and $q$ is “p and q,” denoted 
> $p \wedge q$. It is true when, and only when, both $p$ and $q$ are true. If either $p$ or $q$ is false, 
> or if both are false, $p \wedge q$ is false.

| $p$ | $q$ | $p \wedge q$ |
|-----|-----|--------------|
|  T  |  T  |       T      |
|  T  |  F  |       F      |
|  F  |  T  |       F      |
|  F  |  F  |       F      |


### OR
> If $p$ and $q$ are statement variables, the disjunction of $p$ and $q$ is “p or q,” denoted
> $p \vee q$. It is true when either $p$ is true, or $q$ is true, or both $p$ and $q$ are true; it is false
> only when both $p$ and $q$ are false.

| $p$ | $q$ | $p \vee q$ |
|-----|-----|------------|
|  T  |  T  |      T     |
|  T  |  F  |      T     |
|  F  |  T  |      T     |
|  F  |  F  |      F     |


### IF THEN


### IFF


---

## Logical Equivalences

### Logically Equivalent Statements
> Two statements are called logically equivalent if, and only if, they have logically
> equivalent forms when identical component statement variables are used to
> replace identical component statements.

### Logically Equivalent Statement Forms
> Two statement forms are called logically equivalent if, and only if, they have identical
> truth values for each possible substitution of statements for their statement
> variables. The logical equivalence of statement forms $P$ and $Q$ is denoted by writing $P \equiv Q$.
