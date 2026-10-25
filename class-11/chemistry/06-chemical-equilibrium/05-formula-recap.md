# Chemical Equilibrium — Quick Formula Recap

> Everything you need on one page for last-minute revision. If a formula here feels unfamiliar,
> jump back to [Concepts](./01-concepts.md) or the [Deep Dive](./04-deep-dive.md).

<!-- RENDERING: inside math use \cdot (not ·), \rightleftharpoons for equilibrium, \Delta n. -->

---

## 📑 Index

- [Equilibrium constant](#equilibrium-constant)
- [Kp–Kc relation](#kp-kc-relation)
- [Manipulating K](#manipulating-k)
- [Reaction quotient Q](#reaction-quotient)
- [Degree of dissociation](#degree-of-dissociation)
- [Vapour density](#vapour-density)
- [Le Chatelier at a glance](#le-chatelier)
- [Constants & cheat values](#constants)

---

<a id="equilibrium-constant"></a>
## Equilibrium constant

For $aA + bB \rightleftharpoons cC + dD$:

$$K_c = \frac{[C]^c[D]^d}{[A]^a[B]^b} \qquad K_p = \frac{(p_C)^c(p_D)^d}{(p_A)^a(p_B)^b}$$

- Products on top, each raised to its coefficient.
- Pure solids and pure liquids are **omitted**.
- Units: $(\text{mol/L})^{\Delta n}$ for $K_c$; dimensionless if $\Delta n = 0$.
- $K$ depends on **temperature only**.

---

<a id="kp-kc-relation"></a>
## Kp–Kc relation

$$\boxed{K_p = K_c\,(RT)^{\Delta n}}, \qquad \Delta n = n_{\text{gas prod}} - n_{\text{gas react}}$$

| $\Delta n$ | relation |
|---|---|
| $= 0$ | $K_p = K_c$ |
| $> 0$ | $K_p > K_c$ |
| $< 0$ | $K_p < K_c$ |

Use $R = 0.0821$ L atm mol⁻¹ K⁻¹ (atm) or $0.0831$ L bar mol⁻¹ K⁻¹ (bar).

---

<a id="manipulating-k"></a>
## Manipulating K

| Operation | New $K$ |
|---|---|
| Reverse | $1/K$ |
| Multiply coefficients by $n$ | $K^n$ |
| Divide coefficients by $n$ | $K^{1/n}$ |
| Add reactions | $K_1 \times K_2$ |

---

<a id="reaction-quotient"></a>
## Reaction quotient Q

Same expression as $K$ but with **current** values.

$$Q < K \Rightarrow \text{forward} \quad|\quad Q = K \Rightarrow \text{equilibrium} \quad|\quad Q > K \Rightarrow \text{backward}$$

---

<a id="degree-of-dissociation"></a>
## Degree of dissociation (α)

| Reaction type | $K_p$ in terms of α and total $P$ |
|---|---|
| $A \rightleftharpoons B + C$  (e.g. PCl₅) | $K_p = \dfrac{\alpha^2}{1-\alpha^2}\,P$ |
| $A \rightleftharpoons 2B$  (e.g. N₂O₄) | $K_p = \dfrac{4\alpha^2}{1-\alpha^2}\,P$ |

$\alpha$ = fraction dissociated, $0 \le \alpha \le 1$. Total moles at eqm $= 1 + (\Delta n_{\text{per mole}})\alpha$.

---

<a id="vapour-density"></a>
## Vapour density → α

$$\boxed{\alpha = \frac{D - d}{(n-1)\,d}}$$

$D$ = normal vapour density, $d$ = observed, $n$ = moles of product per mole dissociated.
(For PCl₅ and N₂O₄, $n = 2$, so $\alpha = \dfrac{D-d}{d}$.) PCl₅: $D = 104.25$.

---

<a id="le-chatelier"></a>
## Le Chatelier at a glance

| Stress | Shift |
|---|---|
| ↑ reactant / ↓ product | forward |
| ↑ product / ↓ reactant | backward |
| ↑ pressure (↓ volume) | fewer gas moles |
| ↓ pressure (↑ volume) | more gas moles |
| ↑ temperature | endothermic direction ($K$ changes) |
| ↓ temperature | exothermic direction ($K$ changes) |
| catalyst | no shift (faster only) |
| inert gas, constant $V$ | no shift |
| inert gas, constant $P$ | more gas moles |

> [!IMPORTANT]
> Only **temperature** changes the value of $K$. Everything else moves the position but leaves $K$ fixed.

---

<a id="constants"></a>
## Constants & cheat values

| Quantity | Value |
|---|---|
| $R$ (atm) | $0.0821$ L atm mol⁻¹ K⁻¹ |
| $R$ (bar) | $0.0831$ L bar mol⁻¹ K⁻¹ |
| $R$ (SI) | $8.314$ J mol⁻¹ K⁻¹ |
| $\Delta G^\circ$ ↔ $K$ | $\Delta G^\circ = -RT\ln K$ |
| PCl₅ normal VD | $104.25$ |
| 0 °C | $273.15$ K |

> [!TIP]
> If stuck on any numerical: write the balanced equation → ICE table → convert to conc./pressure
> → substitute. Three steps, every time.

---

**Back to:** [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Practice](./03-practice.md) · [Deep Dive](./04-deep-dive.md)
