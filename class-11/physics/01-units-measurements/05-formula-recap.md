# Units & Measurements — Formula Recap

> One-page revision sheet. Everything from [Concepts](./01-concepts.md) condensed to formulas and the cue for
> each. Pair with the flash sheet ([`flash.html`](./flash.html)) the night before a test.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq, \pm, \times. -->

---

## 🔵 SI base quantities (seven)

| Quantity | Unit (symbol) | Dimension |
|---|---|---|
| Length | metre (m) | $[\text{L}]$ |
| Mass | kilogram (kg) | $[\text{M}]$ |
| Time | second (s) | $[\text{T}]$ |
| Electric current | ampere (A) | $[\text{A}]$ |
| Temperature | kelvin (K) | $[\text{K}]$ |
| Amount of substance | mole (mol) | $[\text{N}]$ |
| Luminous intensity | candela (cd) | $[\text{J}]$ |

> **Mnemonic:** "Lil Me Time I Took Some Coffee."

---

## 🟢 Key dimensional formulae

| Quantity | Formula |
|---|---|
| Velocity / Acceleration | $[\text{LT}^{-1}]$ / $[\text{LT}^{-2}]$ |
| Force | $[\text{MLT}^{-2}]$ |
| Work / Energy | $[\text{ML}^2\text{T}^{-2}]$ |
| Power | $[\text{ML}^2\text{T}^{-3}]$ |
| Pressure / Stress | $[\text{ML}^{-1}\text{T}^{-2}]$ |
| Momentum / Impulse | $[\text{MLT}^{-1}]$ |
| $G$ | $[\text{M}^{-1}\text{L}^3\text{T}^{-2}]$ |
| $h$ (Planck) | $[\text{ML}^2\text{T}^{-1}]$ |
| Viscosity | $[\text{ML}^{-1}\text{T}^{-1}]$ |
| Surface tension | $[\text{MT}^{-2}]$ |

---

## 🟡 Conversion & dimensional method

$$n_1 u_1 = n_2 u_2, \qquad n_2 = n_1\left(\frac{\text{M}_1}{\text{M}_2}\right)^a\left(\frac{\text{L}_1}{\text{L}_2}\right)^b\left(\frac{\text{T}_1}{\text{T}_2}\right)^c$$

**Power-law method:** $Q = k\,a^x b^y c^z$ → equate powers of M, L, T → solve for $x, y, z$.

---

## 🟣 Significant figures

- Non-zero digits: significant. Zeros between them: significant.
- Leading zeros: **not** significant. Trailing zeros after decimal: significant.
- **×, ÷:** result keeps **fewest significant figures**.
- **+, −:** result keeps **fewest decimal places**.
- Round once, at the end; $\ge 5$ rounds up.

---

## 🔴 Errors

| Error | Formula |
|---|---|
| Absolute | $\Delta x = \lvert x_m - \bar x\rvert$ |
| Mean absolute | $\overline{\Delta x} = \tfrac1n\sum\lvert\Delta x_i\rvert$ |
| Relative | $\overline{\Delta x}/\bar x$ |
| Percentage | $(\overline{\Delta x}/\bar x)\times100\%$ |

**Propagation:**

| Operation | Error rule |
|---|---|
| $Z = A \pm B$ | $\Delta Z = \Delta A + \Delta B$ |
| $Z = AB$ or $A/B$ | $\tfrac{\Delta Z}{Z} = \tfrac{\Delta A}{A} + \tfrac{\Delta B}{B}$ |
| $Z = A^n$ | $\tfrac{\Delta Z}{Z} = \lvert n\rvert\tfrac{\Delta A}{A}$ |
| $Z = \tfrac{A^pB^q}{C^r}$ | $\tfrac{\Delta Z}{Z} = p\tfrac{\Delta A}{A} + q\tfrac{\Delta B}{B} + r\tfrac{\Delta C}{C}$ |

---

## ⚫ Other essentials

- **Scientific notation:** $N \times 10^n$, $1 \le N < 10$; **order of magnitude** = $n$ (round $N$ up if $\ge 3.16$).
- **Dimensional-analysis limits:** no dimensionless constants, no trig/exp/log, no multi-term (sum) laws.
- **Precision** = repeatability (random error, least count); **accuracy** = closeness to truth (systematic error).
- Report as $\bar x \pm \Delta x$.

---

## 🎯 Exam cues

> [!TIP]
> - **"Find the dimensional formula"** → start from a defining equation.
> - **"Is this equation correct?"** → check homogeneity (all terms same dimensions).
> - **"Derive the relation"** → power-law method, equate M/L/T powers.
> - **"Max % error"** → add relative errors × exponent magnitudes.
> - **"How many significant figures?"** → leading zeros out, trailing-after-decimal in.
> - **Convert units** → $n_2 = n_1\prod(\text{unit ratio})^{\text{power}}$.

---

📄 **Google Drive source:** [`notes/scans/`](./notes/scans/) — three formula/revision sheets
(`Units_And_Measurements.jpg`, `Units_And_Dimensions_Formula.jpg`, `Units_And_Dimensions_50Points.jpg`) and the
full notes PDF (`class_11_phy_ch01_units-and-measurements.pdf`).

**Back to:** [Concepts](./01-concepts.md) · [Flash sheet](./flash.html)
