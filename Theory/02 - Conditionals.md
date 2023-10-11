# Conditional Statements 

When you make a logical inference or deduction, you reason from a hypothesis to a conclusion. Your aim is to be able to say, “If such and such is known, then something or other must be the case.”

Let $p$ and $q$ be statements. A sentence of the form “**If** $p$ **then** $q$” is denoted symbolically by $p \Rightarrow q$;
* $p$ is called the hypothesis 
* And $q$ is called the conclusion.

## Implication - IF THEN
If $p$ and $q$ are statement variables, the conditional of $q$ by $p$ is “If $p$ then $q$” or
“$p$ implies $q$” and is denoted $p \Rightarrow q$. It is false when $p$ is true and $q$ is false; otherwise it is true. We call $p$ the hypothesis

| $p$ | $q$ | $\sim p$ | $(\sim p) \vee q$ | $p \Rightarrow q$ |
|-----|-----|----------|-------------------|-------------------|
| T   | T   | F        | **T**             | **T**             |
| T   | F   | F        | **F**             | **F**             |
| F   | T   | T        | **T**             | **T**             |
| F   | F   | T        | **T**             | **T**             |

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

> A conditional statement is logically equivalent to its contrapositive.

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
