# Complex Numbers — Deep Dive

> The techniques that make complex numbers fast: compare-parts, the conjugate trick, polar form as the key
> to powers/roots, De Moivre for trig identities, the roots-of-unity shortcuts, and "complex numbers as
> geometry." Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \to, i, \bar z, |z|, \arg z, \omega. -->

---

## 📑 Index

1. [Compare-parts and the conjugate trick](#1-compare)
2. [Why polar form wins](#2-polar)
3. [De Moivre for trig identities](#3-de-moivre)
4. [Roots of unity shortcuts](#4-roots)
5. [Complex numbers as geometry](#5-geometry)
6. [Finding square roots directly](#6-square-roots)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-compare"></a>
## 1. Compare-parts and the conjugate trick

Two tools solve most "find $x, y$" problems:
- **Compare parts:** $a + ib = c + id \iff a = c$ and $b = d$. Split any complex equation into two real ones.
- **Conjugate trick:** to simplify $\dfrac{1}{z}$ or $\dfrac{z_1}{z_2}$, multiply by the conjugate of the
  denominator — since $z\bar z = |z|^2$ is real, the denominator becomes real.

> [!TIP]
> Tests for special numbers: $z$ is **real** iff $z = \bar z$; **purely imaginary** iff $z + \bar z = 0$
> (with $z\ne0$). Use $\operatorname{Re}(z) = \frac{z+\bar z}{2}$ and $\operatorname{Im}(z) = \frac{z-\bar z}{2i}$
> to turn "real/imaginary part = …" conditions into algebra.

---

<a id="2-polar"></a>
## 2. Why polar form wins

In **polar form** $z = re^{i\theta}$, multiplication, division, powers and roots are trivial:
$$z_1 z_2 = r_1 r_2 e^{i(\theta_1+\theta_2)}, \quad \frac{z_1}{z_2} = \frac{r_1}{r_2}e^{i(\theta_1-\theta_2)}, \quad z^n = r^n e^{in\theta}$$

So: **moduli multiply, arguments add.** Powers that would be painful in $a+ib$ form are one line in polar.

> [!WARNING]
> Getting the **argument's quadrant** right is the usual slip: $\tan^{-1}(b/a)$ only gives the reference
> angle. For $(a,b)$ in the 2nd quadrant add $\pi$ (or $180°$); in the 3rd subtract $\pi$; in the 4th the
> angle is negative. Always sketch the point on the Argand plane first.

---

<a id="3-de-moivre"></a>
## 3. De Moivre for trig identities

$(\cos\theta + i\sin\theta)^n = \cos n\theta + i\sin n\theta$. Expanding the left side by the binomial
theorem and **comparing real/imaginary parts** gives multiple-angle formulas:
- Real part → $\cos n\theta$ in terms of $\cos\theta, \sin\theta$.
- Imaginary part → $\sin n\theta$.

E.g. $\cos3\theta = 4\cos^3\theta - 3\cos\theta$, $\sin3\theta = 3\sin\theta - 4\sin^3\theta$.

> [!TIP]
> The identity $z + \frac1z = 2\cos\theta$ (for $z = e^{i\theta}$) gives $z^n + \frac1{z^n} = 2\cos n\theta$
> and $z^n - \frac1{z^n} = 2i\sin n\theta$ — a fast route to powers of cosines/sines and to summing certain
> series.

---

<a id="4-roots"></a>
## 4. Roots of unity shortcuts

The $n$-th roots of unity are $1, \alpha, \dots, \alpha^{n-1}$ with $\alpha = e^{2\pi i/n}$:
- **Sum $= 0$** (for $n \ge 2$) — collapses many summations.
- **Product $= (-1)^{n-1}$.**
- They are the vertices of a **regular $n$-gon** on the unit circle.
- **Cube roots:** $1, \omega, \omega^2$ with $1 + \omega + \omega^2 = 0$, $\omega^3 = 1$, $\bar\omega = \omega^2$. Reduce any power of $\omega$ **mod 3**.

> [!IMPORTANT]
> $1 + \omega + \omega^2 = 0$ is the single most useful identity here: it zeroes out grouped sums, factorises
> $a^3 + b^3 + c^3 - 3abc$, and simplifies $\omega^{\text{big}}$ (take the exponent mod 3). For general
> $n$-th roots of $z = re^{i\theta}$: radius $r^{1/n}$, angles $\frac{\theta + 2\pi k}{n}$, $n$ of them equally spaced.

---

<a id="5-geometry"></a>
## 5. Complex numbers as geometry

A complex number is a point/vector, so:
- $|z_1 - z_2|$ = distance; $\arg(z_1 - z_2)$ = direction of the segment.
- **Rotation:** multiply by $e^{i\theta}$ to rotate about the origin; $z' = z_0 + (z - z_0)e^{i\theta}$ about $z_0$.
- **Rotation formula** (angle $\theta$ at vertex $B = z_2$): $\dfrac{z_3 - z_2}{z_1 - z_2} = \dfrac{|z_3-z_2|}{|z_1-z_2|}e^{i\theta}$.

| Condition | Shape |
|---|---|
| $\|z - z_0\| = r$ | circle |
| $\|z - z_1\| = \|z - z_2\|$ | perpendicular bisector |
| $\|z - z_1\| + \|z - z_2\| = k$ | ellipse |
| $\arg\frac{z-z_1}{z-z_2} = \alpha$ | arc of a circle |

> [!IMPORTANT]
> Translate every $|...|$ into a **distance** and every $\arg(...)$ into an **angle/direction**; the condition
> then names a familiar shape. The rotation formula proves equilateral-triangle and square conditions in one
> step — this is the heart of the Advanced geometry problems.

---

<a id="6-square-roots"></a>
## 6. Finding square roots directly

To find $\sqrt{a + ib}$ without polar form, set $\sqrt{a+ib} = x + iy$ and square:
$$x^2 - y^2 = a, \qquad 2xy = b, \qquad x^2 + y^2 = \sqrt{a^2 + b^2}.$$
Add/subtract the first and third to get $x^2$ and $y^2$; the sign of $b$ fixes the relative signs of $x, y$.

> [!TIP]
> The extra equation $x^2 + y^2 = |a + ib|$ (from $|{\sqrt{z}}|^2 = |z|$) is what makes this quick: you get
> $x^2$ and $y^2$ immediately, then pick signs so that $2xy$ matches the sign of $b$.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **$\sqrt{a}\sqrt{b} \ne \sqrt{ab}$ for negatives** — convert to $i$ first ($\sqrt{-2}\sqrt{-3} = -\sqrt6$).
> - **Argument needs the correct quadrant**, not just $\tan^{-1}(b/a)$.
> - **$z\bar z = |z|^2$** (real) — the rationalising tool.
> - **Powers of $\omega$:** reduce the exponent **mod 3**; $1 + \omega + \omega^2 = 0$.
> - **De Moivre needs integer $n$** (for the simple statement); compare real/imag parts for trig identities.
> - **Complex roots of real quadratics come in conjugate pairs.**
> - **$n$-th roots of unity sum to 0** and form a regular polygon.
> - **Geometry:** $|...|$ → distance, $\arg(...)$ → angle; use the rotation formula.
