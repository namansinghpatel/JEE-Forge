# Units & Measurements — Deep Dive

> Beyond the textbook: the **techniques** that make this chapter a toolkit rather than a list. The thread —
> **dimensions are a bookkeeping system; use them to check, convert, and derive.**

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq, \pm, \times. -->

---

## 📑 Index

1. [The power-law method in full](#1-powerlaw)
2. [Unit conversion the dimensional way](#2-conversion)
3. [Why error propagation uses the rules it does](#3-errors)
4. [Significant figures done right in multi-step calculations](#4-sigfig)
5. [The three limitations of dimensional analysis](#5-limits)
6. [Dimensional formulae worth memorising](#6-table)
7. [Precision, accuracy and reporting a result](#7-reporting)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Practice](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-powerlaw"></a>
## 1. The power-law method in full

To find how $Q$ depends on quantities $a, b, c$:

1. Assume $Q = k\,a^x b^y c^z$ ($k$ dimensionless).
2. Replace each symbol with its dimensional formula.
3. **Equate the powers** of M, L, T (and any other base) on both sides — one equation per base dimension.
4. Solve the linear system for $x, y, z$.

**Worked skeleton** (wave speed on a string, $v = k\,F^x\mu^y$):
$$[\text{LT}^{-1}] = [\text{MLT}^{-2}]^x[\text{ML}^{-1}]^y \Rightarrow \begin{cases} \text{M}: & x + y = 0 \\ \text{L}: & x - y = 1 \\ \text{T}: & -2x = -1 \end{cases} \Rightarrow x = \tfrac12,\ y = -\tfrac12.$$

> [!IMPORTANT]
> The method is just **solving simultaneous equations in the exponents**. You can determine at most as many
> unknown exponents as there are independent base dimensions in play (usually 3: M, L, T). If a quantity depends
> on more variables than that, the method can't fix all the exponents uniquely.

---

<a id="2-conversion"></a>
## 2. Unit conversion the dimensional way

To convert a quantity with dimensional formula $[\text{M}^a\text{L}^b\text{T}^c]$ from system 1 to system 2:
$$n_2 = n_1 \left(\frac{\text{M}_1}{\text{M}_2}\right)^a \left(\frac{\text{L}_1}{\text{L}_2}\right)^b \left(\frac{\text{T}_1}{\text{T}_2}\right)^c.$$

**Example** (1 N → dyne, $[\text{MLT}^{-2}]$): $n_2 = 1\cdot\left(\tfrac{\text{kg}}{\text{g}}\right)^1\left(\tfrac{\text m}{\text{cm}}\right)^1\left(\tfrac{\text s}{\text s}\right)^{-2} = 10^3\cdot10^2 = 10^5$ dyne.

> [!TIP]
> Write the **dimensional formula first**, then plug the ratio of base units raised to each power. The exponents
> carry their signs — a $\text{T}^{-2}$ means the time ratio is raised to $-2$. This one formula replaces all the
> ad-hoc conversion tricks.

---

<a id="3-errors"></a>
## 3. Why error propagation uses the rules it does

The rules come from calculus (differentials), taken at worst case:

- **Sum/difference** $Z = A \pm B$: $dZ = dA \pm dB$; worst case $\Delta Z = \Delta A + \Delta B$ (errors never
  subtract — you assume they conspire).
- **Product/quotient** $Z = AB$: take logs, $\ln Z = \ln A + \ln B$, differentiate →
  $\dfrac{\Delta Z}{Z} = \dfrac{\Delta A}{A} + \dfrac{\Delta B}{B}$.
- **Power** $Z = A^n$: $\ln Z = n\ln A \Rightarrow \dfrac{\Delta Z}{Z} = \lvert n\rvert\dfrac{\Delta A}{A}$.

> [!IMPORTANT]
> The "take logs, then differentiate" derivation is why **products/quotients add relative errors** and **powers
> multiply by the exponent**. Always use the **magnitude** of the exponent and **add** (never cancel) — this
> gives the maximum possible error, which is what JEE asks for.

---

<a id="4-sigfig"></a>
## 4. Significant figures done right in multi-step calculations

The discipline:
1. **Carry extra (guard) digits** through intermediate steps.
2. Apply the **×/÷ rule** (fewest s.f.) and **+/− rule** (fewest decimal places) at each operation to know the
   final precision.
3. **Round only once**, at the very end.

**Trap:** mixing the two rules. In $\dfrac{a + b}{c}$, first do the sum by decimal places, then the division by
significant figures.

> [!WARNING]
> Rounding at every intermediate step **accumulates error** and can shift the last digit. Keep one or two guard
> digits until the final answer, then round. Exact numbers (counts, defined constants like $2$ in $2\pi r$) have
> **infinite** significant figures and never limit the result.

---

<a id="5-limits"></a>
## 5. The three limitations of dimensional analysis

1. **No dimensionless constants.** $T = 2\pi\sqrt{\ell/g}$ — the method gives $\sqrt{\ell/g}$ but not the $2\pi$.
2. **No transcendental functions.** Anything with $\sin$, $\cos$, $e^x$, $\ln$ can't be derived (their arguments
   must be dimensionless, but the functional form is invisible to dimensions).
3. **No multi-term relations.** A law like $s = ut + \tfrac12at^2$ (a *sum* of terms) can't be produced — the
   method assumes a single product of powers.

> [!NOTE]
> Dimensional analysis is powerful for **checking** and for **guessing the form** of simple laws, but it is blind
> to numbers and to additive structure. Treat a dimensionally-correct formula as *necessary but not sufficient*
> for correctness.

---

<a id="6-table"></a>
## 6. Dimensional formulae worth memorising

| Quantity | Dimensional formula |
|---|---|
| Velocity | $[\text{LT}^{-1}]$ |
| Acceleration | $[\text{LT}^{-2}]$ |
| Force | $[\text{MLT}^{-2}]$ |
| Work / energy | $[\text{ML}^2\text{T}^{-2}]$ |
| Power | $[\text{ML}^2\text{T}^{-3}]$ |
| Pressure / stress | $[\text{ML}^{-1}\text{T}^{-2}]$ |
| Momentum / impulse | $[\text{MLT}^{-1}]$ |
| Gravitational constant $G$ | $[\text{M}^{-1}\text{L}^3\text{T}^{-2}]$ |
| Planck's constant $h$ | $[\text{ML}^2\text{T}^{-1}]$ |
| Coefficient of viscosity | $[\text{ML}^{-1}\text{T}^{-1}]$ |
| Surface tension | $[\text{MT}^{-2}]$ |
| Charge | $[\text{AT}]$ |

> [!TIP]
> Learn the **first six** cold — most derived formulae build from force and energy. For the rest, re-derive from
> a defining equation on the spot; that's faster and more reliable than rote memory under exam pressure.

---

<a id="7-reporting"></a>
## 7. Precision, accuracy and reporting a result

A measured result is reported as $\bar{x} \pm \Delta x$, with:
- $\bar{x}$ = mean of readings (reduces random error),
- $\Delta x$ = mean absolute error (or least-count-based estimate),
- both quoted to **consistent** significant figures and units.

**Accuracy** (closeness to truth) is limited by **systematic** error; **precision** (repeatability) is limited by
**random** error and the **least count**.

> [!IMPORTANT]
> A tight $\pm\Delta x$ means high **precision**, not necessarily high **accuracy** — a zero-error instrument can
> be precisely wrong. Correct systematic errors (zero error, calibration) *before* averaging; averaging only
> tackles the random part.

---

## ✅ Deep-dive takeaways

> - **Power-law method:** assume $Q = k\,a^xb^yc^z$, equate M/L/T powers, solve the linear system.
> - **Conversion:** $n_2 = n_1(\text{M}_1/\text{M}_2)^a(\text{L}_1/\text{L}_2)^b(\text{T}_1/\text{T}_2)^c$.
> - **Errors:** sums add absolute, products add relative (× the exponent magnitude), worst-case always.
> - **Sig figs:** carry guard digits, apply ×/÷ (s.f.) and +/− (decimals) rules, round once at the end.
> - **Limits:** no constants, no transcendental functions, no multi-term laws.
> - **Report** as $\bar{x} \pm \Delta x$; precision ≠ accuracy.

**Next:** [Formula Recap →](./05-formula-recap.md)
