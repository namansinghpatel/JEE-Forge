# Chemical Equilibrium — Deep Dive

> Beyond the syllabus basics: *why* the equilibrium constant is what it is, the traps that cost
> marks, and the fast methods that separate a 2-minute solve from a 6-minute one. Read this once
> you are comfortable with [Concepts](./01-concepts.md) and have done a few
> [Solved Numericals](./02-solved-numericals.md).

<!-- RENDERING: inside math use \cdot (not ·), \rightleftharpoons for equilibrium, \Delta n. -->

---

## 📑 Index

1. [Where $K$ really comes from — thermodynamics in one line](#1-where-k-comes-from)
2. [The ICE table, mastered — the one tool for every numerical](#2-ice-table-mastered)
3. [Choosing your variable: α vs x vs partial pressure](#3-choosing-your-variable)
4. [The square-root trick and when a quadratic is unavoidable](#4-square-root-trick)
5. [Pressure, volume and inert gas — the three that get confused](#5-pressure-volume-inert-gas)
6. [Temperature is the only thing that changes K](#6-temperature-changes-k)
7. [Vapour density ↔ degree of dissociation](#7-vapour-density)
8. [Exam traps checklist](#8-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-where-k-comes-from"></a>
## 1. Where K really comes from — thermodynamics in one line

You'll meet this properly in thermodynamics, but it's worth seeing now because it explains *every*
property of $K$ in the Concepts table:
$$\Delta G^\circ = -RT\ln K$$

Read it slowly:
- $K$ depends on $\Delta G^\circ$ and $T$ **only** — not on how much you started with, not on pressure, not on a catalyst. That's *why* $K$ is constant at fixed temperature.
- $\Delta G^\circ$ is fixed once the reaction and temperature are fixed, so $K$ is too.
- Change $T$ and $K$ changes — the direction is set by whether the reaction is exo- or endothermic (via $\Delta G^\circ = \Delta H^\circ - T\Delta S^\circ$). This is the molecular reason behind the "exothermic → $K$ falls as $T$ rises" rule.

> [!NOTE]
> You don't need to *use* this formula for most Class 11 numericals, but keeping it in mind means
> you never have to memorise *why* catalysts and starting amounts don't affect $K$ — they don't
> appear on the right-hand side.

---

<a id="2-ice-table-mastered"></a>
## 2. The ICE table, mastered

Almost every equilibrium numerical is the same three-row table. Master the setup and the algebra
is routine.

**I**nitial → **C**hange → **E**quilibrium, in **moles** (convert to concentration/pressure *after*).

The change row always uses **one unknown** scaled by the coefficients:

$$a\text{A} + b\text{B} \rightleftharpoons c\text{C} + d\text{D}$$

| | A | B | C | D |
|---|---|---|---|---|
| I | $A_0$ | $B_0$ | 0 | 0 |
| C | $-ax$ | $-bx$ | $+cx$ | $+dx$ |
| E | $A_0-ax$ | $B_0-bx$ | $cx$ | $dx$ |

> [!IMPORTANT]
> Three rules that prevent 90% of ICE errors:
> 1. **The change row respects coefficients.** If a coefficient is 2, the change is $2x$, not $x$.
> 2. **Convert to concentration or partial pressure only at the end**, and only if the volume isn't 1 L (or pressure isn't already given).
> 3. **Check the physical range** of your answer: $0 \le x$, and every equilibrium amount must be $\ge 0$. Reject the root that makes a concentration negative.

---

<a id="3-choosing-your-variable"></a>
## 3. Choosing your variable: α vs x vs partial pressure

Three equivalent ways to set up the same problem — pick by what the question gives:

| Question gives… | Use variable | Typical formula |
|---|---|---|
| Moles / concentrations | $x$ (moles reacted) | substitute into $K_c$ |
| "Degree of dissociation" or % dissociated | $\alpha$ | $K_p = \dfrac{\alpha^2}{1-\alpha^2}P$ (for $A\to B+C$) |
| Total pressure + mole ratios | partial pressures $p_i = x_i P$ | substitute into $K_p$ |

> [!TIP]
> For the **two standard dissociations**, learn these closed forms so you skip the ICE table:
> - $A \rightleftharpoons B + C$ (like PCl₅): $\quad K_p = \dfrac{\alpha^2}{1-\alpha^2}P$
> - $A \rightleftharpoons 2B$ (like N₂O₄): $\quad K_p = \dfrac{4\alpha^2}{1-\alpha^2}P$
>
> The factor of 4 in the second comes from the coefficient 2 appearing as $(2\alpha)^2$. Mixing
> these two up is a frequent, avoidable error.

---

<a id="4-square-root-trick"></a>
## 4. The square-root trick and when a quadratic is unavoidable

When the equilibrium expression is a **perfect square over a perfect square**, take the square
root of both sides *before* clearing fractions. This turns a quadratic into a linear equation.

**Works** for $\text{H}_2 + \text{I}_2 \rightleftharpoons 2\text{HI}$ started with equal amounts:
$$\frac{(2x)^2}{(1-x)^2} = K \;\Rightarrow\; \frac{2x}{1-x} = \sqrt{K} \quad\text{(linear!)}$$

**Doesn't work** (genuine quadratic) when the denominator isn't a matching square — e.g.
$\text{N}_2\text{O}_4 \rightleftharpoons 2\text{NO}_2$ with $\dfrac{(2x)^2}{A_0 - x} = K$. Here
$4x^2 + Kx - KA_0 = 0$; use the quadratic formula and keep the root with $0 < x < A_0$.

> [!NOTE]
> **Small-$K$ approximation:** if $K$ is very small (say $< 10^{-3}$) and you're dissociating, $x$
> is tiny, so $A_0 - x \approx A_0$. This kills the quadratic. Always *verify* afterwards that
> $x \ll A_0$ (the "5% rule"): if $x$ is more than ~5% of $A_0$, redo it exactly.

---

<a id="5-pressure-volume-inert-gas"></a>
## 5. Pressure, volume and inert gas — the three that get confused

These three "pressure-like" changes behave differently. Keep them straight:

| Change | What physically happens | Effect on equilibrium |
|---|---|---|
| **↑ Pressure by compression** (↓ volume) | every partial pressure rises | shifts to **fewer gas moles** |
| **↓ Pressure by expansion** (↑ volume) | every partial pressure falls | shifts to **more gas moles** |
| **Inert gas at constant *volume*** | total $P$ rises, but each partial pressure unchanged | **no shift** |
| **Inert gas at constant *pressure*** | volume expands, each partial pressure falls | shifts to **more gas moles** |

> [!WARNING]
> The exam loves the **inert-gas-at-constant-volume → no shift** case. The trick is to remember
> the system reacts to *partial pressures of the reacting species*, which don't change when you
> add argon into a rigid box. The total-pressure gauge goes up, but the reaction can't "feel" it.

The quickest way to settle *any* volume/pressure question is the $Q$ method from
[A7](./02-solved-numericals.md#a7): scale the concentrations, recompute $Q$, compare to $K$. It
never relies on remembering a rule.

---

<a id="6-temperature-changes-k"></a>
## 6. Temperature is the only thing that changes K

Every other disturbance (concentration, pressure, catalyst) shifts the *position* but leaves $K$
untouched. **Temperature changes $K$ itself.** Treat heat as a species:

- **Exothermic** $A + B \rightleftharpoons C + \text{heat}$: raising $T$ adds heat (a "product") → shifts backward → $K$ **decreases**.
- **Endothermic** $A + B + \text{heat} \rightleftharpoons C$: raising $T$ adds heat (a "reactant") → shifts forward → $K$ **increases**.

Quantitatively (van 't Hoff, seen later):
$$\ln\frac{K_2}{K_1} = -\frac{\Delta H^\circ}{R}\left(\frac{1}{T_2} - \frac{1}{T_1}\right)$$

> [!TIP]
> If a question says "$K$ increased when the mixture was heated," you can *immediately* conclude
> the forward reaction is **endothermic** — a free deduction worth marks.

---

<a id="7-vapour-density"></a>
## 7. Vapour density ↔ degree of dissociation

When a gas dissociates into more particles, the average molar mass of the gas *falls*, and since
vapour density $\propto$ molar mass, the **observed vapour density falls** too. This gives an
experimental handle on $\alpha$ without measuring concentrations.

For a dissociation producing $n$ moles from 1:
$$\boxed{\alpha = \frac{D - d}{(n-1)\,d}}$$

where $D$ = normal (theoretical, undissociated) vapour density and $d$ = observed vapour density.

- $\text{PCl}_5 \to \text{PCl}_3 + \text{Cl}_2$: $n = 2$, so $\alpha = \dfrac{D-d}{d}$.
- $\text{N}_2\text{O}_4 \to 2\text{NO}_2$: $n = 2$, same formula.
- $\text{PCl}_5$ fully associated has $M = 208.5$, so $D = 104.25$ — a number worth recognising.

An equivalent molar-mass form: $\alpha = \dfrac{M_{\text{normal}} - M_{\text{obs}}}{(n-1)M_{\text{obs}}}$.

---

<a id="8-exam-traps"></a>
## 8. Exam traps checklist

> [!WARNING]
> Run through these before you write the final answer:
> - **Did you divide moles by volume?** Only skip it if $V = 1$ L.
> - **Pure solids/liquids left out** of both $K$ and $\Delta n$? ($\text{CaCO}_3$, $\text{CaO}$, liquid water in a gas reaction.)
> - **Right dissociation formula?** $\dfrac{\alpha^2}{1-\alpha^2}P$ for $A\to B+C$ vs $\dfrac{4\alpha^2}{1-\alpha^2}P$ for $A\to 2B$.
> - **$R$ matched to the pressure unit?** 0.0821 for atm, 0.0831 for bar.
> - **$\Delta n$ sign right?** products minus reactants; only gases count.
> - **Catalyst / inert-gas-at-constant-V** → no shift, no change to $K$.
> - **Physical root chosen?** $0 \le \alpha \le 1$; no negative concentrations.
> - **Units on $K$** reported as $(\text{mol/L})^{\Delta n}$ (or dimensionless if $\Delta n = 0$)?

---

## 🎯 One strategic takeaway

> Three tools cover the entire chapter: the **ICE table** (for any numerical), the **$Q$ vs $K$
> comparison** (for any "which way / what if" question), and **$K_p = K_c(RT)^{\Delta n}$** (to move
> between pressure and concentration). Temperature is the only lever that moves $K$ itself;
> everything else only moves the position. If you can reach for the right one of these three on
> sight, this chapter becomes fast marks.

---

**Next:** [Quick Formula Recap →](./05-formula-recap.md)
