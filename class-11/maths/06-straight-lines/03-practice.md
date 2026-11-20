# Straight Lines — Practice Range

> **35 practice problems**, graded **Basic (10) · Medium (15) · Advanced (10)**. Each has an **approach hint**
> (open after a real attempt) and a **collapsible full solution**. Topics: slope & angle, forms, distance,
> foot/image, family of lines, bisectors, concurrency, pair of lines.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

> **Key formulas:** $m = \tan\theta = -a/b$; $\tan\theta = \left|\tfrac{m_1-m_2}{1+m_1m_2}\right|$; $d = \tfrac{|ax_1+by_1+c|}{\sqrt{a^2+b^2}}$; family $L_1 + \lambda L_2 = 0$.

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
> Find the slope of the line through $(1, 2)$ and $(4, 11)$.

<details><summary>🧭 Approach</summary>

$m = \frac{y_2 - y_1}{x_2 - x_1}$.
</details>

<details><summary>✅ Solution</summary>

$m = \dfrac{11 - 2}{4 - 1} = \boxed{3}$.
</details>

---

### P2
> Find the slope of $5x - 2y + 3 = 0$.

<details><summary>🧭 Approach</summary>

$m = -a/b$.
</details>

<details><summary>✅ Solution</summary>

$m = -\dfrac{5}{-2} = \boxed{\tfrac52}$.
</details>

---

### P3
> Write the line with slope $-1$ through $(2, 5)$.

<details><summary>🧭 Approach</summary>

Point–slope.
</details>

<details><summary>✅ Solution</summary>

$y - 5 = -1(x - 2) \Rightarrow x + y = 7$.
</details>

---

### P4
> Find the $y$-intercept of $4x + 3y = 24$.

<details><summary>🧭 Approach</summary>

Set $x = 0$.
</details>

<details><summary>✅ Solution</summary>

$3y = 24 \Rightarrow y = \boxed{8}$.
</details>

---

### P5
> Are $y = 3x + 1$ and $y = 3x - 4$ parallel, perpendicular, or neither?

<details><summary>🧭 Approach</summary>

Compare slopes.
</details>

<details><summary>✅ Solution</summary>

Both slope $3$ → **parallel**.
</details>

---

### P6
> Find the slope of a line perpendicular to $2x + 5y = 1$.

<details><summary>🧭 Approach</summary>

Slope of given $= -2/5$; take negative reciprocal.
</details>

<details><summary>✅ Solution</summary>

$m = \boxed{\tfrac52}$.
</details>

---

### P7
> Find the distance of $(2, 1)$ from $5x - 12y + 2 = 0$.

<details><summary>🧭 Approach</summary>

$d = \frac{|ax_1+by_1+c|}{\sqrt{a^2+b^2}}$.
</details>

<details><summary>✅ Solution</summary>

$d = \dfrac{|10 - 12 + 2|}{\sqrt{25 + 144}} = \dfrac{0}{13} = \boxed{0}$ (the point is on the line).
</details>

---

### P8
> Write the line with intercepts $a = 2$, $b = -3$.

<details><summary>🧭 Approach</summary>

Intercept form.
</details>

<details><summary>✅ Solution</summary>

$\dfrac x2 + \dfrac y{-3} = 1 \Rightarrow 3x - 2y = 6$.
</details>

---

### P9
> What angle does slope $m = \tfrac1{\sqrt3}$ make with the $x$-axis?

<details><summary>🧭 Approach</summary>

$\theta = \tan^{-1} m$.
</details>

<details><summary>✅ Solution</summary>

$\tan^{-1}\tfrac1{\sqrt3} = \boxed{30°}$.
</details>

---

### P10
> Convert $6x + 2y - 8 = 0$ to slope–intercept form.

<details><summary>🧭 Approach</summary>

Solve for $y$.
</details>

<details><summary>✅ Solution</summary>

$y = -3x + 4$.
</details>

---

<a id="medium"></a>
## 🟡 Medium (P11–P25)

### P11
> Find the acute angle between $y = x$ and $y = \sqrt3 x$.

<details><summary>🧭 Approach</summary>

$\tan\theta = |\frac{m_1 - m_2}{1 + m_1 m_2}|$.
</details>

<details><summary>✅ Solution</summary>

$\tan\theta = \left|\dfrac{1 - \sqrt3}{1 + \sqrt3}\right| = \left|\dfrac{(1-\sqrt3)}{(1+\sqrt3)}\right| = 2 - \sqrt3$, so $\theta = 15°$.
</details>

---

### P12
> Find the equation of the line through $(0, 5)$ perpendicular to $3x - y + 2 = 0$.

<details><summary>🧭 Approach</summary>

Given slope $3$; perpendicular slope $-1/3$.
</details>

<details><summary>✅ Solution</summary>

$y - 5 = -\tfrac13 x \Rightarrow x + 3y - 15 = 0$.
</details>

---

### P13
> Find the distance between $2x - 3y + 4 = 0$ and $2x - 3y - 9 = 0$.

<details><summary>🧭 Approach</summary>

