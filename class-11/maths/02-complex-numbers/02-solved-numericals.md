# Complex Numbers — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning algebra of complex
> numbers, conjugate/modulus, polar form, De Moivre's theorem, cube/nth roots of unity, and the geometry of
> complex numbers. Every problem marks the **❓ Question** and **✅ Answer**; Medium and Advanced carry a
> **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \to, i, \bar z, |z|, \arg z, \omega. -->

> **Reminders:** $i^2=-1$; $z\bar z=|z|^2$; polar $z=re^{i\theta}$; $1+\omega+\omega^2=0$, $\omega^3=1$; De Moivre $(\cos\theta+i\sin\theta)^n=\cos n\theta+i\sin n\theta$.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — powers of i, algebra, conjugate, modulus, simple polar
- [Medium (M1–M15)](#medium) — division, polar form, De Moivre, cube roots of unity, equations
- [Advanced (A1–A10)](#advanced) — nth roots, rotation, loci, modulus identities
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** Simplify $i^{23}$.

**✅ Answer.** $23 = 4(5) + 3$, so $i^{23} = i^3 = \boxed{-i}$.

---

<a id="b2"></a>
### B2

> ❓ **Question.** Find $(3 + 2i) + (1 - 4i)$.

**✅ Answer.** $4 - 2i$.

---

<a id="b3"></a>
### B3

> ❓ **Question.** Multiply $(2 + 3i)(1 - i)$.

**✅ Answer.** $2 - 2i + 3i - 3i^2 = 2 + i + 3 = \boxed{5 + i}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** Find the conjugate and modulus of $z = 3 - 4i$.

**✅ Answer.** $\bar z = 3 + 4i$; $|z| = \sqrt{9 + 16} = \boxed{5}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** Simplify $\sqrt{-16}$.

**✅ Answer.** $\sqrt{-16} = 4i$.

---

<a id="b6"></a>
### B6

> ❓ **Question.** Compute $\sqrt{-2}\cdot\sqrt{-8}$ (careful!).

**✅ Answer.** $i\sqrt2 \cdot i\sqrt8 = i^2\sqrt{16} = -4$ (not $+4$).

---

<a id="b7"></a>
### B7

> ❓ **Question.** Find $z\bar z$ for $z = 2 + 5i$.

**✅ Answer.** $|z|^2 = 4 + 25 = \boxed{29}$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** Write $1 + i$ in modulus–argument form.

**✅ Answer.** $r = \sqrt2$, $\theta = 45°$: $\sqrt2(\cos45° + i\sin45°)$.

---

<a id="b9"></a>
### B9

> ❓ **Question.** State the value of $1 + \omega + \omega^2$.

**✅ Answer.** $0$.

---

<a id="b10"></a>
### B10

> ❓ **Question.** Find the modulus of $z = -3 + 4i$.

**✅ Answer.** $\sqrt{9 + 16} = \boxed{5}$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** Express $\dfrac{1}{2 + 3i}$ in the form $a + ib$.

> [!TIP]
> 🧭 **Strategy.** Multiply numerator and denominator by the conjugate $2 - 3i$.

**Steps.** $\dfrac{2 - 3i}{(2)^2 + (3)^2} = \dfrac{2 - 3i}{13}$.

**✅ Answer.** $\dfrac{2}{13} - \dfrac{3}{13}i$.

---

<a id="m2"></a>
### M2

> ❓ **Question.** Find the argument of $z = -1 + i$.

> [!TIP]
> 🧭 **Strategy.** It's in the 2nd quadrant, so adjust $\tan^{-1}(b/a)$.

**Steps.** Reference angle $45°$; 2nd quadrant → $\theta = 135°$ ($3\pi/4$).

**✅ Answer.** $\dfrac{3\pi}{4}$.

---

<a id="m3"></a>
### M3

> ❓ **Question.** Use De Moivre to find $(1 + i)^8$.

> [!TIP]
> 🧭 **Strategy.** Convert to polar ($r = \sqrt2$, $\theta = 45°$), raise to the 8th power.

**Steps.** $(\sqrt2)^8[\cos(8\cdot45°) + i\sin(360°)] = 16[\cos360° + i\sin360°] = 16(1)$.

**✅ Answer.** $16$.

---

<a id="m4"></a>
### M4

> ❓ **Question.** Simplify $\omega^{10} + \omega^{20}$ (where $\omega$ is a cube root of unity).

> [!TIP]
> 🧭 **Strategy.** Reduce exponents mod 3 ($\omega^3 = 1$).

**Steps.** $10 \equiv 1$, $20 \equiv 2 \pmod 3$: $\omega + \omega^2 = -1$.

**✅ Answer.** $-1$.

---

<a id="m5"></a>
### M5

> ❓ **Question.** Find the modulus and argument of $z = \sqrt3 + i$.

> [!TIP]
> 🧭 **Strategy.** $r = \sqrt{3+1}$; $\theta = \tan^{-1}(1/\sqrt3)$.

**Steps.** $r = 2$, $\theta = 30°$ (1st quadrant).

**✅ Answer.** $|z| = 2$, $\arg z = 30°$ ($\pi/6$).

---

<a id="m6"></a>
### M6

> ❓ **Question.** Solve $z^2 = -5 + 12i$ (find the square roots).

> [!TIP]
> 🧭 **Strategy.** Let $z = a + ib$; then $a^2 - b^2 = -5$ and $2ab = 12$. Solve the pair.

**Steps.** $ab = 6$; with $a^2 - b^2 = -5$ and $a^2 + b^2 = |{-5+12i}| = 13$: $a^2 = 4, b^2 = 9 \Rightarrow a = 2, b = 3$ (same sign as $ab>0$).

**✅ Answer.** $z = \pm(2 + 3i)$.

---

<a id="m7"></a>
### M7

> ❓ **Question.** If $z = 2 + 3i$, find $\operatorname{Re}(z^2)$ and $\operatorname{Im}(z^2)$.

> [!TIP]
> 🧭 **Strategy.** Expand $z^2 = (a+ib)^2 = a^2 - b^2 + 2abi$.

**Steps.** $z^2 = 4 - 9 + 12i = -5 + 12i$.

**✅ Answer.** $\operatorname{Re} = -5$, $\operatorname{Im} = 12$.

---

<a id="m8"></a>
### M8

> ❓ **Question.** Find the cube roots of unity's product $\omega \cdot \omega^2$ and $\omega + \omega^2$.

> [!TIP]
> 🧭 **Strategy.** $\omega^3 = 1$ and $1 + \omega + \omega^2 = 0$.

**Steps.** $\omega\cdot\omega^2 = \omega^3 = 1$; $\omega + \omega^2 = -1$.

**✅ Answer.** Product $= 1$; sum $= -1$.

---

<a id="m9"></a>
### M9

> ❓ **Question.** For what real $x, y$ is $(x + iy)(2 - 3i) = 13$?

> [!TIP]
> 🧭 **Strategy.** Expand and equate real and imaginary parts to $13 + 0i$.

**Steps.** $(2x + 3y) + i(2y - 3x) = 13$: so $2x + 3y = 13$, $2y - 3x = 0 \Rightarrow y = \tfrac{3x}{2}$. Then $2x + \tfrac{9x}{2} = 13 \Rightarrow \tfrac{13x}{2} = 13 \Rightarrow x = 2, y = 3$.

**✅ Answer.** $x = 2$, $y = 3$.

---

<a id="m10"></a>
### M10

> ❓ **Question.** Find $\left|\dfrac{3 + 4i}{1 - 2i}\right|$.

> [!TIP]
> 🧭 **Strategy.** $\left|\frac{z_1}{z_2}\right| = \frac{|z_1|}{|z_2|}$.

**Steps.** $\dfrac{\sqrt{9+16}}{\sqrt{1+4}} = \dfrac{5}{\sqrt5} = \sqrt5$.

**✅ Answer.** $\sqrt5$.

---

<a id="m11"></a>
### M11

> ❓ **Question.** Express $z = -1 - i$ in polar form.

> [!TIP]
> 🧭 **Strategy.** 3rd quadrant: adjust the argument.

**Steps.** $r = \sqrt2$; reference $45°$; 3rd quadrant → $\theta = -135°$ (or $225°$).

**✅ Answer.** $\sqrt2(\cos(-135°) + i\sin(-135°))$.

---

<a id="m12"></a>
### M12

> ❓ **Question.** Compute $(\cos20° + i\sin20°)^9$.

> [!TIP]
> 🧭 **Strategy.** De Moivre: multiply the angle by 9.

**Steps.** $\cos180° + i\sin180° = -1$.

**✅ Answer.** $-1$.

---

<a id="m13"></a>
### M13

> ❓ **Question.** Solve $z^2 + z + 1 = 0$.

> [!TIP]
> 🧭 **Strategy.** The roots are the non-real cube roots of unity ($\omega, \omega^2$).

**Steps.** $z = \dfrac{-1 \pm \sqrt{1 - 4}}{2} = \dfrac{-1 \pm i\sqrt3}{2}$.

**✅ Answer.** $z = \omega, \omega^2 = \dfrac{-1 \pm i\sqrt3}{2}$.

---

<a id="m14"></a>
### M14

> ❓ **Question.** If $z = x + iy$ and $|z - 1| = |z + 1|$, find the locus.

> [!TIP]
> 🧭 **Strategy.** Equal distances from $1$ and $-1$ → perpendicular bisector.

**Steps.** $(x-1)^2 + y^2 = (x+1)^2 + y^2 \Rightarrow -4x = 0 \Rightarrow x = 0$.

**✅ Answer.** The imaginary axis ($x = 0$).

---

<a id="m15"></a>
### M15

> ❓ **Question.** Find $|z|$ and $\arg z$ for $z = -2i$.

> [!TIP]
> 🧭 **Strategy.** Purely imaginary, negative → points down the imaginary axis.

**Steps.** $r = 2$; $\theta = -90°$ ($-\pi/2$).

**✅ Answer.** $|z| = 2$, $\arg z = -\dfrac{\pi}{2}$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** Find all 4th roots of unity.

> [!TIP]
> 🧭 **Strategy.** $z_k = e^{2\pi i k/4}$ for $k = 0,1,2,3$.

**Steps.** $e^0, e^{i\pi/2}, e^{i\pi}, e^{3i\pi/2} = 1, i, -1, -i$.

**✅ Answer.** $1, i, -1, -i$ (sum $= 0$, a square on the unit circle).

---

<a id="a2"></a>
### A2

> ❓ **Question.** Find the cube roots of $8i$.

> [!TIP]
> 🧭 **Strategy.** $8i = 8e^{i\pi/2}$; roots are $8^{1/3}e^{i(\pi/2 + 2\pi k)/3}$ for $k=0,1,2$.

**Steps.** $r^{1/3} = 2$; angles $\frac{\pi/2 + 2\pi k}{3} = 30°, 150°, 270°$.

**✅ Answer.** $2\,\text{cis}\,30°,\ 2\,\text{cis}\,150°,\ 2\,\text{cis}\,270°$ (i.e. $\sqrt3 + i,\ -\sqrt3 + i,\ -2i$).

---

<a id="a3"></a>
### A3

> ❓ **Question.** Prove/evaluate $1 + \omega^n + \omega^{2n}$ for $n$ a multiple of 3 vs not.

> [!TIP]
> 🧭 **Strategy.** If $3 \mid n$, each term is 1; otherwise it's $1 + \omega + \omega^2$ (reindexed).

**Steps.** $3 \mid n$: $1+1+1 = 3$. Else: $1 + \omega^n + \omega^{2n} = 0$.

**✅ Answer.** $3$ if $3 \mid n$, else $0$.

---

<a id="a4"></a>
### A4

> ❓ **Question.** The vertices of an equilateral triangle on the Argand plane are $z_1, z_2, z_3$. Show $z_1^2 + z_2^2 + z_3^2 = z_1 z_2 + z_2 z_3 + z_3 z_1$.

> [!TIP]
> 🧭 **Strategy.** Equilateral ⇔ $z_1 + \omega z_2 + \omega^2 z_3 = 0$ (or its conjugate); expand.

**Steps.** The equilateral condition is equivalent to $z_1^2+z_2^2+z_3^2 - (z_1z_2+z_2z_3+z_3z_1) = 0$ (a standard result).

**✅ Answer.** $z_1^2 + z_2^2 + z_3^2 = z_1z_2 + z_2z_3 + z_3z_1$ (the equilateral-triangle identity).

---

<a id="a5"></a>
### A5

> ❓ **Question.** If $|z - 2| = 3$, describe the locus and give its centre and radius.

> [!TIP]
> 🧭 **Strategy.** $|z - z_0| = r$ is a circle.

**Steps.** Centre at $z_0 = 2$ (point $(2,0)$), radius $3$.

**✅ Answer.** A circle, centre $(2, 0)$, radius $3$.

---

<a id="a6"></a>
### A6

> ❓ **Question.** Rotate the point $z = 1 + i$ by $90°$ about the origin.

> [!TIP]
> 🧭 **Strategy.** Multiply by $e^{i90°} = i$.

**Steps.** $(1 + i)\cdot i = i + i^2 = -1 + i$.

**✅ Answer.** $-1 + i$.

---

<a id="a7"></a>
### A7

> ❓ **Question.** Find the sum $1 + \omega + \omega^2 + \dots + \omega^{98}$ ($\omega$ a cube root of unity).

> [!TIP]
> 🧭 **Strategy.** Group in threes ($1 + \omega + \omega^2 = 0$); count leftover terms.

**Steps.** 99 terms = 33 complete groups of 3, each summing to 0.

**✅ Answer.** $0$.

---

<a id="a8"></a>
### A8

> ❓ **Question.** If $z + \dfrac{1}{z} = 2\cos\theta$, find $z^n + \dfrac{1}{z^n}$.

> [!TIP]
> 🧭 **Strategy.** $z = e^{i\theta}$, so $z^n + z^{-n} = 2\cos n\theta$ (De Moivre).

**Steps.** From $z + 1/z = 2\cos\theta$, $z = \cos\theta + i\sin\theta$; then $z^n + z^{-n} = 2\cos n\theta$.

**✅ Answer.** $2\cos n\theta$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** Find the locus of $z$ if $\arg\!\left(\dfrac{z - 1}{z + 1}\right) = \dfrac{\pi}{2}$.

> [!TIP]
> 🧭 **Strategy.** $\arg = \pi/2$ means the vector is purely imaginary → the two position vectors are perpendicular → a circle (semicircle) on diameter from $-1$ to $1$.

**Steps.** The condition gives a circle with the segment from $z=1$ to $z=-1$ as a diameter (excluding the endpoints), i.e. $|z| = 1$ in the upper half.

**✅ Answer.** The arc of the unit circle $|z| = 1$ (with $\operatorname{Im} z > 0$).

---

<a id="a10"></a>
### A10

> ❓ **Question.** Using De Moivre, express $\cos3\theta$ in terms of $\cos\theta$.

> [!TIP]
> 🧭 **Strategy.** Expand $(\cos\theta + i\sin\theta)^3$ and compare real parts.

**Steps.** $(\cos\theta+i\sin\theta)^3 = \cos^3\theta + 3\cos^2\theta(i\sin\theta) + 3\cos\theta(i^2\sin^2\theta) + i^3\sin^3\theta$. Real part: $\cos^3\theta - 3\cos\theta\sin^2\theta = \cos^3\theta - 3\cos\theta(1-\cos^2\theta)$.

**✅ Answer.** $\cos3\theta = 4\cos^3\theta - 3\cos\theta$.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style, and tag each
> with its difficulty and sub-topic (algebra / polar / De Moivre / roots of unity / geometry).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <algebra/polar/demoivre/roots/geometry>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
