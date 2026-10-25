# Conic Sections — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spread across all four
> conics (circle, parabola, ellipse, hyperbola). Every problem marks the **❓ Question** and the
> **✅ Answer**. Medium and Advanced carry a **🧭 Strategy** block that explains *how to attack it in
> the exam* before the step-by-step working.

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. -->

---

## 📑 Index

- [Basic (B1–B10)](#basic) — read off centre/focus/eccentricity, identify the conic
- [Medium (M1–M15)](#medium) — build equations, tangents, focal distances, directrices
- [Advanced (A1–A10)](#advanced) — 3-point circles, tangent conditions, focal chords, director circle
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** Find the centre and radius of $x^2 + y^2 - 4x + 6y - 12 = 0$.

**✅ Answer.** Compare with $x^2+y^2+2gx+2fy+c=0$: $2g=-4\Rightarrow g=-2$, $2f=6\Rightarrow f=3$, $c=-12$.
Centre $=(-g,-f)=(2,-3)$; radius $=\sqrt{g^2+f^2-c}=\sqrt{4+9+12}=\boxed{5}$.

---

<a id="b2"></a>
### B2

> ❓ **Question.** Write the equation of the circle with centre $(1,2)$ and radius $3$.

**✅ Answer.** $(x-1)^2+(y-2)^2 = 9$.

---

<a id="b3"></a>
### B3

> ❓ **Question.** For the parabola $y^2 = 12x$, find the focus, directrix and length of latus rectum.

**✅ Answer.** $4a=12\Rightarrow a=3$. Focus $(3,0)$; directrix $x=-3$; latus rectum $=4a=\boxed{12}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** Describe the parabola $x^2 = -8y$: direction, focus, directrix.

**✅ Answer.** $x^2$ term with a minus → opens **downward**; $4a=8\Rightarrow a=2$. Focus $(0,-2)$; directrix $y=2$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** For the ellipse $\dfrac{x^2}{25}+\dfrac{y^2}{9}=1$, find $e$ and the foci.

**✅ Answer.** $a^2=25,\ b^2=9$. $e=\sqrt{1-\tfrac{b^2}{a^2}}=\sqrt{1-\tfrac{9}{25}}=\tfrac{4}{5}$. Foci $(\pm ae,0)=(\pm4,0)$.

---

<a id="b6"></a>
### B6

> ❓ **Question.** Find the length of the latus rectum of $\dfrac{x^2}{25}+\dfrac{y^2}{9}=1$.

**✅ Answer.** $\dfrac{2b^2}{a}=\dfrac{2\cdot9}{5}=\boxed{\tfrac{18}{5}=3.6}$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** For $\dfrac{x^2}{16}-\dfrac{y^2}{9}=1$, find $e$ and the foci.

**✅ Answer.** $a^2=16,\ b^2=9$. $e=\sqrt{1+\tfrac{b^2}{a^2}}=\sqrt{1+\tfrac{9}{16}}=\tfrac{5}{4}$. Foci $(\pm ae,0)=(\pm5,0)$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** Write the asymptotes of $\dfrac{x^2}{16}-\dfrac{y^2}{9}=1$.

**✅ Answer.** $y=\pm\dfrac{b}{a}x=\pm\dfrac{3}{4}x$.

---

<a id="b9"></a>
### B9

> ❓ **Question.** Identify the conic $9x^2+4y^2=36$ and state its major axis.

**✅ Answer.** Divide by 36: $\dfrac{x^2}{4}+\dfrac{y^2}{9}=1$. Both squares, same sign → **ellipse**; larger denominator ($9$) under $y^2$ → **major axis along the $y$-axis**.

---

<a id="b10"></a>
### B10

> ❓ **Question.** What is the eccentricity of a rectangular (equilateral) hyperbola?

**✅ Answer.** $a=b\Rightarrow e=\sqrt{1+\tfrac{b^2}{a^2}}=\sqrt{2}$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** Find the equation of the circle passing through $(0,0)$, $(2,0)$ and $(0,4)$.

> [!TIP]
> 🧭 **Strategy.** Use the general form $x^2+y^2+2gx+2fy+c=0$ and substitute the three points to get
> three linear equations in $g,f,c$. Passing through the origin instantly gives $c=0$, which makes
> the rest easy.

**Steps.**
1. Through $(0,0)$: $c=0$.
2. Through $(2,0)$: $4+4g=0\Rightarrow g=-1$.
3. Through $(0,4)$: $16+8f=0\Rightarrow f=-2$.

**✅ Answer.** $x^2+y^2-2x-4y=0$ (centre $(1,2)$, radius $\sqrt5$).

---

<a id="m2"></a>
### M2

> ❓ **Question.** Find the equation of the circle with centre $(2,3)$ that is tangent to the $x$-axis.

> [!TIP]
> 🧭 **Strategy.** "Tangent to the $x$-axis" means the radius equals the perpendicular distance from
> the centre to that axis — which is just the $|y|$-coordinate of the centre. Draw it to see why.

**Steps.** Distance from $(2,3)$ to the $x$-axis $=3$, so $r=3$.

**✅ Answer.** $(x-2)^2+(y-3)^2=9$.

---

<a id="m3"></a>
### M3

> ❓ **Question.** Find the equation of the parabola with vertex at the origin and focus $(0,4)$.

> [!TIP]
> 🧭 **Strategy.** Focus on the positive $y$-axis → parabola opens **up** → form $x^2=4ay$. The focus
> distance $a$ is just the focus coordinate.

**Steps.** $a=4$, so $x^2=4(4)y$.

**✅ Answer.** $x^2=16y$.

---

<a id="m4"></a>
### M4

> ❓ **Question.** A parabola has vertex $(0,0)$, axis along the $x$-axis, and passes through $(2,3)$. Find its equation and latus rectum.

> [!TIP]
> 🧭 **Strategy.** Axis along $x$ → form $y^2=4ax$. Substitute the known point to find $4a$ directly
> (you don't even need $a$ alone — $4a$ *is* the latus rectum).

**Steps.** $y^2=4ax$; at $(2,3)$: $9=4a(2)\Rightarrow 4a=\tfrac{9}{2}$.

**✅ Answer.** $y^2=\tfrac{9}{2}x$; latus rectum $=4a=\tfrac{9}{2}$.

---

<a id="m5"></a>
### M5

> ❓ **Question.** Find the ellipse with foci $(\pm3,0)$ and eccentricity $\tfrac12$.

> [!TIP]
> 🧭 **Strategy.** Foci give $ae=3$; combine with the given $e$ to get $a$, then use $b^2=a^2(1-e^2)$.

**Steps.**
1. $ae=3,\ e=\tfrac12\Rightarrow a=6$, so $a^2=36$.
2. $b^2=a^2(1-e^2)=36\left(1-\tfrac14\right)=36\cdot\tfrac34=27$.

**✅ Answer.** $\dfrac{x^2}{36}+\dfrac{y^2}{27}=1$.

---

<a id="m6"></a>
### M6

> ❓ **Question.** Find the eccentricity of an ellipse whose major axis is twice its minor axis.

> [!TIP]
> 🧭 **Strategy.** "Major = twice minor" means $a=2b$ (semi-axes). Feed the ratio $b^2/a^2$ straight
> into $e=\sqrt{1-b^2/a^2}$.

**Steps.** $a=2b\Rightarrow \dfrac{b^2}{a^2}=\dfrac14$; $e=\sqrt{1-\tfrac14}=\sqrt{\tfrac34}$.

**✅ Answer.** $e=\dfrac{\sqrt3}{2}$.

---

<a id="m7"></a>
### M7

> ❓ **Question.** Find the hyperbola with foci $(\pm5,0)$ and vertices $(\pm3,0)$.

> [!TIP]
> 🧭 **Strategy.** Vertices give $a$; foci give $ae$; then $b^2=a^2(e^2-1)$ — or more directly, for a
> hyperbola $b^2=(ae)^2-a^2$ (focal-distance² minus $a^2$).

**Steps.**
1. $a=3$, $ae=5\Rightarrow e=\tfrac53$.
2. $b^2=(ae)^2-a^2=25-9=16$.

**✅ Answer.** $\dfrac{x^2}{9}-\dfrac{y^2}{16}=1$.

---

<a id="m8"></a>
### M8

> ❓ **Question.** Find the circle with the points $(1,2)$ and $(3,4)$ as ends of a diameter.

> [!TIP]
> 🧭 **Strategy.** Use the **diameter form** $(x-x_1)(x-x_2)+(y-y_1)(y-y_2)=0$ — it's built exactly
> for "ends of a diameter" and skips finding the centre/radius separately.

**Steps.** $(x-1)(x-3)+(y-2)(y-4)=0 \Rightarrow x^2-4x+3+y^2-6y+8=0$.

**✅ Answer.** $x^2+y^2-4x-6y+11=0$ (centre $(2,3)$, radius $\sqrt2$).

---

<a id="m9"></a>
### M9

> ❓ **Question.** Find the parabola with focus $(2,0)$ and directrix $x=-2$.

> [!TIP]
> 🧭 **Strategy.** Focus and directrix are symmetric about the origin here, so the **vertex is the
> origin** and the axis is the $x$-axis. The vertex-to-focus distance is $a$.

**Steps.** $a=2$, opens right → $y^2=4ax=8x$.

**✅ Answer.** $y^2=8x$.

---

<a id="m10"></a>
### M10

> ❓ **Question.** For the parabola $y^2=8x$, find the focal distance of the point $(2,4)$ on it.

> [!TIP]
> 🧭 **Strategy.** The focal distance of a point on a parabola equals its distance to the directrix
> (that's the definition $e=1$). For $y^2=4ax$ this is simply $x+a$ — no distance formula needed.

**Steps.** $a=2$; focal distance $=x+a=2+2=4$.

**✅ Answer.** $4$.

---

<a id="m11"></a>
### M11

> ❓ **Question.** Find the directrices of $\dfrac{x^2}{25}+\dfrac{y^2}{16}=1$.

> [!TIP]
> 🧭 **Strategy.** Get $e$ from $a,b$, then the directrices are the vertical lines $x=\pm a/e$.

**Steps.** $a=5,b=4$; $e=\sqrt{1-\tfrac{16}{25}}=\tfrac35$; $\dfrac{a}{e}=\dfrac{5}{3/5}=\dfrac{25}{3}$.

**✅ Answer.** $x=\pm\dfrac{25}{3}$.

---

<a id="m12"></a>
### M12

> ❓ **Question.** Find the tangent to the circle $x^2+y^2=25$ at the point $(3,4)$.

> [!TIP]
> 🧭 **Strategy.** Use the **point form** of the tangent ("$T=0$"): replace $x^2\to xx_1$ and
> $y^2\to yy_1$. For $x^2+y^2=r^2$ this gives $xx_1+yy_1=r^2$ instantly.

**Steps.** $3x+4y=25$.

**✅ Answer.** $3x+4y=25$.

---

<a id="m13"></a>
### M13

> ❓ **Question.** For a point $P$ on $\dfrac{x^2}{16}+\dfrac{y^2}{9}=1$, find $PS_1+PS_2$ (sum of distances to the foci).

> [!TIP]
> 🧭 **Strategy.** Don't compute distances — use the **defining property** of the ellipse: the sum
> is always the major-axis length $2a$, for *every* point on the curve.

**Steps.** $a=4$, so $PS_1+PS_2=2a=8$.

**✅ Answer.** $8$.

---

<a id="m14"></a>
### M14

> ❓ **Question.** For what value of $c$ is the line $y=2x+c$ tangent to the parabola $y^2=8x$?

> [!TIP]
> 🧭 **Strategy.** The tangency condition for $y=mx+c$ to $y^2=4ax$ is $c=\dfrac{a}{m}$. Just read off
> $a$ and $m$. (If you forget it, substitute the line and set the discriminant to zero.)

**Steps.** $a=2,\ m=2$; $c=\dfrac{a}{m}=\dfrac{2}{2}=1$.

**✅ Answer.** $c=1$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** The hyperbola $\dfrac{x^2}{16}-\dfrac{y^2}{9}=1$ has eccentricity $e_1$; its conjugate $\dfrac{y^2}{9}-\dfrac{x^2}{16}=1$ has $e_2$. Show that $\dfrac{1}{e_1^2}+\dfrac{1}{e_2^2}=1$.

> [!TIP]
> 🧭 **Strategy.** Compute each eccentricity from its own $a,b$ (careful: for the conjugate, the
> transverse axis is the $y$-axis, so its "$a^2$" is $9$). Then add the reciprocals of the squares.

**Steps.**
1. $e_1^2=1+\tfrac{9}{16}=\tfrac{25}{16}\Rightarrow \tfrac{1}{e_1^2}=\tfrac{16}{25}$.
2. $e_2^2=1+\tfrac{16}{9}=\tfrac{25}{9}\Rightarrow \tfrac{1}{e_2^2}=\tfrac{9}{25}$.
3. Sum $=\tfrac{16}{25}+\tfrac{9}{25}=\tfrac{25}{25}=1$.

**✅ Answer.** $\dfrac{1}{e_1^2}+\dfrac{1}{e_2^2}=1$ (a standard conjugate-hyperbola identity).

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** Find the circle through $(1,1)$, $(2,-1)$ and $(3,2)$.

> [!TIP]
> 🧭 **Strategy.** General form, three substitutions → three equations in $g,f,c$. Subtract equations
> **pairwise** to eliminate $c$ and get two linear equations in $g,f$; solve, then back-substitute.

**Steps.** With $x^2+y^2+2gx+2fy+c=0$:
- $(1,1)$: $2g+2f+c=-2$ … (i)
- $(2,-1)$: $4g-2f+c=-5$ … (ii)
- $(3,2)$: $6g+4f+c=-13$ … (iii)

(ii)$-$(i): $2g-4f=-3$. (iii)$-$(ii): $2g+6f=-8$. Subtract: $10f=-5\Rightarrow f=-\tfrac12$; then $g=-\tfrac52$; from (i) $c=4$.

**✅ Answer.** $x^2+y^2-5x-y+4=0$ (centre $(\tfrac52,\tfrac12)$, radius $\sqrt{\tfrac52}$).

---

<a id="a2"></a>
### A2

> ❓ **Question.** For what $c$ is the line $y=x+c$ tangent to the ellipse $\dfrac{x^2}{4}+\dfrac{y^2}{1}=1$?

> [!TIP]
> 🧭 **Strategy.** The tangency condition for $y=mx+c$ to $\dfrac{x^2}{a^2}+\dfrac{y^2}{b^2}=1$ is
> $c^2=a^2m^2+b^2$. Plug $m=1$, $a^2=4$, $b^2=1$.

**Steps.** $c^2=4(1)^2+1=5\Rightarrow c=\pm\sqrt5$.

**✅ Answer.** $c=\pm\sqrt5$ (two parallel tangents).

---

<a id="a3"></a>
### A3

> ❓ **Question.** A focal chord of $y^2=4x$ has one end at parameter $t=2$. Find both endpoints and the chord's length.

> [!TIP]
> 🧭 **Strategy.** Use parametric points $(at^2,2at)$. For a **focal** chord the two parameters satisfy
> $t_1t_2=-1$, so the other end is $t_2=-1/t_1$. Focal-chord length $=a\left(t+\tfrac1t\right)^2$.

**Steps.** Here $a=1$, $t_1=2\Rightarrow t_2=-\tfrac12$.
- End 1: $(1\cdot4,\ 2\cdot2)=(4,4)$. End 2: $(1\cdot\tfrac14,\ 2\cdot(-\tfrac12))=(\tfrac14,-1)$.
- Length $=a\left(t+\tfrac1t\right)^2=1\left(2+\tfrac12\right)^2=\left(\tfrac52\right)^2=\tfrac{25}{4}$.

**✅ Answer.** Endpoints $(4,4)$ and $(\tfrac14,-1)$; length $=\tfrac{25}{4}=6.25$.

---

<a id="a4"></a>
### A4

> ❓ **Question.** Find the eccentricity of an ellipse whose latus rectum equals half its major axis.

> [!TIP]
> 🧭 **Strategy.** Translate the words into an equation: latus rectum $=\dfrac{2b^2}{a}$, major axis
> $=2a$. Set $\dfrac{2b^2}{a}=\dfrac12(2a)$, simplify to a $b^2/a^2$ ratio, then use $e$.

**Steps.** $\dfrac{2b^2}{a}=a\Rightarrow 2b^2=a^2\Rightarrow \dfrac{b^2}{a^2}=\tfrac12$; $e=\sqrt{1-\tfrac12}=\tfrac{1}{\sqrt2}$.

**✅ Answer.** $e=\dfrac{1}{\sqrt2}$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** Find the hyperbola (centre origin, transverse axis along $x$) with asymptotes $y=\pm2x$ passing through $(2,2\sqrt3)$.

> [!TIP]
> 🧭 **Strategy.** Asymptote slope $b/a=2$ fixes the *shape*; write $b=2a$ so the equation is
> $\dfrac{x^2}{a^2}-\dfrac{y^2}{4a^2}=1$, then substitute the point to pin down $a^2$.

**Steps.** $\dfrac{x^2}{a^2}-\dfrac{y^2}{4a^2}=1$; at $(2,2\sqrt3)$: $\dfrac{4}{a^2}-\dfrac{12}{4a^2}=\dfrac{4}{a^2}-\dfrac{3}{a^2}=\dfrac{1}{a^2}=1\Rightarrow a^2=1,\ b^2=4$.

**✅ Answer.** $x^2-\dfrac{y^2}{4}=1$.

---

<a id="a6"></a>
### A6

> ❓ **Question.** Identify and describe $9x^2+4y^2-18x-16y-11=0$ (type, centre, eccentricity).

> [!TIP]
> 🧭 **Strategy.** **Complete the square** in $x$ and in $y$ to shift to centred form. Group the
> $x$-terms and $y$-terms, factor out the leading coefficients, and absorb the constants.

**Steps.**
1. $9(x^2-2x)+4(y^2-4y)=11$.
2. $9[(x-1)^2-1]+4[(y-2)^2-4]=11 \Rightarrow 9(x-1)^2+4(y-2)^2=11+9+16=36$.
3. $\dfrac{(x-1)^2}{4}+\dfrac{(y-2)^2}{9}=1$ → ellipse, larger denom under $y$ → major axis vertical.
4. $a^2=9,b^2=4$ (here $a>b$ along $y$): $e=\sqrt{1-\tfrac{4}{9}}=\dfrac{\sqrt5}{3}$.

**✅ Answer.** Ellipse, centre $(1,2)$, major axis vertical, $e=\dfrac{\sqrt5}{3}$.

---

<a id="a7"></a>
### A7

> ❓ **Question.** Find the chord of contact of tangents drawn from the external point $(6,8)$ to the circle $x^2+y^2=25$, and the length of the tangent from that point.

> [!TIP]
> 🧭 **Strategy.** Two standard tools: the **chord of contact** is "$T=0$", i.e. $xx_1+yy_1=r^2$; the
> **length of tangent** from $(x_1,y_1)$ is $\sqrt{x_1^2+y_1^2-r^2}$ (= $\sqrt{S_1}$).

**Steps.**
- Chord of contact: $6x+8y=25$.
- Tangent length: $\sqrt{36+64-25}=\sqrt{75}=5\sqrt3$.

**✅ Answer.** Chord of contact $6x+8y=25$; tangent length $5\sqrt3$.

---

<a id="a8"></a>
### A8

> ❓ **Question.** Find the parabola with vertex $(0,0)$, symmetric about the $y$-axis, passing through $(5,2)$.

> [!TIP]
> 🧭 **Strategy.** Symmetric about the $y$-axis → form $x^2=4ay$. Substitute the point to find $4a$.

**Steps.** $x^2=4ay$; at $(5,2)$: $25=4a(2)\Rightarrow 4a=\tfrac{25}{2}$.

**✅ Answer.** $x^2=\dfrac{25}{2}y$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** From which locus of points are the two tangents to $\dfrac{x^2}{16}+\dfrac{y^2}{9}=1$ perpendicular to each other?

> [!TIP]
> 🧭 **Strategy.** This locus is the **director circle** of the ellipse: $x^2+y^2=a^2+b^2$. Just add
> the two denominators.

**Steps.** $x^2+y^2=16+9=25$.

**✅ Answer.** The director circle $x^2+y^2=25$ (radius $5$).

---

<a id="a10"></a>
### A10

> ❓ **Question.** An ellipse has foci $(\pm4,0)$ and passes through $(0,3)$. Find its equation.

> [!TIP]
> 🧭 **Strategy.** Use the defining property $PS_1+PS_2=2a$ at the given point to get $a$ directly,
> then $b^2=a^2-c^2$ with $c=4$. Much faster than plugging the point into the general equation.

**Steps.**
1. At $(0,3)$: distance to each focus $(\pm4,0)$ is $\sqrt{16+9}=5$, so $PS_1+PS_2=10=2a\Rightarrow a=5$.
2. $c=4\Rightarrow b^2=a^2-c^2=25-16=9$.

**✅ Answer.** $\dfrac{x^2}{25}+\dfrac{y^2}{9}=1$.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style as above, and
> tag each with its difficulty and which conic it tests.

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <circle/parabola/ellipse/hyperbola>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
