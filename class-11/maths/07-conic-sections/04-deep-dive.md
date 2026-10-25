# Conic Sections — Deep Dive

> The toolkit that turns conic-section problems from slow to fast: the parametric forms, the
> tangent/normal "T = 0" machinery, focal-chord facts, the director circle, and the recurring exam
> traps. Read once you're solid on the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. -->

---

## 📑 Index

1. [Parametric forms — the fastest way to name a point](#1-parametric-forms)
2. [The "T = 0" rule for tangents and chords](#2-the-t0-rule)
3. [Focal chords and focal distances](#3-focal-chords)
4. [Tangency conditions you must memorise](#4-tangency-conditions)
5. [The director circle (perpendicular tangents)](#5-director-circle)
6. [Shifting the origin — non-centred conics](#6-shifting-the-origin)
7. [Ellipse and hyperbola as a mirror pair](#7-ellipse-hyperbola-pair)
8. [Exam traps checklist](#8-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-parametric-forms"></a>
## 1. Parametric forms — the fastest way to name a point

Instead of carrying two coordinates tied by an equation, name a point with a **single parameter**.
This collapses most chord/tangent problems to one variable.

| Conic | Parametric point |
|---|---|
| Circle $x^2+y^2=r^2$ | $(r\cos\theta,\ r\sin\theta)$ |
| Parabola $y^2=4ax$ | $(at^2,\ 2at)$ |
| Ellipse $\dfrac{x^2}{a^2}+\dfrac{y^2}{b^2}=1$ | $(a\cos\theta,\ b\sin\theta)$ |
| Hyperbola $\dfrac{x^2}{a^2}-\dfrac{y^2}{b^2}=1$ | $(a\sec\theta,\ b\tan\theta)$ |

> [!TIP]
> The parabola's $(at^2,2at)$ is the workhorse of JEE parabola questions. Two points $t_1,t_2$ give
> clean results: chord slope $=\dfrac{2}{t_1+t_2}$, and the chord passes through the focus exactly
> when $t_1t_2=-1$. Commit those two to memory.

---

<a id="2-the-t0-rule"></a>
## 2. The "T = 0" rule for tangents and chords

There's **one pattern** behind the tangent at a point, the chord of contact, and the polar line.
Start from the curve's equation $S=0$ and "split" every term using the external/contact point
$(x_1,y_1)$:

- $x^2 \to x x_1$
- $y^2 \to y y_1$
- $x \to \dfrac{x+x_1}{2}$, and $y \to \dfrac{y+y_1}{2}$

The result is called $T$. Then:

| You want… | Use |
|---|---|
| Tangent **at** a point on the curve | $T=0$ |
| **Chord of contact** from an external point | $T=0$ |
| Check a point inside/outside | sign of $S_1$ (plug the point into $S$) |

**Examples.**
- Circle $x^2+y^2=r^2$: tangent at $(x_1,y_1)$ is $xx_1+yy_1=r^2$.
- Parabola $y^2=4ax$: tangent at $(x_1,y_1)$ is $yy_1=2a(x+x_1)$.
- Ellipse: tangent at $(x_1,y_1)$ is $\dfrac{xx_1}{a^2}+\dfrac{yy_1}{b^2}=1$.
- Hyperbola: tangent at $(x_1,y_1)$ is $\dfrac{xx_1}{a^2}-\dfrac{yy_1}{b^2}=1$.

> [!IMPORTANT]
> Learn the *rule* (split the terms), not four separate formulas. "$T=0$" gives the tangent when the
> point is on the curve and the chord of contact when it's outside — same expression, different
> interpretation. This single idea answers a large share of coordinate-geometry questions.

---

<a id="3-focal-chords"></a>
## 3. Focal chords and focal distances

**Focal distance** = distance from a point on the conic to a focus. Because of the focus–directrix
definition, these have shortcut formulas (no distance formula needed):

| Conic | Focal distance of a point |
|---|---|
| Parabola $y^2=4ax$ | $x+a$ (= distance to directrix) |
| Ellipse (point $(x,y)$) | $a\pm ex$ → the two foci give $a-ex$ and $a+ex$ |
| Hyperbola | $|ex\pm a|$ |

**Parabola focal chord facts** (ends at $t_1,t_2$ with $t_1t_2=-1$):
- Length $=a\left(t+\dfrac1t\right)^2$ for an end at parameter $t$.
- The **latus rectum** is the focal chord with $t=1$ (length $4a$) — the shortest focal chord.
- Semi-latus rectum is the harmonic mean of the two focal segment lengths.

> [!TIP]
> If a question gives "a focal chord of the parabola," your first move is to write the ends as
> $t$ and $-1/t$. Everything (length, midpoint, slope) then falls out in terms of one variable.

---

<a id="4-tangency-conditions"></a>
## 4. Tangency conditions you must memorise

For a line $y=mx+c$ to **touch** a conic, substitute and set the discriminant to zero. The results
are worth memorising because they appear constantly:

| Conic | Tangent condition | Tangent line form |
|---|---|---|
| Circle $x^2+y^2=r^2$ | $c^2=r^2(1+m^2)$ | $y=mx\pm r\sqrt{1+m^2}$ |
| Parabola $y^2=4ax$ | $c=\dfrac{a}{m}$ | $y=mx+\dfrac{a}{m}$ |
| Ellipse $\dfrac{x^2}{a^2}+\dfrac{y^2}{b^2}=1$ | $c^2=a^2m^2+b^2$ | $y=mx\pm\sqrt{a^2m^2+b^2}$ |
| Hyperbola $\dfrac{x^2}{a^2}-\dfrac{y^2}{b^2}=1$ | $c^2=a^2m^2-b^2$ | $y=mx\pm\sqrt{a^2m^2-b^2}$ |

> [!WARNING]
> Note the **sign flip** between ellipse ($+b^2$) and hyperbola ($-b^2$) — the same sign flip as in
> their standard equations. For the hyperbola, $a^2m^2-b^2$ must be $\ge 0$, so not every slope gives
> a (real) tangent; that condition itself is often the crux of a problem.

---

<a id="5-director-circle"></a>
## 5. The director circle (perpendicular tangents)

The **director circle** is the locus of points from which the two tangents to a conic are
**perpendicular** to each other:

| Conic | Director circle |
|---|---|
| Ellipse $\dfrac{x^2}{a^2}+\dfrac{y^2}{b^2}=1$ | $x^2+y^2=a^2+b^2$ |
| Hyperbola $\dfrac{x^2}{a^2}-\dfrac{y^2}{b^2}=1$ | $x^2+y^2=a^2-b^2$ (real only if $a>b$) |
| Parabola | degenerates to the **directrix** |

> [!NOTE]
> Derivation idea: write both tangents as $y=mx\pm\sqrt{a^2m^2+b^2}$, impose that they pass through
> $(h,k)$ and that the two slopes multiply to $-1$. The $m$ eliminates to give $h^2+k^2=a^2+b^2$.
> For a parabola, perpendicular tangents always meet on the directrix — a neat, frequently-tested fact.

---

<a id="6-shifting-the-origin"></a>
## 6. Shifting the origin — non-centred conics

Real exam equations are rarely centred at the origin. The move is always **complete the square**:
turn $Ax^2+Cy^2+Dx+Ey+F=0$ into a centred standard form in $(x-h)$ and $(y-k)$.

**Worked pattern** for $9x^2+4y^2-18x-16y-11=0$:
1. Group: $9(x^2-2x)+4(y^2-4y)=11$.
2. Complete squares: $9[(x-1)^2-1]+4[(y-2)^2-4]=11$.
3. Tidy: $9(x-1)^2+4(y-2)^2=36 \Rightarrow \dfrac{(x-1)^2}{4}+\dfrac{(y-2)^2}{9}=1$.
4. Read off: ellipse, centre $(1,2)$, axes as usual **about the new centre**.

> [!TIP]
> Once centred, *every* formula (foci, directrices, latus rectum) applies as if the centre were the
> origin — then translate the final points back by $(h,k)$. Don't try to use the origin formulas on
> the un-shifted equation.

---

<a id="7-ellipse-hyperbola-pair"></a>
## 7. Ellipse and hyperbola as a mirror pair

Treat these two together — they differ by a single sign in several places:

| | Ellipse | Hyperbola |
|---|---|---|
| Equation | $\dfrac{x^2}{a^2}+\dfrac{y^2}{b^2}=1$ | $\dfrac{x^2}{a^2}-\dfrac{y^2}{b^2}=1$ |
| $b^2$ | $a^2(1-e^2)$ | $a^2(e^2-1)$ |
| Eccentricity | $\sqrt{1-b^2/a^2}<1$ | $\sqrt{1+b^2/a^2}>1$ |
| Focal property | sum $=2a$ | difference $=2a$ |
| Tangent condition | $c^2=a^2m^2+b^2$ | $c^2=a^2m^2-b^2$ |
| Director circle | $x^2+y^2=a^2+b^2$ | $x^2+y^2=a^2-b^2$ |
| Asymptotes | none | $y=\pm(b/a)x$ |

**Conjugate hyperbola identity:** if $e_1,e_2$ are the eccentricities of a hyperbola and its
conjugate, then $\dfrac{1}{e_1^2}+\dfrac{1}{e_2^2}=1$.

---

<a id="8-exam-traps"></a>
## 8. Exam traps checklist

> [!WARNING]
> - **Which axis is major/transverse?** Compare the denominators: the larger one (ellipse) or the
>   positive-term one (hyperbola) sets the axis direction. Don't assume it's $x$.
> - **Centred at the origin?** If there are linear $x$ or $y$ terms, complete the square first.
> - **Right $b^2$ relation:** $1-e^2$ for ellipse, $e^2-1$ for hyperbola.
> - **Latus rectum** is $4a$ for a parabola but $\dfrac{2b^2}{a}$ for ellipse/hyperbola — don't mix them.
> - **Focal distance** shortcuts ($x+a$, $a\pm ex$) save time — use them instead of the distance formula.
> - **Tangent sign:** $+b^2$ (ellipse) vs $-b^2$ (hyperbola).
> - **Hyperbola director circle** is real only when $a>b$.
> - **Parabola:** square term names the axis; the sign names the direction of opening.
