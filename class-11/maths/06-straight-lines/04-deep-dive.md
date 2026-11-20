# Straight Lines — Deep Dive

> Beyond the textbook: the **techniques** that turn coordinate-geometry questions into routine. The common
> thread — **translate the geometric condition into an algebraic one, then solve.**

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

---

## 📑 Index

1. [The family of lines — writing a line without finding the intersection](#1-family)
2. [Foot, image and reflection — one formula, three uses](#2-reflection)
3. [Angle bisectors: acute vs obtuse, and the origin rule](#3-bisectors)
4. [The pair of straight lines in depth](#4-pair)
5. [Shifting the origin (translation of axes)](#5-translation)
6. [Triangle centres on the coordinate plane](#6-centres)
7. [The locus method as a universal tool](#7-locus)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Practice](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-family"></a>
## 1. The family of lines — writing a line without finding the intersection

Any line through the intersection of $L_1 = 0$ and $L_2 = 0$ is $L_1 + \lambda L_2 = 0$. The power is that you
**never solve for the intersection point** — you impose the one extra condition directly on $\lambda$.

**Workflow:**
1. Write $S \equiv L_1 + \lambda L_2 = 0$ (a line for every $\lambda$).
2. Apply the extra condition — passes through a point (substitute), given slope (set $-a/b$), perpendicular to a
   line, etc.
3. Solve the resulting equation for $\lambda$ and substitute back.

> [!IMPORTANT]
> The family trick converts a two-step problem (find intersection, then find line) into one step. It also
> generalises: $S_1 + \lambda S_2 = 0$ gives the family of **curves** through the intersection of two curves —
> the exact idea you'll reuse for circles and conics.

---

<a id="2-reflection"></a>
## 2. Foot, image and reflection — one formula, three uses

For the line $ax + by + c = 0$ and a point $(x_1, y_1)$, compute the single ratio
$$t = -\frac{a x_1 + b y_1 + c}{a^2 + b^2}.$$
Then:

| Want | Formula |
|---|---|
| Perpendicular **distance** | $\lvert t\rvert \sqrt{a^2 + b^2} = \dfrac{\lvert ax_1+by_1+c\rvert}{\sqrt{a^2+b^2}}$ |
| **Foot** of perpendicular | $(x_1 + at,\ y_1 + bt)$ |
| **Image** (reflection) | $(x_1 + 2at,\ y_1 + 2bt)$ |

> [!TIP]
> One computation, three answers. The foot is "move $t$ along the normal direction $(a, b)$"; the image is
> "move twice as far." Reflecting a **whole line** in another line = reflect two of its points, then join —
> or, for reflection in an axis, just flip the sign of the relevant variable.

---

<a id="3-bisectors"></a>
## 3. Angle bisectors: acute vs obtuse, and the origin rule

The bisectors of $a_1x+b_1y+c_1 = 0$ and $a_2x+b_2y+c_2 = 0$ are
$$\frac{a_1x+b_1y+c_1}{\sqrt{a_1^2+b_1^2}} = \pm\frac{a_2x+b_2y+c_2}{\sqrt{a_2^2+b_2^2}}.$$

**To identify which is which**, first make $c_1, c_2 > 0$ (multiply through by $-1$ if needed). Then:
- the **$+$ sign** gives the bisector of the angle **containing the origin**;
- compare $a_1a_2 + b_1b_2$ with $0$: if $a_1a_2 + b_1b_2 > 0$, the origin lies in the **obtuse** angle, so the
  $+$ bisector is the **obtuse-angle** bisector (and vice versa).

> [!IMPORTANT]
> The $\pm$ comes straight from "equidistant from both lines." The sign-rule table (normalise $c > 0$, then
> check $a_1a_2 + b_1b_2$) is the standard way to label the acute/obtuse bisector without plotting — worth
> memorising for JEE Advanced.

---

<a id="4-pair"></a>
## 4. The pair of straight lines in depth

$ax^2 + 2hxy + by^2 = 0$ (homogeneous) = two lines through the origin with slopes $m_1, m_2$:
$$m_1 + m_2 = -\frac{2h}{b}, \qquad m_1 m_2 = \frac ab.$$

- **Angle:** $\tan\theta = \left|\dfrac{2\sqrt{h^2 - ab}}{a + b}\right|$.
- **Perpendicular** iff $a + b = 0$; **coincident** iff $h^2 = ab$.
- The general second-degree $ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0$ is a pair of lines iff
  $abc + 2fgh - af^2 - bg^2 - ch^2 = 0$ (the determinant condition).

> [!TIP]
> Treat the homogeneous form as a **quadratic in $m = y/x$**: $bm^2 + 2hm + a = 0$. Sum and product of roots
> give the slope relations instantly. The angle formula is just $|m_1 - m_2|/|1 + m_1 m_2|$ rewritten using
> those symmetric functions.

---

<a id="5-translation"></a>
## 5. Shifting the origin (translation of axes)

Moving the origin to $(h, k)$ replaces $x \to X + h$, $y \to Y + k$. A point's new coordinates are
$(X, Y) = (x - h, y - k)$. This **kills the linear terms** of a curve when you shift to its centre — the trick
that simplifies conic equations later.

> [!NOTE]
> Translation changes intercepts and constant terms but **not** slopes, lengths, or angles — those are
> translation-invariant. Use it to move an awkward point (like a triangle's vertex) to the origin and shrink the
> algebra.

---

<a id="6-centres"></a>
## 6. Triangle centres on the coordinate plane

For a triangle with vertices $A(x_1,y_1), B(x_2,y_2), C(x_3,y_3)$:

| Centre | Coordinates / how |
|---|---|
| **Centroid** $G$ | $\left(\dfrac{x_1+x_2+x_3}{3}, \dfrac{y_1+y_2+y_3}{3}\right)$ |
| **Circumcentre** $O$ | equidistant from all three vertices — solve two perpendicular bisectors |
| **Orthocentre** $H$ | intersection of two altitudes; for a right triangle, $H$ = right-angle vertex |
| **Incentre** $I$ | $\left(\dfrac{ax_1+bx_2+cx_3}{a+b+c}, \dots\right)$, weights = opposite side lengths |

A beautiful fact: $O$, $G$, $H$ are collinear (the **Euler line**) with $G$ dividing $OH$ in ratio $1:2$.

> [!IMPORTANT]
> The **centroid is the easy average**; circumcentre and orthocentre need you to intersect two lines
> (bisectors / altitudes). The Euler-line relation $H = 3G - 2O$ lets you get the third centre free once you
> have two — a slick JEE shortcut.

---

<a id="7-locus"></a>
## 7. The locus method as a universal tool

Almost every "find the path of a point such that…" problem follows one discipline:

1. Let the moving point be $P(h, k)$.
2. Write the given geometric condition as an **equation in $h, k$** (use distance, slope, section, area…).
3. Eliminate any parameters.
4. Replace $(h, k) \to (x, y)$ — that equation **is** the locus.

> [!IMPORTANT]
> The locus method is the single most transferable skill in coordinate geometry — it reappears for circles,
> parabolas and the rest. The only art is step 2: faithfully turning words ("equidistant", "sum of distances",
> "ratio") into algebra. Everything after is mechanical.

---

## ✅ Deep-dive takeaways

> - **Family $L_1 + \lambda L_2 = 0$:** write any line through an intersection without solving for the point.
> - **One ratio $t = -\tfrac{ax_1+by_1+c}{a^2+b^2}$** gives distance, foot and image together.
> - **Bisectors:** $\pm$ from equidistance; normalise $c > 0$ then check $a_1a_2 + b_1b_2$ for acute/obtuse.
> - **Pair of lines:** quadratic in $y/x$; perpendicular iff $a + b = 0$, coincident iff $h^2 = ab$.
> - **Translation** kills linear terms and preserves slopes/angles.
> - **Triangle centres:** centroid = average; $O, G, H$ collinear with $H = 3G - 2O$.
> - **Locus method:** point $(h,k)$ → condition as algebra → rename to $(x,y)$.

**Next:** [Formula Recap →](./05-formula-recap.md)
