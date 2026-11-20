# Sets, Relations & Functions — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning set operations,
> inclusion–exclusion, relations and their types, functions, domain/range, and composition/inverse. Every
> problem marks the **❓ Question** and **✅ Answer**; Medium and Advanced carry a **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \to, \geq/\leq, \in, \cup, \cap. -->

> **Notation:** $n(A)$ = number of elements; $P(A)$ = power set; $f: A \to B$ a function; $g\circ f$ = composition (f first).

---

## 📑 Index

- [Basic (B1–B10)](#basic) — set operations, subsets, Cartesian product, simple functions
- [Medium (M1–M15)](#medium) — inclusion–exclusion, relation types, domain/range, counting
- [Advanced (A1–A10)](#advanced) — composition/inverse, equivalence classes, injective/onto counts
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** If $A = \{1,2,3\}$ and $B = \{2,3,4\}$, find $A \cup B$ and $A \cap B$.

**✅ Answer.** $A\cup B = \{1,2,3,4\}$; $A\cap B = \{2,3\}$.

---

<a id="b2"></a>
### B2

> ❓ **Question.** How many subsets does a set with 5 elements have?

**✅ Answer.** $2^5 = \boxed{32}$.

---

<a id="b3"></a>
### B3

> ❓ **Question.** For $A = \{1,2,3\}$, $B = \{2,3,4\}$, find $A - B$.

**✅ Answer.** $A - B = \{1\}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** If $n(A) = 3$ and $n(B) = 4$, find $n(A \times B)$.

**✅ Answer.** $3 \times 4 = \boxed{12}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** Find the domain of $f(x) = \dfrac{1}{x-2}$.

**✅ Answer.** All real $x$ except $x = 2$: $\mathbb{R} - \{2\}$.

---

<a id="b6"></a>
### B6

> ❓ **Question.** Find the range of $f(x) = x^2$ ($x \in \mathbb{R}$).

**✅ Answer.** $[0, \infty)$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** How many relations are there from a set of 2 elements to a set of 3 elements?

**✅ Answer.** $2^{2\times3} = 2^6 = \boxed{64}$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** State De Morgan's law for $(A \cup B)'$.

**✅ Answer.** $(A \cup B)' = A' \cap B'$.

---

<a id="b9"></a>
### B9

> ❓ **Question.** Is $f(x) = x^3$ even, odd or neither?

**✅ Answer.** **Odd** ($f(-x) = -x^3 = -f(x)$).

---

<a id="b10"></a>
### B10

> ❓ **Question.** Find the domain of $f(x) = \sqrt{x - 3}$.

**✅ Answer.** $x - 3 \ge 0 \Rightarrow x \ge 3$, i.e. $[3, \infty)$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** In a class of 40, 25 play cricket, 20 play football, 10 play both. How many play neither?

> [!TIP]
> 🧭 **Strategy.** $n(C\cup F) = n(C)+n(F)-n(C\cap F)$; neither $= n(U) - n(C\cup F)$.

**Steps.** $n(C\cup F) = 25 + 20 - 10 = 35$; neither $= 40 - 35$.

**✅ Answer.** $5$.

---

<a id="m2"></a>
### M2

> ❓ **Question.** How many play exactly one of cricket/football (data of M1)?

> [!TIP]
> 🧭 **Strategy.** Exactly one $= n(C\cup F) - n(C\cap F)$, or $(25-10)+(20-10)$.

**Steps.** $15 + 10 = 25$.

**✅ Answer.** $25$.

---

<a id="m3"></a>
### M3

> ❓ **Question.** Let $R = \{(a,b) : a,b \in \{1,2,3\},\ a = b\}$. Is $R$ reflexive, symmetric, transitive?

> [!TIP]
> 🧭 **Strategy.** Check each property against the definition.

**Steps.** $R = \{(1,1),(2,2),(3,3)\}$ (the identity): reflexive ✓, symmetric ✓, transitive ✓.

**✅ Answer.** It is an **equivalence relation** (all three hold).

---

<a id="m4"></a>
### M4

> ❓ **Question.** Is the relation "is perpendicular to" on lines reflexive, symmetric, transitive?

> [!TIP]
> 🧭 **Strategy.** Test each with a quick example.

**Steps.** A line isn't ⊥ to itself (not reflexive); if $a\perp b$ then $b\perp a$ (symmetric ✓); $a\perp b$, $b\perp c$ gives $a\parallel c$ not ⊥ (not transitive).

**✅ Answer.** **Symmetric only** (not reflexive, not transitive).

---

<a id="m5"></a>
### M5

> ❓ **Question.** Find the domain of $f(x) = \dfrac{1}{\sqrt{4 - x^2}}$.

> [!TIP]
> 🧭 **Strategy.** Need $4 - x^2 > 0$ (strictly, because it's under a root **and** in a denominator).

**Steps.** $4 - x^2 > 0 \Rightarrow x^2 < 4 \Rightarrow -2 < x < 2$.

**✅ Answer.** $(-2, 2)$.

---

<a id="m6"></a>
### M6

> ❓ **Question.** Find the range of $f(x) = \dfrac{x}{1 + x^2}$ (real $x$).

> [!TIP]
> 🧭 **Strategy.** Set $y = \frac{x}{1+x^2}$, cross-multiply to a quadratic in $x$, require real $x$ (discriminant $\ge 0$).

**Steps.** $yx^2 - x + y = 0$; for real $x$: $1 - 4y^2 \ge 0 \Rightarrow y^2 \le \tfrac14$.

**✅ Answer.** $\left[-\tfrac12, \tfrac12\right]$.

---

<a id="m7"></a>
### M7

> ❓ **Question.** How many functions are there from a 3-element set to a 2-element set?

> [!TIP]
> 🧭 **Strategy.** Each of the 3 inputs independently maps to one of 2 outputs: $n^m = 2^3$.

**Steps.** $2^3 = 8$.

**✅ Answer.** $8$.

---

<a id="m8"></a>
### M8

> ❓ **Question.** How many one-one functions are there from a 2-element set to a 4-element set?

> [!TIP]
> 🧭 **Strategy.** Injective count $= {}^nP_m = 4\cdot3$.

**Steps.** ${}^4P_2 = 12$.

**✅ Answer.** $12$.

---

<a id="m9"></a>
### M9

> ❓ **Question.** If $f(x) = 2x + 3$ and $g(x) = x^2$, find $(g \circ f)(1)$ and $(f \circ g)(1)$.

> [!TIP]
> 🧭 **Strategy.** $(g\circ f)(x) = g(f(x))$; apply the inner function first.

**Steps.** $(g\circ f)(1) = g(5) = 25$; $(f\circ g)(1) = f(1) = 5$.

**✅ Answer.** $25$ and $5$ (note they differ — composition isn't commutative).

---

<a id="m10"></a>
### M10

> ❓ **Question.** Find the inverse of $f(x) = \dfrac{x - 1}{2}$.

> [!TIP]
> 🧭 **Strategy.** Set $y = f(x)$, solve for $x$, swap.

**Steps.** $y = \frac{x-1}{2} \Rightarrow x = 2y + 1$, so $f^{-1}(x) = 2x + 1$.

**✅ Answer.** $f^{-1}(x) = 2x + 1$.

---

<a id="m11"></a>
### M11

> ❓ **Question.** In a survey of 100 people, 60 like tea, 50 like coffee, 30 like both. How many like at least one?

> [!TIP]
> 🧭 **Strategy.** $n(T\cup C) = 60 + 50 - 30$.

**Steps.** $= 80$.

**✅ Answer.** $80$.

---

<a id="m12"></a>
### M12

> ❓ **Question.** Determine whether $f: \mathbb{R}\to\mathbb{R}$, $f(x) = x^2$ is one-one and/or onto.

> [!TIP]
> 🧭 **Strategy.** One-one: distinct inputs → distinct outputs? Onto: range = $\mathbb{R}$?

**Steps.** $f(2) = f(-2) = 4$ → not one-one; range $[0,\infty) \ne \mathbb{R}$ → not onto.

**✅ Answer.** Neither one-one nor onto (it's many-one, into).

---

<a id="m13"></a>
### M13

> ❓ **Question.** Find the domain of $f(x) = \log(x^2 - 5x + 6)$.

> [!TIP]
> 🧭 **Strategy.** Log needs a positive argument: $x^2 - 5x + 6 > 0$.

**Steps.** $(x-2)(x-3) > 0 \Rightarrow x < 2$ or $x > 3$.

**✅ Answer.** $(-\infty, 2) \cup (3, \infty)$.

---

<a id="m14"></a>
### M14

> ❓ **Question.** Let $A = \{1,2,3\}$. How many reflexive relations are there on $A$?

> [!TIP]
> 🧭 **Strategy.** The 3 diagonal pairs must be included; the other $n^2 - n = 6$ pairs are free.

**Steps.** $2^{6} = 64$.

**✅ Answer.** $64$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** Is $f(x) = |x|$ even, odd or neither? State its range.

> [!TIP]
> 🧭 **Strategy.** Check $f(-x)$; range from the graph.

**Steps.** $f(-x) = |-x| = |x| = f(x)$ → even; outputs are $\ge 0$.

**✅ Answer.** **Even**; range $[0, \infty)$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** In a group of 100, 40 read newspaper A, 30 read B, 20 read C, 10 read both A and B, 8 read B and C, 5 read A and C, 3 read all three. How many read none?

> [!TIP]
> 🧭 **Strategy.** Three-set inclusion–exclusion, then subtract from 100.

**Steps.** $n(A\cup B\cup C) = 40+30+20 - 10-8-5 + 3 = 70$; none $= 100 - 70$.

**✅ Answer.** $30$.

---

<a id="a2"></a>
### A2

> ❓ **Question.** How many onto functions are there from a 3-element set to a 2-element set?

> [!TIP]
> 🧭 **Strategy.** Total functions $2^3 = 8$; subtract the non-onto ones (those missing an image) by inclusion–exclusion: $2^3 - 2\cdot1^3$.

**Steps.** $8 - 2 = 6$.

**✅ Answer.** $6$.

---

<a id="a3"></a>
### A3

> ❓ **Question.** Let $R$ on $\mathbb{Z}$ be $aRb \iff a - b$ is divisible by 5. Show it is an equivalence relation and give the number of equivalence classes.

> [!TIP]
> 🧭 **Strategy.** Check reflexive/symmetric/transitive for "congruent mod 5"; classes = residues.

**Steps.** $a-a=0$ (÷5, reflexive); $a-b$÷5 ⇒ $b-a$÷5 (symmetric); divisibility is transitive. Classes are remainders $0,1,2,3,4$.

**✅ Answer.** It is an equivalence relation with **5** equivalence classes.

---

<a id="a4"></a>
### A4

> ❓ **Question.** Find the range of $f(x) = \dfrac{x^2 + x + 1}{x^2 + x - 1}$... simplify to $f(x) = 1 + \dfrac{2}{x^2+x-1}$ and reason, or set $y=f$ and use the discriminant. Find the range for real $x$ where defined.

> [!TIP]
> 🧭 **Strategy.** Cross-multiply $y(x^2+x-1) = x^2+x+1$, group into a quadratic in $x$, require discriminant $\ge 0$.

**Steps.** $(y-1)x^2 + (y-1)x - (y+1) = 0$. For $y \ne 1$: discriminant $(y-1)^2 + 4(y-1)(y+1) \ge 0 \Rightarrow (y-1)(5y+3) \ge 0 \Rightarrow y \le -\tfrac35$ or $y > 1$ (with $y=1$ excluded).

**✅ Answer.** $y \in \left(-\infty, -\tfrac35\right] \cup (1, \infty)$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** If $f(x) = \dfrac{x}{x-1}$ ($x \ne 1$), find $f(f(x))$.

> [!TIP]
> 🧭 **Strategy.** Substitute $f(x)$ into $f$ and simplify.

**Steps.** $f(f(x)) = \dfrac{\frac{x}{x-1}}{\frac{x}{x-1} - 1} = \dfrac{\frac{x}{x-1}}{\frac{x-(x-1)}{x-1}} = \dfrac{x}{1} = x$.

**✅ Answer.** $f(f(x)) = x$ (so $f$ is its own inverse — an involution).

---

<a id="a6"></a>
### A6

> ❓ **Question.** How many bijective functions are there from a set of 4 elements to itself?

> [!TIP]
> 🧭 **Strategy.** Bijections of an $n$-set = permutations = $n!$.

**Steps.** $4! = 24$.

**✅ Answer.** $24$.

---

<a id="a7"></a>
### A7

> ❓ **Question.** Find the domain of $f(x) = \sqrt{\dfrac{x-1}{x+2}}$.

> [!TIP]
> 🧭 **Strategy.** Need the fraction $\ge 0$ (and denominator $\ne 0$); sign chart.

**Steps.** $\frac{x-1}{x+2} \ge 0$ with $x \ne -2$: positive for $x < -2$ or $x \ge 1$.

**✅ Answer.** $(-\infty, -2) \cup [1, \infty)$.

---

<a id="a8"></a>
### A8

> ❓ **Question.** Let $f: \mathbb{R}\to\mathbb{R}$, $f(x) = 3x - 2$ and $g(x) = \dfrac{x+2}{3}$. Show $g = f^{-1}$.

> [!TIP]
> 🧭 **Strategy.** Check $f(g(x)) = x$ and $g(f(x)) = x$.

**Steps.** $f(g(x)) = 3\cdot\frac{x+2}{3} - 2 = x$; $g(f(x)) = \frac{(3x-2)+2}{3} = x$.

**✅ Answer.** Both compositions give $x$, so $g = f^{-1}$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** How many relations on a 3-element set are both reflexive and symmetric?

> [!TIP]
> 🧭 **Strategy.** Diagonal (3 pairs) forced in; the $\binom{3}{2}=3$ off-diagonal **unordered** pairs are each freely in/out (symmetric ⇒ both or neither).

**Steps.** $2^{3} = 8$ (one binary choice per unordered off-diagonal pair).

**✅ Answer.** $8$.

---

<a id="a10"></a>
### A10

> ❓ **Question.** Find the period of $f(x) = \sin x + \sin\!\left(\dfrac{x}{2}\right)$... careful: combine the periods. Give the fundamental period.

> [!TIP]
> 🧭 **Strategy.** Period of a sum = LCM of the individual periods.

**Steps.** $\sin x$ has period $2\pi$; $\sin(x/2)$ has period $4\pi$; LCM$(2\pi, 4\pi) = 4\pi$.

**✅ Answer.** $4\pi$.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style, and tag each
> with its difficulty and sub-topic (sets / relations / functions / domain-range / counting).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <sets/relations/functions/domain/counting>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
