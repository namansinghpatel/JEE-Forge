# Straight Lines — Formula Recap

> One-page revision sheet. Everything from [Concepts](./01-concepts.md) condensed to formulas and the cue for
> each. Pair with the flash sheet ([`flash.html`](./flash.html)) the night before a test.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

---

## 🔵 Slope & angle

| Quantity | Formula |
|---|---|
| Slope from two points | $m = \dfrac{y_2 - y_1}{x_2 - x_1} = \tan\theta$ |
| Slope from general form | $m = -\dfrac ab$ for $ax + by + c = 0$ |
| Angle between two lines | $\tan\theta = \left\lvert\dfrac{m_1 - m_2}{1 + m_1 m_2}\right\rvert$ |
| Parallel | $m_1 = m_2$ (or $a_1 b_2 = a_2 b_1$) |
| Perpendicular | $m_1 m_2 = -1$ (or $a_1 a_2 + b_1 b_2 = 0$) |

---

## 🟢 Forms of a line

| Form | Equation |
|---|---|
| Slope–intercept | $y = mx + c$ |
| Point–slope | $y - y_1 = m(x - x_1)$ |
| Two–point | $y - y_1 = \dfrac{y_2-y_1}{x_2-x_1}(x - x_1)$ |
| Intercept | $\dfrac xa + \dfrac yb = 1$ |
| Normal | $x\cos\alpha + y\sin\alpha = p$ |
| General | $ax + by + c = 0$ |

> **Cue:** match the form to the data you're given.

---

## 🟡 Distance & area

| Quantity | Formula |
|---|---|
| Distance between points | $\sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$ |
| Point to line | $d = \dfrac{\lvert ax_1 + by_1 + c\rvert}{\sqrt{a^2 + b^2}}$ |
| Between parallels | $d = \dfrac{\lvert c_1 - c_2\rvert}{\sqrt{a^2 + b^2}}$ (same $a, b$) |
| Area of triangle | $\dfrac12\lvert x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\rvert$ |
| Collinear | area $= 0$ ⟺ equal slopes |

---

## 🟣 Foot, image & reflection

With $t = -\dfrac{ax_1 + by_1 + c}{a^2 + b^2}$:
- **Foot** of perpendicular $= (x_1 + at,\ y_1 + bt)$
- **Image** (reflection) $= (x_1 + 2at,\ y_1 + 2bt)$
- Reflection in $x$-axis: $y \to -y$ · in $y$-axis: $x \to -x$ · in $y = x$: swap coordinates.

---

## ⚫ Advanced tools

| Tool | Formula / method |
|---|---|
| Family of lines | $L_1 + \lambda L_2 = 0$ (any line through the intersection) |
| Angle bisectors | $\dfrac{a_1x+b_1y+c_1}{\sqrt{a_1^2+b_1^2}} = \pm\dfrac{a_2x+b_2y+c_2}{\sqrt{a_2^2+b_2^2}}$ |
| Concurrency | $\begin{vmatrix} a_1 & b_1 & c_1 \\ a_2 & b_2 & c_2 \\ a_3 & b_3 & c_3 \end{vmatrix} = 0$ |
| Pair of lines (slopes) | $m_1 + m_2 = -\dfrac{2h}{b},\ m_1 m_2 = \dfrac ab$ |
| Pair: angle | $\tan\theta = \left\lvert\dfrac{2\sqrt{h^2 - ab}}{a + b}\right\rvert$ |
| Pair: ⟂ / coincident | $a + b = 0$ / $h^2 = ab$ |
| Centroid | $\left(\dfrac{\sum x_i}{3}, \dfrac{\sum y_i}{3}\right)$ |

---

## 🎯 Exam cues

> [!TIP]
> - **Line through an intersection + one condition** → family $L_1 + \lambda L_2 = 0$.
> - **"Reflect / foot / image"** → compute $t = -\tfrac{ax_1+by_1+c}{a^2+b^2}$ once.
> - **Equidistant from two lines** → angle bisectors ($\pm$).
> - **Three lines meet at a point?** → determinant $= 0$.
> - **$ax^2 + 2hxy + by^2 = 0$** → quadratic in $y/x$; ⟂ iff $a + b = 0$.
> - **"Find the path of a point"** → locus method: $(h,k)$ → algebra → rename $(x,y)$.
> - **Min-area triangle with axes** → AM–GM on the intercepts.

---

📄 **Google Drive source:** [`notes/scans/Class_11_MT_Straight_Lines_Formula.png`](./notes/scans/Class_11_MT_Straight_Lines_Formula.png) — the chapter formula sheet (vector PDF alongside).

**Back to:** [Concepts](./01-concepts.md) · [Flash sheet](./flash.html)
