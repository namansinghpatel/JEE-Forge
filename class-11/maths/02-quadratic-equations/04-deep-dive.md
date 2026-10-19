# Quadratic Equations — Deep Dive

> JEE **Advanced**-level depth: the subtle points, the traps that quietly cost marks, and the
> recurring patterns of previous-year questions (PYQs). Read this once the
> [concepts](./01-concepts.md) and [solved numericals](./02-solved-numericals.md) feel solid.

<!-- RENDERING: inside math use \cdot, \to, \geq, \leq, \in. Units/graphs via SVG. -->

---

## 📑 Index

1. [Location of roots — the four-tool kit](#1-location-of-roots--the-four-tool-kit)
2. [Work with the roots, not the roots themselves](#2-work-with-the-roots-not-the-roots-themselves)
3. [The conjugate-root theorem](#3-the-conjugate-root-theorem)
4. [Range of a rational function via the discriminant](#4-range-of-a-rational-function-via-the-discriminant)
5. [Sign of a quadratic and "always positive" problems](#5-sign-of-a-quadratic-and-always-positive-problems)
6. [Common traps checklist](#6-common-traps-checklist)
7. [Previous-year question (PYQ) patterns](#7-previous-year-question-pyq-patterns)

---

## 1. Location of roots — the four-tool kit

"Both roots positive", "both roots in $(1,5)$", "exactly one root in $(0,2)$", "$k$ lies between the roots" — these *root-location* problems are the heart of Advanced quadratics. You solve them all by combining four tools, read off the parabola $f(x)=ax^2+bx+c$ (take $a>0$; flip signs if $a<0$):

1. **Discriminant** $D \geq 0$ — roots are real (needed for *any* real-location statement).
2. **Sign of $f$ at a point:** $a\cdot f(t) < 0$ ⟺ $t$ lies **between** the roots; $a\cdot f(t) > 0$ ⟺ $t$ is **outside**.
3. **Vertex position** $x_v = -\dfrac{b}{2a}$ — must lie in the interval if both roots do.
4. **Sum / product signs** — e.g. both roots positive needs sum $>0$ **and** product $>0$.

> [!IMPORTANT]
> "Both roots positive" is **not** just "product $> 0$" (that only says they have the *same* sign). You need **all three**: $D \geq 0$, sum $> 0$, product $> 0$. Dropping the discriminant check is the single most common mistake in this topic.

**Template — both roots in an interval $(p,q)$** (with $a>0$): $D \geq 0$, $f(p) > 0$, $f(q) > 0$, and $p < -\dfrac{b}{2a} < q$.

---

## 2. Work with the roots, not the roots themselves

The whole philosophy of JEE quadratics: **never find the roots if you can avoid it.** Vieta's relations let you compute any symmetric function from $S=\alpha+\beta$ and $P=\alpha\beta$.

- **Power sums** $p_n = \alpha^n + \beta^n$ follow the recurrence
$$p_n = S\,p_{n-1} - P\,p_{n-2}, \qquad p_0 = 2,\ p_1 = S$$
This computes $\alpha^{10}+\beta^{10}$ in a few lines — expanding would be hopeless.
- **Difference** $|\alpha-\beta| = \dfrac{\sqrt D}{|a|}$ (useful whenever a problem states "roots differ by…").
- **Transforming roots** (reciprocals, squares, shifts): build the *new* sum and product, then write $x^2 - (\text{new sum})x + (\text{new product}) = 0$.

> [!TIP]
> If an expression in $\alpha,\beta$ is **symmetric** (unchanged when you swap them), it can be written in $S$ and $P$ — so you never need the actual roots. If it's **not** symmetric (e.g. $\alpha - \beta$ with a definite sign), you may also need $|\alpha-\beta| = \sqrt D/|a|$.

---

## 3. The conjugate-root theorem

For a polynomial with **real** coefficients, complex roots occur in conjugate pairs $p \pm iq$. For a polynomial with **rational** coefficients, irrational (surd) roots occur in conjugate pairs $p \pm \sqrt q$.

This is a free second root:
- Root $2 + \sqrt3$ (rational coeffs) $\Rightarrow$ other root $2 - \sqrt3$.
- Root $3 - 2i$ (real coeffs) $\Rightarrow$ other root $3 + 2i$.

And it immediately gives sum and product, hence the equation (solved M7).

> [!WARNING]
> The theorem needs the **right kind of coefficients**. Surd conjugates are guaranteed only for **rational** coefficients; if the coefficients already contain surds, $2+\sqrt3$ being a root tells you nothing about $2-\sqrt3$.

---

## 4. Range of a rational function via the discriminant

To find the range of $y = \dfrac{a_1x^2+b_1x+c_1}{a_2x^2+b_2x+c_2}$ for real $x$:

1. Cross-multiply and collect as a **quadratic in $x$** (coefficients now involve $y$).
2. For a real $x$ to exist, that quadratic needs $D \geq 0$ — an inequality **in $y$**.
3. Solving it gives the range. (Watch the case where the $x^2$ coefficient vanishes — check that $y$ value separately.)

This "discriminant method" (used in solved A3) converts a range question into a quadratic inequality — a very common Advanced device, especially when the numerator and denominator are both quadratics with no real roots (so the denominator never vanishes).

---

## 5. Sign of a quadratic and "always positive" problems

$ax^2+bx+c$ has the **same sign as $a$ for all real $x$** exactly when $D < 0$ (it never touches the axis). This single idea answers a whole family of problems:

- **"$ax^2+bx+c > 0$ for all $x$"** ⟺ $a > 0$ **and** $D < 0$.
- **"$ax^2+bx+c < 0$ for all $x$"** ⟺ $a < 0$ **and** $D < 0$.
- **"$ax^2+bx+c \geq 0$ for all $x$"** ⟺ $a > 0$ **and** $D \leq 0$.

> [!NOTE]
> Don't forget the $a$ condition. "$D < 0$" alone only says the expression keeps a constant sign — it could be constantly *negative*. You need the sign of $a$ to say *which* sign.

---

## 6. Common traps checklist

- [ ] **"Both roots positive" = product $>0$ only** — you also need $D\geq0$ and sum $>0$.
- [ ] **Forgetting $D\geq0$** in any real-root-location problem.
- [ ] **Assuming two roots over the reals** — a real quadratic may have 0 real roots ($D<0$).
- [ ] **Applying surd-conjugate theorem with irrational coefficients** — only valid for rational coefficients.
- [ ] **"Always positive" without checking the sign of $a$.**
- [ ] **Dividing by $(y-1)$** in the range method without checking $y=1$ separately (the $x^2$ term vanishes there).
- [ ] **$a = 0$ overlooked** — then it's not a quadratic; "has real roots for all $k$" type questions often hide this.
- [ ] **Using calculus for max/min** when $-D/4a$ is faster and expected.

---

## 7. Previous-year question (PYQ) patterns

These recur almost every year:

1. **Root-location / parameter-range** — "find all values of $k$ such that both roots are positive / lie in an interval / one root is greater than 2," solved with the four-tool kit.
2. **Symmetric-function evaluation** — $\alpha^2+\beta^2$, $\alpha^3+\beta^3$, power sums via recurrence.
3. **Transforming roots** — form the equation whose roots are reciprocals / squares / $\alpha/\beta$.
4. **Nature of roots with a parameter** — "for what $k$ are the roots real / equal / complex."
5. **Common-root problems** — one common root (subtract to find it) or both common (proportional coefficients).
6. **Range of a rational function** via the discriminant method.
7. **"Always positive / negative" inequalities** — $a$ and $D$ conditions together.
8. **Max/min of a quadratic expression** — vertex value $-D/4a$.
9. **Quadratic-in-disguise** — biquadratics, equations in $2^x$, $\sin x$, $\sqrt x$, reducible by substitution.
10. **Conjugate-root** deductions — given one surd/complex root, find the equation.

> [!NOTE]
> Advanced problems chain ideas: e.g. *conjugate root → form the equation → then a root-location condition on a related equation.* Identify which tool each clause ("both positive", "differ by 2", "one root in $(0,1)$") triggers.

---

**Next:** [Formula Recap →](./05-formula-recap.md)
