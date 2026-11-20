# Structure of Atom — Deep Dive

> The ideas that tie the chapter together: why spectra prove quantisation, how to scale Bohr results with
> $Z^2/n^2$, the wave–particle bridge, reading quantum numbers as an address, and the stability behind
> configuration exceptions. Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \to for arrows, \lambda \nu. -->

---

## 📑 Index

1. [Why line spectra force quantisation](#1-quantisation)
2. [Scaling Bohr results with Z²/n²](#2-scaling)
3. [The wave–particle bridge](#3-bridge)
4. [Quantum numbers as an address](#4-address)
5. [Nodes without the algebra](#5-nodes)
6. [The logic behind configuration exceptions](#6-exceptions)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-quantisation"></a>
## 1. Why line spectra force quantisation

A heated gas emits only **specific** wavelengths, not a continuous rainbow. If electron energies could be
anything, every wavelength would appear. Discrete lines mean the energy *differences* — and hence the
energy *levels* — are discrete. Each line is one jump $n_2 \to n_1$ with
$$\Delta E = h\nu = \frac{hc}{\lambda}.$$

> [!IMPORTANT]
> Emission vs absorption: an **emission** line appears when an electron falls to a lower level (releases a
> photon); an **absorption** line is a dark gap where that same photon was absorbed to lift the electron
> up. Both occur at the **same wavelengths** for a given element — its fingerprint.

---

<a id="2-scaling"></a>
## 2. Scaling Bohr results with Z²/n²

Every Bohr quantity scales cleanly, so you rarely plug in full constants:

| Quantity | Scaling | Remember |
|---|---|---|
| Radius $r_n$ | $\propto n^2/Z$ | $0.529\ \text{Å}$ at H, $n=1$ |
| Energy $E_n$ | $\propto Z^2/n^2$ | $-13.6\ \mathrm{eV}$ at H, $n=1$ |
| Velocity $v_n$ | $\propto Z/n$ | $2.18\times10^6\ \mathrm{m/s}$ at H, $n=1$ |

So He⁺ ($Z=2$) has energies $4\times$ hydrogen's; its ground-state ionisation energy is $54.4\ \mathrm{eV}$.

> [!TIP]
> For any hydrogen-like ion, take the hydrogen value and multiply: energy and ionisation energy by $Z^2$,
> radius by $1/Z$, velocity by $Z$. This turns most "He⁺ / Li²⁺" problems into one-line scalings.

---

<a id="3-bridge"></a>
## 3. The wave–particle bridge

Light is both wave ($\lambda, \nu$) and particle (photon, $E = h\nu$); de Broglie said matter is too
($\lambda = h/mv$). Two numerical bridges carry most problems:

- **Photon energy from wavelength:** $E(\text{eV}) = \dfrac{1240}{\lambda(\text{nm})}$.
- **Electron wavelength from accelerating voltage:** $\lambda = \dfrac{12.27}{\sqrt{V}}\ \text{Å}$.

> [!NOTE]
> The de Broglie wavelength is inversely proportional to mass, so it matters only for electrons and other
> tiny particles; for a cricket ball it is $\sim10^{-34}\ \mathrm{m}$ — utterly unobservable. This is why
> we never notice the wave nature of everyday objects.

---

<a id="4-address"></a>
## 4. Quantum numbers as an address

Think of $(n, l, m_l, m_s)$ as a unique address for every electron:

- $n$ → the **shell** (size, main energy). Capacity $2n^2$.
- $l$ → the **subshell/shape** ($s,p,d,f$). Capacity $2(2l+1)$; number of orbitals $2l+1$.
- $m_l$ → the **orientation** (which specific orbital), $-l \dots +l$.
- $m_s$ → the **spin** ($\pm\tfrac12$), the two seats in each orbital.

**Pauli** forbids two electrons sharing all four; **Hund** fills the seats of a subshell singly before
pairing (maximising parallel spin).

> [!TIP]
> Most "is this set allowed?" questions reduce to two checks: $0 \le l \le n-1$, and $-l \le m_l \le +l$.
> If either fails, the set is impossible.

---

<a id="5-nodes"></a>
## 5. Nodes without the algebra

For an orbital $(n, l)$:
$$\text{total nodes} = n-1, \quad \text{angular} = l, \quad \text{radial} = n - l - 1.$$

- $s$ orbitals ($l=0$) have **no angular nodes** (spherical); all their nodes are radial shells.
- $p, d, f$ have $l$ nodal planes/cones (the "lobes" meet at these).

> [!IMPORTANT]
> Don't memorise node counts per orbital — derive them: write $n-1$ total, assign $l$ to angular, and the
> leftover is radial. This works for any orbital, including exotic ones like $4f$ or $5g$.

---

<a id="6-exceptions"></a>
## 6. The logic behind configuration exceptions

Half-filled ($d^5, f^7$) and fully-filled ($d^{10}, f^{14}$) subshells are **extra stable** because of
symmetric charge distribution and large **exchange energy** (more parallel-spin electron pairs lower the
energy). So an electron will move from $4s$ to $3d$ to reach $d^5$ or $d^{10}$:

- Cr: $[\text{Ar}]3d^5 4s^1$ (not $3d^4 4s^2$).
- Cu: $[\text{Ar}]3d^{10}4s^1$ (not $3d^9 4s^2$).

For **ions**, electrons leave from the **highest principal quantum number first** — $4s$ before $3d$:
$$\text{Fe } [\text{Ar}]3d^6 4s^2 \to \text{Fe}^{2+}\ [\text{Ar}]3d^6, \quad \text{Fe}^{3+}\ [\text{Ar}]3d^5.$$

> [!WARNING]
> The "remove 4s before 3d" rule trips up almost everyone: even though $4s$ fills *before* $3d$ (Aufbau),
> once filled it is higher in energy, so it **empties first** on ionisation. Fe³⁺ being $3d^5$ (a stable
> half-filled set) is why iron(III) is so common.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **Bohr works only for one-electron species** (H, He⁺, Li²⁺) — never for multi-electron atoms.
> - **Energies are negative**; ionisation energy $= 0 - E_n = +13.6\,Z^2/n^2$ eV from level $n$.
> - **Photoelectric effect depends on frequency**, not intensity; no emission below threshold $\nu_0$.
> - **de Broglie:** longer wavelength for lighter particles / lower momentum.
> - **Quantum numbers:** $0\le l\le n-1$, $-l\le m_l\le +l$; node total $= n-1$.
> - **Remove 4s before 3d** when writing cation configurations.
> - **Cr and Cu exceptions** ($3d^5 4s^1$, $3d^{10}4s^1$) from half/fully-filled stability.
> - **Match units:** use $hc = 1240\ \mathrm{eV\,nm}$ and keep $\lambda$ in nm, energy in eV.