$\frac{|c_1 - c_2|}{\sqrt{a^2+b^2}}$ (coefficients match).
</details>

<details><summary>✅ Solution</summary>

$\dfrac{|4 - (-9)|}{\sqrt{4 + 9}} = \dfrac{13}{\sqrt{13}} = \boxed{\sqrt{13}}$.
</details>

---

### P14
> Find $k$ so that $(k, 3), (2, -1), (5, 2)$ are collinear.

<details><summary>🧭 Approach</summary>

Area $= 0$ (or equal slopes).
</details>

<details><summary>✅ Solution</summary>

Slope of last two $= \dfrac{2 - (-1)}{5 - 2} = 1$. Slope $(k,3)\to(2,-1)$: $\dfrac{-1 - 3}{2 - k} = 1 \Rightarrow -4 = 2 - k \Rightarrow k = 6$.
</details>

---

### P15
> Find the area of the triangle formed by $x = 0$, $y = 0$ and $3x + 4y = 12$.

<details><summary>🧭 Approach</summary>

Intercepts give the legs of a right triangle.
</details>

<details><summary>✅ Solution</summary>

Intercepts $4$ and $3$: area $= \tfrac12(4)(3) = \boxed{6}$.
</details>

---

### P16
> Find the foot of the perpendicular from $(0, 0)$ to $x + y - 2 = 0$.

<details><summary>🧭 Approach</summary>

Ratio $-\frac{ax_1+by_1+c}{a^2+b^2}$.
</details>

<details><summary>✅ Solution</summary>

$-\dfrac{-2}{2} = 1$; foot $= (0 + 1, 0 + 1) = (1, 1)$.
</details>

---

### P17
> Find the equation of the line making an angle of $135°$ with the $x$-axis and passing through $(1, 1)$.

<details><summary>🧭 Approach</summary>

$m = \tan 135° = -1$.
</details>

<details><summary>✅ Solution</summary>

$y - 1 = -1(x - 1) \Rightarrow x + y = 2$.
</details>

---

### P18
> Find the value of $k$ for which $kx + 2y = 3$ and $3x - y = 1$ are perpendicular.

<details><summary>🧭 Approach</summary>

$a_1 a_2 + b_1 b_2 = 0$.
</details>

<details><summary>✅ Solution</summary>

$k(3) + 2(-1) = 0 \Rightarrow 3k = 2 \Rightarrow k = \tfrac23$.
</details>

---

### P19
> Find the reflection of $(3, 4)$ in the line $y = x$.

<details><summary>🧭 Approach</summary>

Reflection in $y = x$ swaps coordinates.
</details>

<details><summary>✅ Solution</summary>

$(4, 3)$.
</details>

---

### P20
> A line has intercepts whose sum is $7$ and it passes through $(3, 2)$. Find it (assume distinct intercepts).

<details><summary>🧭 Approach</summary>

$\frac x a + \frac y b = 1$ with $a + b = 7$ and $(3,2)$ on it.
</details>

<details><summary>✅ Solution</summary>

$\frac 3a + \frac 2{7-a} = 1 \Rightarrow 3(7-a) + 2a = a(7-a) \Rightarrow 21 - a = 7a - a^2 \Rightarrow a^2 - 8a + 21 = 0$. Discriminant $64 - 84 < 0$ → no real distinct-intercept solution; the condition forces equal-intercept check. _(Good trap: verify feasibility before solving.)_ With $a = b$: $a + b = 7$ impossible for integer equal; so no such line with real intercepts summing to 7 through $(3,2)$.
</details>

---

### P21
> Find the equation of the line parallel to $3x - 4y + 5 = 0$ and passing through $(1, 1)$.

<details><summary>🧭 Approach</summary>

Same $a, b$; find new $c$ from the point.
</details>

<details><summary>✅ Solution</summary>

$3(1) - 4(1) + c = 0 \Rightarrow c = 1$: $3x - 4y + 1 = 0$.
</details>

---

### P22
> Find the length of the perpendicular from $(1, -1)$ to $3x + 4y - 2 = 0$.

<details><summary>🧭 Approach</summary>

Distance formula.
</details>

<details><summary>✅ Solution</summary>

$\dfrac{|3 - 4 - 2|}{5} = \dfrac{3}{5} = \boxed{0.6}$.
</details>

---

### P23
> Find the point of intersection of $x + 2y = 5$ and $2x - y = 0$.

<details><summary>🧭 Approach</summary>

Solve simultaneously.
</details>

<details><summary>✅ Solution</summary>

$y = 2x$; $x + 4x = 5 \Rightarrow x = 1, y = 2$. Point $(1, 2)$.
</details>

---

### P24
> Find the equation of the line through $(2, 2)$ equally inclined to the axes (two answers).

<details><summary>🧭 Approach</summary>

Slopes $\pm 1$.
</details>

<details><summary>✅ Solution</summary>

$m = 1$: $y = x$. $m = -1$: $x + y = 4$.
</details>

---

### P25
> Find the distance of the point $(3, -5)$ from the line $3x - 4y - 26 = 0$.

<details><summary>🧭 Approach</summary>

Distance formula.
</details>

