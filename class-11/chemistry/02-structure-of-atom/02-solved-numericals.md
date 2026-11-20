# Structure of Atom — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning subatomic counting,
> Bohr's model, spectra, dual nature, quantum numbers and electronic configuration. Every problem marks the
> **❓ Question** and **✅ Answer**; Medium and Advanced carry a **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \to for arrows, \lambda \nu. -->

> **Useful constants:** $h = 6.626\times10^{-34}\ \mathrm{J\,s}$, $c = 3\times10^8\ \mathrm{m/s}$, $R_H = 1.097\times10^7\ \mathrm{m^{-1}}$, $E_n = -13.6\,Z^2/n^2$ eV, $r_n = 0.529\,n^2/Z$ Å, $hc = 1240\ \mathrm{eV\,nm}$.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — particle counting, isotopes, $c=\nu\lambda$, $E=h\nu$, Bohr basics
- [Medium (M1–M15)](#medium) — Bohr jumps, spectra, de Broglie, photoelectric, quantum numbers, configuration
- [Advanced (A1–A10)](#advanced) — Rydberg/series, nodes, ionisation, accelerated electrons, exceptions
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** How many protons, neutrons and electrons are in ${}^{40}_{20}\text{Ca}$?

**✅ Answer.** Protons $= 20$, electrons $= 20$, neutrons $= 40 - 20 = \boxed{20}$.

---

<a id="b2"></a>
### B2

> ❓ **Question.** Identify the relation: ${}^{14}_{6}\text{C}$ and ${}^{14}_{7}\text{N}$.

**✅ Answer.** Same mass number $A = 14$, different $Z$ → **isobars**.

---

<a id="b3"></a>
### B3

> ❓ **Question.** Find the frequency of light of wavelength $600\ \mathrm{nm}$.

**✅ Answer.** $\nu = \dfrac{c}{\lambda} = \dfrac{3\times10^8}{600\times10^{-9}} = \boxed{5\times10^{14}\ \mathrm{Hz}}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** Find the energy of one photon of wavelength $400\ \mathrm{nm}$ (in eV).

**✅ Answer.** $E = \dfrac{1240}{400} = \boxed{3.1\ \mathrm{eV}}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** Find the radius of the 2nd Bohr orbit of hydrogen.

**✅ Answer.** $r = 0.529\,n^2 = 0.529(4) = \boxed{2.116\ \text{Å}}$.

---

<a id="b6"></a>
### B6

> ❓ **Question.** Find the energy of the electron in the ground state ($n=1$) of hydrogen.

**✅ Answer.** $E_1 = -13.6/1 = \boxed{-13.6\ \mathrm{eV}}$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** What is the ionisation energy of hydrogen from its ground state?

**✅ Answer.** $E_\infty - E_1 = 0 - (-13.6) = \boxed{13.6\ \mathrm{eV}}$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** How many orbitals are in the $n = 3$ shell?

**✅ Answer.** $n^2 = 3^2 = \boxed{9}$ orbitals ($3s + 3p + 3d = 1+3+5$).

---

<a id="b9"></a>
### B9

> ❓ **Question.** What is the maximum number of electrons in the $n = 4$ shell?

**✅ Answer.** $2n^2 = 2(16) = \boxed{32}$.

---

<a id="b10"></a>
### B10

> ❓ **Question.** Write the ground-state electronic configuration of nitrogen ($Z = 7$).

**✅ Answer.** $1s^2\,2s^2\,2p^3$ (the three $2p$ electrons singly occupy each $p$ orbital — Hund's rule).

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** Find the energy released when an electron in hydrogen falls from $n = 3$ to $n = 2$.

> [!TIP]
> 🧭 **Strategy.** $\Delta E = 13.6\left(\dfrac{1}{n_1^2} - \dfrac{1}{n_2^2}\right)$ eV for H.

**Steps.** $\Delta E = 13.6\left(\dfrac14 - \dfrac19\right) = 13.6\left(\dfrac{5}{36}\right) = 1.89\ \mathrm{eV}$.

**✅ Answer.** $\approx 1.89\ \mathrm{eV}$ (a Balmer line, visible — H-alpha).

---

<a id="m2"></a>
### M2

> ❓ **Question.** Find the wavelength of the photon emitted in the $n=2 \to n=1$ transition of hydrogen.

> [!TIP]
> 🧭 **Strategy.** Get $\Delta E$ in eV, then $\lambda(\text{nm}) = 1240/E$.

**Steps.** $\Delta E = 13.6(1 - \tfrac14) = 10.2\ \mathrm{eV}$; $\lambda = 1240/10.2$.

**✅ Answer.** $\lambda \approx 121.6\ \mathrm{nm}$ (Lyman-alpha, UV).

---

<a id="m3"></a>
### M3

> ❓ **Question.** Find the energy of the electron in the 2nd orbit of He⁺ ($Z = 2$).

> [!TIP]
> 🧭 **Strategy.** $E_n = -13.6\,Z^2/n^2$.

**Steps.** $E = -13.6(4)/4 = -13.6\ \mathrm{eV}$.

**✅ Answer.** $-13.6\ \mathrm{eV}$ (same as H ground state — note $Z^2/n^2 = 1$).

---

<a id="m4"></a>
### M4

> ❓ **Question.** Calculate the de Broglie wavelength of an electron moving at $2.18\times10^6\ \mathrm{m/s}$. ($m_e = 9.1\times10^{-31}$ kg)

> [!TIP]
> 🧭 **Strategy.** $\lambda = h/(mv)$.

**Steps.** $\lambda = \dfrac{6.626\times10^{-34}}{(9.1\times10^{-31})(2.18\times10^6)} = \dfrac{6.626\times10^{-34}}{1.98\times10^{-24}}$.

**✅ Answer.** $\lambda \approx 3.34\times10^{-10}\ \mathrm{m} = 3.34\ \text{Å}$.

---

<a id="m5"></a>
### M5

> ❓ **Question.** A metal has work function $2\ \mathrm{eV}$. Light of $3.1\ \mathrm{eV}$ falls on it. Find the maximum KE of ejected electrons.

> [!TIP]
> 🧭 **Strategy.** $KE_{\max} = h\nu - W_0$.

**Steps.** $KE = 3.1 - 2 = 1.1\ \mathrm{eV}$.

**✅ Answer.** $1.1\ \mathrm{eV}$.

---

<a id="m6"></a>
### M6

> ❓ **Question.** Find the threshold wavelength for a metal with work function $3.1\ \mathrm{eV}$.

> [!TIP]
> 🧭 **Strategy.** At threshold, photon energy = work function: $\lambda_0 = 1240/W_0$ (nm).

**Steps.** $\lambda_0 = 1240/3.1 = 400\ \mathrm{nm}$.

**✅ Answer.** $400\ \mathrm{nm}$ (longer wavelengths won't eject electrons).

---

<a id="m7"></a>
### M7

> ❓ **Question.** Which set of quantum numbers is **not** allowed: (a) $n=2, l=1, m_l=0$; (b) $n=2, l=2, m_l=1$; (c) $n=3, l=2, m_l=-2$?

> [!TIP]
> 🧭 **Strategy.** $l$ ranges $0$ to $n-1$; $m_l$ ranges $-l$ to $+l$.

**Steps.** (b) has $l = 2$ with $n = 2$, but $l$ max is $n-1 = 1$. Not allowed.

**✅ Answer.** **(b)** is invalid.

---

<a id="m8"></a>
### M8

> ❓ **Question.** How many electrons in an atom can have $n = 3, l = 2$?

> [!TIP]
> 🧭 **Strategy.** $n=3, l=2$ is the $3d$ subshell; electrons $= 2(2l+1)$.

**Steps.** $2(2\cdot2+1) = 2(5) = 10$.

**✅ Answer.** $10$ electrons.

---

<a id="m9"></a>
### M9

> ❓ **Question.** Write the electronic configuration of chromium ($Z = 24$).

> [!TIP]
> 🧭 **Strategy.** Expect the half-filled-stability exception.

**Steps.** $[\text{Ar}]3d^5 4s^1$ (not $3d^4 4s^2$) — a half-filled $3d$ is extra stable.

**✅ Answer.** $[\text{Ar}]\,3d^5\,4s^1$.

---

<a id="m10"></a>
### M10

> ❓ **Question.** Write the configuration of the Fe²⁺ ion ($Z$ of Fe $= 26$).

> [!TIP]
> 🧭 **Strategy.** Write Fe first, then remove electrons from the **highest $n$ (4s) first**.

**Steps.** Fe $= [\text{Ar}]3d^6 4s^2$; remove two $4s$: Fe²⁺ $= [\text{Ar}]3d^6$.

**✅ Answer.** $[\text{Ar}]\,3d^6$.

---

<a id="m11"></a>
### M11

> ❓ **Question.** Find the number of spectral lines produced when electrons de-excite from $n = 4$ to $n = 1$.

> [!TIP]
> 🧭 **Strategy.** Lines $= \dfrac{n(n-1)}{2}$ for de-excitation to ground from level $n$.

**Steps.** $\dfrac{4(3)}{2} = 6$.

**✅ Answer.** $6$ lines.

---

<a id="m12"></a>
### M12

> ❓ **Question.** The wavelength of the first Balmer line ($n=3\to2$) — find its wavenumber using the Rydberg formula.

> [!TIP]
> 🧭 **Strategy.** $\bar\nu = R_H\left(\dfrac{1}{2^2} - \dfrac{1}{3^2}\right)$.

**Steps.** $\bar\nu = 1.097\times10^7\left(\dfrac14 - \dfrac19\right) = 1.097\times10^7(0.1389) = 1.524\times10^6\ \mathrm{m^{-1}}$.

**✅ Answer.** $\bar\nu \approx 1.52\times10^6\ \mathrm{m^{-1}}$ ($\lambda \approx 656\ \mathrm{nm}$).

---

<a id="m13"></a>
### M13

> ❓ **Question.** Find the velocity of the electron in the 3rd Bohr orbit of hydrogen.

> [!TIP]
> 🧭 **Strategy.** $v_n = 2.18\times10^6\,Z/n$ m/s.

**Steps.** $v_3 = 2.18\times10^6/3$.

**✅ Answer.** $\approx 7.27\times10^5\ \mathrm{m/s}$.

---

<a id="m14"></a>
### M14

> ❓ **Question.** The uncertainty in position of an electron is $1\ \text{Å}$. Find the minimum uncertainty in its velocity. ($m_e = 9.1\times10^{-31}$ kg)

> [!TIP]
> 🧭 **Strategy.** $\Delta v \ge \dfrac{h}{4\pi m\,\Delta x}$.

**Steps.** $\Delta v = \dfrac{6.626\times10^{-34}}{4\pi(9.1\times10^{-31})(10^{-10})} = \dfrac{6.626\times10^{-34}}{1.143\times10^{-39}}$.

**✅ Answer.** $\Delta v \approx 5.8\times10^5\ \mathrm{m/s}$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** How many unpaired electrons are in the ground state of iron ($Z = 26$)?

> [!TIP]
> 🧭 **Strategy.** Configuration $[\text{Ar}]3d^6 4s^2$; apply Hund's rule to the $3d^6$.

**Steps.** $3d^6$: five orbitals, six electrons → one orbital paired, four singly occupied.

**✅ Answer.** $4$ unpaired electrons.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** Find the shortest wavelength (series limit) of the Lyman series of hydrogen.

> [!TIP]
> 🧭 **Strategy.** Series limit: $n_2 \to \infty$, $n_1 = 1$. $\bar\nu = R_H(1)$.

**Steps.** $\bar\nu = 1.097\times10^7\ \mathrm{m^{-1}} \Rightarrow \lambda = 1/\bar\nu = 9.11\times10^{-8}\ \mathrm{m}$.

**✅ Answer.** $\lambda \approx 91.2\ \mathrm{nm}$.

---

<a id="a2"></a>
### A2

> ❓ **Question.** Find the number of radial and angular nodes in a $4d$ orbital.

> [!TIP]
> 🧭 **Strategy.** Radial $= n-l-1$; angular $= l$; total $= n-1$.

**Steps.** $n=4, l=2$: radial $= 4-2-1 = 1$; angular $= 2$; total $= 3$.

**✅ Answer.** $1$ radial node, $2$ angular nodes ($3$ total).

---

<a id="a3"></a>
### A3

> ❓ **Question.** The ionisation energy of He⁺ (from ground state) — find it.

> [!TIP]
> 🧭 **Strategy.** $IE = 13.6\,Z^2/n^2$ from $n=1$; $Z = 2$.

**Steps.** $IE = 13.6(4)/1 = 54.4\ \mathrm{eV}$.

**✅ Answer.** $54.4\ \mathrm{eV}$ (4× hydrogen).

---

<a id="a4"></a>
### A4

> ❓ **Question.** Find the de Broglie wavelength of an electron accelerated through $100\ \mathrm{V}$.

> [!TIP]
> 🧭 **Strategy.** $\lambda = \dfrac{12.27}{\sqrt{V}}\ \text{Å}$.

**Steps.** $\lambda = 12.27/\sqrt{100} = 12.27/10$.

**✅ Answer.** $\lambda \approx 1.227\ \text{Å}$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** An electron drops from $n=5$ to $n=2$ in hydrogen. Find the wavelength of the emitted photon.

> [!TIP]
> 🧭 **Strategy.** $\Delta E = 13.6(1/4 - 1/25)$ eV, then $\lambda = 1240/\Delta E$ nm.

**Steps.** $\Delta E = 13.6(0.25 - 0.04) = 13.6(0.21) = 2.856\ \mathrm{eV}$; $\lambda = 1240/2.856$.

**✅ Answer.** $\lambda \approx 434\ \mathrm{nm}$ (a Balmer line, violet).

---

<a id="a6"></a>
### A6

> ❓ **Question.** A photon of $\lambda = 200\ \mathrm{nm}$ ejects an electron from a metal with work function $4\ \mathrm{eV}$. Find the stopping potential.

> [!TIP]
> 🧭 **Strategy.** $E_{\text{photon}} = 1240/\lambda$; $KE_{\max} = E - W_0$; $V_0 = KE_{\max}/e$ (in volts, with $KE$ in eV).

**Steps.** $E = 1240/200 = 6.2\ \mathrm{eV}$; $KE = 6.2 - 4 = 2.2\ \mathrm{eV}$; $V_0 = 2.2\ \mathrm{V}$.

**✅ Answer.** Stopping potential $= 2.2\ \mathrm{V}$.

---

<a id="a7"></a>
### A7

> ❓ **Question.** The energy required to excite a hydrogen electron from $n=1$ to $n=2$ — find it, and compare with the energy to go from $n=2$ to $n=3$.

> [!TIP]
> 🧭 **Strategy.** Use $\Delta E = 13.6(1/n_1^2 - 1/n_2^2)$ for each.

**Steps.** $1\to2$: $13.6(1 - 1/4) = 10.2\ \mathrm{eV}$. $2\to3$: $13.6(1/4 - 1/9) = 1.89\ \mathrm{eV}$.

**✅ Answer.** $10.2\ \mathrm{eV}$ vs $1.89\ \mathrm{eV}$ — levels crowd together at higher $n$, so jumps need less energy.

---

<a id="a8"></a>
### A8

> ❓ **Question.** Give the four quantum numbers of the last (differentiating) electron of phosphorus ($Z = 15$).

> [!TIP]
> 🧭 **Strategy.** Configuration $1s^2 2s^2 2p^6 3s^2 3p^3$; the last electron is the 3rd in $3p$ (Hund → singly filled, $m_l = +1$ by convention).

**Steps.** $n=3, l=1$ (p), $m_l = +1$ (third of $-1,0,+1$), $m_s = +\tfrac12$.

**✅ Answer.** $(3,\ 1,\ +1,\ +\tfrac12)$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** Find the wavelength associated with a cricket ball of mass $0.15\ \mathrm{kg}$ moving at $40\ \mathrm{m/s}$, and comment.

> [!TIP]
> 🧭 **Strategy.** $\lambda = h/(mv)$ — expect an absurdly tiny value.

**Steps.** $\lambda = \dfrac{6.626\times10^{-34}}{0.15(40)} = \dfrac{6.626\times10^{-34}}{6}$.

**✅ Answer.** $\lambda \approx 1.1\times10^{-34}\ \mathrm{m}$ — immeasurably small, so wave nature is irrelevant for macroscopic objects.

---

<a id="a10"></a>
### A10

> ❓ **Question.** Copper has $Z = 29$. Write its configuration, and that of Cu²⁺, and give the number of unpaired electrons in Cu²⁺.

> [!TIP]
> 🧭 **Strategy.** Cu is a fully-filled-stability exception; for the ion remove 4s first, then 3d.

**Steps.** Cu $= [\text{Ar}]3d^{10}4s^1$. Cu²⁺: remove the $4s^1$ and one $3d$ → $[\text{Ar}]3d^9$, which has one unpaired electron.

**✅ Answer.** Cu $= [\text{Ar}]3d^{10}4s^1$; Cu²⁺ $= [\text{Ar}]3d^9$; **1** unpaired electron.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style, and tag each
> with its difficulty and sub-topic (Bohr / spectra / dual nature / quantum numbers / configuration).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <bohr/spectra/dual/quantum/config>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
