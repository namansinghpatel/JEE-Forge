# Straight Lines — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning slope & angle, the forms
> of a line, perpendicular distance, foot/image of a point, the family of lines, angle bisectors and the pair of
> lines. Every problem marks the **❓ Question** and **✅ Answer**; Medium and Advanced carry a **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

> **Key formulas:** $m = \tfrac{y_2-y_1}{x_2-x_1} = \tan\theta$; perpendicular $m_1m_2=-1$; $\tan\theta=\left|\tfrac{m_1-m_2}{1+m_1m_2}\right|$; distance $d=\tfrac{|ax_1+by_1+c|}{\sqrt{a^2+b^2}}$; family $L_1+\lambda L_2=0$.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — slope, forms, intercepts, distance
- [Medium (M1–M15)](#medium) — angle, perpendiculars, foot/image, parallels
- [Advanced (A1–A10)](#advanced) — family, bisectors, concurrency, pair of lines
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1
> ❓ **Question.** Find the slope of the line through $(2, 3)$ and $(6, 11)$.

**✅ Answer.** $m = \dfrac{11 - 3}{6 - 2} = \dfrac84 = \boxed{2}$.

---

<a id="b2"></a>
### B2
> ❓ **Question.** Find the slope of $3x + 4y - 7 = 0$.

**✅ Answer.** $m = -\dfrac ab = -\dfrac34 = \boxed{-\tfrac34}$.

---

<a id="b3"></a>
### B3
> ❓ **Question.** Write the equation of the line with slope $2$ and $y$-intercept $-5$.

**✅ Answer.** $y = 2x - 5$.

---

<a id="b4"></a>
### B4
> ❓ **Question.** Find the equation of the line through $(1, 4)$ with slope $3$.

**✅ Answer.** $y - 4 = 3(x - 1) \Rightarrow y = 3x + 1$.

---

<a id="b5"></a>
### B5
> ❓ **Question.** Find the $x$- and $y$-intercepts of $2x + 3y = 12$.

**✅ Answer.** $x$-intercept $= 6$ (set $y=0$); $y$-intercept $= 4$ (set $x=0$).

---

<a id="b6"></a>
### B6
> ❓ **Question.** Is the line through $(0,0)$ and $(2,4)$ parallel to $y = 2x + 7$?

**✅ Answer.** Slope $= 2 =$ slope of the given line, so **yes, parallel**.

---

<a id="b7"></a>
### B7
> ❓ **Question.** Find the slope of a line perpendicular to one with slope $\tfrac35$.

**✅ Answer.** Negative reciprocal: $m = -\dfrac53 = \boxed{-\tfrac53}$.

---

<a id="b8"></a>
### B8
> ❓ **Question.** Find the distance of $(1, 2)$ from $3x + 4y - 5 = 0$.

**✅ Answer.** $d = \dfrac{|3(1) + 4(2) - 5|}{\sqrt{9 + 16}} = \dfrac{|6|}{5} = \boxed{\tfrac65}$.

---

<a id="b9"></a>
### B9
> ❓ **Question.** Write the line with $x$-intercept $4$ and $y$-intercept $3$ in intercept form.

**✅ Answer.** $\dfrac x4 + \dfrac y3 = 1$.

---

<a id="b10"></a>
### B10
> ❓ **Question.** Find the angle a line with slope $1$ makes with the $x$-axis.

**✅ Answer.** $\theta = \tan^{-1}(1) = \boxed{45°}$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1
> ❓ **Question.** Find the acute angle between $y = 2x + 1$ and $y = -3x + 4$.

> [!TIP]
> 🧭 **Strategy.** $\tan\theta = \left|\frac{m_1 - m_2}{1 + m_1 m_2}\right|$.

**Steps.** $\tan\theta = \left|\dfrac{2 - (-3)}{1 + (2)(-3)}\right| = \left|\dfrac{5}{-5}\right| = 1$.

**✅ Answer.** $\theta = 45°$.

---

<a id="m2"></a>
### M2
> ❓ **Question.** Find the equation of the line through $(2, 3)$ and $(5, 9)$.

> [!TIP]
> 🧭 **Strategy.** Slope first, then point–slope.

**Steps.** $m = \dfrac{9-3}{5-2} = 2$; $y - 3 = 2(x - 2) \Rightarrow y = 2x - 1$.

**✅ Answer.** $y = 2x - 1$.

---

<a id="m3"></a>
### M3
> ❓ **Question.** Find the equation of the line through $(3, -2)$ perpendicular to $4x - 3y + 5 = 0$.

> [!TIP]
> 🧭 **Strategy.** Slope of given line $= 4/3$; perpendicular slope $= -3/4$; use point–slope.

**Steps.** $y + 2 = -\tfrac34(x - 3) \Rightarrow 3x + 4y - 1 = 0$.

**✅ Answer.** $3x + 4y - 1 = 0$.

---

<a id="m4"></a>
### M4
> ❓ **Question.** Find the distance between the parallel lines $3x + 4y + 7 = 0$ and $3x + 4y - 3 = 0$.

> [!TIP]
> 🧭 **Strategy.** $d = \frac{|c_1 - c_2|}{\sqrt{a^2+b^2}}$ (coefficients already match).

**Steps.** $d = \dfrac{|7 - (-3)|}{\sqrt{9 + 16}} = \dfrac{10}{5} = 2$.

**✅ Answer.** $2$.

---

<a id="m5"></a>
### M5
> ❓ **Question.** Show that $(1, 1), (3, 5), (5, 9)$ are collinear.

> [!TIP]
> 🧭 **Strategy.** Compare slope $AB$ with slope $BC$.

**Steps.** Slope $AB = \dfrac{5-1}{3-1} = 2$; slope $BC = \dfrac{9-5}{5-3} = 2$. Equal, so collinear.

**✅ Answer.** Collinear (common slope $2$).

---

<a id="m6"></a>
### M6
> ❓ **Question.** Find the foot of the perpendicular from $(1, 2)$ to $2x + y - 1 = 0$.

> [!TIP]
> 🧭 **Strategy.** Use $\frac{x - x_1}{a} = \frac{y - y_1}{b} = -\frac{ax_1 + by_1 + c}{a^2 + b^2}$.

**Steps.** $-\dfrac{2(1) + 1(2) - 1}{4 + 1} = -\dfrac35$. So $x = 1 + 2(-\tfrac35) = -\tfrac15$, $y = 2 + 1(-\tfrac35) = \tfrac75$.

**✅ Answer.** Foot $= \left(-\tfrac15, \tfrac75\right)$.

---

<a id="m7"></a>
### M7
> ❓ **Question.** Find the area of the triangle with vertices $(1, 1), (4, 1), (1, 5)$.

> [!TIP]
> 🧭 **Strategy.** Area $= \frac12|x_1(y_2-y_3)+\dots|$.

**Steps.** $\tfrac12|1(1-5) + 4(5-1) + 1(1-1)| = \tfrac12|{-4} + 16 + 0| = 6$.

**✅ Answer.** $6$ square units.

---

<a id="m8"></a>
### M8
> ❓ **Question.** Find the equation of the line through $(2, 3)$ making equal intercepts on the axes.

> [!TIP]
> 🧭 **Strategy.** Equal intercepts $a = b$: $\frac xa + \frac ya = 1 \Rightarrow x + y = a$; pass through the point.

**Steps.** $2 + 3 = a \Rightarrow a = 5$.

**✅ Answer.** $x + y = 5$.

---

<a id="m9"></a>
### M9
> ❓ **Question.** Find $k$ if the lines $2x + 3y - 1 = 0$ and $kx + 6y + 5 = 0$ are parallel.

> [!TIP]
> 🧭 **Strategy.** Parallel ⟺ equal slopes ⟺ $a_1 b_2 = a_2 b_1$.

**Steps.** $-\tfrac23 = -\tfrac k6 \Rightarrow k = 4$.

**✅ Answer.** $k = 4$.

---

<a id="m10"></a>
### M10
> ❓ **Question.** Find the image (reflection) of the point $(1, 2)$ in the line $x - y = 0$.

> [!TIP]
> 🧭 **Strategy.** Reflecting in $y = x$ swaps coordinates.

**Steps.** For $y = x$, image of $(a, b)$ is $(b, a)$.

**✅ Answer.** $(2, 1)$.

---

<a id="m11"></a>
### M11
> ❓ **Question.** Find the equation of the perpendicular bisector of the segment joining $(1, 2)$ and $(3, 4)$.

> [!TIP]
> 🧭 **Strategy.** Midpoint + perpendicular slope.

**Steps.** Midpoint $(2, 3)$; slope of segment $= 1$, so perpendicular slope $= -1$: $y - 3 = -1(x - 2) \Rightarrow x + y = 5$.

**✅ Answer.** $x + y = 5$.

---

<a id="m12"></a>
### M12
> ❓ **Question.** A line passes through $(4, 3)$ and the origin. Find its equation.

> [!TIP]
> 🧭 **Strategy.** Through origin: $y = mx$, $m = 3/4$.

**Steps.** $y = \tfrac34 x \Rightarrow 3x - 4y = 0$.

**✅ Answer.** $3x - 4y = 0$.

---

<a id="m13"></a>
### M13
> ❓ **Question.** Find the value of $p$ if the distance of $(0,0)$ from $3x + 4y + p = 0$ is $2$.

> [!TIP]
> 🧭 **Strategy.** $d = \frac{|p|}{\sqrt{9+16}} = 2$.

**Steps.** $\dfrac{|p|}{5} = 2 \Rightarrow |p| = 10 \Rightarrow p = \pm 10$.

**✅ Answer.** $p = \pm 10$.

---

<a id="m14"></a>
### M14
> ❓ **Question.** Find the line through the intersection of $x + y - 4 = 0$ and $2x - y - 2 = 0$ and through $(1, 0)$, using the family method.

> [!TIP]
> 🧭 **Strategy.** $L_1 + \lambda L_2 = 0$; impose $(1,0)$.

**Steps.** $(x + y - 4) + \lambda(2x - y - 2) = 0$ at $(1,0)$: $(1 - 4) + \lambda(2 - 2) = -3 + 0 \ne 0$ — so $\lambda$ can't fix it unless we check: $-3 + \lambda(0) = -3$, meaning $L_2$ vanishes at $(1,0)$, so the required line **is** $2x - y - 2 = 0$.

**✅ Answer.** $2x - y - 2 = 0$ (the point already lies on $L_2$).

---

<a id="m15"></a>
### M15
> ❓ **Question.** Find the slope of the line making an angle of $60°$ with the positive $x$-axis.

> [!TIP]
> 🧭 **Strategy.** $m = \tan\theta$.

**Steps.** $m = \tan 60° = \sqrt3$.

**✅ Answer.** $\sqrt3$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1
> ❓ **Question.** Find the equation of the line through the intersection of $2x + 3y - 5 = 0$ and $3x - y - 2 = 0$ that is parallel to $y = x$.

> [!TIP]
> 🧭 **Strategy.** Family $L_1 + \lambda L_2 = 0$; set its slope $= 1$.

**Steps.** $(2 + 3\lambda)x + (3 - \lambda)y + (-5 - 2\lambda) = 0$. Slope $= -\dfrac{2 + 3\lambda}{3 - \lambda} = 1 \Rightarrow 2 + 3\lambda = -(3 - \lambda) = -3 + \lambda \Rightarrow 2\lambda = -5 \Rightarrow \lambda = -\tfrac52$. Substituting: $(2 - \tfrac{15}2)x + (3 + \tfrac52)y + (-5 + 5) = 0 \Rightarrow -\tfrac{11}2 x + \tfrac{11}2 y = 0 \Rightarrow y = x$... re-evaluate constant: $-5 - 2(-\tfrac52) = 0$, giving $x - y = 0$.

**✅ Answer.** $x - y = 0$ (i.e. $y = x$ passing through the intersection point).

---

<a id="a2"></a>
### A2
> ❓ **Question.** Find the equations of the bisectors of the angles between $3x - 4y + 7 = 0$ and $12x - 5y - 8 = 0$.

> [!TIP]
> 🧭 **Strategy.** $\frac{a_1x + b_1y + c_1}{\sqrt{a_1^2+b_1^2}} = \pm\frac{a_2x + b_2y + c_2}{\sqrt{a_2^2+b_2^2}}$.

**Steps.** $\dfrac{3x - 4y + 7}{5} = \pm\dfrac{12x - 5y - 8}{13}$. Cross-multiply: $13(3x - 4y + 7) = \pm 5(12x - 5y - 8)$.
$+$: $39x - 52y + 91 = 60x - 25y - 40 \Rightarrow 21x + 27y - 131 = 0$.
$-$: $39x - 52y + 91 = -60x + 25y + 40 \Rightarrow 99x - 77y + 51 = 0$.

**✅ Answer.** $21x + 27y - 131 = 0$ and $99x - 77y + 51 = 0$.

---

<a id="a3"></a>
### A3
> ❓ **Question.** Show that the lines $x + y - 1 = 0$, $2x - y + 1 = 0$ and $x - 2y + 2 = 0$ are concurrent.

> [!TIP]
> 🧭 **Strategy.** Determinant of coefficients $= 0$.

**Steps.** $\begin{vmatrix} 1 & 1 & -1 \\ 2 & -1 & 1 \\ 1 & -2 & 2 \end{vmatrix} = 1(-2 + 2) - 1(4 - 1) + (-1)(-4 + 1) = 0 - 3 + 3 = 0$.

**✅ Answer.** Determinant $= 0$, so the three lines are concurrent.

---

<a id="a4"></a>
### A4
> ❓ **Question.** Find the slopes of the two lines represented by $6x^2 + 11xy + 3y^2 = 0$.

> [!TIP]
> 🧭 **Strategy.** Divide by $x^2$ → quadratic in $m = y/x$: $3m^2 + 11m + 6 = 0$.

**Steps.** $3m^2 + 11m + 6 = 0 \Rightarrow m = \dfrac{-11 \pm \sqrt{121 - 72}}{6} = \dfrac{-11 \pm 7}{6}$, giving $m = -\tfrac23$ or $-3$.

**✅ Answer.** Slopes $-\tfrac23$ and $-3$.

---

<a id="a5"></a>
### A5
> ❓ **Question.** Find the angle between the pair of lines $x^2 - 4xy + y^2 = 0$.

> [!TIP]
> 🧭 **Strategy.** $\tan\theta = \left|\frac{2\sqrt{h^2 - ab}}{a + b}\right|$ with $a = 1, 2h = -4, b = 1$.

**Steps.** $h = -2$: $\tan\theta = \left|\dfrac{2\sqrt{4 - 1}}{1 + 1}\right| = \left|\dfrac{2\sqrt3}{2}\right| = \sqrt3$.

**✅ Answer.** $\theta = 60°$.

---

<a id="a6"></a>
### A6
> ❓ **Question.** Find the foot of the perpendicular and hence the image of $(2, 3)$ in the line $x + y - 2 = 0$.

> [!TIP]
> 🧭 **Strategy.** Use the ratio $-\frac{ax_1 + by_1 + c}{a^2 + b^2}$: once for the foot, twice for the image.

**Steps.** $-\dfrac{2 + 3 - 2}{1 + 1} = -\dfrac32$. Foot: $(2 - \tfrac32, 3 - \tfrac32) = (\tfrac12, \tfrac32)$. Image: $(2 + 2(-\tfrac32), 3 + 2(-\tfrac32)) = (-1, 0)$.

**✅ Answer.** Foot $(\tfrac12, \tfrac32)$; image $(-1, 0)$.

---

<a id="a7"></a>
### A7
> ❓ **Question.** A ray of light along $x + y = 1$ reflects off the $x$-axis. Find the equation of the reflected ray.

> [!TIP]
> 🧭 **Strategy.** Reflection in the $x$-axis sends $y \to -y$ in the line's equation.

**Steps.** Replace $y$ with $-y$: $x + (-y) = 1 \Rightarrow x - y = 1$.

**✅ Answer.** $x - y = 1$.

---

<a id="a8"></a>
### A8
> ❓ **Question.** Find the equation of the line through $(1, 2)$ whose perpendicular distance from the origin is maximum.

> [!TIP]
> 🧭 **Strategy.** The max distance equals $OP$, achieved when the line ⟂ $OP$ (where $P = (1,2)$).

**Steps.** Slope of $OP = 2$, so line slope $= -\tfrac12$: $y - 2 = -\tfrac12(x - 1) \Rightarrow x + 2y - 5 = 0$.

**✅ Answer.** $x + 2y - 5 = 0$ (max distance $= \sqrt5$).

---

<a id="a9"></a>
### A9
> ❓ **Question.** Find the locus of a point that is equidistant from $(1, 0)$ and $(0, 1)$.

> [!TIP]
> 🧭 **Strategy.** Equidistant locus = perpendicular bisector; set distances (squared) equal.

**Steps.** $(h-1)^2 + k^2 = h^2 + (k-1)^2 \Rightarrow -2h + 1 = -2k + 1 \Rightarrow h = k$. Rename: $y = x$.

**✅ Answer.** $y = x$.

---

<a id="a10"></a>
### A10
> ❓ **Question.** Show that $4x^2 + 4xy + y^2 = 0$ represents a pair of coincident lines, and find them.

> [!TIP]
> 🧭 **Strategy.** Coincident iff $h^2 = ab$; factor the perfect square.

**Steps.** $a = 4, h = 2, b = 1$: $h^2 = 4 = ab$, so coincident. $4x^2 + 4xy + y^2 = (2x + y)^2 = 0$.

**✅ Answer.** The coincident line $2x + y = 0$ (double).

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (coaching sheets, PYQs, test series). I'll add a
> full **🧭 Strategy + step-by-step solution** in this style and tag each with its difficulty and sub-topic
> (slope / forms / distance / family / bisector / pair-of-lines).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will be solved
> and logged here with the date.

<!--
TEMPLATE for each entry:

### Q1 · <short title> · <🟢/🟡/🔴> · <slope/forms/distance/family/bisector/pair>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
