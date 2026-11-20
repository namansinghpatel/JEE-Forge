# Thermodynamics — Deep Dive

> The methods that make thermodynamics fast: nailing the sign convention, choosing $\Delta U$ vs $\Delta H$,
> treating thermochemistry as algebra (Hess), the three-way spontaneity test, and the reversible/irreversible
> work distinction. Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \Delta, \to, ^\circ. -->

---

## 📑 Index

1. [The sign convention, pinned down](#1-signs)
2. [ΔU vs ΔH: which, and when](#2-du-dh)
3. [Thermochemistry is algebra](#3-algebra)
4. [The three-way spontaneity test](#4-spontaneity)
5. [ΔG, ΔG° and the equilibrium bridge](#5-dg-k)
6. [Reversible vs irreversible work](#6-work)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-signs"></a>
## 1. The sign convention, pinned down

The first law $\Delta U = q + w$ only works if signs are consistent. In the **IUPAC** convention:
- **$q > 0$:** heat flows **into** the system.
- **$w > 0$:** work done **on** the system (compression).
- So a gas **expanding** does work on the surroundings → $w = -P_{\text{ext}}\Delta V < 0$.

> [!WARNING]
> Many Indian textbooks use the older form $\Delta U = q - W$ where $W$ is work done **by** the system. Both
> are correct if used consistently — but mixing them flips a sign and ruins the answer. Decide which your
> source uses and stick to it; this prompt uses IUPAC ($w = -P_{\text{ext}}\Delta V$).

---

<a id="2-du-dh"></a>
## 2. ΔU vs ΔH: which, and when

- **Constant volume** → no PV work → $q_V = \Delta U$.
- **Constant pressure** → $q_P = \Delta H = \Delta U + \Delta(PV)$.
- For ideal gases, $\Delta(PV) = \Delta n_g RT$, so:
$$\Delta H = \Delta U + \Delta n_g RT.$$

| $\Delta n_g$ | $\Delta H$ vs $\Delta U$ |
|---|---|
| $> 0$ | $\Delta H > \Delta U$ |
| $= 0$ | $\Delta H = \Delta U$ |
| $< 0$ | $\Delta H < \Delta U$ |

> [!TIP]
> Count **only gaseous** moles for $\Delta n_g$ (solids/liquids don't contribute). Bomb-calorimeter data give
> $\Delta U$ (constant volume); convert to $\Delta H$ with $\Delta n_g RT$ when the question wants constant-pressure heat.

---

<a id="3-algebra"></a>
## 3. Thermochemistry is algebra

Because $H$ is a state function, thermochemical equations behave like algebraic equations:
- **Reverse** a reaction → flip the sign of $\Delta H$.
- **Multiply** by $n$ → multiply $\Delta H$ by $n$.
- **Add** reactions → add their $\Delta H$ values (Hess's law).

Three routes to a reaction enthalpy:
$$\Delta_r H = \sum\Delta_f H(\text{prod}) - \sum\Delta_f H(\text{react}) \quad(\text{formation})$$
$$\Delta_r H = \sum BE(\text{broken}) - \sum BE(\text{formed}) \quad(\text{bond enthalpy, gas phase})$$
$$\Delta_r H = \text{sum of a Hess cycle} \quad(\text{combustion data, Born–Haber})$$

> [!IMPORTANT]
> Mind the **opposite order** in the two main rules: formation enthalpies are **products − reactants**; bond
> enthalpies are **broken − formed**. Swapping these is the single most common thermochemistry error.

---

<a id="4-spontaneity"></a>
## 4. The three-way spontaneity test

$\Delta G = \Delta H - T\Delta S$ compresses the second law into a system-only test:

| $\Delta H$ | $\Delta S$ | Spontaneous? |
|---|---|---|
| $-$ | $+$ | always ($\Delta G < 0$ at all $T$) |
| $+$ | $-$ | never |
| $-$ | $-$ | only **below** $T = \Delta H/\Delta S$ |
| $+$ | $+$ | only **above** $T = \Delta H/\Delta S$ |

> [!TIP]
> For the two "mixed" cases, the crossover temperature is $T = \Delta H/\Delta S$ (the point where $\Delta G =
> 0$). "Enthalpy-favoured, entropy-opposed" reactions ($-,-$) switch off when heated; "entropy-favoured,
> enthalpy-opposed" ($+,+$) switch on when heated (e.g. CaCO₃ decomposition).

---

<a id="5-dg-k"></a>
## 5. ΔG, ΔG° and the equilibrium bridge

- **Standard** Gibbs energy ties to the equilibrium constant: $\Delta G^\circ = -RT\ln K = -2.303\,RT\log K$.
- **Non-standard:** $\Delta G = \Delta G^\circ + RT\ln Q$; at equilibrium $Q = K$ and $\Delta G = 0$.
- This connects to electrochemistry next year: $\Delta G^\circ = -nFE^\circ$.

> [!NOTE]
> Sign logic: $\Delta G^\circ < 0 \Rightarrow \ln K > 0 \Rightarrow K > 1$ (products favoured). $\Delta G$ (not
> $\Delta G^\circ$) is what's zero at equilibrium — $\Delta G^\circ$ is a fixed number for the standard
> reaction, while $\Delta G$ varies with the actual composition through $Q$.

---

<a id="6-work"></a>
## 6. Reversible vs irreversible work

For an **ideal gas** between the same two states:
- **Reversible isothermal:** $w = -nRT\ln(V_2/V_1)$ — the system stays in near-equilibrium, pressure matched at every step, so it does (or absorbs) the **maximum** work.
- **Irreversible (against constant $P_{\text{ext}}$):** $w = -P_{\text{ext}}\Delta V$ — a single step against a lower pressure, so **less** work.

Zero-quantity shortcuts:
- **Isothermal** ideal gas: $\Delta U = 0 \Rightarrow q = -w$.
- **Adiabatic:** $q = 0 \Rightarrow \Delta U = w = nC_V\Delta T$.

> [!IMPORTANT]
> $|w_{\text{reversible}}| > |w_{\text{irreversible}}|$ always (for expansion, reversible gives more work out;
> for compression, reversible needs less work in). Spotting which quantity ($\Delta U$ or $q$) is **zero** —
> isothermal vs adiabatic — turns most of these problems into one line.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **Sign convention:** IUPAC $w = -P_{\text{ext}}\Delta V$; expansion → $w < 0$. Don't mix conventions.
> - **$\Delta n_g$ counts gases only** in $\Delta H = \Delta U + \Delta n_g RT$.
> - **Formation rule = products − reactants; bond rule = broken − formed** (opposite orders).
> - **Element in standard state → $\Delta_f H^\circ = 0$.**
> - **Spontaneity is $\Delta G < 0$** (system test) ⇔ $\Delta S_{\text{universe}} > 0$.
> - **Crossover temperature** $T = \Delta H/\Delta S$ for mixed-sign reactions.
> - **$\Delta G = 0$ at equilibrium / phase transitions** → $\Delta S = \Delta H/T$.
> - **Reversible work is maximum;** isothermal → $\Delta U = 0$, adiabatic → $q = 0$.
> - **Unit care:** keep $\Delta H$ (kJ) and $T\Delta S$ (J → kJ) in the same unit before subtracting.
