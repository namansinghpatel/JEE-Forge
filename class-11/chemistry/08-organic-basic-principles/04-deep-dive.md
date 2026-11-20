# Organic Chemistry (GOC) — Deep Dive

> The reasoning engine behind organic chemistry: electronic effects ranked, the one question behind every
> stability/reactivity call, the aromaticity checklist, carbocation rearrangements, and acid/base logic.
> Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \to, \delta, \text{} for groups. -->

---

## 📑 Index

1. [The one question behind everything](#1-one-question)
2. [Electronic effects, ranked](#2-effects)
3. [Carbocation stability and rearrangements](#3-carbocation)
4. [The aromaticity checklist](#4-aromaticity)
5. [Acidity and basicity logic](#5-acid-base)
6. [Reading reactions: electrophile meets nucleophile](#6-reactions)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-one-question"></a>
## 1. The one question behind everything

Almost every GOC question — fastest reaction, major product, stronger acid, more stable intermediate —
reduces to:

> **"Which species is more stable, and what stabilises it?"**

- A reaction prefers the path through the **more stable intermediate** (carbocation, radical, carbanion).
- A **stronger acid** has a **more stable conjugate base**.
- A **stronger base** has a **more available lone pair** (⇔ stable conjugate acid).

> [!IMPORTANT]
> Train yourself to translate every prompt into a stability comparison, then reach for the tools that create
> stability: **resonance, inductive effect, hyperconjugation, s-character, and (in solution) solvation.**
> This one reflex answers the majority of the chapter.

---

<a id="2-effects"></a>
## 2. Electronic effects, ranked

| Effect | Acts through | Range | Donating (+) | Withdrawing (−) |
|---|---|---|---|---|
| **Inductive (I)** | σ bonds | short (dies with distance) | alkyl (+I) | –NO₂, –CN, –X, –COOH (–I) |
| **Resonance (M)** | π/conjugation | long (whole conjugated system) | –OH, –NH₂, –OR, –X (+M) | –NO₂, –C=O, –CN (–M) |
| **Hyperconjugation** | σ(C–H) → p/π | adjacent | more α-H → more stable | — |

**Usual priority when effects compete:** **resonance > inductive > hyperconjugation > s-character > solvation.**

> [!WARNING]
> Halogens are the classic trap: they are **–I** (electron-withdrawing) *and* **+M** (lone-pair donating).
> On a benzene ring this makes them **o/p-directing (by +M) but deactivating (by –I)** — the only common
> group that directs and deactivates at the same time.

---

<a id="3-carbocation"></a>
## 3. Carbocation stability and rearrangements

$$\text{benzyl} \approx \text{allyl} > 3° > 2° > 1° > \text{methyl} > \text{vinyl}$$

- **Resonance** (benzyl/allyl) is the strongest stabiliser; then **hyperconjugation + +I** (more alkyl groups / α-H).
- A carbocation will **rearrange** (1,2-hydride or 1,2-methyl shift) to reach a more stable cation.

> [!IMPORTANT]
> Any mechanism with a carbocation (HX addition, dehydration/$E1$, $S_N1$) can give a **rearranged product**.
> When you draw the first cation, always ask: "is a 1,2-shift to a more stable (3° or resonance-stabilised)
> cation possible?" If yes, the major product comes from the rearranged cation.

---

<a id="4-aromaticity"></a>
## 4. The aromaticity checklist

Run this in order for any ring:
1. **Cyclic?**
2. **Planar?** (sp² or lone-pair p-orbitals all around)
3. **Fully conjugated?** (every ring atom contributes a p-orbital)
4. **Count π electrons** → $4n+2$ (aromatic), $4n$ (antiaromatic), else non-aromatic (fails 1–3).

- Lone pairs **in the ring p-system** count (pyrrole N, furan O → 6 π electrons, aromatic).
- Charged rings: cyclopentadienyl **anion** (6 π) aromatic; tropylium **cation** (6 π) aromatic.

> [!TIP]
> "Planar + fully conjugated + $4n+2$" is the whole test. Cyclooctatetraene has 8 π electrons but is
> **non-planar** (tub-shaped), so it's non-aromatic, not antiaromatic — planarity is a gatekeeper.

---

<a id="5-acid-base"></a>
## 5. Acidity and basicity logic

**Acidity** — how stable is the conjugate base after losing H⁺?
- **Resonance** stabilises it most: carboxylate (two equivalent O) ≫ phenoxide > alkoxide.
- **–I groups** stabilise it: Cl₃C–COOH ≫ CH₃COOH.
- **s-character** matters for C–H: ethyne (sp) > ethene (sp²) > ethane (sp³).

**Basicity** — how available is the lone pair?
- **+I** increases it (alkylamines > NH₃); **resonance into a ring** decreases it (aniline < NH₃).
- In **water**, solvation scrambles the simple +I order (often $2° > 1° > 3°$); in the **gas phase** the clean +I order holds ($3° > 2° > 1° > $ NH₃).

> [!IMPORTANT]
> For acids ask "conjugate base stability?"; for bases ask "lone-pair availability?". Weigh **resonance
> first**, then inductive, then s-character, then (in water) solvation. Nearly every ranking falls out of this order.

---

<a id="6-reactions"></a>
## 6. Reading reactions: electrophile meets nucleophile

Every polar organic step is an **electron-rich site (nucleophile) attacking an electron-poor site
(electrophile)**; a curly arrow shows the electron **pair** moving from nucleophile to electrophile.

| Mechanism | Driven by |
|---|---|
| $S_N1$ / $E1$ | carbocation stability (rate-determining ionisation) |
| $S_N2$ / $E2$ | steric access + strong nucleophile/base (one concerted step) |
| Electrophilic addition (alkenes) | Markovnikov — more stable carbocation |
| Electrophilic aromatic substitution | ring activation + directing effects |

> [!NOTE]
> Identify the nucleophile and electrophile first, then let stability decide the rest: $S_N1/E1$ favour
> substrates that make stable carbocations (3°, benzylic); $S_N2$ favours unhindered (methyl/1°) carbons.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **Resonance usually beats inductive** when both act (not distance-limited).
> - **Halogens: –I but +M** → o/p-directing *deactivators*.
> - **Carbocations rearrange** (1,2-H / 1,2-CH₃ shifts) — watch for rearranged major products.
> - **Aromaticity needs planarity** — count π electrons only after confirming planar + conjugated.
> - **Acidity = conjugate-base stability; basicity = lone-pair availability.**
> - **Amine basicity order flips** between gas phase (+I only) and water (solvation).
> - **s-character ↑ → C–H acidity ↑** (ethyne most acidic of the three).
> - **IUPAC:** principal functional group gets the lowest locant and the suffix; lowest-locant rule for ties.
