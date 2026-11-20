# Sequences & Series — Deep Dive

> Beyond the textbook: the **toolkit** that turns any "sum this series" question into a routine. The thread
> running through everything here is **identify the $n$-th term's structure, then pick the matching method.**

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

---

## 📑 Index

1. [The "find $a_n$ from $S_n$" trick and type-spotting](#1-an-from-sn)
2. [The AGP engine — multiply-by-$r$ in full](#2-agp)
3. [Telescoping: partial fractions and the difference trick](#3-telescoping)
4. [The Vₙ method for products of consecutive terms](#4-vn)
5. [AM–GM as an optimisation weapon (the "split" idea)](#5-amgm)
6. [Power-series sums via differentiation](#6-power)
7. [Ratio-of-sums ↔ ratio-of-terms shortcut](#7-ratio)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Practice](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-an-from-sn"></a>
## 1. The "find $a_n$ from $S_n$" trick and type-spotting

Given $S_n$ as a formula, the $n$-th term is
$$a_n = S_n - S_{n-1}\ (n \ge 2), \qquad a_1 = S_1.$$

**Type-spotting from $S_n$:**

| $S_n$ looks like | sequence is |
|---|---|
| linear in $n$ (e.g. $5n$) | constant sequence |
| quadratic, no constant term ($An^2 + Bn$) | **AP** (since $a_n = 2An + (B - A)$ is linear) |
| $A\cdot r^n - A$ (e.g. $3^n - 1$) | **GP** with ratio $r$ |

> [!IMPORTANT]
> A **quadratic $S_n$ ⟺ AP**, and a **$(r^n - 1)$-shaped $S_n$ ⟺ GP**. Memorising these two shapes lets you
> name the sequence before computing a single term. Always verify $a_1 = S_1$ separately — the formula
> $a_n = S_n - S_{n-1}$ is only valid for $n \ge 2$.

---

<a id="2-agp"></a>
## 2. The AGP engine — multiply-by-$r$ in full

An **arithmetic–geometric progression** has $T_k = [a + (k-1)d]\,r^{k-1}$ — an AP factor times a GP factor.

**The method, step by step** (finite sum $S_n$):
1. Write $S = a + (a+d)r + (a+2d)r^2 + \dots + [a+(n-1)d]r^{n-1}$.
2. Multiply by $r$: $rS = ar + (a+d)r^2 + \dots + [a+(n-1)d]r^n$.
3. Subtract: $S(1-r) = a + d(r + r^2 + \dots + r^{n-1}) - [a+(n-1)d]r^n$.
4. The middle is a GP — sum it, then divide by $(1-r)$.

**Infinite case** ($|r| < 1$, so $r^n \to 0$):
$$\boxed{S_\infty = \frac{a}{1-r} + \frac{dr}{(1-r)^2}}$$

> [!TIP]
> Recognise an AGP by a **term that is (linear in $k$) × (geometric in $k$)** — e.g. $\sum k x^k$,
> $\sum (2k-1)/2^k$. The "multiply-by-$r$, subtract" move is the *only* technique you need; after the
> subtraction the stubborn middle terms always collapse into a geometric series.

---

<a id="3-telescoping"></a>
## 3. Telescoping: partial fractions and the difference trick

If $T_k = f(k) - f(k+1)$, then $\sum_{k=1}^n T_k = f(1) - f(n+1)$ — everything in between cancels.

**Standard partial-fraction splits to memorise:**
$$\frac{1}{k(k+1)} = \frac1k - \frac1{k+1}, \qquad \frac{1}{k(k+2)} = \frac12\left(\frac1k - \frac1{k+2}\right),$$
$$\frac{1}{(2k-1)(2k+1)} = \frac12\left(\frac1{2k-1} - \frac1{2k+1}\right).$$

**Non-fraction telescoping** also appears: $\sqrt{k+1} - \sqrt{k}$ (rationalise $\tfrac1{\sqrt{k+1}+\sqrt k}$),
and factorial forms $\tfrac{k}{(k+1)!} = \tfrac1{k!} - \tfrac1{(k+1)!}$.

> [!IMPORTANT]
> The cue for telescoping is a **reciprocal of a product** (or a factorial, or a surd denominator). Split
> into a difference, write out the first two and last two terms to see the cancellation pattern, and only
> the **surviving boundary terms** remain. A 2-apart split ($\tfrac1{k(k+2)}$) leaves *two* terms at each end.

---

<a id="4-vn"></a>
## 4. The Vₙ method for products of consecutive terms

For $T_k = k(k+1)(k+2)\cdots(k+m-1)$ (a product of $m$ consecutive integers), define
$$V_k = \frac{k(k+1)\cdots(k+m)}{m+1}.$$
Then $T_k = V_k - V_{k-1}$, so the sum telescopes:
$$\sum_{k=1}^n k(k+1)\cdots(k+m-1) = \frac{n(n+1)(n+2)\cdots(n+m)}{m+1}.$$

**Examples:**
$$\sum k(k+1) = \frac{n(n+1)(n+2)}{3}, \qquad \sum k(k+1)(k+2) = \frac{n(n+1)(n+2)(n+3)}{4}.$$

> [!TIP]
> This is the **product-of-consecutive-integers generalisation** of the standard sums. It's faster than
> expanding into $\sum k, \sum k^2, \sum k^3$ when the term is already factored. For a term like
> $\tfrac1{k(k+1)(k+2)}$, the reciprocal version telescopes the same way with a $\tfrac12$ factor.

---

<a id="5-amgm"></a>
## 5. AM–GM as an optimisation weapon (the "split" idea)

For positive reals, $\dfrac{a_1 + \dots + a_n}{n} \ge \sqrt[n]{a_1 \cdots a_n}$, equality iff all equal.

**The power move — split to make the product constant.** To minimise $x^2 + \tfrac{16}{x}$, you want terms
whose **product has no $x$**. Split $\tfrac{16}{x} = \tfrac8x + \tfrac8x$: then $x^2 \cdot \tfrac8x \cdot \tfrac8x = 64$
(constant!), so
$$\frac{x^2 + \tfrac8x + \tfrac8x}{3} \ge \sqrt[3]{64} = 4 \Rightarrow x^2 + \tfrac{16}{x} \ge 12.$$

> [!IMPORTANT]
> The trick for AM–GM optimisation: **break the expression into pieces whose product is a constant** (free of
> the variable). Equality — all pieces equal — then pins down the optimising value. Choosing how to split
> (into how many equal parts) is the whole art; match the powers so the variable cancels in the product.

---

<a id="6-power"></a>
## 6. Power-series sums via differentiation

Starting from the GP $\sum_{k=0}^\infty x^k = \tfrac1{1-x}$ ($|x| < 1$), differentiate and multiply by $x$:
$$\sum_{k=1}^\infty k x^k = \frac{x}{(1-x)^2}, \qquad \sum_{k=1}^\infty k^2 x^k = \frac{x(1+x)}{(1-x)^3}.$$

These are the closed forms behind many "sum $\sum k/2^k$" or "$\sum k^2/3^k$" problems — just substitute the
value of $x$.

> [!NOTE]
> These are exactly the AGP / "$\sum k x^k$" results re-derived by calculus. In Class 11 you obtain them by
> the multiply-by-$r$ method; recognising them as derivatives of the GP is the Class-12 / Advanced view and a
> fast check. Convergence needs $|x| < 1$.

---

<a id="7-ratio"></a>
## 7. Ratio-of-sums ↔ ratio-of-terms shortcut

If two APs have sums-of-$n$-terms in ratio $\dfrac{S_n}{S'_n} = \dfrac{f(n)}{g(n)}$, then the ratio of their
**$m$-th terms** is
$$\frac{a_m}{a'_m} = \frac{f(2m-1)}{g(2m-1)}.$$

**Why:** $a_m = \tfrac{S_{2m-1}}{2m-1}$ for an AP (the $m$-th term is the average, $=$ middle term of the first
$2m-1$ terms), so the $(2m-1)$ cancels in the ratio.

> [!IMPORTANT]
> When a problem gives a **ratio of $n$-term sums** and asks for a **ratio of particular terms**, substitute
> $n = 2m - 1$. This avoids ever solving for the individual $a, d$ of either AP — a classic time-saver on
> JEE Main.

---

## ✅ Deep-dive takeaways

> - **$S_n \to a_n$:** $a_n = S_n - S_{n-1}$; quadratic $S_n$ means AP, $(r^n-1)$-shape means GP.
> - **AGP:** multiply-by-$r$ and subtract; $S_\infty = \tfrac a{1-r} + \tfrac{dr}{(1-r)^2}$.
> - **Telescoping:** split reciprocals/factorials/surds into $f(k) - f(k+1)$; only boundary terms survive.
> - **Vₙ method:** products of consecutive integers sum to $\tfrac{n(n+1)\cdots(n+m)}{m+1}$.
> - **AM–GM:** split so the product is constant; equality (all equal) gives the extremum.
> - **Ratio shortcut:** ratio of $n$-sums at $n = 2m-1$ gives ratio of $m$-th terms.

**Next:** [Formula Recap →](./05-formula-recap.md)
