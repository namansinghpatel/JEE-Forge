# Thermodynamics — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning the first law,
> enthalpy, thermochemistry (Hess, formation, bond enthalpy), entropy, Gibbs energy and reversible work.
> Every problem marks the **❓ Question** and **✅ Answer**; Medium and Advanced carry a **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \Delta, \to, ^\circ. -->

> **Constants:** $R = 8.314\ \mathrm{J\,K^{-1}mol^{-1}} = 0.0821\ \mathrm{L\,atm\,K^{-1}mol^{-1}}$; $1\ \mathrm{L\,atm} = 101.3\ \mathrm{J}$; $2.303\,R = 19.15\ \mathrm{J\,K^{-1}mol^{-1}}$; standard conditions $298\ \mathrm{K}$, $1\ \mathrm{bar}$.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — first law, w = −PΔV, ΔH–ΔU, q = mcΔT, ΔG sign
- [Medium (M1–M15)](#medium) — Hess, formation enthalpy, entropy, ΔG = ΔH − TΔS, crossover T
- [Advanced (A1–A10)](#advanced) — bond enthalpy, ΔG° = −RT ln K, isothermal/adiabatic work, Born–Haber
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** A system absorbs $100\ \mathrm{J}$ of heat and has $40\ \mathrm{J}$ of work done on it. Find $\Delta U$.

**✅ Answer.** $\Delta U = q + w = 100 + 40 = \boxed{140\ \mathrm{J}}$.

---

<a id="b2"></a>
### B2

> ❓ **Question.** A gas expands by $2\ \mathrm{L}$ against a constant external pressure of $3\ \mathrm{atm}$. Find the work done (in L·atm).

**✅ Answer.** $w = -P_{\text{ext}}\Delta V = -3(2) = \boxed{-6\ \mathrm{L\,atm}}$ (work done by the gas).

---

<a id="b3"></a>
### B3

> ❓ **Question.** Convert $-6\ \mathrm{L\,atm}$ of work into joules.

**✅ Answer.** $-6 \times 101.3 = \boxed{-607.8\ \mathrm{J}}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** For a reaction $\Delta U = -50\ \mathrm{kJ}$ and $\Delta n_g = 0$. Find $\Delta H$.

**✅ Answer.** $\Delta H = \Delta U + \Delta n_g RT = -50 + 0 = \boxed{-50\ \mathrm{kJ}}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** Classify: a reaction with $\Delta H = +120\ \mathrm{kJ}$.

**✅ Answer.** $\Delta H > 0$ → **endothermic** (absorbs heat).

---

<a id="b6"></a>
### B6

> ❓ **Question.** Find the heat to raise $200\ \mathrm{g}$ of water by $10\ \mathrm{K}$ (specific heat $4.18\ \mathrm{J\,g^{-1}K^{-1}}$).

**✅ Answer.** $q = mc\Delta T = 200(4.18)(10) = \boxed{8360\ \mathrm{J}}$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** Is a reaction with $\Delta H < 0$ and $\Delta S > 0$ spontaneous at all temperatures?

**✅ Answer.** Yes — $\Delta G = \Delta H - T\Delta S$ is negative at every $T$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** At constant volume, the heat absorbed by a system is $75\ \mathrm{J}$. What is $\Delta U$?

**✅ Answer.** At constant $V$, $q_V = \Delta U = \boxed{75\ \mathrm{J}}$ (no PV work).

---

<a id="b9"></a>
### B9

> ❓ **Question.** What is $\Delta_f H^\circ$ of O₂(g)?

**✅ Answer.** $\boxed{0}$ — it's an element in its standard state.

---

<a id="b10"></a>
### B10

> ❓ **Question.** For an ideal gas in an isothermal process, what is $\Delta U$?

**✅ Answer.** $\Delta U = 0$ (internal energy of an ideal gas depends only on $T$).

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** For the reaction $\text{N}_2(g) + 3\text{H}_2(g) \to 2\text{NH}_3(g)$, $\Delta U = -92.2\ \mathrm{kJ}$ at $298\ \mathrm{K}$. Find $\Delta H$.

> [!TIP]
> 🧭 **Strategy.** $\Delta H = \Delta U + \Delta n_g RT$; $\Delta n_g = 2 - 4 = -2$.

**Steps.** $\Delta H = -92.2 + (-2)(8.314\times10^{-3})(298) = -92.2 - 4.95$.

**✅ Answer.** $\Delta H \approx -97.2\ \mathrm{kJ}$.

---

<a id="m2"></a>
### M2

> ❓ **Question.** Using $\Delta_f H^\circ$: CO₂(g) $= -393.5$, H₂O(l) $= -285.8$, CH₄(g) $= -74.8\ \mathrm{kJ/mol}$, find $\Delta_c H^\circ$ of methane ($\text{CH}_4 + 2\text{O}_2 \to \text{CO}_2 + 2\text{H}_2\text{O}$).

> [!TIP]
> 🧭 **Strategy.** $\Delta_r H = \sum \Delta_f H(\text{products}) - \sum \Delta_f H(\text{reactants})$; O₂ = 0.

**Steps.** $= [(-393.5) + 2(-285.8)] - [(-74.8) + 0] = (-965.1) - (-74.8)$.

**✅ Answer.** $\Delta_c H^\circ = -890.3\ \mathrm{kJ/mol}$.

---

<a id="m3"></a>
### M3

> ❓ **Question.** A gas does $200\ \mathrm{J}$ of work while absorbing $500\ \mathrm{J}$ of heat. Find $\Delta U$ (IUPAC convention).

> [!TIP]
> 🧭 **Strategy.** Work done **by** the gas → $w$ is negative. $\Delta U = q + w$.

**Steps.** $\Delta U = 500 + (-200)$.

**✅ Answer.** $\Delta U = 300\ \mathrm{J}$.

---

<a id="m4"></a>
### M4

> ❓ **Question.** Given: C(s) + O₂ → CO₂, $\Delta H = -393.5$; CO + ½O₂ → CO₂, $\Delta H = -283$. Find $\Delta H$ for C + ½O₂ → CO.

> [!TIP]
> 🧭 **Strategy.** Hess's law: subtract the second from the first.

**Steps.** (C + O₂ → CO₂) − (CO + ½O₂ → CO₂): $\Delta H = -393.5 - (-283) = -110.5$.

**✅ Answer.** $\Delta H = -110.5\ \mathrm{kJ}$.

---

<a id="m5"></a>
### M5

> ❓ **Question.** For a process $\Delta H = +40\ \mathrm{kJ/mol}$ at $300\ \mathrm{K}$. Find $\Delta S_{\text{surroundings}}$.

> [!TIP]
> 🧭 **Strategy.** $\Delta S_{\text{surr}} = -\Delta H_{\text{sys}}/T$.

**Steps.** $\Delta S_{\text{surr}} = -\dfrac{40000}{300}$.

**✅ Answer.** $\Delta S_{\text{surr}} = -133.3\ \mathrm{J\,K^{-1}mol^{-1}}$.

---

<a id="m6"></a>
### M6

> ❓ **Question.** A reaction has $\Delta H = -100\ \mathrm{kJ}$ and $\Delta S = -200\ \mathrm{J/K}$. Find $\Delta G$ at $298\ \mathrm{K}$ and state spontaneity.

> [!TIP]
> 🧭 **Strategy.** $\Delta G = \Delta H - T\Delta S$; keep units consistent (kJ).

**Steps.** $\Delta G = -100 - 298(-0.200) = -100 + 59.6$.

**✅ Answer.** $\Delta G = -40.4\ \mathrm{kJ}$ → **spontaneous** at 298 K.

---

<a id="m7"></a>
### M7

> ❓ **Question.** For the above reaction ($\Delta H = -100\ \mathrm{kJ}$, $\Delta S = -200\ \mathrm{J/K}$), above what temperature does it become non-spontaneous?

> [!TIP]
> 🧭 **Strategy.** Crossover at $\Delta G = 0 \Rightarrow T = \Delta H/\Delta S$.

**Steps.** $T = \dfrac{-100000}{-200} = 500\ \mathrm{K}$.

**✅ Answer.** Above $500\ \mathrm{K}$ it becomes non-spontaneous (both negative → spontaneous only below the crossover).

---

<a id="m8"></a>
### M8

> ❓ **Question.** The enthalpy of neutralisation of a strong acid by a strong base is $-57.1\ \mathrm{kJ/mol}$. How much heat is released when $0.5\ \mathrm{mol}$ of water forms?

> [!TIP]
> 🧭 **Strategy.** Heat $\propto$ moles of water formed.

**Steps.** $0.5 \times 57.1$.

**✅ Answer.** $28.55\ \mathrm{kJ}$ released.

---

<a id="m9"></a>
### M9

> ❓ **Question.** For the reaction $2\text{SO}_2 + \text{O}_2 \to 2\text{SO}_3$, $\Delta n_g = ?$ and how does $\Delta H$ compare with $\Delta U$?

> [!TIP]
> 🧭 **Strategy.** $\Delta n_g = $ gas products − gas reactants; $\Delta H = \Delta U + \Delta n_g RT$.

**Steps.** $\Delta n_g = 2 - 3 = -1$, so $\Delta H = \Delta U - RT < \Delta U$.

**✅ Answer.** $\Delta n_g = -1$; $\Delta H$ is **less** than $\Delta U$ (by $RT$).

---

<a id="m10"></a>
### M10

> ❓ **Question.** A system's entropy increases by $50\ \mathrm{J/K}$ while the surroundings lose $30\ \mathrm{J/K}$. Is the process spontaneous?

> [!TIP]
> 🧭 **Strategy.** $\Delta S_{\text{univ}} = \Delta S_{\text{sys}} + \Delta S_{\text{surr}} > 0$?

**Steps.** $50 + (-30) = +20\ \mathrm{J/K} > 0$.

**✅ Answer.** Yes — $\Delta S_{\text{universe}} = +20\ \mathrm{J/K}$, spontaneous.

---

<a id="m11"></a>
### M11

> ❓ **Question.** Find $\Delta H$ for $\text{C}_2\text{H}_4 + \text{H}_2 \to \text{C}_2\text{H}_6$ given $\Delta_f H^\circ$: C₂H₄ $= +52.3$, C₂H₆ $= -84.7\ \mathrm{kJ/mol}$ (H₂ = 0).

> [!TIP]
> 🧭 **Strategy.** Products − reactants.

**Steps.** $\Delta H = (-84.7) - (52.3 + 0) = -137$.

**✅ Answer.** $\Delta H = -137\ \mathrm{kJ/mol}$.

---

<a id="m12"></a>
### M12

> ❓ **Question.** One mole of an ideal gas is heated at constant pressure from $300$ to $400\ \mathrm{K}$. Find $\Delta H$ if $C_P = \tfrac{7}{2}R$.

> [!TIP]
> 🧭 **Strategy.** $\Delta H = nC_P\Delta T$.

**Steps.** $\Delta H = 1\times\tfrac72(8.314)(100) = 3.5(831.4)$.

**✅ Answer.** $\Delta H \approx 2910\ \mathrm{J} = 2.91\ \mathrm{kJ}$.

---

<a id="m13"></a>
### M13

> ❓ **Question.** The same gas (above) — find $\Delta U$ ($C_V = \tfrac{5}{2}R$).

> [!TIP]
> 🧭 **Strategy.** $\Delta U = nC_V\Delta T$.

**Steps.** $\Delta U = 1\times\tfrac52(8.314)(100) = 2.5(831.4)$.

**✅ Answer.** $\Delta U \approx 2079\ \mathrm{J} = 2.08\ \mathrm{kJ}$.

---

<a id="m14"></a>
### M14

> ❓ **Question.** For a reaction $K = 10$ at $300\ \mathrm{K}$. Find $\Delta G^\circ$.

> [!TIP]
> 🧭 **Strategy.** $\Delta G^\circ = -2.303\,RT\log K$.

**Steps.** $\Delta G^\circ = -2.303(8.314)(300)\log 10 = -5744(1)$.

**✅ Answer.** $\Delta G^\circ \approx -5.74\ \mathrm{kJ/mol}$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** At the melting point of ice ($273\ \mathrm{K}$), $\Delta_{fus}H = 6.0\ \mathrm{kJ/mol}$. Find $\Delta S_{fus}$.

> [!TIP]
> 🧭 **Strategy.** At a phase transition (equilibrium), $\Delta G = 0 \Rightarrow \Delta S = \Delta H/T$.

**Steps.** $\Delta S = \dfrac{6000}{273}$.

**✅ Answer.** $\Delta S_{fus} \approx 22.0\ \mathrm{J\,K^{-1}mol^{-1}}$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** Estimate $\Delta H$ for $\text{H}_2 + \text{Cl}_2 \to 2\text{HCl}$ using bond enthalpies: H–H $= 436$, Cl–Cl $= 242$, H–Cl $= 431\ \mathrm{kJ/mol}$.

> [!TIP]
> 🧭 **Strategy.** $\Delta H = \sum(\text{bonds broken}) - \sum(\text{bonds formed})$.

**Steps.** Broken: $436 + 242 = 678$; formed: $2(431) = 862$; $\Delta H = 678 - 862$.

**✅ Answer.** $\Delta H = -184\ \mathrm{kJ/mol}$.

---

<a id="a2"></a>
### A2

> ❓ **Question.** One mole of an ideal gas expands **reversibly and isothermally** at $300\ \mathrm{K}$ from $1\ \mathrm{L}$ to $10\ \mathrm{L}$. Find the work done and the heat absorbed.

> [!TIP]
> 🧭 **Strategy.** Isothermal ideal gas: $\Delta U = 0$, so $q = -w$; $w = -2.303\,nRT\log(V_2/V_1)$.

**Steps.** $w = -2.303(1)(8.314)(300)\log 10 = -5744\ \mathrm{J}$; $q = +5744\ \mathrm{J}$.

**✅ Answer.** $w = -5744\ \mathrm{J}$ (done by gas); $q = +5744\ \mathrm{J}$ (absorbed).

---

<a id="a3"></a>
### A3

> ❓ **Question.** A reaction has $\Delta H = +30\ \mathrm{kJ}$ and $\Delta S = +100\ \mathrm{J/K}$. Below what temperature is it non-spontaneous?

> [!TIP]
> 🧭 **Strategy.** Both positive → spontaneous **above** $T = \Delta H/\Delta S$.

**Steps.** $T = \dfrac{30000}{100} = 300\ \mathrm{K}$.

**✅ Answer.** Non-spontaneous **below** $300\ \mathrm{K}$; spontaneous above it.

---

<a id="a4"></a>
### A4

> ❓ **Question.** For a reaction $\Delta G^\circ = -11.5\ \mathrm{kJ/mol}$ at $298\ \mathrm{K}$. Find $K$.

> [!TIP]
> 🧭 **Strategy.** $\Delta G^\circ = -2.303\,RT\log K \Rightarrow \log K = \dfrac{-\Delta G^\circ}{2.303RT}$.

**Steps.** $\log K = \dfrac{11500}{2.303(8.314)(298)} = \dfrac{11500}{5706} \approx 2.0$; $K = 10^2$.

**✅ Answer.** $K \approx 100$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** An ideal gas expands **adiabatically and reversibly**; its temperature falls from $400\ \mathrm{K}$ to $300\ \mathrm{K}$ ($n = 1$, $C_V = \tfrac32 R$). Find $\Delta U$, $q$ and $w$.

> [!TIP]
> 🧭 **Strategy.** Adiabatic: $q = 0$, so $\Delta U = w = nC_V\Delta T$.

**Steps.** $\Delta U = 1\times\tfrac32(8.314)(300-400) = 1.5(8.314)(-100) = -1247\ \mathrm{J}$.

**✅ Answer.** $q = 0$; $\Delta U = w = -1247\ \mathrm{J}$ (gas does work, cooling down).

---

<a id="a6"></a>
### A6

> ❓ **Question.** The lattice enthalpy of NaCl is to be found by a Born–Haber cycle: $\Delta_f H = -411$, sublimation of Na $= +108$, ½ bond of Cl₂ $= +121$, IE of Na $= +496$, electron gain of Cl $= -349\ \mathrm{kJ/mol}$. Find the lattice enthalpy.

> [!TIP]
> 🧭 **Strategy.** Hess loop: $\Delta_f H = \text{sub} + \tfrac12 D + IE + \Delta_{eg}H + U_{\text{lattice}}$; solve for $U_{\text{lattice}}$.

**Steps.** $-411 = 108 + 121 + 496 - 349 + U \Rightarrow -411 = 376 + U \Rightarrow U = -787$.

**✅ Answer.** Lattice enthalpy $\approx -787\ \mathrm{kJ/mol}$.

---

<a id="a7"></a>
### A7

> ❓ **Question.** One mole of an ideal gas expands irreversibly against a constant external pressure of $1\ \mathrm{atm}$ from $5\ \mathrm{L}$ to $15\ \mathrm{L}$ at constant $T$. Find $w$ (in J) and $q$.

> [!TIP]
> 🧭 **Strategy.** Irreversible isothermal: $w = -P_{\text{ext}}\Delta V$; $\Delta U = 0 \Rightarrow q = -w$.

**Steps.** $w = -1(15-5) = -10\ \mathrm{L\,atm} = -10(101.3) = -1013\ \mathrm{J}$; $q = +1013\ \mathrm{J}$.

**✅ Answer.** $w = -1013\ \mathrm{J}$, $q = +1013\ \mathrm{J}$ (less work than the reversible path).

---

<a id="a8"></a>
### A8

> ❓ **Question.** For a reaction $\Delta H = -40\ \mathrm{kJ}$ and $\Delta G = -50\ \mathrm{kJ}$ at $300\ \mathrm{K}$. Find $\Delta S$.

> [!TIP]
> 🧭 **Strategy.** $\Delta G = \Delta H - T\Delta S \Rightarrow \Delta S = \dfrac{\Delta H - \Delta G}{T}$.

**Steps.** $\Delta S = \dfrac{-40 - (-50)}{300} = \dfrac{10}{300}\ \mathrm{kJ/K} = \dfrac{10000}{300}\ \mathrm{J/K}$.

**✅ Answer.** $\Delta S = +33.3\ \mathrm{J\,K^{-1}}$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** Using $\Delta G^\circ = \Delta H^\circ - T\Delta S^\circ$ with $\Delta H^\circ = 178\ \mathrm{kJ}$ and $\Delta S^\circ = 160\ \mathrm{J/K}$ (for CaCO₃ → CaO + CO₂), find the decomposition temperature (where $\Delta G^\circ = 0$).

> [!TIP]
> 🧭 **Strategy.** $T = \Delta H^\circ/\Delta S^\circ$.

**Steps.** $T = \dfrac{178000}{160}$.

**✅ Answer.** $T \approx 1113\ \mathrm{K}$ (above which decomposition is spontaneous).

---

<a id="a10"></a>
### A10

> ❓ **Question.** Compare the work done by an ideal gas expanding from $V_1$ to $V_2$ at constant $T$ via (a) reversible and (b) single-step irreversible (against $P_2$) paths. Which is greater in magnitude, and why?

> [!TIP]
> 🧭 **Strategy.** Reversible work is the area under the full isotherm; irreversible against the lower final pressure is a smaller rectangle.

**Steps.** $|w_{\text{rev}}| = nRT\ln(V_2/V_1)$ vs $|w_{\text{irr}}| = P_2(V_2 - V_1)$; the reversible path stays at higher pressure throughout.

**✅ Answer.** **Reversible work is greater in magnitude** — it is the maximum work obtainable between the two states.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style, and tag each
> with its difficulty and sub-topic (first-law / enthalpy / Hess / entropy / Gibbs / work).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <firstlaw/enthalpy/hess/entropy/gibbs/work>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
