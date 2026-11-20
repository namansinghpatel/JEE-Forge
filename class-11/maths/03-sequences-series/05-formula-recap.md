# Sequences & Series — Formula Recap

> One-page revision sheet. Everything from [Concepts](./01-concepts.md) condensed to formulas and the cue for
> each. Pair with the flash sheet ([`flash.html`](./flash.html)) the night before a test.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

---

## 🔵 Arithmetic Progression (AP)

| Quantity | Formula |
|---|---|
| $n$-th term | $a_n = a + (n-1)d$ |
| Sum of $n$ terms | $S_n = \dfrac n2[2a + (n-1)d] = \dfrac n2(a + \ell)$ |
| Common difference | $d = a_n - a_{n-1}$ |
| 3 terms in AP | $a - d,\ a,\ a + d$ |
| Middle-term property | $a_n = \dfrac{a_{n-1} + a_{n+1}}{2}$ |

> **Cue:** $S_n$ quadratic in $n$ (no constant term) ⟺ AP.

---

## 🟢 Geometric Progression (GP)

| Quantity | Formula |
|---|---|
| $n$-th term | $a_n = a\,r^{n-1}$ |
| Sum of $n$ terms | $S_n = a\dfrac{r^n - 1}{r - 1}\ (r \ne 1)$ |
| Sum to infinity | $S_\infty = \dfrac{a}{1 - r}\ (\lvert r \rvert < 1)$ |
| 3 terms in GP | $\dfrac ar,\ a,\ ar$ |
| Middle-term property | $a_n = \sqrt{a_{n-1}\,a_{n+1}}$ |

> **Cue:** constant ratio; infinite sum only if $\lvert r\rvert < 1$.

---

## 🟡 Means

| Mean of $a, b$ | Formula |
|---|---|
| Arithmetic (AM) | $\dfrac{a+b}{2}$ |
| Geometric (GM) | $\sqrt{ab}$ |
| Harmonic (HM) | $\dfrac{2ab}{a+b}$ |

- **Relation:** $\text{GM}^2 = \text{AM}\cdot\text{HM}$
- **Inequality:** $\text{AM} \ge \text{GM} \ge \text{HM}$ (equality iff $a = b$)
- Two numbers from AM & GM: roots of $x^2 - 2(\text{AM})x + \text{GM}^2 = 0$.

---

## 🟣 Harmonic Progression (HP)

- Reciprocals $\tfrac1{a_1}, \tfrac1{a_2}, \dots$ form an **AP**.
- Work via reciprocals → AP tools → invert back. No simple direct sum formula.

---

## 🔴 Special-power sums

$$\sum_{k=1}^n k = \frac{n(n+1)}{2}, \qquad \sum_{k=1}^n k^2 = \frac{n(n+1)(2n+1)}{6}, \qquad \sum_{k=1}^n k^3 = \left[\frac{n(n+1)}{2}\right]^2$$

- $\sum k^3 = (\sum k)^2$.
- Sum of first $n$ odd numbers $= n^2$; first $n$ even numbers $= n(n+1)$.

---

## ⚫ Advanced tools

| Tool | Formula / method |
|---|---|
| $a_n$ from $S_n$ | $a_n = S_n - S_{n-1}\ (n\ge2),\ a_1 = S_1$ |
| AGP infinite sum | $S_\infty = \dfrac a{1-r} + \dfrac{dr}{(1-r)^2}\ (\lvert r\rvert<1)$; method = multiply-by-$r$, subtract |
| Telescoping | $\sum[f(k) - f(k+1)] = f(1) - f(n+1)$ |
| $\sum \dfrac1{k(k+1)}$ | $= 1 - \dfrac1{n+1} = \dfrac{n}{n+1}$ |
| Vₙ method | $\sum k(k+1)\cdots(k+m-1) = \dfrac{n(n+1)\cdots(n+m)}{m+1}$ |
| $\sum k(k+1)$ | $= \dfrac{n(n+1)(n+2)}{3}$ |
| $\sum k x^k$ (\|x\|<1) | $= \dfrac{x}{(1-x)^2}$ |
| AM–GM ($n$ terms) | $\dfrac{a_1+\dots+a_n}{n} \ge \sqrt[n]{a_1\cdots a_n}$ |
| Ratio shortcut | ratio of $n$-sums at $n = 2m-1$ = ratio of $m$-th terms |

---

## 🎯 Exam cues

> [!TIP]
> - **"Find three numbers in AP/GP"** → symmetric terms ($a-d,a,a+d$ or $\tfrac ar,a,ar$).
> - **"Sum given as a formula, find $n$-th term"** → $a_n = S_n - S_{n-1}$.
> - **"Minimise/maximise with fixed product or sum"** → AM–GM, equality at all-equal.
> - **Reciprocal-of-product term** → partial fractions → telescope.
> - **(linear) × (geometric) term** → AGP, multiply-by-$r$.
> - **Product of consecutive integers** → Vₙ method.
> - **Ratio of $n$-term sums → ratio of terms** → plug $n = 2m - 1$.

---

📄 **Google Drive source:** [`notes/scans/Class_11_MT_Sequences_Series_Formula.png`](./notes/scans/Class_11_MT_Sequences_Series_Formula.png) — the chapter formula sheet (vector PDF alongside).

**Back to:** [Concepts](./01-concepts.md) · [Flash sheet](./flash.html)
