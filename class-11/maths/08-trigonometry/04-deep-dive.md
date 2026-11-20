# Trigonometric Functions — Deep Dive

> Beyond the textbook: the **strategies** that turn any trig question into a routine. The thread throughout —
> **reduce everything to a standard form (one ratio, one angle, or a known family), then apply the matching
> tool.**

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

---

## 📑 Index

1. [Proving identities — the convert-to-sin/cos discipline](#1-identities)
2. [The $R$-form: $a\cos\theta + b\sin\theta = R\cos(\theta - \phi)$](#2-rform)
3. [Solving trig equations systematically](#3-equations)
4. [The $t = \tan(\theta/2)$ substitution](#4-tsub)
5. [Conditional identities for $A + B + C = \pi$](#5-conditional)
6. [Telescoping and series of trig terms](#6-series)
7. [Transforming products and powers for integration](#7-powers)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Practice](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-identities"></a>
## 1. Proving identities — the convert-to-sin/cos discipline

The single most reliable method for "prove LHS = RHS":

1. **Convert everything to $\sin$ and $\cos$** (replace $\tan, \sec, \cot, \csc$).
2. Work on the **more complicated side** only.
3. Use $\sin^2 + \cos^2 = 1$ to trade one for the other.
4. Factor, combine fractions, cancel.

**Alternative cues:** a $1 \pm \cos$ or $1 \pm \sin$ screams **half-angle**; a sum of two ratios screams
**sum-to-product**; a squared ratio screams **Pythagorean**.

> [!IMPORTANT]
> Never work both sides at once in an exam proof — transform **one** side until it equals the other. The
> convert-to-sin/cos move almost never fails; the "clever" identity-specific tricks just make it shorter.

---

<a id="2-rform"></a>
## 2. The $R$-form: $a\cos\theta + b\sin\theta = R\cos(\theta - \phi)$

Write
$$a\cos\theta + b\sin\theta = R\cos(\theta - \phi), \qquad R = \sqrt{a^2 + b^2}, \quad \tan\phi = \frac ba.$$

Because $\cos(\theta - \phi) \in [-1, 1]$:
$$\boxed{-\sqrt{a^2 + b^2} \le a\cos\theta + b\sin\theta \le \sqrt{a^2 + b^2}.}$$

This solves three problem types at once: **range/max/min**, **solving $a\cos\theta + b\sin\theta = c$** (possible
iff $|c| \le R$), and **rewriting** a two-term expression as a single sinusoid.

> [!IMPORTANT]
> $R = \sqrt{a^2+b^2}$ is the amplitude — commit it to memory. An equation $a\cos\theta + b\sin\theta = c$ has
> **no solution when $|c| > \sqrt{a^2+b^2}$**; checking that first saves wasted algebra. You can use either
> $R\cos(\theta - \phi)$ or $R\sin(\theta + \psi)$ — pick whichever matches the leading term.

---

<a id="3-equations"></a>
## 3. Solving trig equations systematically

A reliable pipeline:

1. **Reduce to one ratio** (use identities, or substitute $\cos^2 = 1 - \sin^2$) → get a polynomial in a single
   ratio, or a product $= 0$.
2. **Factor** (sum-to-product is the usual tool for $\sin\pm\sin$, $\cos\pm\cos$).
3. Solve each factor with the **general-solution forms**:
   $$\sin\theta = \sin\alpha \Rightarrow \theta = n\pi + (-1)^n\alpha, \quad \cos\theta = \cos\alpha \Rightarrow \theta = 2n\pi \pm \alpha, \quad \tan\theta = \tan\alpha \Rightarrow \theta = n\pi + \alpha.$$
4. **Discard extraneous roots** introduced by squaring, and check the domain if one is specified.

> [!WARNING]
> **Squaring or cross-multiplying can introduce false solutions** — always substitute back. And when you
> divide by a trig factor (e.g. by $\cos\theta$), you may **lose** the solutions where that factor is zero;
> prefer factoring to dividing.

---

<a id="4-tsub"></a>
## 4. The $t = \tan(\theta/2)$ substitution

Setting $t = \tan\dfrac\theta2$ turns everything rational:
$$\sin\theta = \frac{2t}{1 + t^2}, \qquad \cos\theta = \frac{1 - t^2}{1 + t^2}, \qquad \tan\theta = \frac{2t}{1 - t^2}.$$

This converts a trig equation into an **algebraic (polynomial) equation in $t$** — invaluable when $\sin$ and
$\cos$ appear linearly, and the standard move for certain integrals in Class 12.

> [!TIP]
> The **Weierstrass substitution** $t = \tan(\theta/2)$ is the universal "make it algebraic" tool. Watch the
> special case $\theta = \pi$ (where $t \to \infty$) separately. For $\sin 2\theta$, $\cos 2\theta$, the same
> formulas with $t = \tan\theta$ give the double-angle rationalisation.

---

<a id="5-conditional"></a>
## 5. Conditional identities for $A + B + C = \pi$

When the angles are those of a triangle, $A + B + C = \pi$ unlocks a family of identities. The method is always:
**replace one angle**, e.g. $C = \pi - (A + B)$, then expand.

Classic results:
$$\tan A + \tan B + \tan C = \tan A\tan B\tan C$$
$$\sin 2A + \sin 2B + \sin 2C = 4\sin A\sin B\sin C$$
$$\cos A + \cos B + \cos C = 1 + 4\sin\tfrac A2\sin\tfrac B2\sin\tfrac C2$$

> [!IMPORTANT]
> The trigger is the phrase "$A, B, C$ are angles of a triangle" (or $A + B + C = \pi/180°$). Convert the
> **third angle** using the constraint, apply compound/sum-to-product, and the symmetric product form drops
> out. These are high-frequency in JEE Advanced.

---

<a id="6-series"></a>
## 6. Telescoping and series of trig terms

Some trig sums telescope after the right product-to-sum step. Example:
$$\sum_{k=1}^n \cos(k\theta) = \frac{\sin(n\theta/2)}{\sin(\theta/2)}\cos\frac{(n+1)\theta}{2},$$
obtained by multiplying by $2\sin(\theta/2)$ and converting each product to a difference (telescoping).

> [!TIP]
> To sum $\sum\sin k\theta$ or $\sum\cos k\theta$, **multiply and divide by $2\sin(\theta/2)$** and use
> product-to-sum — consecutive terms cancel. This mirrors the algebraic telescoping you saw in Sequences &
> Series, here powered by the sum↔product identities.

---

<a id="7-powers"></a>
## 7. Transforming products and powers for integration

A preview of why this chapter matters for calculus:
- **Power reduction:** $\sin^2\theta = \dfrac{1 - \cos 2\theta}{2}$, $\cos^2\theta = \dfrac{1 + \cos 2\theta}{2}$.
- **Products to sums:** $2\sin A\cos B = \sin(A+B) + \sin(A-B)$, etc. — turns a product (hard to integrate) into
  a sum (easy).
- **Odd powers:** peel off one factor and convert the rest with $\sin^2 + \cos^2 = 1$.

> [!NOTE]
> You can't integrate $\sin^2\theta$ or $\sin 3\theta\cos\theta$ directly, but **power-reduction** and
> **product-to-sum** turn them into sums of single sinusoids that integrate termwise. Mastering these
> transformations now pays off directly in the integration chapter.

---

## ✅ Deep-dive takeaways

> - **Prove identities** by converting to sin/cos and transforming one side.
> - **$R$-form:** $a\cos\theta + b\sin\theta = \sqrt{a^2+b^2}\cos(\theta - \phi)$ → range, max/min, solvability.
> - **Equations:** reduce to one ratio → factor → general-solution forms → discard extraneous roots.
> - **$t = \tan(\theta/2)$** makes everything rational/algebraic.
> - **$A+B+C = \pi$:** replace the third angle, then expand for conditional identities.
> - **Trig series** telescope after multiplying by $2\sin(\theta/2)$.
> - **Power-reduction & product-to-sum** linearise expressions for integration.

**Next:** [Formula Recap →](./05-formula-recap.md)
