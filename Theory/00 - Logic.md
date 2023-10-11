# Logic
Logic focuses on propositions (or statements)

--- 

<br>

## Basic Concepts for Statements
Here are some basic concepts before starting

### Truth Values
In mathematics the truth values are only two: **True** $T$ and **False** $F$

When we demonstrate a statement, we express a judgement under the form of a truth value:
* The statement is true if we have some kind of proof
* Otherwise the statement is false

### Mathematical Object
Mathematical objects can be of any type such as integer numbers, real numbers, 
matrices, sequences, sets, functions, ...

<br>

## Statements or Propositions
> A statement (or proposition) is a sentence (usually expressed through natural language) 
> that is true or false but not both.

Statements:
* Must take one truth value, **either**:
  * True
  * False
* Have different level of Complexity:
  * Simple (No logical connectives)
  * Compound (logical connectives)
* Can express general facts:
  * **Universal** : They say that if one thing is true then some other thing also has to be true
  * **Existential** : They say that there is at least one thing for which the property is true
  * Both
* Can be **Conditional** : They says that if one thing is true then some other thing also has to be true
  * **If...then...**
  * **If and only if**
* Can have different approaches to build a demonstration:
  * Ad Absurdum
  * Induction 
  * Through Examples (i.e Existential) or Counter-Examples (i.e. Universal)
  * Use of general properties
  * User of inference (sufficient/necessary condtions)

---

<br>

## Basic Concepts for Statement Forms
Now we might want to use some kind of placeholder in order to check 
if the statement can change of truth value when we use different pieces
of the puzzle.

### Variable
> A variable is placeholder for any kind of object

Usually indicated as $x, y, \ldots$

### Statement/Propositional Variables
> A statement/propositional variable is used to indicate a proposition. Basically
> the variabile contains a statement/proposition

Usually indicated as $p, q, r, t$ (tautologies) $, c$ (contradictions) $, \ldots$

<br>

## Statement Forms or Propositional Forms
> A statement form (or propositional form) is an expression made up of statement/propositional variables and logical connectives that becomes a statement when actual statements are substituted for the component statement variables. 

Once we constructed a statement form we can evaluate it through 

Statement Forms:
* Can take different truth values , **either**:
  * Always True (Tautologies)
  * Always False (Contradiction)
  * At least 1 instance is True (Satisfiable)
  * ... We just need to build a Truth Table! 
* Have different level of Complexity:
  * Simple (No logical connectives)
  * Compound (logical connectives)
* Can express general facts:
  * **Universal**
  * **Existential**
  * Both
* Can have **Conditional** forms
  * **If...then...**
  * **If and only if**
  * Both
* Can have different approaches to build a demonstration:
  * Ad Absurdum
  * Induction 
  * Through Examples (i.e Existential) or Counter-Examples (i.e. Universal)
  * Use of general properties
  * User of inference (sufficient/necessary condtions)
* Can be equivalent to other statement forms
  * Use the Truth Tables!

Once we constructed a statement form we can evaluate it through Truth tables

<br>

### Truth Tables
> The truth table for a given statement form displays the truth values
> that correspond to all possible combinations of truth values for its component statement variables

Truth tables are used for logical equivalence checks.

#### References
* [Epp, Susanna](https://condor.depaul.edu/~sepp/). [ETextbook: Discrete Mathematics With Applications, Metric Edition. Fifth Edition](https://condor.depaul.edu/~sepp/DM5e.htm), USA, © 2020, 2011, 2004 Cengage Learning, Inc., 2020.
  * Chapter 1: Speaking Mathematically
    * Section 1.1: Variables
  * Chapter 2: The Logic of Compound Statements 
    * Section 2.1: Logical Form and Logical Equivalence
