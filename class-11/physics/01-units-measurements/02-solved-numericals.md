# Units & Measurements — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning unit conversion,
> dimensional formulae, homogeneity checks, significant figures, error calculation and propagation, and the
> dimensional method. Every problem marks the **❓ Question** and **✅ Answer**; Medium and Advanced carry a
> **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq, \pm, \times. -->

> **Key formulas:** $n_1u_1 = n_2u_2$; $[F]=[\text{MLT}^{-2}]$; sums → $\Delta Z = \Delta A + \Delta B$; products → $\tfrac{\Delta Z}{Z} = p\tfrac{\Delta A}{A} + q\tfrac{\Delta B}{B}$; power-law $Q = k\,a^xb^yc^z$.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — conversions, dimensions, significant figures
- [Medium (M1–M15)](#medium) — homogeneity, error propagation, rounding
- [Advanced (A1–A10)](#advanced) — dimensional method, combined errors, estimation
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1
> ❓ **Question.** How many significant figures are in $0.00430$?

**✅ Answer.** $3$ (leading zeros don't count; the trailing zero after the decimal does): **4, 3, 0**.

---

<a id="b2"></a>
### B2
> ❓ **Question.** Write the dimensional formula of velocity.

**✅ Answer.** $[\text{velocity}] = [\text{LT}^{-1}]$.

---

<a id="b3"></a>
### B3
> ❓ **Question.** Convert $72$ km/h to m/s.

**✅ Answer.** $72 \times \dfrac{1000}{3600} = 20$ m/s.

---

<a id="b4"></a>
### B4
> ❓ **Question.** What is the dimensional formula of force?

**✅ Answer.** $[\text{MLT}^{-2}]$ (from $F = ma$).

---

<a id="b5"></a>
### B5
> ❓ **Question.** How many significant figures in $2.300 \times 10^4$?

**✅ Answer.** $4$ (the trailing zeros in the mantissa count).

---

<a id="b6"></a>
### B6
> ❓ **Question.** Name the SI base unit (and symbol) of amount of substance.

**✅ Answer.** mole (mol).

---

<a id="b7"></a>
### B7
> ❓ **Question.** Round $3.14159$ to $3$ significant figures.

**✅ Answer.** $3.14$.

---

<a id="b8"></a>
### B8
> ❓ **Question.** What is the dimensional formula of area?

**✅ Answer.** $[\text{L}^2]$.

---

<a id="b9"></a>
### B9
> ❓ **Question.** Express $1$ micrometre ($\mu$m) in metres.

**✅ Answer.** $1\,\mu\text{m} = 10^{-6}$ m.

---

<a id="b10"></a>
### B10
> ❓ **Question.** Is "strain" dimensional or dimensionless?

**✅ Answer.** Dimensionless (ratio of two lengths): $[\text{M}^0\text{L}^0\text{T}^0]$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1
> ❓ **Question.** Find the dimensional formula of pressure.

> [!TIP]
> 🧭 **Strategy.** $P = F/A$; use $[F] = [\text{MLT}^{-2}]$, $[A] = [\text{L}^2]$.

**Steps.** $[P] = \dfrac{[\text{MLT}^{-2}]}{[\text{L}^2]} = [\text{ML}^{-1}\text{T}^{-2}]$.

**✅ Answer.** $[\text{ML}^{-1}\text{T}^{-2}]$.

---

<a id="m2"></a>
### M2
> ❓ **Question.** Check whether $v^2 = u^2 + 2as$ is dimensionally consistent.

> [!TIP]
> 🧭 **Strategy.** Each term should reduce to $[\text{L}^2\text{T}^{-2}]$.

**Steps.** $[v^2] = [\text{L}^2\text{T}^{-2}]$; $[u^2] = [\text{L}^2\text{T}^{-2}]$; $[as] = [\text{LT}^{-2}][\text{L}] = [\text{L}^2\text{T}^{-2}]$. All match.

**✅ Answer.** Dimensionally consistent.

---

<a id="m3"></a>
### M3
> ❓ **Question.** The length of a rod is $(25.0 \pm 0.1)$ cm. Find the percentage error.

> [!TIP]
> 🧭 **Strategy.** $\frac{\Delta x}{x} \times 100$.

**Steps.** $\dfrac{0.1}{25.0} \times 100 = 0.4\%$.

**✅ Answer.** $0.4\%$.

---

<a id="m4"></a>
### M4
> ❓ **Question.** Add $12.52 + 0.3 + 6.123$ to the correct number of decimal places.

> [!TIP]
> 🧭 **Strategy.** Keep the fewest decimal places (here $1$, from $0.3$).

**Steps.** Sum $= 18.943$; round to $1$ decimal place → $18.9$.

**✅ Answer.** $18.9$.

---

<a id="m5"></a>
### M5
> ❓ **Question.** Multiply $2.5 \times 3.42$ to the correct number of significant figures.

> [!TIP]
> 🧭 **Strategy.** Keep the fewest s.f. (here $2$, from $2.5$).

**Steps.** $2.5 \times 3.42 = 8.55$; round to $2$ s.f. → $8.6$.

**✅ Answer.** $8.6$.

---

<a id="m6"></a>
### M6
> ❓ **Question.** Find the dimensional formula of the gravitational constant $G$ ($F = \dfrac{Gm_1m_2}{r^2}$).

> [!TIP]
> 🧭 **Strategy.** Solve $G = \dfrac{Fr^2}{m_1m_2}$ dimensionally.

**Steps.** $[G] = \dfrac{[\text{MLT}^{-2}][\text{L}^2]}{[\text{M}^2]} = [\text{M}^{-1}\text{L}^3\text{T}^{-2}]$.

**✅ Answer.** $[\text{M}^{-1}\text{L}^3\text{T}^{-2}]$.

---

<a id="m7"></a>
### M7
> ❓ **Question.** A quantity $Z = A^2B$. If $\Delta A/A = 1\%$ and $\Delta B/B = 2\%$, find $\Delta Z/Z$.

> [!TIP]
> 🧭 **Strategy.** $\frac{\Delta Z}{Z} = 2\frac{\Delta A}{A} + \frac{\Delta B}{B}$.

**Steps.** $2(1\%) + 2\% = 4\%$.

**✅ Answer.** $4\%$.

---

<a id="m8"></a>
### M8
> ❓ **Question.** Find the dimensional formula of Planck's constant $h$ ($E = h\nu$).

> [!TIP]
> 🧭 **Strategy.** $h = E/\nu$; $[E] = [\text{ML}^2\text{T}^{-2}]$, $[\nu] = [\text{T}^{-1}]$.

**Steps.** $[h] = \dfrac{[\text{ML}^2\text{T}^{-2}]}{[\text{T}^{-1}]} = [\text{ML}^2\text{T}^{-1}]$.

**✅ Answer.** $[\text{ML}^2\text{T}^{-1}]$.

---

<a id="m9"></a>
### M9
> ❓ **Question.** The radius of a sphere is measured as $(2.1 \pm 0.1)$ cm. Find the percentage error in its volume.

> [!TIP]
> 🧭 **Strategy.** $V \propto r^3$, so $\frac{\Delta V}{V} = 3\frac{\Delta r}{r}$.

**Steps.** $3 \times \dfrac{0.1}{2.1} \times 100 \approx 3 \times 4.76\% = 14.3\%$.

**✅ Answer.** $\approx 14.3\%$.

---

<a id="m10"></a>
### M10
> ❓ **Question.** Convert $1$ newton to dyne (CGS unit of force).

> [!TIP]
> 🧭 **Strategy.** $1\,\text{N} = 1\,\text{kg}\cdot\text{m/s}^2$; use $1$ kg $= 10^3$ g, $1$ m $= 10^2$ cm.

**Steps.** $1\,\text{N} = 10^3\,\text{g} \times 10^2\,\text{cm/s}^2 = 10^5\,\text{g·cm/s}^2 = 10^5$ dyne.

**✅ Answer.** $1$ N $= 10^5$ dyne.

---

<a id="m11"></a>
### M11
> ❓ **Question.** Two resistances $R_1 = (100 \pm 3)\,\Omega$ and $R_2 = (200 \pm 4)\,\Omega$ are in series. Find the total resistance with error.

> [!TIP]
> 🧭 **Strategy.** Series: $R = R_1 + R_2$; absolute errors add.

**Steps.** $R = 300\,\Omega$; $\Delta R = 3 + 4 = 7\,\Omega$.

**✅ Answer.** $R = (300 \pm 7)\,\Omega$.

---

<a id="m12"></a>
### M12
> ❓ **Question.** Express the order of magnitude of $4.7 \times 10^8$.

> [!TIP]
> 🧭 **Strategy.** Round the mantissa to the nearest power of ten ($4.7 \ge 3.16$ → round up).

**Steps.** $4.7 \times 10^8 \approx 10^1 \times 10^8 = 10^9$.

**✅ Answer.** Order of magnitude $= 9$ (i.e. $10^9$).

---

<a id="m13"></a>
### M13
> ❓ **Question.** Check the dimensional correctness of $T = 2\pi\sqrt{\dfrac{\ell}{g}}$ (pendulum).

> [!TIP]
> 🧭 **Strategy.** $2\pi$ is dimensionless; check $\sqrt{\ell/g}$.

**Steps.** $\left[\sqrt{\ell/g}\right] = \sqrt{\dfrac{[\text{L}]}{[\text{LT}^{-2}]}} = \sqrt{[\text{T}^2]} = [\text{T}]$ — matches $[T]$.

**✅ Answer.** Dimensionally correct.

---

<a id="m14"></a>
### M14
> ❓ **Question.** The density of a cube is found from mass $(10.0 \pm 0.1)$ g and side $(2.00 \pm 0.01)$ cm. Find the percentage error in density.

> [!TIP]
> 🧭 **Strategy.** $\rho = m/a^3$, so $\frac{\Delta\rho}{\rho} = \frac{\Delta m}{m} + 3\frac{\Delta a}{a}$.

**Steps.** $\dfrac{0.1}{10.0}\times100 + 3\cdot\dfrac{0.01}{2.00}\times100 = 1\% + 1.5\% = 2.5\%$.

**✅ Answer.** $2.5\%$.

---

<a id="m15"></a>
### M15
> ❓ **Question.** Find the dimensional formula of coefficient of viscosity $\eta$ (from $F = \eta A \dfrac{dv}{dx}$).

> [!TIP]
> 🧭 **Strategy.** $\eta = \dfrac{F}{A(dv/dx)}$; $[dv/dx] = [\text{T}^{-1}]$.

**Steps.** $[\eta] = \dfrac{[\text{MLT}^{-2}]}{[\text{L}^2][\text{T}^{-1}]} = [\text{ML}^{-1}\text{T}^{-1}]$.

**✅ Answer.** $[\text{ML}^{-1}\text{T}^{-1}]$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1
> ❓ **Question.** Using dimensional analysis, derive how the time period $T$ of a pendulum depends on length $\ell$, gravity $g$ and mass $m$.

> [!TIP]
> 🧭 **Strategy.** Assume $T = k\,\ell^a g^b m^c$; equate dimensions of M, L, T.

**Steps.** $[\text{T}] = [\text{L}]^a[\text{LT}^{-2}]^b[\text{M}]^c$. M: $c = 0$; T: $1 = -2b \Rightarrow b = -\tfrac12$; L: $0 = a + b \Rightarrow a = \tfrac12$. So $T = k\sqrt{\ell/g}$.

**✅ Answer.** $T \propto \sqrt{\ell/g}$ (mass-independent; $k = 2\pi$ not obtainable dimensionally).

---

<a id="a2"></a>
### A2
> ❓ **Question.** The velocity of a wave on a string depends on tension $F$ and linear mass density $\mu$. Find the relation.

> [!TIP]
> 🧭 **Strategy.** $v = k\,F^a\mu^b$; $[\mu] = [\text{ML}^{-1}]$.

**Steps.** $[\text{LT}^{-1}] = [\text{MLT}^{-2}]^a[\text{ML}^{-1}]^b$. M: $a + b = 0$; L: $a - b = 1$; T: $-2a = -1 \Rightarrow a = \tfrac12$, $b = -\tfrac12$. So $v = k\sqrt{F/\mu}$.

**✅ Answer.** $v \propto \sqrt{F/\mu}$.

---

<a id="a3"></a>
### A3
> ❓ **Question.** In an experiment $g$ is found from $g = \dfrac{4\pi^2 \ell}{T^2}$ with $\ell = (100.0 \pm 0.1)$ cm and $T = (2.00 \pm 0.01)$ s. Find the percentage error in $g$.

> [!TIP]
> 🧭 **Strategy.** $\frac{\Delta g}{g} = \frac{\Delta \ell}{\ell} + 2\frac{\Delta T}{T}$.

**Steps.** $\dfrac{0.1}{100.0}\times100 + 2\cdot\dfrac{0.01}{2.00}\times100 = 0.1\% + 1.0\% = 1.1\%$.

**✅ Answer.** $1.1\%$.

---

<a id="a4"></a>
### A4
> ❓ **Question.** Convert the value of $G = 6.67 \times 10^{-11}$ N·m²/kg² to CGS units (dyne·cm²/g²).

> [!TIP]
> 🧭 **Strategy.** $[G] = [\text{M}^{-1}\text{L}^3\text{T}^{-2}]$; use conversion factors for each base unit.

**Steps.** $n_2 = n_1\left(\dfrac{\text{M}_1}{\text{M}_2}\right)^{-1}\left(\dfrac{\text{L}_1}{\text{L}_2}\right)^{3}\left(\dfrac{\text{T}_1}{\text{T}_2}\right)^{-2} = 6.67\times10^{-11}(10^3)^{-1}(10^2)^3(1)^{-2} = 6.67\times10^{-11}\times10^{-3}\times10^{6} = 6.67\times10^{-8}$.

**✅ Answer.** $G = 6.67 \times 10^{-8}$ dyne·cm²/g².

---

<a id="a5"></a>
### A5
> ❓ **Question.** The energy $E$ of a photon depends on Planck's constant $h$, speed of light $c$ and wavelength $\lambda$. Find the form of the relation.

> [!TIP]
> 🧭 **Strategy.** $E = k\,h^a c^b \lambda^d$; $[h] = [\text{ML}^2\text{T}^{-1}]$, $[c] = [\text{LT}^{-1}]$, $[\lambda] = [\text{L}]$.

**Steps.** $[\text{ML}^2\text{T}^{-2}] = [\text{ML}^2\text{T}^{-1}]^a[\text{LT}^{-1}]^b[\text{L}]^d$. M: $a = 1$; T: $-2 = -a - b \Rightarrow b = 1$; L: $2 = 2a + b + d \Rightarrow d = 2 - 2 - 1 = -1$. So $E = k\,hc/\lambda$.

**✅ Answer.** $E \propto \dfrac{hc}{\lambda}$.

---

<a id="a6"></a>
### A6
> ❓ **Question.** A physical quantity $P = \dfrac{a^3 b^2}{\sqrt{c}\,d}$. The percentage errors in $a, b, c, d$ are $1\%, 2\%, 3\%, 4\%$. Find the maximum percentage error in $P$.

> [!TIP]
> 🧭 **Strategy.** Add relative errors weighted by exponent magnitudes.

**Steps.** $\dfrac{\Delta P}{P} = 3(1\%) + 2(2\%) + \tfrac12(3\%) + 1(4\%) = 3 + 4 + 1.5 + 4 = 12.5\%$.

**✅ Answer.** $12.5\%$.

---

<a id="a7"></a>
### A7
> ❓ **Question.** The frequency $f$ of a vibrating string depends on tension $F$, length $L$ and mass per unit length $\mu$. Derive the relation.

> [!TIP]
> 🧭 **Strategy.** $f = k\,F^a L^b \mu^c$; equate dimensions.

**Steps.** $[\text{T}^{-1}] = [\text{MLT}^{-2}]^a[\text{L}]^b[\text{ML}^{-1}]^c$. M: $a + c = 0$; T: $-2a = -1 \Rightarrow a = \tfrac12$, $c = -\tfrac12$; L: $a + b - c = 0 \Rightarrow b = -1$. So $f = \dfrac kL\sqrt{F/\mu}$.

**✅ Answer.** $f \propto \dfrac1L\sqrt{F/\mu}$.

---

<a id="a8"></a>
### A8
> ❓ **Question.** Why can't the formula $x = a\sin(\omega t)$ be derived by dimensional analysis?

> [!TIP]
> 🧭 **Strategy.** Recall the limitations of the dimensional method.

**Steps.** The argument $\omega t$ must be dimensionless, and $\sin$ is a **transcendental function** — dimensional
analysis cannot produce trigonometric, exponential or log dependence, nor the dimensionless constant.

**✅ Answer.** Dimensional analysis fails for relations involving trig/exponential functions (and can't fix dimensionless factors).

---

<a id="a9"></a>
### A9
> ❓ **Question.** A screw gauge has a least count of $0.01$ mm. A wire's diameter is measured as $0.39$ mm. Estimate the percentage error from the least count.

> [!TIP]
> 🧭 **Strategy.** LC error $\approx$ one least count; $\frac{\text{LC}}{\text{reading}} \times 100$.

**Steps.** $\dfrac{0.01}{0.39} \times 100 \approx 2.6\%$.

**✅ Answer.** $\approx 2.6\%$.

---

<a id="a10"></a>
### A10
> ❓ **Question.** The time for $20$ oscillations is measured four times as $39.6, 39.9, 39.5, 40.0$ s. Find the mean period and the mean absolute error in the period.

> [!TIP]
> 🧭 **Strategy.** Mean of readings, mean absolute deviation, then divide by 20 for the period.

**Steps.** Mean time $= \dfrac{39.6 + 39.9 + 39.5 + 40.0}{4} = 39.75$ s. Deviations: $0.15, 0.15, 0.25, 0.25$ → mean $= 0.20$ s. Period $\bar T = 39.75/20 = 1.9875 \approx 1.99$ s; $\Delta T = 0.20/20 = 0.01$ s.

**✅ Answer.** $T = (1.99 \pm 0.01)$ s.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (coaching sheets, PYQs, test series). I'll add a
> full **🧭 Strategy + step-by-step solution** in this style and tag each with its difficulty and sub-topic
> (dimensions / homogeneity / sig-fig / error-propagation / dimensional-method).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will be solved
> and logged here with the date.

<!--
TEMPLATE for each entry:

### Q1 · <short title> · <🟢/🟡/🔴> · <dimensions/homogeneity/sig-fig/error/method>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
