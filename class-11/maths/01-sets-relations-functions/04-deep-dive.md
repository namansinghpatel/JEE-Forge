# Sets, Relations & Functions — Deep Dive

> The techniques that turn this chapter into quick marks: Venn-diagram counting, testing the three relation
> properties, the domain checklist and the two range methods, composition/inverse mechanics, and the
> counting formulas. Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \to, \geq/\leq, \in, \cup, \cap. -->

---

## 📑 Index

1. [Venn diagrams and inclusion–exclusion](#1-venn)
2. [Testing relation properties](#2-relations)
3. [The domain checklist](#3-domain)
4. [Two methods for range](#4-range)
5. [Composition and inverse mechanics](#5-composition)
6. [Counting: the four key formulas](#6-counting)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-venn"></a>
## 1. Venn diagrams and inclusion–exclusion

Any "how many study both / neither / exactly one" problem is inclusion–exclusion, best drawn as a Venn
diagram and **filled from the innermost region outward**:
$$n(A\cup B) = n(A)+n(B)-n(A\cap B)$$
$$n(A\cup B\cup C) = \textstyle\sum n - \sum n(\text{pairs}) + n(\text{triple})$$

- "**Neither**" = $n(U) - n(\text{union})$.
- "**Exactly one**" = $n(\text{union}) - n(\text{at least two})$, or sum the three "only" regions.

> [!TIP]
> Start with $n(A\cap B\cap C)$ (centre), then the pairwise-only regions (subtract the centre), then the
> single-only regions. Once the diagram is numbered, every "exactly/at least/at most" question is just a sum
> of regions.

---

<a id="2-relations"></a>
## 2. Testing relation properties

For a relation $R$ on $A$, check the three properties with their exact definitions:

| Property | Holds if… | Fails if you can find… |
|---|---|---|
| Reflexive | $aRa$ for **all** $a$ | one $a$ with $(a,a)\notin R$ |
| Symmetric | $aRb \Rightarrow bRa$ | one pair with $aRb$ but not $bRa$ |
| Transitive | $aRb, bRc \Rightarrow aRc$ | one chain breaking the conclusion |

**Equivalence** = all three → it **partitions** $A$ into disjoint classes.

> [!WARNING]
> "Symmetric + transitive ⇒ reflexive" is **false** (a common wrong deduction): the empty relation on a
> non-empty set is symmetric and transitive but not reflexive. Always test reflexivity separately. Classic
> traps: "⊥ to" (symmetric only), "≤" (reflexive, transitive, not symmetric).

---

<a id="3-domain"></a>
## 3. The domain checklist

Finding a domain is a mechanical checklist — list every restriction and intersect:

| Feature | Restriction |
|---|---|
| Denominator $\dfrac{1}{g(x)}$ | $g(x) \ne 0$ |
| Even root $\sqrt[2k]{g(x)}$ | $g(x) \ge 0$ |
| Even root in a denominator | $g(x) > 0$ (strict) |
| $\log g(x)$ | $g(x) > 0$ |
| $\arcsin/\arccos$ | argument in $[-1, 1]$ |

> [!TIP]
> When several features appear, write each restriction, solve, and take the **intersection** of the
> solution sets. A sign chart handles rational/root inequalities like $\frac{x-1}{x+2}\ge 0$ cleanly.

---

<a id="4-range"></a>
## 4. Two methods for range

1. **Solve for $x$:** set $y = f(x)$, solve for $x$ in terms of $y$, and keep the $y$-values that give a
   real $x$ in the domain. For $y = \frac{\text{quadratic}}{\text{quadratic}}$, this becomes "discriminant
   $\ge 0$ in $x$."
2. **Transform/known graph:** rewrite $f$ in terms of a known range (e.g. $\frac{1}{1+x^2}$: since
   $1 + x^2 \ge 1$, the fraction lies in $(0, 1]$); use symmetry/monotonicity.

> [!IMPORTANT]
> The **discriminant method** is the workhorse for rational functions: cross-multiply $y = \frac{P(x)}{Q(x)}$
> into a quadratic in $x$, then require its discriminant $\ge 0$ for real $x$. Don't forget to handle the
> leading-coefficient-zero case ($y$ making it linear) separately.

---

<a id="5-composition"></a>
## 5. Composition and inverse mechanics

- **Composition** $(g\circ f)(x) = g(f(x))$ — inner function first; **not commutative**; **associative**.
- **Inverse** exists **iff** $f$ is a **bijection**; then reflect the graph in $y = x$.
- Find $f^{-1}$: write $y = f(x)$, solve for $x$, swap $x \leftrightarrow y$.
- **Reverse-order law:** $(g\circ f)^{-1} = f^{-1}\circ g^{-1}$.

> [!NOTE]
> A function satisfying $f(f(x)) = x$ is an **involution** (its own inverse), e.g. $f(x) = \frac{1}{x}$,
> $f(x) = a - x$, $f(x) = \frac{x}{x-1}$. Spotting an involution instantly gives the inverse and simplifies
> iterated compositions.

---

<a id="6-counting"></a>
## 6. Counting: the four key formulas

For $n(A) = m$, $n(B) = n$:

| Count | Formula |
|---|---|
| Subsets of $A$ | $2^m$ |
| Relations $A \to B$ | $2^{mn}$ |
| Functions $A \to B$ | $n^m$ |
| Injective functions ($n \ge m$) | ${}^nP_m = \dfrac{n!}{(n-m)!}$ |
| Bijections of an $m$-set | $m!$ |
| Reflexive relations on $A$ | $2^{\,m^2 - m}$ |

**Onto functions** are found by inclusion–exclusion (subtract maps missing one or more images).

> [!IMPORTANT]
> Memorise the base four: **$2^m$ subsets, $2^{mn}$ relations, $n^m$ functions, ${}^nP_m$ injections.** The
> reflexive-relation count ($2^{m^2-m}$: diagonal forced, rest free) and symmetric-relation count
> ($2^{m(m+1)/2}$) follow from "which cells of the $m\times m$ grid are free."

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **$\varnothing$ is a subset of every set;** a set of $m$ elements has $2^m$ subsets.
> - **Symmetric + transitive does not imply reflexive** (test reflexivity separately).
> - **Range ⊆ codomain;** equal only for onto functions.
> - **Composition isn't commutative:** $g\circ f \ne f\circ g$ in general.
> - **Inverse needs a bijection;** $(g\circ f)^{-1} = f^{-1}\circ g^{-1}$ (reversed).
> - **Domain checklist:** no zero denominators, non-negative even roots, positive logs — then intersect.
> - **Counting:** $n^m$ functions, ${}^nP_m$ injections, $2^{m^2-m}$ reflexive relations.
> - **Period of a sum** = LCM of the individual periods.
