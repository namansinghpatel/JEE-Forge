# Chemical Equilibrium — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**.
> Every problem marks the **❓ Question** and the **✅ Answer** clearly. For Medium and
> Advanced, a **🧭 Strategy** block explains *how to think about it in the exam* before the
> step-by-step working — so you learn the method, not just the number.

<!-- RENDERING: inside math use \cdot (not ·), \rightleftharpoons for equilibrium, \Delta n. R = 0.0821 L atm/mol/K throughout unless stated. -->

---

## 📑 Index

- [Basic (B1–B10)](#basic) — expressions, Δn, simple $K$, direction, units
- [Medium (M1–M15)](#medium) — ICE tables, $K_p$–$K_c$, degree of dissociation, Le Chatelier
- [Advanced (A1–A10)](#advanced) — quadratics, vapour density, pressure effects, combined constants
- [⭐ JEE Questions by Me](#jee-questions-by-me) — your own problems, solved

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** Write the equilibrium-constant expression $K_c$ for
> $$\text{N}_2(g) + 3\text{H}_2(g) \rightleftharpoons 2\text{NH}_3(g)$$

**✅ Answer.** Products over reactants, each to its coefficient:
$$K_c = \frac{[\text{NH}_3]^2}{[\text{N}_2]\,[\text{H}_2]^3}$$

---

<a id="b2"></a>
### B2

> ❓ **Question.** For the same ammonia synthesis, find $\Delta n$ and write the $K_p$–$K_c$ relation.

**✅ Answer.** $\Delta n = (\text{gas products}) - (\text{gas reactants}) = 2 - (1+3) = -2$.
$$K_p = K_c\,(RT)^{\Delta n} = K_c\,(RT)^{-2} = \frac{K_c}{(RT)^2}$$

---

<a id="b3"></a>
### B3

> ❓ **Question.** For $\text{H}_2 + \text{I}_2 \rightleftharpoons 2\text{HI}$ the equilibrium concentrations are
> $[\text{H}_2] = 0.2$, $[\text{I}_2] = 0.2$, $[\text{HI}] = 1.0$ mol/L. Find $K_c$.

**✅ Answer.**
$$K_c = \frac{[\text{HI}]^2}{[\text{H}_2][\text{I}_2]} = \frac{(1.0)^2}{(0.2)(0.2)} = \frac{1}{0.04} = \boxed{25}$$

---

<a id="b4"></a>
### B4

> ❓ **Question.** The forward reaction has $K = 4$. What is $K$ for the reverse reaction?

**✅ Answer.** Reversing inverts the constant: $K' = \dfrac{1}{K} = \dfrac{1}{4} = \boxed{0.25}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** For which of these is $K_p = K_c$?
> (a) $\text{N}_2 + 3\text{H}_2 \rightleftharpoons 2\text{NH}_3$  (b) $\text{H}_2 + \text{I}_2 \rightleftharpoons 2\text{HI}$  (c) $\text{PCl}_5 \rightleftharpoons \text{PCl}_3 + \text{Cl}_2$

**✅ Answer.** $K_p = K_c$ only when $\Delta n = 0$. (a) $\Delta n=-2$, (b) $\Delta n = 2-2 = 0$ ✓, (c) $\Delta n = +1$. So **(b)**.

---

<a id="b6"></a>
### B6

> ❓ **Question.** State the units of $K_c$ for $\text{PCl}_5 \rightleftharpoons \text{PCl}_3 + \text{Cl}_2$.

**✅ Answer.** $\Delta n = +1$, so units are $(\text{mol/L})^{1} = \boxed{\text{mol L}^{-1}}$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** A reaction has $K = 5$. At a given instant $Q = 2$. Which way does it shift?

**✅ Answer.** $Q < K$, so there are too few products → the reaction shifts **forward (→)**.

---

<a id="b8"></a>
### B8

> ❓ **Question.** Write $K_c$ for the heterogeneous equilibrium
> $\text{CaCO}_3(s) \rightleftharpoons \text{CaO}(s) + \text{CO}_2(g)$.

**✅ Answer.** Pure solids are omitted:
$$K_c = [\text{CO}_2]$$

---

<a id="b9"></a>
### B9

> ❓ **Question.** Find $\Delta n$ for $2\text{SO}_2(g) + \text{O}_2(g) \rightleftharpoons 2\text{SO}_3(g)$.

**✅ Answer.** $\Delta n = 2 - (2+1) = \boxed{-1}$.

---

<a id="b10"></a>
### B10

> ❓ **Question.** For $A \rightleftharpoons B$, $K = 9$. What is $K$ for $2A \rightleftharpoons 2B$?

**✅ Answer.** Multiplying coefficients by $n$ raises $K$ to the power $n$: $K' = K^2 = 9^2 = \boxed{81}$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** 1 mol $\text{H}_2$ and 1 mol $\text{I}_2$ are placed in a 1 L flask. At equilibrium 0.8 mol of $\text{H}_2$ has reacted. Find $K_c$ for $\text{H}_2 + \text{I}_2 \rightleftharpoons 2\text{HI}$.

> [!TIP]
> 🧭 **Strategy.** Build an **ICE table** in moles. "0.8 mol $\text{H}_2$ reacted" is your change $x$. Because the coefficient of HI is 2, HI formed $= 2x$. Volume is 1 L, so moles *are* concentrations — no extra conversion.

**Steps.**
1. ICE (mol, in 1 L so = mol/L):

| | $\text{H}_2$ | $\text{I}_2$ | $\text{HI}$ |
|---|---|---|---|
| Initial | 1 | 1 | 0 |
| Change | $-0.8$ | $-0.8$ | $+1.6$ |
| Eqm | 0.2 | 0.2 | 1.6 |

2. Substitute:
$$K_c = \frac{(1.6)^2}{(0.2)(0.2)} = \frac{2.56}{0.04}$$

**✅ Answer.** $K_c = \boxed{64}$.

---

<a id="m2"></a>
### M2

> ❓ **Question.** For $\text{N}_2\text{O}_4 \rightleftharpoons 2\text{NO}_2$, $K_c = 0.5\ \text{mol/L}$ at 300 K. Find $K_p$.

> [!TIP]
> 🧭 **Strategy.** Use $K_p = K_c(RT)^{\Delta n}$. Get $\Delta n$ from the equation ($2-1 = +1$), then plug in $R = 0.0821$ and $T = 300$. Match $R$ to atm because the answer will be in atm.

**Steps.**
1. $\Delta n = 2 - 1 = +1$.
2. $K_p = K_c(RT)^1 = 0.5 \times (0.0821 \times 300) = 0.5 \times 24.63$.

**✅ Answer.** $K_p = \boxed{12.3\ \text{atm}}$ (approx).

---

<a id="m3"></a>
### M3

> ❓ **Question.** For $\text{PCl}_5 \rightleftharpoons \text{PCl}_3 + \text{Cl}_2$, the degree of dissociation is $\alpha = 0.2$ at a total pressure of 2 atm. Find $K_p$.

> [!TIP]
> 🧭 **Strategy.** This is the standard "$A \rightleftharpoons B + C$ at pressure $P$" result. Memorise $K_p = \dfrac{\alpha^2}{1-\alpha^2}P$. Just substitute $\alpha$ and $P$ — no ICE table needed once you trust the formula (its derivation is in Concepts §6).

**Steps.**
$$K_p = \frac{\alpha^2}{1-\alpha^2}P = \frac{(0.2)^2}{1-(0.2)^2}\times 2 = \frac{0.04}{0.96}\times 2 = \frac{0.08}{0.96}$$

**✅ Answer.** $K_p \approx \boxed{0.083\ \text{atm}}$.

---

<a id="m4"></a>
### M4

> ❓ **Question.** For $A \rightleftharpoons B$, $K_c = 10$. Currently $[A] = 2$, $[B] = 5$ mol/L. Is the mixture at equilibrium? If not, which way does it go?

> [!TIP]
> 🧭 **Strategy.** Compute $Q$ with the *current* concentrations (same formula as $K$) and compare. Don't assume it's at equilibrium just because numbers are given.

**Steps.**
$$Q = \frac{[B]}{[A]} = \frac{5}{2} = 2.5$$
$Q = 2.5 < K = 10$.

**✅ Answer.** Not at equilibrium; $Q < K$ → shifts **forward** to make more $B$.

---

<a id="m5"></a>
### M5

> ❓ **Question.** For $2\text{SO}_2 + \text{O}_2 \rightleftharpoons 2\text{SO}_3$, $K_c = 100$. Find $K_c$ for $2\text{SO}_3 \rightleftharpoons 2\text{SO}_2 + \text{O}_2$.

> [!TIP]
> 🧭 **Strategy.** The target is the exact **reverse** of the given reaction — don't recompute, just invert.

**Steps.** $K' = \dfrac{1}{K} = \dfrac{1}{100}$.

**✅ Answer.** $K_c' = \boxed{0.01}$.

---

<a id="m6"></a>
### M6

> ❓ **Question.** For $A \rightleftharpoons B$, $K_c = 4$. Start with $[A] = 1$ mol/L, $[B] = 0$. Find equilibrium concentrations.

> [!TIP]
> 🧭 **Strategy.** One unknown $x$ = amount of $A$ converted. Write both species in terms of $x$, substitute into $K_c$, solve the simple linear equation (no quadratic here because both coefficients are 1 and $K$ is just a ratio).

**Steps.**
1. Eqm: $[A] = 1-x$, $[B] = x$.
2. $K_c = \dfrac{x}{1-x} = 4 \Rightarrow x = 4(1-x) = 4 - 4x \Rightarrow 5x = 4 \Rightarrow x = 0.8$.

**✅ Answer.** $[A] = 0.2$ mol/L, $[B] = 0.8$ mol/L.

---

<a id="m7"></a>
### M7

> ❓ **Question.** For $\text{N}_2 + 3\text{H}_2 \rightleftharpoons 2\text{NH}_3$ ($\Delta H < 0$, exothermic), state how (i) increasing pressure and (ii) lowering temperature each affect the yield of $\text{NH}_3$.

> [!TIP]
> 🧭 **Strategy.** Apply Le Chatelier term by term. For pressure, count gas moles on each side. For temperature on an exothermic reaction, treat heat as a *product*.

**Steps.**
- Gas moles: 4 (left) → 2 (right). Increasing pressure favours the **fewer-moles** side = products → **more $\text{NH}_3$**.
- Exothermic: heat is a product. Lowering $T$ removes heat → shifts **forward** → **more $\text{NH}_3$**.

**✅ Answer.** Both high pressure and low temperature increase the $\text{NH}_3$ yield. (This is exactly the compromise the Haber process balances — low $T$ helps yield but slows the rate, so a moderate $T$ with a catalyst is used.)

---

<a id="m8"></a>
### M8

> ❓ **Question.** 1 mol $\text{N}_2\text{O}_4$ is taken at a total pressure of 1 atm and dissociates 20% ($\alpha = 0.2$) as $\text{N}_2\text{O}_4 \rightleftharpoons 2\text{NO}_2$. Find $K_p$.

> [!TIP]
> 🧭 **Strategy.** This is the $A \rightleftharpoons 2B$ case — note it differs from PCl₅ ($A\to B+C$) because the mole change is different. Safest route: write mole fractions at equilibrium, convert to partial pressures via $p_i = x_i P$, then substitute. Or use the ready formula $K_p = \dfrac{4\alpha^2}{1-\alpha^2}P$.

**Steps.**
1. Moles at eqm: $\text{N}_2\text{O}_4 = 1-\alpha = 0.8$, $\text{NO}_2 = 2\alpha = 0.4$. Total $= 1+\alpha = 1.2$.
2. Partial pressures: $p_{\text{NO}_2} = \frac{0.4}{1.2}(1) = 0.333$, $p_{\text{N}_2\text{O}_4} = \frac{0.8}{1.2}(1) = 0.667$ atm.
3. $K_p = \dfrac{(p_{\text{NO}_2})^2}{p_{\text{N}_2\text{O}_4}} = \dfrac{(0.333)^2}{0.667} = \dfrac{0.111}{0.667}$.

**✅ Answer.** $K_p \approx \boxed{0.167\ \text{atm}}$. (Check with formula: $\frac{4(0.04)}{0.96}\times 1 = \frac{0.16}{0.96} = 0.167$ ✓.)

---

<a id="m9"></a>
### M9

> ❓ **Question.** At equilibrium a 2 L vessel holds 1 mol $\text{N}_2$, 3 mol $\text{H}_2$ and 2 mol $\text{NH}_3$. Find $K_c$ for $\text{N}_2 + 3\text{H}_2 \rightleftharpoons 2\text{NH}_3$.

> [!TIP]
> 🧭 **Strategy.** The vessel is **not** 1 L, so you must convert moles → concentrations by dividing by $V = 2$ *before* substituting. Forgetting this is the most common slip.

**Steps.**
1. Concentrations: $[\text{N}_2] = 0.5$, $[\text{H}_2] = 1.5$, $[\text{NH}_3] = 1.0$ mol/L.
2. $K_c = \dfrac{(1.0)^2}{(0.5)(1.5)^3} = \dfrac{1}{0.5 \times 3.375} = \dfrac{1}{1.6875}$.

**✅ Answer.** $K_c \approx \boxed{0.59\ (\text{mol/L})^{-2}}$.

---

<a id="m10"></a>
### M10

> ❓ **Question.** For $\text{PCl}_5 \rightleftharpoons \text{PCl}_3 + \text{Cl}_2$, $K_c = 4\ \text{mol/L}$ at 500 K. Find $K_p$.

> [!TIP]
> 🧭 **Strategy.** $K_p = K_c(RT)^{\Delta n}$; $\Delta n = +1$ so it's a single factor of $RT$.

**Steps.** $K_p = 4 \times (0.0821 \times 500) = 4 \times 41.05$.

**✅ Answer.** $K_p \approx \boxed{164\ \text{atm}}$.

---

<a id="m11"></a>
### M11

> ❓ **Question.** Given $A \rightleftharpoons B$ ($K_1 = 2$) and $B \rightleftharpoons C$ ($K_2 = 3$), find $K$ for $A \rightleftharpoons C$.

> [!TIP]
> 🧭 **Strategy.** Adding reactions **multiplies** their constants. $A\to C$ is the sum of the two steps.

**Steps.** $K = K_1 \times K_2 = 2 \times 3$.

**✅ Answer.** $K = \boxed{6}$.

---

<a id="m12"></a>
### M12

> ❓ **Question.** Explain why adding an inert gas (e.g. argon) **at constant volume** does not shift the equilibrium $\text{PCl}_5 \rightleftharpoons \text{PCl}_3 + \text{Cl}_2$.

> [!TIP]
> 🧭 **Strategy.** The system responds to **partial pressures / concentrations**, not total pressure. Ask: did any reacting species' partial pressure change?

**✅ Answer.** At constant volume, the moles and volume of each reacting gas are unchanged, so each **partial pressure** (and each concentration) is unchanged. $Q$ therefore equals $K$ still → **no shift**. The total pressure rises, but that rise is carried entirely by the inert gas. (Contrast: at constant *pressure*, adding inert gas expands the volume, lowering every partial pressure → shifts toward **more moles**.)

---

<a id="m13"></a>
### M13

> ❓ **Question.** For $\text{N}_2\text{O}_4 \rightleftharpoons 2\text{NO}_2$ at total pressure 1 atm, $K_p = 0.16$ atm. Find the degree of dissociation $\alpha$.

> [!TIP]
> 🧭 **Strategy.** Use the $A\rightleftharpoons 2B$ formula $K_p = \dfrac{4\alpha^2}{1-\alpha^2}P$ and solve for $\alpha$. It rearranges to a simple equation in $\alpha^2$.

**Steps.**
$$0.16 = \frac{4\alpha^2}{1-\alpha^2}(1) \Rightarrow 0.16(1-\alpha^2) = 4\alpha^2 \Rightarrow 0.16 = 4.16\,\alpha^2 \Rightarrow \alpha^2 = 0.0385$$

**✅ Answer.** $\alpha \approx \boxed{0.196}$ (about 20% dissociated).

---

<a id="m14"></a>
### M14

> ❓ **Question.** For $\text{N}_2 + 3\text{H}_2 \rightleftharpoons 2\text{NH}_3$, $K_p = 0.5$. At one instant the partial pressures are $p_{\text{N}_2} = p_{\text{H}_2} = p_{\text{NH}_3} = 1$ atm. Which way does the reaction proceed?

> [!TIP]
> 🧭 **Strategy.** Form $Q_p$ with current partial pressures and compare to $K_p$.

**Steps.**
$$Q_p = \frac{(p_{\text{NH}_3})^2}{p_{\text{N}_2}(p_{\text{H}_2})^3} = \frac{1^2}{1\cdot 1^3} = 1$$
$Q_p = 1 > K_p = 0.5$.

**✅ Answer.** $Q > K$ → too many products → shifts **backward (←)**, decomposing $\text{NH}_3$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** The vapour density of $\text{PCl}_5$ vapour at equilibrium is found to be $d$, while its normal (undissociated) vapour density is $D$. If $D = 100$ and $d = 80$, find the degree of dissociation (dissociation gives 2 moles from 1, so $n = 2$).

> [!TIP]
> 🧭 **Strategy.** Dissociation increases the number of particles, which *lowers* the observed vapour density. The link is $\alpha = \dfrac{D - d}{(n-1)\,d}$. Just plug in; $n-1 = 1$ here.

**Steps.**
$$\alpha = \frac{D-d}{(n-1)d} = \frac{100-80}{(2-1)\times 80} = \frac{20}{80}$$

**✅ Answer.** $\alpha = \boxed{0.25}$ (25% dissociated).

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** $\text{H}_2 + \text{I}_2 \rightleftharpoons 2\text{HI}$, $K_c = 50$. Start with 1 mol $\text{H}_2$ and 1 mol $\text{I}_2$ in a 1 L vessel. Find all equilibrium concentrations.

> [!TIP]
> 🧭 **Strategy.** ICE with unknown $x$ = mol of $\text{H}_2$ consumed. Here the equation *would* be quadratic, but because both sides are symmetric you can take the **square root of both sides** to avoid the quadratic formula entirely — a classic exam shortcut whenever $K_c$ sits over a perfect square.

**Steps.**
1. Eqm: $[\text{H}_2] = [\text{I}_2] = 1-x$, $[\text{HI}] = 2x$.
2. $K_c = \dfrac{(2x)^2}{(1-x)^2} = 50$. Take $\sqrt{\ }$: $\dfrac{2x}{1-x} = \sqrt{50} = 7.07$.
3. $2x = 7.07 - 7.07x \Rightarrow 9.07x = 7.07 \Rightarrow x = 0.779$.

**✅ Answer.** $[\text{H}_2] = [\text{I}_2] = 0.221$ mol/L, $[\text{HI}] = 1.558$ mol/L.

---

<a id="a2"></a>
### A2

> ❓ **Question.** $\text{PCl}_5 \rightleftharpoons \text{PCl}_3 + \text{Cl}_2$ at total pressure 1 atm has $K_p = 1.78$ atm. Find $\alpha$.

> [!TIP]
> 🧭 **Strategy.** Use $K_p = \dfrac{\alpha^2}{1-\alpha^2}P$ and solve for $\alpha^2$. Watch that $\alpha$ comes out large here (strongly dissociated) — a good reality check that $\alpha < 1$ still holds.

**Steps.**
$$1.78 = \frac{\alpha^2}{1-\alpha^2}(1) \Rightarrow \alpha^2 = 1.78(1-\alpha^2) \Rightarrow 2.78\,\alpha^2 = 1.78 \Rightarrow \alpha^2 = 0.640$$

**✅ Answer.** $\alpha = \boxed{0.80}$ (80% dissociated).

---

<a id="a3"></a>
### A3

> ❓ **Question.** For $\text{PCl}_5 \rightleftharpoons \text{PCl}_3 + \text{Cl}_2$, $K_p = 0.3$ atm (fixed by temperature). Compute $\alpha$ at $P = 1$ atm and at $P = 0.5$ atm, and comment.

> [!TIP]
> 🧭 **Strategy.** $K_p$ is constant (temperature fixed); only $P$ changes. Solve $K_p = \dfrac{\alpha^2}{1-\alpha^2}P$ for $\alpha$ twice. This *proves numerically* the Le Chatelier statement "lower pressure → more dissociation."

**Steps.**
- $P = 1$: $0.3 = \dfrac{\alpha^2}{1-\alpha^2} \Rightarrow 1.3\alpha^2 = 0.3 \Rightarrow \alpha^2 = 0.2308 \Rightarrow \alpha = 0.48$.
- $P = 0.5$: $0.3 = \dfrac{0.5\,\alpha^2}{1-\alpha^2} \Rightarrow 0.6 = \dfrac{\alpha^2}{1-\alpha^2} \Rightarrow 1.6\alpha^2 = 0.6 \Rightarrow \alpha^2 = 0.375 \Rightarrow \alpha = 0.61$.

**✅ Answer.** $\alpha$ rises from **0.48 → 0.61** when pressure is halved. Lower pressure favours the side with more gas moles (dissociation), exactly as Le Chatelier predicts.

---

<a id="a4"></a>
### A4

> ❓ **Question.** For $2\text{NH}_3 \rightleftharpoons \text{N}_2 + 3\text{H}_2$ at 400 K, $K_p = 16.4\ \text{atm}^2$. Find $K_c$.

> [!TIP]
> 🧭 **Strategy.** Rearrange $K_p = K_c(RT)^{\Delta n}$ to $K_c = \dfrac{K_p}{(RT)^{\Delta n}}$. Here $\Delta n = (1+3)-2 = +2$, so divide by $(RT)^2$. Keep units straight: $K_c$ will be in $(\text{mol/L})^2$.

**Steps.**
1. $RT = 0.0821 \times 400 = 32.84$; $(RT)^2 = 1078$.
2. $K_c = \dfrac{16.4}{1078}$.

**✅ Answer.** $K_c \approx \boxed{0.0152\ (\text{mol/L})^2}$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** $\text{N}_2\text{O}_4 \rightleftharpoons 2\text{NO}_2$, $K_c = 0.21\ \text{mol/L}$ at 100 °C. Starting from $[\text{N}_2\text{O}_4] = 0.1$ M (no $\text{NO}_2$), find the equilibrium $[\text{NO}_2]$.

> [!TIP]
> 🧭 **Strategy.** ICE with $x$ = mol/L of $\text{N}_2\text{O}_4$ that reacts; $[\text{NO}_2] = 2x$. The algebra gives a genuine **quadratic** $4x^2 + K_c x - 0.1K_c = 0$ — use the quadratic formula and keep only the positive root with $x < 0.1$.

**Steps.**
1. Eqm: $[\text{N}_2\text{O}_4] = 0.1 - x$, $[\text{NO}_2] = 2x$.
2. $K_c = \dfrac{(2x)^2}{0.1-x} = 0.21 \Rightarrow 4x^2 = 0.21(0.1-x) \Rightarrow 4x^2 + 0.21x - 0.021 = 0$.
3. $x = \dfrac{-0.21 + \sqrt{0.21^2 + 4\cdot4\cdot0.021}}{2\cdot4} = \dfrac{-0.21 + \sqrt{0.0441 + 0.336}}{8} = \dfrac{-0.21 + 0.6165}{8} = 0.0508$.

**✅ Answer.** $[\text{NO}_2] = 2x = \boxed{0.102\ \text{M}}$ (and $[\text{N}_2\text{O}_4] = 0.049$ M).

---

<a id="a6"></a>
### A6

> ❓ **Question.** $\text{PCl}_5$ has normal vapour density $D = 104.25$. At equilibrium the observed vapour density is $d = 62$. Find $\alpha$, then $K_p$ at total pressure 1 atm.

> [!TIP]
> 🧭 **Strategy.** Two linked steps: (1) vapour density → $\alpha$ via $\alpha = \dfrac{D-d}{(n-1)d}$ with $n = 2$; (2) feed that $\alpha$ into $K_p = \dfrac{\alpha^2}{1-\alpha^2}P$. This "VD then $K_p$" chain is a very common Advanced pattern.

**Steps.**
1. $\alpha = \dfrac{104.25 - 62}{(2-1)\times 62} = \dfrac{42.25}{62} = 0.681$.
2. $K_p = \dfrac{(0.681)^2}{1-(0.681)^2}(1) = \dfrac{0.464}{1-0.464} = \dfrac{0.464}{0.536}$.

**✅ Answer.** $\alpha = 0.68$ and $K_p \approx \boxed{0.87\ \text{atm}}$.

---

<a id="a7"></a>
### A7

> ❓ **Question.** The equilibrium $\text{N}_2 + 3\text{H}_2 \rightleftharpoons 2\text{NH}_3$ is at balance. The container volume is suddenly **doubled** at constant temperature. Predict, with reasoning via $Q$, the direction of the shift.

> [!TIP]
> 🧭 **Strategy.** Doubling volume halves every concentration. Rather than memorise a rule, plug "halved concentrations" into $Q$ and see whether $Q$ rose above or fell below $K$ — the sign of the mismatch gives the direction. This method never fails even when the mole-count rule feels ambiguous.

**Steps.**
1. Let equilibrium concentrations be $n, h, a$ for $\text{N}_2, \text{H}_2, \text{NH}_3$; then $K_c = \dfrac{a^2}{n h^3}$.
2. After doubling $V$, each concentration halves: $Q = \dfrac{(a/2)^2}{(n/2)(h/2)^3} = \dfrac{a^2/4}{n h^3/16} = 4\cdot\dfrac{a^2}{n h^3} = 4K_c$.
3. $Q = 4K > K$ → too many products relatively → shifts **backward**.

**✅ Answer.** The equilibrium shifts **backward (toward $\text{N}_2 + \text{H}_2$)** — i.e. toward the side with more gas moles, as expected when pressure drops. Yield of $\text{NH}_3$ falls.

---

<a id="a8"></a>
### A8

> ❓ **Question.** Given $2\text{SO}_2 + \text{O}_2 \rightleftharpoons 2\text{SO}_3$ with $K_c = 100$, find $K_c$ for $\text{SO}_2 + \tfrac{1}{2}\text{O}_2 \rightleftharpoons \text{SO}_3$.

> [!TIP]
> 🧭 **Strategy.** The target is the given reaction with **all coefficients halved**. Dividing coefficients by $n$ raises $K$ to the power $1/n$. Here $n = 2$, so take the square root.

**Steps.** $K' = K^{1/2} = \sqrt{100}$.

**✅ Answer.** $K_c' = \boxed{10}$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** For $\text{CaCO}_3(s) \rightleftharpoons \text{CaO}(s) + \text{CO}_2(g)$ the equilibrium ("decomposition") pressure of $\text{CO}_2$ is 1.16 atm at 1000 K. Find $K_p$ and $K_c$.

> [!TIP]
> 🧭 **Strategy.** Heterogeneous: only $\text{CO}_2$ appears, so $K_p = p_{\text{CO}_2}$ directly. Then convert with $K_p = K_c(RT)^{\Delta n}$, where $\Delta n = +1$ (only the one gas counts — solids are excluded from $\Delta n$).

**Steps.**
1. $K_p = p_{\text{CO}_2} = 1.16$ atm.
2. $K_c = \dfrac{K_p}{(RT)^{1}} = \dfrac{1.16}{0.0821 \times 1000} = \dfrac{1.16}{82.1}$.

**✅ Answer.** $K_p = 1.16$ atm and $K_c \approx \boxed{0.0141\ \text{mol/L}}$.

---

<a id="a10"></a>
### A10

> ❓ **Question.** 2 mol of HI is placed in a 1 L flask and dissociates as $2\text{HI} \rightleftharpoons \text{H}_2 + \text{I}_2$ with $K_c = \tfrac{1}{64}$. Find the equilibrium concentrations.

> [!TIP]
> 🧭 **Strategy.** ICE with $2x$ = mol/L of HI that dissociates (coefficient 2). The expression becomes a perfect square again → take the square root to avoid the quadratic. Note $K_c = 1/64$ is just the reverse of B3/M1's $K_c = 64$ — a nice consistency check.

**Steps.**
1. Eqm: $[\text{HI}] = 2-2x$, $[\text{H}_2] = [\text{I}_2] = x$.
2. $K_c = \dfrac{x^2}{(2-2x)^2} = \dfrac{1}{64}$. Take $\sqrt{\ }$: $\dfrac{x}{2-2x} = \dfrac{1}{8}$.
3. $8x = 2 - 2x \Rightarrow 10x = 2 \Rightarrow x = 0.2$.

**✅ Answer.** $[\text{H}_2] = [\text{I}_2] = 0.2$ mol/L, $[\text{HI}] = 1.6$ mol/L.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs,
> test series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style as
> above, and tag each with its difficulty. This keeps your personal problem bank and its
> worked solutions in one place.

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it
> will be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