<details><summary>✅ Solution</summary>

$\dfrac{|9 + 20 - 26|}{5} = \dfrac{3}{5} = \boxed{0.6}$.
</details>

---

<a id="advanced"></a>
## 🔴 Advanced (P26–P35)

### P26
> Find the line through the intersection of $x + y = 1$ and $2x - 3y = 5$ that passes through $(0, 0)$.

<details><summary>🧭 Approach</summary>

Family $L_1 + \lambda L_2 = 0$, impose origin.
</details>

<details><summary>✅ Solution</summary>

$(x + y - 1) + \lambda(2x - 3y - 5) = 0$ at $(0,0)$: $-1 - 5\lambda = 0 \Rightarrow \lambda = -\tfrac15$. Line: $(x+y-1) - \tfrac15(2x-3y-5) = 0 \Rightarrow 3x + 8y = 0$.
</details>

---

### P27
> Find the bisectors of the angles between $x = 0$ and $y = 0$ (the axes).

<details><summary>🧭 Approach</summary>

Equidistant from both axes: $|x| = |y|$.
</details>

<details><summary>✅ Solution</summary>

$y = x$ and $y = -x$.
</details>

---

### P28
> Show the lines $2x + y - 3 = 0$, $x - y = 0$, $3x - 3 = 0$ are concurrent and find the point.

<details><summary>🧭 Approach</summary>

Solve two, verify the third.
</details>

<details><summary>✅ Solution</summary>

$x = 1$ (third line); $x - y = 0 \Rightarrow y = 1$; check $2(1) + 1 - 3 = 0$ ✓. Point $(1, 1)$.
</details>

---

### P29
> Find the slopes of the lines $2x^2 - 7xy + 3y^2 = 0$.

<details><summary>🧭 Approach</summary>

$3m^2 - 7m + 2 = 0$ (divide by $x^2$, $m = y/x$).
</details>

<details><summary>✅ Solution</summary>

$m = \dfrac{7 \pm \sqrt{49 - 24}}{6} = \dfrac{7 \pm 5}{6}$: $m = 2$ or $\tfrac13$.
</details>

---

### P30
> Find the angle between the pair $3x^2 + 8xy - 3y^2 = 0$.

<details><summary>🧭 Approach</summary>

$a + b = 3 + (-3) = 0$ → perpendicular.
</details>

<details><summary>✅ Solution</summary>

$a + b = 0$, so the lines are perpendicular; $\theta = 90°$.
</details>

---

### P31
> Find the image of $(4, 1)$ in the line $2x - 3y + 5 = 0$.

<details><summary>🧭 Approach</summary>

Use the reflection ratio, twice.
</details>

<details><summary>✅ Solution</summary>

$-\dfrac{2(4) - 3(1) + 5}{4 + 9} = -\dfrac{10}{13}$. Image $= (4 + 2\cdot2(-\tfrac{10}{13}),\ 1 + 2\cdot(-3)(-\tfrac{10}{13})) = (4 - \tfrac{40}{13},\ 1 + \tfrac{60}{13}) = (\tfrac{12}{13}, \tfrac{73}{13})$.
</details>

---

### P32
> Find the equation of the line through $(1, 2)$ that is at the maximum distance from the point $(3, 4)$.

<details><summary>🧭 Approach</summary>

Max distance when the line ⟂ to the segment joining the two points.
</details>

<details><summary>✅ Solution</summary>

Slope of segment $= 1$; line slope $= -1$: $y - 2 = -1(x - 1) \Rightarrow x + y = 3$.
</details>

---

### P33
> Find the locus of a point equidistant from the lines $3x - 4y + 1 = 0$ and $4x + 3y - 2 = 0$.

<details><summary>🧭 Approach</summary>

Set perpendicular distances equal (angle bisectors).
</details>

<details><summary>✅ Solution</summary>

$\dfrac{|3x - 4y + 1|}{5} = \dfrac{|4x + 3y - 2|}{5} \Rightarrow 3x - 4y + 1 = \pm(4x + 3y - 2)$, giving $x + 7y - 3 = 0$ and $7x - y - 1 = 0$.
</details>

---

### P34
> The line $x/a + y/b = 1$ passes through $(1, 1)$ and makes a triangle of minimum area with the axes. Find $a, b$.

<details><summary>🧭 Approach</summary>

Area $= \tfrac12 ab$; minimise subject to $\tfrac1a + \tfrac1b = 1$ (AM–GM or calculus).
</details>

<details><summary>✅ Solution</summary>

By symmetry/AM–GM, minimum at $a = b = 2$: line $x + y = 2$, area $= 2$.
</details>

---

### P35
> Find the orthocentre of the triangle with vertices $(0,0), (4,0), (0,3)$.

<details><summary>🧭 Approach</summary>

Right-angled triangle → orthocentre is at the right-angle vertex.
</details>

<details><summary>✅ Solution</summary>

The right angle is at the origin, so the orthocentre is $(0, 0)$.
</details>

---

**Next:** [Deep Dive →](./04-deep-dive.md) · [Formula Recap →](./05-formula-recap.md)
