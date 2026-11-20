# Classification & Periodicity — Deep Dive

> The reasoning engine behind every trend: effective nuclear charge as the master variable, why the
> anomalies happen, how to read position → properties, and the data-interpretation tricks (successive IE,
> isoelectronic series) that JEE loves. Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \to for arrows, Z_eff, superscripts for configs. -->

---

## 📑 Index

1. [Effective nuclear charge is the master variable](#1-zeff)
2. [Every trend from one idea](#2-trends)
3. [Why the anomalies happen](#3-anomalies)
4. [Reading successive ionisation enthalpies](#4-successive)
5. [Isoelectronic series and ionic size](#5-isoelectronic)
6. [Position → properties](#6-position)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-zeff"></a>
## 1. Effective nuclear charge is the master variable

A valence electron does not feel the full nuclear charge $Z$ — inner electrons **screen** it. The net pull is
$$Z_{\text{eff}} = Z - \sigma.$$

- **Across a period:** $Z$ rises by 1 per element, but the added electron enters the **same shell** and
  screens by only ~0.35 — so $Z_{\text{eff}}$ climbs steadily.
- **Down a group:** each step adds a **new inner shell**, raising $\sigma$ substantially, so $Z_{\text{eff}}$
  per valence electron grows only slowly while the electron sits in a much larger shell.

> [!IMPORTANT]
> Hold one picture: a valence electron pulled by $Z_{\text{eff}}$ at some distance. Across a period the pull
> tightens (radius ↓, everything-holding-electrons ↑); down a group the distance dominates (radius ↑,
> everything ↓). All seven trends are this one tug-of-war between charge and distance.

---

<a id="2-trends"></a>
## 2. Every trend from one idea

| Property | Driven by | Across period → | Down group ↓ |
|---|---|---|---|
| Atomic radius | distance vs $Z_{\text{eff}}$ | decreases | increases |
| Ionisation enthalpy | how hard to pull an electron off | increases | decreases |
| Electron gain enthalpy | how strongly it attracts an extra electron | more negative | less negative |
| Electronegativity | pull on bonding electrons | increases | decreases |
| Metallic character | ease of losing electrons | decreases | increases |
| Oxide nature | metal vs non-metal | basic → acidic | more basic |

> [!TIP]
> If you remember only "**smaller + higher $Z_{\text{eff}}$ holds electrons tighter**," you can regenerate the
> whole table on the spot: tight hold → high IE, strong electron attraction (negative $\Delta_{eg}H$), high
> electronegativity, non-metallic, acidic oxide.

---

<a id="3-anomalies"></a>
## 3. Why the anomalies happen

Two stability effects break the smooth trends:

- **Filled subshell ($s^2$):** Be ($2s^2$) and Mg ($3s^2$) are extra stable, so **IE(B) < IE(Be)** and
  **IE(Al) < IE(Mg)**.
- **Half-filled subshell ($p^3$):** N ($2p^3$) and P ($3p^3$) are extra stable, so **IE(O) < IE(N)** and
  **IE(S) < IE(P)**.

The **fluorine electron-gain anomaly**: F is so small that adding an electron into its compact $2p$ shell
costs significant repulsion, making $\Delta_{eg}H(\text{F})$ **less** negative than $\Delta_{eg}H(\text{Cl})$.

> [!WARNING]
> In any "arrange by ionisation enthalpy across a period" question, pre-insert the two dips: the element
> just **after** a filled $s^2$ drops (B, Al), and the element just **after** a half-filled $p^3$ drops
> (O, S). Miss these and the ordering is wrong.

---

<a id="4-successive"></a>
## 4. Reading successive ionisation enthalpies

Successive IEs always rise, but a **sudden large jump** marks the point where a **noble-gas core** starts to
break. The number of electrons removed *before* the jump = the element's group valency.

$$\text{Na: } \underbrace{496}_{\text{easy}} \;|\; \underbrace{4562}_{\text{big jump}} \to \text{group 1}$$
$$\text{Mg: } 738,\ 1451 \;|\; \underbrace{7733}_{\text{jump}} \to \text{group 2}$$

> [!IMPORTANT]
> This is a classic data problem: scan the list for the biggest ratio between consecutive IEs; that boundary
> separates valence electrons from the core. Count the valence electrons to name the group — no configuration
> needed.

---

<a id="5-isoelectronic"></a>
## 5. Isoelectronic series and ionic size

Species with the **same number of electrons** (isoelectronic) differ only in nuclear charge. More protons
pull the same electron cloud inward, so:
$$\text{radius} \downarrow \text{ as } Z \uparrow: \quad \text{N}^{3-} > \text{O}^{2-} > \text{F}^- > \text{Ne} > \text{Na}^+ > \text{Mg}^{2+} > \text{Al}^{3+}.$$

> [!TIP]
> For any isoelectronic set, **"count the protons"** — fewer protons means larger. This single rule orders
> mixed cation/anion/noble-gas sets instantly, a frequent exam shortcut.

---

<a id="6-position"></a>
## 6. Position → properties

From an element's **period and group** alone you can predict a surprising amount:
- **Block & configuration** (period = valence $n$; block = region of the table).
- **Common oxidation state** (group number, or group − 10 for high p-block groups).
- **Metallic character & oxide nature** (left/bottom = metallic/basic; right/top = non-metallic/acidic).
- **Rough radius/IE/electronegativity** by comparison with neighbours.

**Diagonal relationships** (Li–Mg, Be–Al, B–Si) appear because going right (↑ charge density) roughly cancels
going down (↓ charge density).

> [!NOTE]
> "Read the position, predict the chemistry" is the core inorganic skill. Many JEE questions give an unnamed
> element by position or by a clue (oxide formula, successive IE) and ask you to deduce its block, valency
> and reactivity — all answerable from periodic logic.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **Ordering by atomic number, not mass** (Moseley fixed Mendeleev).
> - **IE anomalies:** B < Be, Al < Mg (filled $s^2$); O < N, S < P (half-filled $p^3$).
> - **Electron gain enthalpy:** Cl more negative than F (F's small size); noble gases positive.
> - **Isoelectronic size:** more protons → smaller.
> - **Cations smaller, anions larger** than the parent atom.
> - **Successive IE jump** reveals the group/valency.
> - **Oxide trend:** basic (left) → amphoteric (Al, Be, Zn) → acidic (right).
> - **Fluorine is the most electronegative**, but its $\Delta_{eg}H$ is not the most negative.
