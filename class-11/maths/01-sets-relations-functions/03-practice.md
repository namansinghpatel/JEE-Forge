# Sets, Relations & Functions — Practice Range

> **35 problems to solve yourself**, split **Basic (10) · Medium (15) · Advanced (10)** across sets,
> inclusion–exclusion, relations, functions, domain/range and composition/inverse. Each has a **💡 Approach
> hint** (reveal only if stuck) and a **collapsible answer**. Attempt with pen and paper first.

<!-- RENDERING: inside math use \cdot (not ·), \to, \geq/\leq, \in, \cup, \cap. -->

> **Notation:** $n(A)$ = number of elements; $g\circ f$ = composition (f first); ${}^nP_m$ = injective count.

---

## 📑 Index

- [Basic (P1–P10)](#basic)
- [Medium (P11–P25)](#medium)
- [Advanced (P26–P35)](#advanced)
- [How to log your attempts](#log)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (P1–P10)

**P1.** If $A=\{1,2\}$, $B=\{2,3,4\}$, find $A\cup B$.

<details><summary>💡 Approach hint</summary>

All elements in either set.
</details>

<details><summary>✅ Answer</summary>

$\{1,2,3,4\}$.
</details>

---

**P2.** Number of subsets of a 4-element set?

<details><summary>💡 Approach hint</summary>

$2^n$.
</details>

<details><summary>✅ Answer</summary>

$\mathbf{16}$.
</details>

---

**P3.** $n(A)=5$, $n(B)=2$. Find $n(A\times B)$.

<details><summary>💡 Approach hint</summary>

$n(A)\cdot n(B)$.
</details>

<details><summary>✅ Answer</summary>

$\mathbf{10}$.
</details>

---

**P4.** Domain of $f(x)=\dfrac{1}{x+5}$?

<details><summary>💡 Approach hint</summary>

Denominator $\ne 0$.
</details>

<details><summary>✅ Answer</summary>

$\mathbb{R}-\{-5\}$.
</details>

---

**P5.** Range of $f(x)=x^2+1$?

<details><summary>💡 Approach hint</summary>

Minimum at $x=0$.
</details>

<details><summary>✅ Answer</summary>

$[1,\infty)$.
</details>

---

**P6.** Number of relations from a 3-set to a 2-set?

<details><summary>💡 Approach hint</summary>

$2^{mn}$.
</details>

<details><summary>✅ Answer</summary>

$2^6=\mathbf{64}$.
</details>

---

**P7.** $(A\cap B)'=?$ (De Morgan)

<details><summary>💡 Approach hint</summary>

Complement flips ∩ to ∪.
</details>

<details><summary>✅ Answer</summary>

$A'\cup B'$.
</details>

---

**P8.** Is $f(x)=x^2$ even or odd?

<details><summary>💡 Approach hint</summary>

$f(-x)=?$
</details>

<details><summary>✅ Answer</summary>

**Even.**
</details>

---

**P9.** Domain of $\sqrt{5-x}$?

<details><summary>💡 Approach hint</summary>

Radicand $\ge 0$.
</details>

<details><summary>✅ Answer</summary>

$(-\infty,5]$.
</details>

---

**P10.** Number of functions from a 2-set to a 3-set?

<details><summary>💡 Approach hint</summary>

$n^m$.
</details>

<details><summary>✅ Answer</summary>

$3^2=\mathbf{9}$.
</details>

---

<a id="medium"></a>
## 🟡 Medium (P11–P25)

**P11.** Class of 50: 30 like maths, 25 like physics, 15 like both. How many like neither?

<details><summary>💡 Approach hint</summary>

$n(U)-n(M\cup P)$.
</details>

<details><summary>✅ Answer</summary>

$50-(30+25-15)=\mathbf{10}$.
</details>

---

**P12.** From P11, how many like exactly one subject?

<details><summary>💡 Approach hint</summary>

$(30-15)+(25-15)$.
</details>

<details><summary>✅ Answer</summary>

$15+10=\mathbf{25}$.
</details>

---

**P13.** Is "is a brother of" symmetric? (consider a set of people, all male)

<details><summary>💡 Approach hint</summary>

If a is brother of b, is b brother of a?
</details>

<details><summary>✅ Answer</summary>

Among males, yes symmetric (but in general, not — a sister complicates it).
</details>

---

**P14.** Domain of $f(x)=\dfrac{1}{\sqrt{x-1}}$?

<details><summary>💡 Approach hint</summary>

Under root and in denominator → strict.
</details>

<details><summary>✅ Answer</summary>

$x-1>0\Rightarrow(1,\infty)$.
</details>

---

**P15.** Number of one-one functions from a 3-set to a 5-set?

<details><summary>💡 Approach hint</summary>

${}^5P_3$.
</details>

<details><summary>✅ Answer</summary>

$5\cdot4\cdot3=\mathbf{60}$.
</details>

---

**P16.** $f(x)=2x+1$, $g(x)=x^2$. Find $(f\circ g)(2)$.

<details><summary>💡 Approach hint</summary>

$g$ first.
</details>

<details><summary>✅ Answer</summary>

$f(4)=\mathbf{9}$.
</details>

---

**P17.** Inverse of $f(x)=3x+4$?

<details><summary>💡 Approach hint</summary>

Solve $y=3x+4$ for $x$.
</details>

<details><summary>✅ Answer</summary>

$f^{-1}(x)=\dfrac{x-4}{3}$.
</details>

---

**P18.** Domain of $\log(3-x)$?

<details><summary>💡 Approach hint</summary>

Argument $>0$.
</details>

<details><summary>✅ Answer</summary>

$x<3\Rightarrow(-\infty,3)$.
</details>

---

**P19.** Range of $f(x)=\dfrac{1}{1+x^2}$?

<details><summary>💡 Approach hint</summary>

Max at $x=0$, approaches 0.
</details>

<details><summary>✅ Answer</summary>

$(0,1]$.
</details>

---

**P20.** Number of reflexive relations on a 2-set?

<details><summary>💡 Approach hint</summary>

2 diagonal forced; $n^2-n=2$ free.
</details>

<details><summary>✅ Answer</summary>

$2^2=\mathbf{4}$.
</details>

---

**P21.** Is $f(x)=x^3-x$ even, odd, or neither?

<details><summary>💡 Approach hint</summary>

$f(-x)$.
</details>

<details><summary>✅ Answer</summary>

**Odd** ($f(-x)=-x^3+x=-f(x)$).
</details>

---

**P22.** Three-set survey: $|A|=20,|B|=15,|C|=10$, pairwise overlaps 5,4,3, all-three 2. Find $|A\cup B\cup C|$.

<details><summary>💡 Approach hint</summary>

Inclusion–exclusion.
</details>

<details><summary>✅ Answer</summary>

$20+15+10-5-4-3+2=\mathbf{35}$.
</details>

---

**P23.** Is $f:\mathbb{R}\to\mathbb{R}$, $f(x)=2x+3$ bijective?

<details><summary>💡 Approach hint</summary>

Linear, non-zero slope.
</details>

<details><summary>✅ Answer</summary>

**Yes** (one-one and onto).
</details>

---

**P24.** Domain of $f(x)=\dfrac{x}{x^2-9}$?

<details><summary>💡 Approach hint</summary>

Denominator $\ne 0$.
</details>

<details><summary>✅ Answer</summary>

$\mathbb{R}-\{-3,3\}$.
</details>

---

**P25.** Number of onto functions from a 4-set to a 2-set?

<details><summary>💡 Approach hint</summary>

$2^4 - 2$.
</details>

<details><summary>✅ Answer</summary>

$16-2=\mathbf{14}$.
</details>

---

<a id="advanced"></a>
## 🔴 Advanced (P26–P35)

**P26.** Find the range of $f(x)=\dfrac{x-1}{x+1}$ ($x\ne -1$).

<details><summary>💡 Approach hint</summary>

Solve for $x$; which $y$ are excluded?
</details>

<details><summary>✅ Answer</summary>

$y=\dfrac{x-1}{x+1}\Rightarrow x=\dfrac{1+y}{1-y}$; $y\ne 1$. Range $\mathbb{R}-\{1\}$.
</details>

---

**P27.** How many equivalence classes does "congruent mod 7" have on $\mathbb{Z}$?

<details><summary>💡 Approach hint</summary>

Residues.
</details>

<details><summary>✅ Answer</summary>

$\mathbf{7}$.
</details>

---

**P28.** If $f(x)=\dfrac{1}{1-x}$, find $f(f(f(x)))$.

<details><summary>💡 Approach hint</summary>

Compose twice, then once more; look for a cycle.
</details>

<details><summary>✅ Answer</summary>

$f(f(x))=\dfrac{x-1}{x}$; $f(f(f(x)))=x$ (period-3 cycle).
</details>

---

**P29.** Number of bijections from a 5-set to itself?

<details><summary>💡 Approach hint</summary>

$n!$.
</details>

<details><summary>✅ Answer</summary>

$5!=\mathbf{120}$.
</details>

---

**P30.** Domain of $f(x)=\sqrt{x^2-3x+2}$.

<details><summary>💡 Approach hint</summary>

$(x-1)(x-2)\ge 0$.
</details>

<details><summary>✅ Answer</summary>

$(-\infty,1]\cup[2,\infty)$.
</details>

---

**P31.** Range of $f(x)=\dfrac{x^2}{1+x^2}$.

<details><summary>💡 Approach hint</summary>

Write as $1-\dfrac{1}{1+x^2}$.
</details>

<details><summary>✅ Answer</summary>

$[0,1)$.
</details>

---

**P32.** Number of relations on a 3-set that are reflexive and symmetric.

<details><summary>💡 Approach hint</summary>

3 off-diagonal unordered pairs, each free.
</details>

<details><summary>✅ Answer</summary>

$2^3=\mathbf{8}$.
</details>

---

**P33.** If $f(x)=ax+b$ and $f(f(x))=x$ for all $x$, find the relation between $a$ and $b$.

<details><summary>💡 Approach hint</summary>

Compose and match coefficients.
</details>

<details><summary>✅ Answer</summary>

$a^2=1$ and $b(a+1)=0$: so $a=1,b=0$ (identity) or $a=-1$, any $b$.
</details>

---

**P34.** Fundamental period of $f(x)=\sin 2x + \cos 3x$.

<details><summary>💡 Approach hint</summary>

LCM of periods $\pi$ and $\tfrac{2\pi}{3}$.
</details>

<details><summary>✅ Answer</summary>

LCM$(\pi,\tfrac{2\pi}{3})=\mathbf{2\pi}$.
</details>

---

**P35.** How many onto functions from a 3-set to a 3-set?

<details><summary>💡 Approach hint</summary>

Onto to same size = bijections = $3!$.
</details>

<details><summary>✅ Answer</summary>

$\mathbf{6}$.
</details>

---

<a id="log"></a>
## 🗒️ How to log your attempts

| Date | Problems attempted | First-try correct | Needed hint | Revisit |
|---|---|---|---|---|
| | | | | |

> [!TIP]
> Any problem you got wrong, copy into **[⭐ JEE Questions by Me](./02-solved-numericals.md#jee-questions-by-me)**
> and I'll write out the full strategy + solution so you master that exact type.

---

**Next:** [Deep Dive →](./04-deep-dive.md) · [Formula Recap →](./05-formula-recap.md)
