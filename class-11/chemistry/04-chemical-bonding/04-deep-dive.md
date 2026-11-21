# Chemical Bonding & Molecular Structure — Deep Dive

> Beyond the textbook: the **decision procedures** that turn "predict the structure/property" into a routine. The
> common thread — **count the electrons, then let repulsion, overlap or MO energy decide.**

<!-- RENDERING: inside math use \cdot, \to, \text{...} for formulae, subscripts. -->

---

## 📑 Index

1. [A reliable Lewis-structure + formal-charge procedure](#1-lewis)
2. [VSEPR: the steric-number method for any molecule](#2-vsepr)
3. [Hybridization without memorising examples](#3-hybrid)
4. [MOT: filling diagrams and the s–p mixing switch](#4-mot)
5. [Deciding polarity from shape](#5-polarity)
6. [When each theory wins — VBT vs MOT vs VSEPR](#6-compare)
7. [Fajans' rules and the ionic–covalent continuum](#7-fajans)

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Practice](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-lewis"></a>
## 1. A reliable Lewis-structure + formal-charge procedure

1. **Total valence electrons** = sum over atoms (add for anion charge, subtract for cation).
2. **Skeleton:** least electronegative atom central (never H); connect with single bonds.
3. **Complete octets** on outer atoms with lone pairs.
4. **Leftover electrons** → lone pairs on the central atom.
5. **Electron-deficient centre?** Form multiple bonds using outer-atom lone pairs.
6. **Check with formal charge** $\text{FC} = V - L - \tfrac12 B$; choose the structure with FCs nearest zero and
   any negative FC on the most electronegative atom.

> [!IMPORTANT]
> Formal charge is the **tie-breaker**, not an afterthought — compute it for every candidate structure. The sum
> of formal charges must equal the overall charge of the species; use that as a built-in check.

---

<a id="2-vsepr"></a>
## 2. VSEPR: the steric-number method for any molecule

Define the **steric number** of the central atom:
$$\text{SN} = (\text{number of }\sigma\text{-bonded atoms}) + (\text{number of lone pairs}).$$

SN gives the **electron geometry**; subtracting lone pairs gives the **molecular shape**:

| SN | Electron geometry | 0 LP | 1 LP | 2 LP | 3 LP |
|---|---|---|---|---|---|
| 2 | Linear | linear | — | — | — |
| 3 | Trigonal planar | trigonal planar | bent | — | — |
| 4 | Tetrahedral | tetrahedral | pyramidal | bent | — |
| 5 | Trigonal bipyramidal | TBP | see-saw | T-shaped | linear |
| 6 | Octahedral | octahedral | square pyramidal | square planar | — |

Lone pairs occupy **equatorial** positions in TBP (less repulsion) and **axial/opposite** positions in octahedral.

> [!IMPORTANT]
> Memorise this one table and you can predict **any** main-group shape. The trick for SN 5 and 6 is where the
> lone pairs go: **equatorial** in trigonal bipyramidal, **trans (opposite)** in octahedral — that placement is
> what makes $\text{SF}_4$ see-saw and $\text{XeF}_4$ square planar.

---

<a id="3-hybrid"></a>
## 3. Hybridization without memorising examples

The **steric number = hybridization** directly:

| SN | Hybridization |
|---|---|
| 2 | $sp$ |
| 3 | $sp^2$ |
| 4 | $sp^3$ |
| 5 | $sp^3d$ |
| 6 | $sp^3d^2$ |

Only **σ-bonds and lone pairs** count; **π-bonds use leftover unhybridized p-orbitals**. For a quick formula on
simple molecules: hybridization index $= \tfrac12(\text{valence e⁻ of central atom} + \text{monovalent atoms} \pm \text{charge})$.

> [!TIP]
> Never count π-bonds toward hybridization. A C with a double bond ($sp^2$) still has SN 3 because the second
> bond of the double is a π. This is the most common hybridization mistake — count **atoms bonded + lone pairs**,
> full stop.

---

<a id="4-mot"></a>
## 4. MOT: filling diagrams and the s–p mixing switch

For homonuclear diatomics of period 2, fill MOs in energy order. **Crucial detail:** for
$\text{B}_2, \text{C}_2, \text{N}_2$ (and lighter) the order is
$$\sigma_{2s} < \sigma^*_{2s} < \pi_{2p} < \sigma_{2p} < \pi^*_{2p} < \sigma^*_{2p},$$
but for $\text{O}_2, \text{F}_2$ the $\sigma_{2p}$ drops **below** the $\pi_{2p}$ (the s–p mixing that raised
$\sigma_{2p}$ in lighter atoms weakens).

Then: **bond order** $= \tfrac{N_b - N_a}{2}$; **unpaired electrons → paramagnetic**.

> [!IMPORTANT]
> The $\pi$-before-$\sigma$ switch (≤ N₂) vs $\sigma$-before-$\pi$ (O₂, F₂) changes which orbital electrons enter,
> and so predicts magnetism. This is exactly why $\text{B}_2$ and $\text{O}_2$ are paramagnetic while $\text{C}_2$
> and $\text{N}_2$ are diamagnetic. Know both orderings.

---

<a id="5-polarity"></a>
## 5. Deciding polarity from shape

A molecule is **polar** only if the vector sum of its bond dipoles (and lone-pair dipoles) is non-zero.

**Procedure:**
1. Identify polar bonds ($\Delta\text{EN} \ne 0$).
2. Draw the 3-D shape (from VSEPR).
3. Add bond dipoles as vectors — **symmetry cancels** them.

Symmetric shapes with identical outer atoms ($\text{CO}_2$, $\text{BF}_3$, $\text{CH}_4$, $\text{PCl}_5$,
$\text{SF}_6$) are **non-polar**; lone pairs or unlike atoms break symmetry and create a net dipole.

> [!TIP]
> The fast rule: **symmetric molecule with all-identical terminal atoms ⟹ non-polar**; a lone pair on the central
> atom almost always makes it polar (its dipole has nothing to cancel it). Shape, not just bond polarity, decides.

---

<a id="6-compare"></a>
## 6. When each theory wins — VBT vs MOT vs VSEPR

| Theory | Good for | Fails at |
|---|---|---|
| **VSEPR** | predicting shapes & bond angles | bond strength, magnetism, delocalisation |
| **VBT / hybridization** | σ/π framework, geometry, localized bonds | paramagnetism of $\text{O}_2$, delocalised/odd-e⁻ species |
| **MOT** | bond order, magnetism, spectra, ions | quick shape prediction (no simple geometry output) |

> [!IMPORTANT]
> No single theory does everything. Use **VSEPR for shape**, **hybridization for the bonding framework**, and
> **MOT for bond order and magnetism**. Questions that ask "why is $\text{O}_2$ paramagnetic?" are signalling
> **MOT**; "what is the shape of…?" signals **VSEPR**.

---

<a id="7-fajans"></a>
## 7. Fajans' rules and the ionic–covalent continuum

No bond is purely ionic or purely covalent. **Fajans' rules** predict covalent character in a nominally ionic
bond:

Covalent character **increases** with:
1. **Small, highly charged cation** (high polarising power),
2. **Large, highly charged anion** (high polarisability),
3. **Pseudo-noble-gas (18-electron) cation configuration** (e.g. $\text{Cu}^+$, $\text{Ag}^+$).

This explains colour, lower melting points and solubility of "ionic" compounds like $\text{AgI}$, $\text{AlCl}_3$.

> [!IMPORTANT]
> Fajans' rules connect to **percentage ionic character** and dipole moment: more polarisation ⟹ more electron
> sharing ⟹ more covalent. The cation's **polarising power** ($\text{charge}/\text{size}^2$) and the anion's
> **polarisability** (size) are the two levers — a compact way to rank covalent character across a series.

---

## ✅ Deep-dive takeaways

> - **Lewis:** count valence e⁻ → skeleton → octets → multiple bonds; use **formal charge** as tie-breaker.
> - **VSEPR:** steric number (σ + lone pairs) → electron geometry → subtract lone pairs for shape.
> - **Hybridization = steric number** ($sp$…$sp^3d^2$); π-bonds don't count.
> - **MOT:** mind the $\pi/\sigma$ ordering switch at O₂; bond order $= \tfrac{N_b - N_a}{2}$; unpaired e⁻ ⟹ paramagnetic.
> - **Polarity:** vector-sum bond dipoles; symmetry cancels.
> - **Theory choice:** VSEPR (shape), VBT (framework), MOT (bond order/magnetism).
> - **Fajans:** small/highly-charged cation + large anion ⟹ more covalent character.

**Next:** [Formula Recap →](./05-formula-recap.md)
