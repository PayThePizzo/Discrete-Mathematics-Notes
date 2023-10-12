# Arguments and their Validity
In mathematics and logic an argument is not a dispute. It is simply a **sequence of statements ending in a conclusion**. In this section we show how to determine whether an argument is valid—that is, whether the conclusion follows necessarily from the preceding
statements

Table of Contents - Arguments

```text
Arguments/
	Arguments and Argument Forms - Definition
	Validity of Arguments
	Infer Validity of Arguments - Truth Tables
	Type of Arguments
		Syllogism
			Modus Ponens (or Deduction)

```

---

<br>

## Arguments and Argument Forms 
> An argument is a sequence of statements, and an argument form is a sequence
> of statement forms. 

We can divide them in two parts
* All statements in an argument and all statement forms in an argument form, except for the final one, are called **premises** (or assumptions or hypotheses)
* The final statement or statement form is called the **conclusion**. 
  * The symbol $\therefore$, which is read “therefore,” is normally placed just before the conclusion.

```math
\begin{align*}
  \text{if } p \text{ then } q \\
  p \\ 
  \therefore q
\end{align*}
```
When considering the abstract form of an argument, think of $p$ and $q$ as variables for
which statements may be substituted. 

An argument form is called **valid if, and only if,** whenever statements are substituted that make 
**all the premises true**, **the conclusion is also true**.

<br>

## Valid Arguments and Valid Argument Forms 
> To say that an argument form is valid means that no matter what particular
> statements are substituted for the statement variables in its premises, if the resulting
> premises are all true, then the conclusion is also true. To say that an argument is
> valid means that its form is valid

It is impossible to have a valid argument with all true premises and a false conclusion. When an
argument is valid and its premises are true, the truth of the conclusion is said to be inferred
or deduced from the truth of the premises.

## Testing an Argument for Validity - Truth Tables
1. Identify the premises and conclusion of the argument form.
2. Construct a truth table showing the truth values of all the premises and the conclusion.
   1. When you fill in the table, you only need to indicate the truth values for the conclusion in the rows where all 
   the premises are true (the critical rows) because the truth values of the conclusion in the other rows are
   irrelevant to the validity or invalidity of the argument.
1. A row of the truth table in which all the premises are true is called a critical row. 
   1. If there is a critical row in which the conclusion is false, then it is possible for an argument of the given form to have true premises 	and a false conclusion, and so the argument form is invalid. 
   2. If the conclusion in **every critical row is true**, then the argument form is valid.

Attention: If at least one premise of an argument is false, then we have no information about the 
conclusion: It might be true or it might be false!

--- 

<br>

## Rules of Inference  
> A rule of inference is a form of argument that is valid

Valid Argument Forms:

![Rules of Inference](../Resources/InferenceRules.png)

### 1 - Syllogisms
> An argument form consisting of two premises and a conclusion is called a syllogism.
> The first and second premises are called the **major premise** and **minor premise**, respectively.

Chains of arguments are often used to provide proof/demonstration for theorems. 
In fact, it is very common to face something like: $p_{0} \Rightarrow p_{1} \Rightarrow p_{2} \Rightarrow \ldots p_{n}$
where $p_{0}$ is usually called "postulate" or "axiom", which is argument that is considered true although no 
demonstration has been provided.

Two types of syllogism that are widely used are: Modus Ponens and Modus Tollens.

#### Deduction or Modus Ponens 
The term modus ponens is Latin meaning *method of affirming* (the conclusion is an affirmation)

It is a type of syllogism which implies reasoning of the form "if $p$ is true and $p \Rightarrow q$ is true, then $q$ is true"

```math
\begin{align*}
  \text{if } p \text{ then } q \\
  p \\ 
  \therefore q
\end{align*}
```

#### Modus Tollens 
The term modus ponens is Latin meaning *method of denying* (the conclusion is a denial)

It is a type of syllogism which implies reasoning of the form "if $p$ is true and $p \Rightarrow q$ is true, then $q$ is true"

```math
\begin{align*}
  \text{if } p \text{ then } q \\
  \sim q \\ 
  \therefore \sim p
\end{align*}
```

The validity of modus tollens can be shown to follow from modus ponens together with the fact that a conditional statement is logically equivalent to its contrapositive.


### 2 - Generalization
These argument forms are used for making generalizations. For instance, according to
the first, if p is true, then, more generally, “p or q” is true for any other statement q.

```math
p \\
\therefore p \vee q
```

Example:


### 3 - Specialization
These argument forms are used for specializing. When classifying objects according to
some property, you often know much more about them than whether they do or do not have
that property. When this happens, you discard extraneous information as you concentrate
on the particular property of interest.

Example: 

### 4 - Elimination


### 5 - Transitivity 