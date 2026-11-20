# Thermodynamics — Practice Range

> **35 problems to solve yourself**, split **Basic (10) · Medium (15) · Advanced (10)** across the first
> law, enthalpy, thermochemistry, entropy, Gibbs energy and reversible work. Each has a **💡 Approach hint**
> (reveal only if stuck) and a **collapsible answer**. Attempt with pen and paper first.

<!-- RENDERING: inside math use \cdot (not ·), \Delta, \to, ^\circ. -->

> **Constants:** $R = 8.314\ \mathrm{J\,K^{-1}mol^{-1}}$; $1\ \mathrm{L\,atm} = 101.3\ \mathrm{J}$; $2.303R = 19.15\ \mathrm{J\,K^{-1}mol^{-1}}$.

---

## 📑 Index

- [Basic (P1–P10)](#basic)
- [Medium (P11–P25)](#medium)
- [Advanced (P26–P35)](#advanced)
- [How to log your attempts](#log)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (P1–P10)

**P1.** A system releases $60\ \mathrm{J}$ of heat and $20\ \mathrm{J}$ of work is done on it. Find $\Delta U$.

<details><summary>💡 Approach hint</summary>

$\Delta U = q + w$; heat released → $q$ negative.
</details>

<details><summary>✅ Answer</summary>

$\Delta U = -60 + 20 = \mathbf{-40\ J}$.
</details>

---

**P2.** A gas expands $5\ \mathrm{L}$ against $2\ \mathrm{atm}$. Find the work (L·atm).

<details><summary>💡 Approach hint</summary>

$w = -P_{\text{ext}}\Delta V$.
</details>

<details><summary>✅ Answer</summary>

$-2(5) = \mathbf{-10\ L\,atm}$.
</details>

---

**P3.** Convert $-10\ \mathrm{L\,atm}$ to joules.

<details><summary>💡 Approach hint</summary>

$\times 101.3$.
</details>

<details><summary>✅ Answer</summary>

$\mathbf{-1013\ J}$.
</details>

---

**P4.** For a reaction $\Delta n_g = +1$ at $300\ \mathrm{K}$, $\Delta U = 50\ \mathrm{kJ}$. Find $\Delta H$.

<details><summary>💡 Approach hint</summary>

$\Delta H = \Delta U + \Delta n_g RT$.
</details>

<details><summary>✅ Answer</summary>

$50 + (1)(8.314\times10^{-3})(300) = 50 + 2.49 = \mathbf{52.5\ kJ}$.
</details>

---

**P5.** Classify: $\Delta H = -200\ \mathrm{kJ}$.

<details><summary>💡 Approach hint</summary>

Sign of $\Delta H$.
</details>

<details><summary>✅ Answer</summary>

**Exothermic.**
</details>

---

**P6.** Heat to raise $100\ \mathrm{g}$ water by $20\ \mathrm{K}$ ($c = 4.18$).

<details><summary>💡 Approach hint</summary>

$q = mc\Delta T$.
</details>

<details><summary>✅ Answer</summary>

$100(4.18)(20) = \mathbf{8360\ J}$.
</details>

---

**P7.** Is $\Delta H > 0$, $\Delta S < 0$ ever spontaneous?

<details><summary>💡 Approach hint</summary>

$\Delta G = \Delta H - T\Delta S$.
</details>

<details><summary>✅ Answer</summary>

**No** — $\Delta G > 0$ at all $T$.
</details>

---

**P8.** $\Delta_f H^\circ$ of graphite?

<details><summary>💡 Approach hint</summary>

Standard-state element.
</details>

<details><summary>✅ Answer</summary>

**0.**
</details>

---

**P9.** For an ideal gas isothermal process, what is $\Delta U$?

<details><summary>💡 Approach hint</summary>

$U$ depends only on $T$.
</details>

<details><summary>✅ Answer</summary>

$\mathbf{0}$.
</details>

---

**P10.** At constant volume, heat absorbed equals which state-function change?

<details><summary>💡 Approach hint</summary>

$q_V = ?$
</details>

<details><summary>✅ Answer</summary>

$\Delta U$.
</details>

---

<a id="medium"></a>
## 🟡 Medium (P11–P25)

**P11.** For $2\text{CO} + \text{O}_2 \to 2\text{CO}_2$, find $\Delta n_g$ and whether $\Delta H$ is greater or less than $\Delta U$.

<details><summary>💡 Approach hint</summary>

$\Delta n_g = $ gas products − reactants.
</details>

<details><summary>✅ Answer</summary>

$\Delta n_g = 2 - 3 = -1$; $\Delta H < \Delta U$.
</details>

---

**P12.** Using $\Delta_f H^\circ$: CO₂ $=-393.5$, H₂O(l) $=-285.8$, C₂H₅OH(l) $=-277.7$; find $\Delta_c H$ of ethanol ($\text{C}_2\text{H}_5\text{OH} + 3\text{O}_2 \to 2\text{CO}_2 + 3\text{H}_2\text{O}$).

<details><summary>💡 Approach hint</summary>

Products − reactants.
</details>

<details><summary>✅ Answer</summary>

$[2(-393.5) + 3(-285.8)] - (-277.7) = (-787 - 857.4) + 277.7 = \mathbf{-1366.7\ kJ/mol}$.
</details>

---

**P13.** Given C+O₂→CO₂ ($-393.5$) and H₂+½O₂→H₂O ($-285.8$) and C+2H₂+... — use Hess: find $\Delta_f H$ of CH₄ given $\Delta_c H(\text{CH}_4) = -890.3$.

<details><summary>💡 Approach hint</summary>

$\Delta_f(\text{CH}_4) = \Delta_f(\text{CO}_2) + 2\Delta_f(\text{H}_2\text{O}) - \Delta_c(\text{CH}_4)$.
</details>

<details><summary>✅ Answer</summary>

$-393.5 + 2(-285.8) - (-890.3) = -965.1 + 890.3 = \mathbf{-74.8\ kJ/mol}$.
</details>

---

**P14.** A reaction has $\Delta H = +50\ \mathrm{kJ}$ at $250\ \mathrm{K}$. Find $\Delta S_{\text{surr}}$.

<details><summary>💡 Approach hint</summary>

$-\Delta H/T$.
</details>

<details><summary>✅ Answer</summary>

$-50000/250 = \mathbf{-200\ J/K}$.
</details>

---

**P15.** $\Delta H = -80\ \mathrm{kJ}$, $\Delta S = -100\ \mathrm{J/K}$. Find $\Delta G$ at $300\ \mathrm{K}$.

<details><summary>💡 Approach hint</summary>

$\Delta G = \Delta H - T\Delta S$.
</details>

<details><summary>✅ Answer</summary>

$-80 - 300(-0.1) = -80 + 30 = \mathbf{-50\ kJ}$ (spontaneous).
</details>

---

**P16.** For the above, find the crossover temperature.

<details><summary>💡 Approach hint</summary>

$T = \Delta H/\Delta S$.
</details>

<details><summary>✅ Answer</summary>

$-80000/-100 = \mathbf{800\ K}$ (spontaneous below this).
</details>

---

**P17.** Heat of neutralisation is $-57.1\ \mathrm{kJ/mol}$. Heat released forming $0.25\ \mathrm{mol}$ water?

<details><summary>💡 Approach hint</summary>

$\propto$ moles water.
</details>

<details><summary>✅ Answer</summary>

$0.25 \times 57.1 = \mathbf{14.3\ kJ}$.
</details>

---

**P18.** $\Delta S_{\text{sys}} = +120\ \mathrm{J/K}$, $\Delta S_{\text{surr}} = -80\ \mathrm{J/K}$. Spontaneous?

<details><summary>💡 Approach hint</summary>

$\Delta S_{\text{univ}} > 0$?
</details>

<details><summary>✅ Answer</summary>

$+40\ \mathrm{J/K} > 0$ → **yes**.
</details>

---

**P19.** One mole ideal gas heated at constant $P$, $300\to350\ \mathrm{K}$, $C_P = \tfrac72 R$. Find $\Delta H$.

<details><summary>💡 Approach hint</summary>

$\Delta H = nC_P\Delta T$.
</details>

<details><summary>✅ Answer</summary>

$\tfrac72(8.314)(50) = \mathbf{1455\ J}$.
</details>

---

**P20.** For $K = 100$ at $300\ \mathrm{K}$, find $\Delta G^\circ$.

<details><summary>💡 Approach hint</summary>

$\Delta G^\circ = -2.303RT\log K$.
</details>

<details><summary>✅ Answer</summary>

$-2.303(8.314)(300)(2) = \mathbf{-11.5\ kJ/mol}$.
</details>

---

**P21.** At $373\ \mathrm{K}$, $\Delta_{vap}H$ of water $= 40.7\ \mathrm{kJ/mol}$. Find $\Delta S_{vap}$.

<details><summary>💡 Approach hint</summary>

$\Delta S = \Delta H/T$ (equilibrium transition).
</details>

<details><summary>✅ Answer</summary>

$40700/373 = \mathbf{109\ J\,K^{-1}mol^{-1}}$ (Trouton's rule).
</details>

---

**P22.** A reaction at constant volume releases $100\ \mathrm{kJ}$. What is $\Delta U$?

<details><summary>💡 Approach hint</summary>

$q_V = \Delta U$.
</details>

<details><summary>✅ Answer</summary>

$\mathbf{-100\ kJ}$.
</details>

---

**P23.** $\Delta H = +100\ \mathrm{kJ}$, $\Delta S = +250\ \mathrm{J/K}$. Spontaneous at $298\ \mathrm{K}$?

<details><summary>💡 Approach hint</summary>

Compare $T$ with $\Delta H/\Delta S$.
</details>

<details><summary>✅ Answer</summary>

Crossover $T = 400\ \mathrm{K}$; at 298 K < 400 K → **not spontaneous**.
</details>

---

**P24.** One mole ideal gas, constant $V$, $300\to400\ \mathrm{K}$, $C_V = \tfrac52 R$. Find $\Delta U$.

<details><summary>💡 Approach hint</summary>

$\Delta U = nC_V\Delta T$.
</details>

<details><summary>✅ Answer</summary>

$\tfrac52(8.314)(100) = \mathbf{2079\ J}$.
</details>

---

**P25.** $\Delta G^\circ = 0$ for a reaction. What is $K$?

<details><summary>💡 Approach hint</summary>

$\Delta G^\circ = -RT\ln K$.
</details>

<details><summary>✅ Answer</summary>

$K = \mathbf{1}$.
</details>

---

<a id="advanced"></a>
## 🔴 Advanced (P26–P35)

**P26.** Estimate $\Delta H$ for $\text{CH}_4 + \text{Cl}_2 \to \text{CH}_3\text{Cl} + \text{HCl}$. Bonds (kJ/mol): C–H $=413$, Cl–Cl $=242$, C–Cl $=328$, H–Cl $=431$.

<details><summary>💡 Approach hint</summary>

Broken − formed (only the bonds that change).
</details>

<details><summary>✅ Answer</summary>

Broken: C–H(413)+Cl–Cl(242)=655; formed: C–Cl(328)+H–Cl(431)=759; $\Delta H = 655-759 = \mathbf{-104\ kJ/mol}$.
</details>

---

**P27.** One mole ideal gas expands reversibly isothermally at $300\ \mathrm{K}$, $V_1\to 2V_1$. Find $w$.

<details><summary>💡 Approach hint</summary>

$w = -2.303nRT\log(V_2/V_1)$.
</details>

<details><summary>✅ Answer</summary>

$-2.303(8.314)(300)\log 2 = -5744(0.301) = \mathbf{-1729\ J}$.
</details>

---

**P28.** $\Delta H = +60\ \mathrm{kJ}$, $\Delta S = +150\ \mathrm{J/K}$. Above what $T$ is it spontaneous?

<details><summary>💡 Approach hint</summary>

$T = \Delta H/\Delta S$.
</details>

<details><summary>✅ Answer</summary>

$60000/150 = \mathbf{400\ K}$ (spontaneous above).
</details>

---

**P29.** $\Delta G^\circ = -23\ \mathrm{kJ/mol}$ at $298\ \mathrm{K}$. Find $K$.

<details><summary>💡 Approach hint</summary>

$\log K = -\Delta G^\circ/(2.303RT)$.
</details>

<details><summary>✅ Answer</summary>

$\log K = 23000/5706 \approx 4.03$; $K \approx \mathbf{10^4}$.
</details>

---

**P30.** Ideal gas expands adiabatically reversibly, $n=2$, $C_V=\tfrac32 R$, $T: 500\to350\ \mathrm{K}$. Find $w$.

<details><summary>💡 Approach hint</summary>

Adiabatic: $q=0$, $w=\Delta U = nC_V\Delta T$.
</details>

<details><summary>✅ Answer</summary>

$2(\tfrac32)(8.314)(-150) = 3(8.314)(-150) = \mathbf{-3741\ J}$.
</details>

---

**P31.** Born–Haber: $\Delta_f H(\text{KCl}) = -437$, sub(K)$=+89$, ½D(Cl₂)$=+121$, IE(K)$=+419$, $\Delta_{eg}(\text{Cl})=-349$. Find lattice enthalpy.

<details><summary>💡 Approach hint</summary>

$\Delta_f H = \text{sub} + \tfrac12 D + IE + \Delta_{eg} + U$.
</details>

<details><summary>✅ Answer</summary>

$-437 = 89+121+419-349 + U = 280 + U \Rightarrow U = \mathbf{-717\ kJ/mol}$.
</details>

---

**P32.** $\Delta H = -90\ \mathrm{kJ}$, $\Delta G = -100\ \mathrm{kJ}$ at $250\ \mathrm{K}$. Find $\Delta S$.

<details><summary>💡 Approach hint</summary>

$\Delta S = (\Delta H - \Delta G)/T$.
</details>

<details><summary>✅ Answer</summary>

$(-90+100)/250 = 10000/250 = \mathbf{+40\ J/K}$.
</details>

---

**P33.** One mole ideal gas expands irreversibly against $P_{\text{ext}} = 2\ \mathrm{atm}$ from $4$ to $9\ \mathrm{L}$ at constant $T$. Find $q$.

<details><summary>💡 Approach hint</summary>

$w = -P_{\text{ext}}\Delta V$; isothermal $\Delta U=0 \Rightarrow q=-w$.
</details>

<details><summary>✅ Answer</summary>

$w = -2(5) = -10\ \mathrm{L\,atm} = -1013\ \mathrm{J}$; $q = \mathbf{+1013\ J}$.
</details>

---

**P34.** For CaCO₃ → CaO + CO₂: $\Delta H = 178\ \mathrm{kJ}$, $\Delta S = 161\ \mathrm{J/K}$. Decomposition temperature?

<details><summary>💡 Approach hint</summary>

$T = \Delta H/\Delta S$.
</details>

<details><summary>✅ Answer</summary>

$178000/161 \approx \mathbf{1106\ K}$.
</details>

---

**P35.** Which does more work: a gas expanding $V_1\to V_2$ reversibly or irreversibly (isothermal)? Explain in one line.

<details><summary>💡 Approach hint</summary>

Area under the isotherm vs a rectangle at the lower pressure.
</details>

<details><summary>✅ Answer</summary>

**Reversible** — it stays at higher pressure throughout, giving the maximum work.
</details>

---

<a id="log"></a>
## 🗒️ How to log your attempts

| Date | Problems attempted | First-try correct | Needed hint | Revisit |
|---|---|---|---|---|
| | | | | |

> [!TIP]
> Any problem you got wrong, copy into **[⭐ JEE Questions by Me](./02-solved-numericals.md#jee-questions-by-me)**
> and I'll write out the full strategy + solution so you master that exact type.

---

**Next:** [Deep Dive →](./04-deep-dive.md) · [Formula Recap →](./05-formula-recap.md)
