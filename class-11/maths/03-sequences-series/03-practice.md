# Sequences & Series — Practice Range

> **35 practice problems**, graded **Basic (10) · Medium (15) · Advanced (10)**. Each has an
> **approach hint** (open it only after a real attempt) and a **collapsible full solution**. Topics: AP, GP,
> infinite GP, AM/GM/HM, special-power sums, telescoping, AGP, Vₙ method.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

> **Key formulas:** AP $a_n=a+(n-1)d$, $S_n=\tfrac n2[2a+(n-1)d]$; GP $a_n=ar^{n-1}$, $S_n=a\tfrac{r^n-1}{r-1}$, $S_\infty=\tfrac{a}{1-r}$ ($|r|<1$); $\sum k,\ \sum k^2,\ \sum k^3$ standard.

---

## 📑 Index

- [Basic (P1–P10)](#basic)
- [Medium (P11–P25)](#medium)
- [Advanced (P26–P35)](#advanced)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (P1–P10)

### P1
> Find the 15th term of the AP $5, 8, 11, \dots$

<details><summary>🧭 Approach</summary>

$a_n = a + (n-1)d$ with $a=5$, $d=3$.
</details>

<details><summary>✅ Solution</summary>

$a_{15} = 5 + 14(3) = \boxed{47}$.
</details>

---

### P2
> Find the sum of the first 25 terms of $5, 8, 11, \dots$

<details><summary>🧭 Approach</summary>

$S_n = \tfrac n2[2a + (n-1)d]$.
</details>

<details><summary>✅ Solution</summary>

$S_{25} = \tfrac{25}{2}[10 + 24(3)] = \tfrac{25}{2}(82) = \boxed{1025}$.
</details>

---

### P3
> Find the 7th term of the GP $3, 6, 12, \dots$

<details><summary>🧭 Approach</summary>

$a_n = ar^{n-1}$, $r = 2$.
</details>

<details><summary>✅ Solution</summary>

$a_7 = 3\cdot2^6 = 3(64) = \boxed{192}$.
</details>

---

### P4
> Sum the first 6 terms of $3, 6, 12, \dots$

<details><summary>🧭 Approach</summary>

$S_n = a\tfrac{r^n - 1}{r - 1}$.
</details>

<details><summary>✅ Solution</summary>

$S_6 = 3\tfrac{2^6 - 1}{1} = 3(63) = \boxed{189}$.
</details>

---

### P5
> Find the sum to infinity of $9 + 3 + 1 + \tfrac13 + \dots$

<details><summary>🧭 Approach</summary>

GP, $a=9$, $r = \tfrac13$; $S_\infty = \tfrac{a}{1-r}$.
</details>

<details><summary>✅ Solution</summary>

$S_\infty = \tfrac{9}{1 - 1/3} = \tfrac{9}{2/3} = \boxed{13.5}$.
</details>

---

### P6
> Find the AM of 7 and 13.

<details><summary>🧭 Approach</summary>

$\tfrac{a+b}{2}$.
</details>

<details><summary>✅ Solution</summary>

$\tfrac{20}{2} = \boxed{10}$.
</details>

---

### P7
> Find the GM of 3 and 27.

<details><summary>🧭 Approach</summary>

$\sqrt{ab}$.
</details>

<details><summary>✅ Solution</summary>

$\sqrt{81} = \boxed{9}$.
</details>

---

### P8
> Find $\sum_{k=1}^{20} k$.

<details><summary>🧭 Approach</summary>

$\tfrac{n(n+1)}{2}$.
</details>

<details><summary>✅ Solution</summary>

$\tfrac{20(21)}{2} = \boxed{210}$.
</details>

---

### P9
> Find $\sum_{k=1}^{4} k^3$.

<details><summary>🧭 Approach</summary>

$\left[\tfrac{n(n+1)}{2}\right]^2$.
</details>

<details><summary>✅ Solution</summary>

$\left[\tfrac{4(5)}{2}\right]^2 = 10^2 = \boxed{100}$.
</details>

---

### P10
> The 3rd term of an AP is 12 and the common difference is 4. Find the first term.

<details><summary>🧭 Approach</summary>

$a_3 = a + 2d$.
</details>

<details><summary>✅ Solution</summary>

$12 = a + 8 \Rightarrow a = \boxed{4}$.
</details>

---

<a id="medium"></a>
## 🟡 Medium (P11–P25)

### P11
> The 5th term of an AP is 16 and the 9th is 28. Find the sum of the first 12 terms.

<details><summary>🧭 Approach</summary>

Two equations → $a, d$; then $S_{12}$.
</details>

<details><summary>✅ Solution</summary>

$a + 4d = 16$, $a + 8d = 28 \Rightarrow 4d = 12 \Rightarrow d = 3$, $a = 4$. $S_{12} = \tfrac{12}{2}[8 + 11(3)] = 6(41) = \boxed{246}$.
</details>

---

### P12
> Find three numbers in GP with sum 21 and product 216.

<details><summary>🧭 Approach</summary>

Take $\tfrac ar, a, ar$: product $= a^3$.
</details>

<details><summary>✅ Solution</summary>

$a^3 = 216 \Rightarrow a = 6$. $\tfrac6r + 6 + 6r = 21 \Rightarrow 6r^2 - 15r + 6 = 0 \Rightarrow 2r^2 - 5r + 2 = 0 \Rightarrow r = 2$ or $\tfrac12$. Numbers: $\boxed{3, 6, 12}$.
</details>

---

### P13
> Insert 4 geometric means between 5 and 160.

<details><summary>🧭 Approach</summary>

6 terms (GP); $r^5 = \tfrac{160}{5}$.
</details>

<details><summary>✅ Solution</summary>

$r^5 = 32 \Rightarrow r = 2$. Means: $\boxed{10, 20, 40, 80}$.
</details>

---

### P14
> $S_n = n^2 + 2n$ for a series. Find its 8th term.

<details><summary>🧭 Approach</summary>

$a_n = S_n - S_{n-1}$.
</details>

<details><summary>✅ Solution</summary>

$a_n = (n^2 + 2n) - ((n-1)^2 + 2(n-1)) = 2n + 1$; $a_8 = \boxed{17}$.
</details>

---

### P15
> Prove $a + b + c \ge 3\sqrt[3]{abc}$ for positive $a, b, c$, and state equality.

<details><summary>🧭 Approach</summary>

AM–GM on three numbers.
</details>

<details><summary>✅ Solution</summary>

$\tfrac{a+b+c}{3} \ge \sqrt[3]{abc}$, so $a+b+c \ge 3\sqrt[3]{abc}$; equality iff $a = b = c$.
</details>

---

### P16
> Find $\sum_{k=1}^{n} (2k - 1)$ (sum of first $n$ odd numbers).

<details><summary>🧭 Approach</summary>

Split: $2\sum k - \sum 1$.
</details>

<details><summary>✅ Solution</summary>

$2\cdot\tfrac{n(n+1)}{2} - n = n^2 + n - n = \boxed{n^2}$.
</details>

---

### P17
> The 2nd and 5th terms of a GP are 24 and 3. Find the first term.

<details><summary>🧭 Approach</summary>

$ar = 24$, $ar^4 = 3$; divide.
</details>

<details><summary>✅ Solution</summary>

$r^3 = \tfrac{3}{24} = \tfrac18 \Rightarrow r = \tfrac12$; $a = 48$. First term $= \boxed{48}$.
</details>

---

### P18
> Find $\sum_{k=1}^{n} \dfrac{1}{(2k-1)(2k+1)}$.

<details><summary>🧭 Approach</summary>

Partial fractions: $\tfrac12\left(\tfrac1{2k-1} - \tfrac1{2k+1}\right)$, telescopes.
</details>

<details><summary>✅ Solution</summary>

$\tfrac12\left(1 - \tfrac1{2n+1}\right) = \boxed{\dfrac{n}{2n+1}}$.
</details>

---

### P19
> If $a, b, c$ are in AP, show $b = \tfrac{a+c}{2}$, and find $b$ when $a = 7, c = 19$.

<details><summary>🧭 Approach</summary>

AP middle term = average.
</details>

<details><summary>✅ Solution</summary>

$2b = a + c \Rightarrow b = \tfrac{a+c}{2}$; $b = \tfrac{26}{2} = \boxed{13}$.
</details>

---

### P20
> A GP has $r = \tfrac23$ and $S_\infty = 27$. Find the first term.

<details><summary>🧭 Approach</summary>

$S_\infty = \tfrac{a}{1-r}$.
</details>

<details><summary>✅ Solution</summary>

$27 = \tfrac{a}{1 - 2/3} = 3a \Rightarrow a = \boxed{9}$.
</details>

---

### P21
> How many terms of $2 + 4 + 6 + \dots$ add up to 210?

<details><summary>🧭 Approach</summary>

$S_n = n(n+1)$ for this series (sum of first $n$ evens).
</details>

<details><summary>✅ Solution</summary>

$n(n+1) = 210 \Rightarrow n^2 + n - 210 = 0 \Rightarrow n = 14$. $\boxed{14}$ terms.
</details>

---

### P22
> The AM of two numbers is 25 and their GM is 20. Find them.

<details><summary>🧭 Approach</summary>

Roots of $x^2 - 2(25)x + 20^2 = 0$.
</details>

<details><summary>✅ Solution</summary>

$x^2 - 50x + 400 = 0 \Rightarrow (x - 10)(x - 40) = 0$. Numbers: $\boxed{10, 40}$.
</details>

---

### P23
> Find $\sum_{k=1}^{n} k(k+1)$ and evaluate at $n = 10$.

<details><summary>🧭 Approach</summary>

$\sum(k^2 + k)$; closed form $\tfrac{n(n+1)(n+2)}{3}$.
</details>

<details><summary>✅ Solution</summary>

At $n = 10$: $\tfrac{10(11)(12)}{3} = \boxed{440}$.
</details>

---

### P24
> The sum of three numbers in AP is 24 and the sum of their squares is 200. Find the numbers.

<details><summary>🧭 Approach</summary>

$a - d, a, a + d$: sum $= 3a = 24$.
</details>

<details><summary>✅ Solution</summary>

$a = 8$; $(8-d)^2 + 64 + (8+d)^2 = 200 \Rightarrow 128 + 2d^2 + 64 = 200 \Rightarrow 2d^2 = 8 \Rightarrow d = 2$. Numbers: $\boxed{6, 8, 10}$.
</details>

---

### P25
> If $a, b, c$ are in HP, show $\tfrac{a-b}{b-c} = \tfrac ac$.

<details><summary>🧭 Approach</summary>

HP → $\tfrac1a, \tfrac1b, \tfrac1c$ in AP, so $\tfrac1b - \tfrac1a = \tfrac1c - \tfrac1b$.
</details>

<details><summary>✅ Solution</summary>

$\tfrac1b - \tfrac1a = \tfrac{a-b}{ab}$ and $\tfrac1c - \tfrac1b = \tfrac{b-c}{bc}$; equating gives $\tfrac{a-b}{ab} = \tfrac{b-c}{bc} \Rightarrow \tfrac{a-b}{b-c} = \tfrac{ab}{bc} = \tfrac ac$. ∎
</details>

---

<a id="advanced"></a>
## 🔴 Advanced (P26–P35)

### P26
> Sum the infinite AGP $1 + 3x + 5x^2 + 7x^3 + \dots$ for $|x| < 1$.

<details><summary>🧭 Approach</summary>

Multiply-by-$x$ and subtract; AP coefficients $(2k-1)$.
</details>

<details><summary>✅ Solution</summary>

$S - xS = 1 + 2x + 2x^2 + \dots = 1 + \tfrac{2x}{1-x} = \tfrac{1+x}{1-x}$, so $S = \boxed{\dfrac{1+x}{(1-x)^2}}$.
</details>

---

### P27
> Find $\sum_{k=1}^{n} k(k+1)(k+2)$.

<details><summary>🧭 Approach</summary>

Vₙ method (product of 3 consecutive).
</details>

<details><summary>✅ Solution</summary>

$\boxed{\dfrac{n(n+1)(n+2)(n+3)}{4}}$.
</details>

---

### P28
> Minimise $4x + \dfrac{9}{x}$ for $x > 0$.

<details><summary>🧭 Approach</summary>

AM–GM on $4x$ and $\tfrac9x$.
</details>

<details><summary>✅ Solution</summary>

$\tfrac{4x + 9/x}{2} \ge \sqrt{4x\cdot\tfrac9x} = 6$, so $4x + \tfrac9x \ge 12$, equality at $4x = \tfrac9x \Rightarrow x = \tfrac32$. Minimum $\boxed{12}$.
</details>

---

### P29
> Find $\sum_{k=1}^{n} \dfrac{k}{(k+1)!}$.

<details><summary>🧭 Approach</summary>

Write $\tfrac{k}{(k+1)!} = \tfrac1{k!} - \tfrac1{(k+1)!}$; telescopes.
</details>

<details><summary>✅ Solution</summary>

$\sum = 1 - \tfrac{1}{(n+1)!} = \boxed{1 - \dfrac{1}{(n+1)!}}$.
</details>

---

### P30
> If $S_n = 3^n - 1$ is the sum of $n$ terms of a GP, find the common ratio.

<details><summary>🧭 Approach</summary>

$a_1 = S_1$; $a_2 = S_2 - S_1$; $r = a_2/a_1$.
</details>

<details><summary>✅ Solution</summary>

$a_1 = 2$; $a_2 = 8 - 2 = 6$; $r = \boxed{3}$.
</details>

---

### P31
> Prove that if $a, b, c, d$ are in GP, then $(a^2 + b^2 + c^2)(b^2 + c^2 + d^2) = (ab + bc + cd)^2$.

<details><summary>🧭 Approach</summary>

Equality case of Cauchy–Schwarz holds when ratios are equal — exactly the GP condition.
</details>

<details><summary>✅ Solution</summary>

In a GP, $\tfrac ab = \tfrac bc = \tfrac cd = \tfrac1r$. Cauchy–Schwarz gives $(ab+bc+cd)^2 \le (a^2+b^2+c^2)(b^2+c^2+d^2)$ with equality iff $\tfrac ab = \tfrac bc = \tfrac cd$, which holds. ∎
</details>

---

### P32
> Find the sum $\sum_{k=1}^{\infty} \dfrac{k^2}{2^k}$.

<details><summary>🧭 Approach</summary>

Use $\sum k^2 x^k = \tfrac{x(1+x)}{(1-x)^3}$ (from differentiating the GP twice), $x = \tfrac12$.
</details>

<details><summary>✅ Solution</summary>

$\tfrac{(1/2)(3/2)}{(1/2)^3} = \tfrac{3/4}{1/8} = \boxed{6}$.
</details>

---

### P33
> The sum of $n$ terms of two APs are in ratio $(3n + 8):(7n + 15)$. Find the ratio of their 12th terms.

<details><summary>🧭 Approach</summary>

Ratio of $n$-th terms = ratio of $S_{2n-1}$ sums; put $n = 2(12) - 1 = 23$.
</details>

<details><summary>✅ Solution</summary>

$\tfrac{a_{12}}{a'_{12}} = \tfrac{3(23) + 8}{7(23) + 15} = \tfrac{77}{176} = \boxed{\tfrac{7}{16}}$.
</details>

---

### P34
> Find $\sum_{k=1}^{n} \dfrac{2k+1}{k^2(k+1)^2}$.

<details><summary>🧭 Approach</summary>

Notice $\tfrac{2k+1}{k^2(k+1)^2} = \tfrac1{k^2} - \tfrac1{(k+1)^2}$; telescopes.
</details>

<details><summary>✅ Solution</summary>

$\sum = 1 - \tfrac1{(n+1)^2} = \boxed{\dfrac{n(n+2)}{(n+1)^2}}$.
</details>

---

### P35
> If $x > 0$, find the minimum of $x^2 + \dfrac{16}{x}$ using AM–GM (hint: split into equal parts).

<details><summary>🧭 Approach</summary>

Split $\tfrac{16}{x} = \tfrac8x + \tfrac8x$ so three terms have a constant product; apply AM–GM to $x^2, \tfrac8x, \tfrac8x$.
</details>

<details><summary>✅ Solution</summary>

$\tfrac{x^2 + 8/x + 8/x}{3} \ge \sqrt[3]{x^2\cdot\tfrac8x\cdot\tfrac8x} = \sqrt[3]{64} = 4$, so $x^2 + \tfrac{16}{x} \ge 12$, equality when $x^2 = \tfrac8x \Rightarrow x = 2$. Minimum $\boxed{12}$.
</details>

---

**Next:** [Deep Dive →](./04-deep-dive.md) · [Formula Recap →](./05-formula-recap.md)
