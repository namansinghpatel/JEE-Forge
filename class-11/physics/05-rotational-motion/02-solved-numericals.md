# Rotational Motion — Solved Numericals

> **35 fully worked problems** · Basic (10) · Medium (15) · Advanced (10)
> Take $g = 10\ \mathrm{m/s^2}$ unless stated otherwise. Redo each on paper before reading the solution.
>
> **How to read a solution:** every problem has a **❓ Question**, then the worked **Solution**, then a boxed **✅ Answer**. Medium and advanced problems also start with a **🧭 Strategy** line (how to recognise the method) and are broken into numbered **Steps**, so you learn *how to attack it in the exam*, not just the final number.

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

## 📑 Index

**🟢 Basic** —
[B1](#b1) rpm→rad/s ·
[B2](#b2) const. α ·
[B3](#b3) I of sphere ·
[B4](#b4) torque ·
[B5](#b5) α from τ ·
[B6](#b6) rotational KE ·
[B7](#b7) centre of mass ·
[B8](#b8) rolling ring KE ·
[B9](#b9) radius of gyration ·
[B10](#b10) L of particle

**🟡 Medium** —
[M1](#m1) parallel axis ·
[M2](#m2) rod about end ·
[M3](#m3) cylinder on incline ·
[M4](#m4) skater ·
[M5](#m5) decelerating flywheel ·
[M6](#m6) ring diameter ·
[M7](#m7) point masses ·
[M8](#m8) pulley + block ·
[M9](#m9) ring on disc ·
[M10](#m10) braking torque ·
[M11](#m11) sphere race ·
[M12](#m12) falling rod ·
[M13](#m13) disc with hole ·
[M14](#m14) straight-line L ·
[M15](#m15) rotational KE fraction

**🔴 Advanced** —
[A1](#a1) hinged rod ·
[A2](#a2) walk to centre ·
[A3](#a3) unwinding cylinder ·
[A4](#a4) bullet + rod ·
[A5](#a5) slide→roll ·
[A6](#a6) roll up incline ·
[A7](#a7) clutch ·
[A8](#a8) ladder ·
[A9](#a9) massive-pulley Atwood ·
[A10](#a10) loop-the-loop

**⭐ My own:** [JEE Questions by Me](#jee-questions-by-me)

---

## 🟢 Basic (foundation / board level)

<a id="b1"></a>
### B1 — rpm to rad/s
**❓ Question.** A wheel rotates at **300 rpm**. Find its angular velocity in rad/s.

**Solution.** $1\ \text{revolution} = 2\pi\ \text{rad}$ and $1\ \text{min} = 60\ \text{s}$:
$$\omega = 300\times\frac{2\pi}{60} = 10\pi$$

**✅ Answer:** $\boxed{\omega \approx 31.4\ \mathrm{rad/s}}$

---

<a id="b2"></a>
### B2 — constant angular acceleration
**❓ Question.** A flywheel starts from rest and reaches $120\ \mathrm{rad/s}$ in $8\ \mathrm{s}$ at constant $\alpha$. Find $\alpha$ and the angle turned.

**Solution.**
$$\alpha = \frac{\omega-\omega_0}{t} = \frac{120-0}{8} = 15\ \mathrm{rad/s^2}$$
$$\theta = \omega_0 t + \tfrac12\alpha t^2 = 0 + \tfrac12(15)(8)^2 = 480\ \text{rad}$$

**✅ Answer:** $\boxed{\alpha = 15\ \mathrm{rad/s^2},\quad \theta = 480\ \text{rad}}$

---

<a id="b3"></a>
### B3 — moment of inertia of a sphere
**❓ Question.** A solid sphere has mass $2\ \text{kg}$ and radius $0.1\ \text{m}$. Find $I$ about a diameter.

**Solution.**
$$I = \tfrac25 MR^2 = \tfrac25(2)(0.1)^2 = \tfrac25(2)(0.01)$$

**✅ Answer:** $\boxed{I = 8\times10^{-3}\ \mathrm{kg\cdot m^2}}$

---

<a id="b4"></a>
### B4 — torque from a tangential force
**❓ Question.** A force of $10\ \text{N}$ is applied tangentially at the rim of a disc of radius $0.5\ \text{m}$. Find the torque about the centre.

**Solution.** Tangential force ⟹ moment arm $=R$:
$$\tau = F\,r_\perp = 10\times0.5$$

**✅ Answer:** $\boxed{\tau = 5\ \mathrm{N\cdot m}}$

---

<a id="b5"></a>
### B5 — angular acceleration from torque
**❓ Question.** A torque of $20\ \mathrm{N\cdot m}$ acts on a body of $I = 4\ \mathrm{kg\cdot m^2}$. Find $\alpha$.

**Solution.** $\tau = I\alpha \Rightarrow \alpha = \tau/I = 20/4$.

**✅ Answer:** $\boxed{\alpha = 5\ \mathrm{rad/s^2}}$

---

<a id="b6"></a>
### B6 — rotational kinetic energy
**❓ Question.** A disc ($M=4\ \text{kg}$, $R=0.2\ \text{m}$) spins at $\omega = 10\ \mathrm{rad/s}$. Find its rotational KE.

**Solution.**
$$I = \tfrac12 MR^2 = \tfrac12(4)(0.2)^2 = 0.08\ \mathrm{kg\cdot m^2}$$
$$K = \tfrac12 I\omega^2 = \tfrac12(0.08)(10)^2$$

**✅ Answer:** $\boxed{K = 4\ \text{J}}$

---

<a id="b7"></a>
### B7 — centre of mass of two particles
**❓ Question.** Masses $2\ \text{kg}$ at $x=0$ and $3\ \text{kg}$ at $x=5\ \text{m}$. Find the COM.

**Solution.**
$$x_{cm} = \frac{m_1x_1+m_2x_2}{m_1+m_2} = \frac{2(0)+3(5)}{2+3} = \frac{15}{5}$$

**✅ Answer:** $\boxed{x_{cm} = 3\ \text{m}}$ (closer to the heavier mass, as expected)

---

<a id="b8"></a>
### B8 — KE of a rolling ring
**❓ Question.** A ring ($M=1\ \text{kg}$, $R=0.5\ \text{m}$) rolls without slipping at $v = 2\ \mathrm{m/s}$. Find total KE.

**Solution.** For a ring $k^2/R^2 = 1$:
$$K = \tfrac12 Mv^2\left(1+\tfrac{k^2}{R^2}\right) = \tfrac12(1)(2)^2(1+1)$$

**✅ Answer:** $\boxed{K = 4\ \text{J}}$ (half translational, half rotational)

---

<a id="b9"></a>
### B9 — radius of gyration
**❓ Question.** Find the radius of gyration of a disc of radius $0.4\ \text{m}$ about its central axis.

**Solution.** $I = \tfrac12 MR^2 = Mk^2 \Rightarrow k = R/\sqrt2$:
$$k = \frac{0.4}{1.414}$$

**✅ Answer:** $\boxed{k \approx 0.283\ \text{m}}$

---

<a id="b10"></a>
### B10 — angular momentum of a particle
**❓ Question.** A $0.5\ \text{kg}$ particle moves at $4\ \mathrm{m/s}$, its line of motion passing $2\ \text{m}$ from the axis. Find $L$.

**Solution.** $L = mvr_\perp = 0.5\times4\times2$.

**✅ Answer:** $\boxed{L = 4\ \mathrm{kg\cdot m^2/s}}$

---

## 🟡 Medium (JEE Main level)

<a id="m1"></a>
### M1 — parallel axis theorem
**❓ Question.** A disc ($M=2\ \text{kg}$, $R=0.3\ \text{m}$). Find $I$ about an axis **tangent to the rim and perpendicular to the plane**.

**🧭 Strategy.** The axis is parallel to the central ⟂ axis (through COM) but shifted by $d=R$. That is exactly the parallel-axis theorem $I = I_{cm}+Md^2$.

**Step 1 — $I$ about the COM axis.**
$$I_{cm} = \tfrac12 MR^2 = \tfrac12(2)(0.3)^2 = 0.09\ \mathrm{kg\cdot m^2}$$
**Step 2 — shift the axis by $d=R=0.3$ m.**
$$I = I_{cm} + Md^2 = 0.09 + 2(0.3)^2 = 0.09 + 0.18$$

**✅ Answer:** $\boxed{I = 0.27\ \mathrm{kg\cdot m^2}}$ (i.e. $\tfrac32 MR^2$)

> **Exam tip:** "tangent + perpendicular to plane" = parallel axis with $d=R$. "Tangent in the plane" would instead start from the *diameter* value $\tfrac14 MR^2$.

---

<a id="m2"></a>
### M2 — rod about its end
**❓ Question.** A rod of length $1\ \text{m}$, mass $3\ \text{kg}$, axis through one end ⟂ to rod. Find $I$.

**🧭 Strategy.** Use the standard end-axis result directly — or derive it from the centre value with parallel axis ($I_{end}=\tfrac1{12}ML^2 + M(L/2)^2 = \tfrac13 ML^2$).

**Step 1.** $I = \tfrac13 ML^2 = \tfrac13(3)(1)^2$.

**✅ Answer:** $\boxed{I = 1\ \mathrm{kg\cdot m^2}}$

---

<a id="m3"></a>
### M3 — cylinder rolling down an incline
**❓ Question.** A solid cylinder rolls without slipping down a $30°$ incline. Find $a_{cm}$.

**🧭 Strategy.** For any body rolling without slipping down an incline, $a_{cm} = \dfrac{g\sin\theta}{1+k^2/R^2}$. Identify the shape factor and plug in.

**Step 1 — shape factor.** Solid cylinder: $k^2/R^2 = 1/2$.
**Step 2 — substitute** ($\sin30° = 0.5$):
$$a_{cm} = \frac{g\sin\theta}{1+k^2/R^2} = \frac{10(0.5)}{1+0.5} = \frac{5}{1.5}$$

**✅ Answer:** $\boxed{a_{cm} \approx 3.33\ \mathrm{m/s^2}}$

> **Exam tip:** The acceleration is independent of mass and radius — only the shape factor matters.

---

<a id="m4"></a>
### M4 — skater pulls arms in
**❓ Question.** A skater with $I_1 = 6\ \mathrm{kg\cdot m^2}$ spins at $\omega_1 = 2\ \mathrm{rad/s}$, then pulls arms in to $I_2 = 2\ \mathrm{kg\cdot m^2}$. Find $\omega_2$ and the change in KE.

**🧭 Strategy.** No external torque about the spin axis ⟹ **angular momentum is conserved**. KE is *not* — compute it before and after separately.

**Step 1 — conserve $L$.**
$$I_1\omega_1 = I_2\omega_2 \Rightarrow \omega_2 = \frac{6\times2}{2} = 6\ \mathrm{rad/s}$$
**Step 2 — compare KE.**
$$K_1 = \tfrac12 I_1\omega_1^2 = \tfrac12(6)(2)^2 = 12\ \text{J}, \qquad K_2 = \tfrac12 I_2\omega_2^2 = \tfrac12(2)(6)^2 = 36\ \text{J}$$

**✅ Answer:** $\boxed{\omega_2 = 6\ \mathrm{rad/s},\quad \Delta K = +24\ \text{J}}$ — the extra energy is the muscular work done pulling the arms in.

> **Exam tip:** Whenever something is "pulled in / dropped on / walks in", first write $L_i = L_f$. Never equate kinetic energies across such an event.

---

<a id="m5"></a>
### M5 — decelerating flywheel
**❓ Question.** A flywheel ($I = 0.5\ \mathrm{kg\cdot m^2}$) slows from $60\ \mathrm{rad/s}$ to rest in $30\ \mathrm{s}$. Find the retarding torque and the number of revolutions.

**🧭 Strategy.** Constant deceleration: find $\alpha$ from $\omega$–$t$, then $\tau=I\alpha$, then the angle from $\omega^2 = \omega_0^2 - 2\alpha\theta$, and convert radians to revolutions.

**Step 1 — angular deceleration.** $\alpha = \dfrac{0-60}{30} = -2\ \mathrm{rad/s^2}$.
**Step 2 — torque.** $|\tau| = I|\alpha| = 0.5\times2 = 1\ \mathrm{N\cdot m}$.
**Step 3 — angle, then revolutions.**
$$\theta = \frac{\omega_0^2}{2|\alpha|} = \frac{60^2}{2(2)} = 900\ \text{rad}, \qquad n = \frac{\theta}{2\pi} = \frac{900}{6.283} \approx 143$$

**✅ Answer:** $\boxed{|\tau| = 1\ \mathrm{N\cdot m},\quad n \approx 143\ \text{revolutions}}$

---

<a id="m6"></a>
### M6 — ring about a diameter (perpendicular axis theorem)
**❓ Question.** Ring $M = 0.5\ \text{kg}$, $R = 0.2\ \text{m}$. Find $I$ about a diameter.

**🧭 Strategy.** A ring is a flat lamina, so the perpendicular-axis theorem applies: $I_z = I_x + I_y$, and the two in-plane diameters are equal by symmetry.

**Step 1.** $I_z$ (⟂ to plane) $= MR^2$.
**Step 2.** $I_x = I_y$ and $I_z = I_x + I_y = 2I_x \Rightarrow I_{diameter} = \tfrac12 MR^2 = \tfrac12(0.5)(0.2)^2$.

**✅ Answer:** $\boxed{I = 0.01\ \mathrm{kg\cdot m^2}}$

> **Exam tip:** Perpendicular-axis theorem works **only for laminae** (ring, disc, plate), never for a sphere or solid cylinder.

---

<a id="m7"></a>
### M7 — two point masses on a rod
**❓ Question.** Point masses $2\ \text{kg}$ at $0.5\ \text{m}$ and $3\ \text{kg}$ at $1\ \text{m}$ from an axis (massless rod). Find $I$.

**🧭 Strategy.** For point masses, $I = \sum m_i r_i^2$ — just add $mr^2$ for each.

**Step 1.** $I = 2(0.5)^2 + 3(1)^2 = 0.5 + 3$.

**✅ Answer:** $\boxed{I = 3.5\ \mathrm{kg\cdot m^2}}$

---

<a id="m8"></a>
### M8 — mass on a string over a disc pulley
**❓ Question.** A block of $1\ \text{kg}$ hangs from a string wound over a disc pulley ($M = 2\ \text{kg}$, $R = 0.1\ \text{m}$). Find the acceleration and string tension.

**🧭 Strategy.** Two free-body diagrams — block (translation) and pulley (rotation) — linked by the rolling constraint $a = R\alpha$ and the same tension $T$.

**Step 1 — block:** $mg - T = ma$.
**Step 2 — pulley:** $TR = I\alpha = \left(\tfrac12 MR^2\right)\dfrac{a}{R} \Rightarrow T = \tfrac12 Ma$.
**Step 3 — combine:**
$$mg = ma + \tfrac12 Ma \Rightarrow a = \frac{mg}{m + M/2} = \frac{1(10)}{1+1} = 5\ \mathrm{m/s^2}$$
**Step 4 — tension:** $T = \tfrac12 Ma = \tfrac12(2)(5) = 5\ \text{N}$.

**✅ Answer:** $\boxed{a = 5\ \mathrm{m/s^2},\quad T = 5\ \text{N}}$

> **Exam tip:** A massive pulley makes $T \ne mg$. The term $M/2$ (for a disc) is the pulley's "effective mass" added to the system.

---

<a id="m9"></a>
### M9 — ring dropped on a spinning disc
**❓ Question.** A disc ($I = 0.2\ \mathrm{kg\cdot m^2}$) spins at $50\ \mathrm{rad/s}$. A ring ($I = 0.3\ \mathrm{kg\cdot m^2}$) is gently dropped coaxially onto it. Find the common angular velocity.

**🧭 Strategy.** Internal friction brings them to a common $\omega$; there is no *external* torque, so conserve $L$ (energy is lost to friction).

**Step 1.**
$$I_1\omega_1 = (I_1+I_2)\omega \Rightarrow \omega = \frac{0.2\times50}{0.2+0.3} = \frac{10}{0.5}$$

**✅ Answer:** $\boxed{\omega = 20\ \mathrm{rad/s}}$

---

<a id="m10"></a>
### M10 — torque to stop a wheel in a given number of turns
**❓ Question.** A wheel ($I = 4\ \mathrm{kg\cdot m^2}$) rotating at $20\ \mathrm{rad/s}$ is stopped in $10\ \text{revolutions}$. Find the braking torque.

**🧭 Strategy.** Convert revolutions to radians, find $\alpha$ from $\omega^2 = \omega_0^2 - 2\alpha\theta$, then $\tau = I\alpha$.

**Step 1 — angle.** $\theta = 10\times2\pi = 62.83\ \text{rad}$.
**Step 2 — deceleration.** $|\alpha| = \dfrac{\omega_0^2}{2\theta} = \dfrac{20^2}{2(62.83)} = 3.18\ \mathrm{rad/s^2}$.
**Step 3 — torque.** $|\tau| = I|\alpha| = 4\times3.18$.

**✅ Answer:** $\boxed{|\tau| \approx 12.7\ \mathrm{N\cdot m}}$

---

<a id="m11"></a>
### M11 — solid vs hollow sphere race
**❓ Question.** Find the ratio of accelerations of a solid sphere and a hollow sphere rolling down the same incline.

**🧭 Strategy.** $a \propto \dfrac{1}{1+k^2/R^2}$; take the ratio so $g\sin\theta$ cancels.

**Step 1.** Solid $k^2/R^2 = 2/5$; hollow $k^2/R^2 = 2/3$.
**Step 2.**
$$\frac{a_{solid}}{a_{hollow}} = \frac{1+2/3}{1+2/5} = \frac{5/3}{7/5} = \frac{25}{21}$$

**✅ Answer:** $\boxed{\dfrac{a_{solid}}{a_{hollow}} = \dfrac{25}{21} \approx 1.19}$ — the solid sphere is faster.

---

<a id="m12"></a>
### M12 — falling rod, angular velocity at the bottom
**❓ Question.** A rod ($L = 1.2\ \text{m}$) is pivoted at one end, held horizontal, and released. Find $\omega$ when it is vertical.

**🧭 Strategy.** Energy conservation about the pivot: the loss in gravitational PE of the COM equals the rotational KE. (The pivot does no work.)

**Step 1 — PE lost.** COM drops by $L/2$: $\Delta U = Mg\dfrac{L}{2}$.
**Step 2 — equate to rotational KE**, with $I = \tfrac13 ML^2$:
$$Mg\frac{L}{2} = \tfrac12\left(\tfrac13 ML^2\right)\omega^2 \Rightarrow \omega = \sqrt{\frac{3g}{L}} = \sqrt{\frac{3(10)}{1.2}} = \sqrt{25}$$

**✅ Answer:** $\boxed{\omega = 5\ \mathrm{rad/s}}$

> **Exam tip:** Use rotational KE $\tfrac12 I\omega^2$ about the pivot — do **not** use $\tfrac12 mv^2$ of the COM alone; that misses the spin.

---

<a id="m13"></a>
### M13 — COM of a disc with a hole
**❓ Question.** From a disc of radius $R$, a disc of radius $R/2$ is removed, its edge touching the big disc's edge (centre of hole at $R/2$ from centre). Find the new COM.

**🧭 Strategy.** Treat the hole as **negative mass**. Mass $\propto$ area, so a radius-$R/2$ hole has $1/4$ the mass of the full disc.

**Step 1 — masses & positions.** Full disc mass $M$ at $x=0$; removed mass $m = M/4$ at $x = R/2$.
**Step 2 — COM with negative mass.**
$$x_{cm} = \frac{M(0) - \tfrac{M}{4}\cdot\tfrac{R}{2}}{M - \tfrac{M}{4}} = \frac{-MR/8}{3M/4} = -\frac{R}{6}$$

**✅ Answer:** $\boxed{x_{cm} = -\dfrac{R}{6}}$ — the COM shifts $R/6$ from the centre, **away** from the hole.

---

<a id="m14"></a>
### M14 — angular momentum of a particle in straight-line motion
**❓ Question.** A particle ($m = 2\ \text{kg}$) moves in a straight line at $3\ \mathrm{m/s}$; the line is $4\ \text{m}$ from point O. Find its angular momentum about O and state whether it changes.

**🧭 Strategy.** $L = mvr_\perp$ where $r_\perp$ is the (constant) perpendicular distance from O to the line of motion. Check for any torque.

**Step 1.** $L = mvr_\perp = 2\times3\times4 = 24$.
**Step 2.** No force acts ⟹ no torque about O ⟹ $L$ is constant even though the particle moves in a straight line.

**✅ Answer:** $\boxed{L = 24\ \mathrm{kg\cdot m^2/s},\ \text{constant}}$

---

<a id="m15"></a>
### M15 — rotational fraction of rolling KE
**❓ Question.** What fraction of a rolling solid cylinder's total KE is rotational?

**🧭 Strategy.** Write both KE parts in terms of $v$ using $\omega = v/R$; the fraction depends only on $I/MR^2$.

**Step 1.**
$$\frac{K_{rot}}{K_{total}} = \frac{\tfrac12 I\omega^2}{\tfrac12 Mv^2 + \tfrac12 I\omega^2} = \frac{I/MR^2}{1+I/MR^2}$$
**Step 2.** Solid cylinder $I/MR^2 = 1/2$:
$$= \frac{1/2}{1+1/2} = \frac13$$

**✅ Answer:** $\boxed{\tfrac13 \approx 33.3\%}$

---

## 🔴 Advanced (JEE Advanced level)

<a id="a1"></a>
### A1 — rod released from horizontal (pivot force)
**❓ Question.** A uniform rod ($M$, length $L$) is pivoted at one end and released from horizontal. Find, at the instant of release: (a) $\alpha$, (b) linear acceleration of the free end, (c) the vertical force exerted by the pivot.

**🧭 Strategy.** Take torque about the pivot (kills the unknown pivot force) to get $\alpha$. Then the COM acceleration gives the pivot force via Newton's 2nd law on the whole rod.

**Step 1 — angular acceleration.** Weight acts at the COM, distance $L/2$ from pivot:
$$\tau = Mg\frac{L}{2} = I\alpha = \frac{ML^2}{3}\alpha \Rightarrow \alpha = \frac{3g}{2L}$$
**Step 2 — free-end acceleration.** $a_{end} = L\alpha = \dfrac{3g}{2}$.
**Step 3 — COM acceleration.** $a_{cm} = \dfrac{L}{2}\alpha = \dfrac{3g}{4}$ (downward).
**Step 4 — pivot force.** Newton's 2nd law vertically on the rod: $Mg - N = Ma_{cm}$:
$$N = Mg - M\frac{3g}{4} = \frac{Mg}{4}$$

**✅ Answer:** $\boxed{\alpha = \dfrac{3g}{2L},\quad a_{end} = \dfrac{3g}{2},\quad N = \dfrac{Mg}{4}}$

> **Exam tip:** $a_{end} = \tfrac{3g}{2} > g$ — the far end falls *faster* than free fall. A coin resting beyond $2L/3$ from the pivot separates from the rod. This is a favourite conceptual MCQ.

---

<a id="a2"></a>
### A2 — person walks to the centre of a turntable
**❓ Question.** A platform (disc, $I = 100\ \mathrm{kg\cdot m^2}$, $R = 2\ \text{m}$) rotates at $\omega_1 = 2\ \mathrm{rad/s}$. A $50\ \text{kg}$ person stands at the rim and walks to the centre. Find the final $\omega$ and the work done.

**🧭 Strategy.** Treat the person as a point mass $mR^2$ that changes with position. No external torque ⟹ conserve $L$. Work done = change in KE.

**Step 1 — initial and final moments of inertia.**
$$I_1 = 100 + mR^2 = 100 + 50(2)^2 = 300\ \mathrm{kg\cdot m^2}, \qquad I_2 = 100\ \mathrm{kg\cdot m^2}$$
**Step 2 — conserve $L$.** $\omega_2 = \dfrac{I_1\omega_1}{I_2} = \dfrac{300(2)}{100} = 6\ \mathrm{rad/s}$.
**Step 3 — work = ΔKE.**
$$W = \tfrac12 I_2\omega_2^2 - \tfrac12 I_1\omega_1^2 = \tfrac12(100)(36) - \tfrac12(300)(4) = 1800 - 600$$

**✅ Answer:** $\boxed{\omega_2 = 6\ \mathrm{rad/s},\quad W = 1200\ \text{J}}$

---

<a id="a3"></a>
### A3 — cylinder unwinding from a string (vertical)
**❓ Question.** A solid cylinder ($M$, $R$) falls as a light string, fixed at the top, unwinds from it. Find the acceleration of its centre and the string tension.

**🧭 Strategy.** Same two-equation method as a pulley, but now the cylinder *is* the falling body. The constraint is still $a = R\alpha$.

**Step 1 — translation:** $Mg - T = Ma$.
**Step 2 — rotation about COM:** $TR = I\alpha = \left(\tfrac12 MR^2\right)\dfrac{a}{R} \Rightarrow T = \tfrac12 Ma$.
**Step 3 — combine:**
$$Mg = Ma + \tfrac12 Ma \Rightarrow a = \frac{g}{1+1/2} = \frac{2g}{3} \approx 6.67\ \mathrm{m/s^2}$$
**Step 4 — tension:** $T = \tfrac12 Ma = \tfrac12 M\cdot\tfrac{2g}{3} = \dfrac{Mg}{3}$.

**✅ Answer:** $\boxed{a = \dfrac{2g}{3} \approx 6.67\ \mathrm{m/s^2},\quad T = \dfrac{Mg}{3}}$

---

<a id="a4"></a>
### A4 — bullet embeds in a pivoted rod
**❓ Question.** A rod ($M = 1\ \text{kg}$, $L = 1\ \text{m}$) lies on a frictionless table, pivoted at its **centre**. A bullet ($m = 0.01\ \text{kg}$, $v = 200\ \mathrm{m/s}$) strikes one end perpendicularly and embeds. Find the angular velocity afterward.

**🧭 Strategy.** The pivot delivers an unknown impulsive force, so **linear** momentum is *not* conserved — but **angular momentum about the pivot is** (the pivot force has zero moment arm). Set $L$(before) $= L$(after).

**Step 1 — angular momentum before** (bullet only), about the pivot:
$$L_i = m v \frac{L}{2} = 0.01(200)(0.5) = 1\ \mathrm{kg\cdot m^2/s}$$
**Step 2 — moment of inertia after** (rod + embedded bullet at the end):
$$I = \tfrac{1}{12}ML^2 + m\left(\tfrac{L}{2}\right)^2 = 0.0833 + 0.01(0.25) = 0.0858\ \mathrm{kg\cdot m^2}$$
**Step 3 — solve.** $L_i = I\omega \Rightarrow \omega = \dfrac{1}{0.0858}$.

**✅ Answer:** $\boxed{\omega \approx 11.66\ \mathrm{rad/s}}$

> **Exam tip:** Pivoted ⟹ conserve angular momentum, not linear. If the rod were **free** (no pivot), both linear and angular momentum would be conserved and you'd track the COM separately.

---

<a id="a5"></a>
### A5 — sliding ball transitions to rolling
**❓ Question.** A solid sphere is projected along rough ground at $v_0 = 7\ \mathrm{m/s}$ with **no spin**. Find its speed when pure rolling begins.

**🧭 Strategy.** Friction acts backward (slowing $v$) and forward-of-contact (spinning it up). Angular momentum about a point **on the ground** is conserved, because friction acts at that level and has zero moment arm there.

**Step 1 — conserve $L$ about the ground line.**
$$m v_0 R = \left(I_{cm}+mR^2\right)\omega_f = \left(\tfrac25 mR^2 + mR^2\right)\frac{v_f}{R}$$
**Step 2 — simplify.** $v_0 = \tfrac75 v_f \Rightarrow v_f = \tfrac57 v_0 = \tfrac57(7)$.

**✅ Answer:** $\boxed{v_f = 5\ \mathrm{m/s}}$

> **Exam tip:** The clean trick is "angular momentum about a point on the surface." Solving it with forces and time also works but is longer.

---

<a id="a6"></a>
### A6 — cylinder rolls up an incline
**❓ Question.** A solid cylinder rolls without slipping up a $30°$ incline with initial speed $v = 6\ \mathrm{m/s}$. Find the distance travelled up the incline before it stops.

**🧭 Strategy.** Energy conservation: total KE (translation + rotation) converts entirely into gravitational PE. Then convert height to distance along the incline.

**Step 1 — total KE** ($k^2/R^2 = 1/2$):
$$K = \tfrac12 Mv^2\left(1+\tfrac12\right) = \tfrac34 Mv^2$$
**Step 2 — set $K = Mgh$:**
$$h = \frac{v^2(1+1/2)}{2g} = \frac{36(1.5)}{20} = 2.7\ \text{m}$$
**Step 3 — distance up the slope:** $s = \dfrac{h}{\sin30°} = \dfrac{2.7}{0.5}$.

**✅ Answer:** $\boxed{s = 5.4\ \text{m}}$

---

<a id="a7"></a>
### A7 — two spinning discs coupled (clutch)
**❓ Question.** Disc 1 ($I_1 = 2\ \mathrm{kg\cdot m^2}$, $\omega_1 = 50\ \mathrm{rad/s}$) and disc 2 ($I_2 = 4\ \mathrm{kg\cdot m^2}$, $\omega_2 = 20\ \mathrm{rad/s}$), spinning the same way on a common axle, are pushed into contact. Find the common $\omega$ and the energy lost.

**🧭 Strategy.** "Rotational perfectly inelastic collision": conserve $L$ to get the common $\omega$; the lost KE is dissipated as heat at the coupling.

**Step 1 — conserve $L$.**
$$\omega = \frac{I_1\omega_1 + I_2\omega_2}{I_1+I_2} = \frac{2(50)+4(20)}{6} = \frac{180}{6} = 30\ \mathrm{rad/s}$$
**Step 2 — energy lost.**
$$\Delta K = \left[\tfrac12(2)(50)^2 + \tfrac12(4)(20)^2\right] - \tfrac12(6)(30)^2 = (2500+800) - 2700$$

**✅ Answer:** $\boxed{\omega = 30\ \mathrm{rad/s},\quad \Delta K = 600\ \text{J lost}}$

---

<a id="a8"></a>
### A8 — ladder equilibrium (minimum friction)
**❓ Question.** A uniform ladder rests against a **smooth** wall, making angle $\theta$ with the rough floor (coefficient $\mu$). Find the minimum $\mu$ and evaluate for $\theta = 45°$.

**🧭 Strategy.** Static equilibrium: $\sum F_x = 0$, $\sum F_y = 0$, and $\sum\tau = 0$ about the foot (which removes the floor's unknowns). Then apply $f \le \mu N_f$.

**Step 1 — forces.** Wall (smooth) gives horizontal $N_w$. Floor gives vertical $N_f$ and friction $f$.
$$\sum F_y = 0:\ N_f = W \qquad \sum F_x = 0:\ f = N_w$$
**Step 2 — torque about the foot** (weight at midpoint):
$$N_w(L\sin\theta) = W\left(\tfrac{L}{2}\cos\theta\right) \Rightarrow N_w = \tfrac{W}{2}\cot\theta$$
**Step 3 — no-slip condition.** $f \le \mu N_f \Rightarrow \tfrac{W}{2}\cot\theta \le \mu W$:
$$\mu_{min} = \tfrac12\cot\theta$$
**Step 4 — evaluate** at $\theta = 45°$: $\mu_{min} = \tfrac12(1)$.

**✅ Answer:** $\boxed{\mu_{min} = \tfrac12\cot\theta;\quad \mu_{min} = 0.5\ \text{at }45°}$

---

<a id="a9"></a>
### A9 — Atwood machine with a massive pulley
**❓ Question.** Masses $m_1 = 3\ \text{kg}$ and $m_2 = 5\ \text{kg}$ hang over a disc pulley ($M = 4\ \text{kg}$). Find the acceleration and the two tensions. (String does not slip.)

**🧭 Strategy.** Three equations: one per block, one for the pulley rotation. The pulley's inertia makes the two tensions **different**.

**Step 1 — write the equations** ($T_2$ side descends):
$$m_2 g - T_2 = m_2 a, \quad T_1 - m_1 g = m_1 a, \quad (T_2 - T_1)R = \tfrac12 MR^2\frac{a}{R}$$
**Step 2 — add them** (the last gives $T_2 - T_1 = \tfrac12 Ma$):
$$a = \frac{(m_2 - m_1)g}{m_1 + m_2 + M/2} = \frac{2(10)}{3+5+2} = \frac{20}{10} = 2\ \mathrm{m/s^2}$$
**Step 3 — tensions.**
$$T_1 = m_1(g+a) = 3(12) = 36\ \text{N}, \qquad T_2 = m_2(g-a) = 5(8) = 40\ \text{N}$$
**Check:** $T_2 - T_1 = 4 = \tfrac12 Ma = \tfrac12(4)(2)$ ✔.

**✅ Answer:** $\boxed{a = 2\ \mathrm{m/s^2},\quad T_1 = 36\ \text{N},\quad T_2 = 40\ \text{N}}$

---

<a id="a10"></a>
### A10 — rolling sphere completing a vertical loop
**❓ Question.** A solid sphere (radius $\ll$ loop radius $R$) rolls without slipping. Find the minimum height $h$ above the bottom of the loop from which it must start to complete a vertical loop of radius $R$.

**🧭 Strategy.** Two ingredients: (1) the *minimum-speed condition* at the top, where gravity alone supplies the centripetal force; (2) energy conservation from start to top, **including rotational KE**.

**Step 1 — top condition.** $mg = \dfrac{mv_{top}^2}{R} \Rightarrow v_{top}^2 = gR$.
**Step 2 — energy conservation** (rolling KE $= \tfrac12 mv^2\cdot\tfrac75$), top is height $2R$:
$$mgh = mg(2R) + \tfrac12 mv_{top}^2\cdot\tfrac75$$
**Step 3 — solve.**
$$h = 2R + \frac{7}{10}\frac{v_{top}^2}{g} = 2R + \frac{7}{10}R = 2.7R$$

**✅ Answer:** $\boxed{h = 2.7\,R}$

> **Exam tip:** A sliding point mass needs $2.5R$; the extra $0.2R$ is the rotational KE the sphere must also carry. Forgetting rotation is the classic mistake here.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **Your personal log.** Whenever you hit a tough or interesting rotational-motion
> question during practice — a PYQ, a coaching-sheet problem, a doubt from a mock —
> drop it here (or just paste it to Claude) and I'll add it below with a full,
> plain-English, step-by-step solution in the same style as above.
>
> **How to add one:** paste the question and say *"add this to JEE Questions by Me
> in Rotational Motion."* I'll number it **MY-1, MY-2, …**, keep the 🧭 Strategy →
> Steps → ✅ Answer format, and tag the source/year if you tell me.

<!-- New solved questions will be appended below this line. Keep this comment. -->

*(No entries yet — add your first one!)*

---

**Next:** [Practice Range →](./03-practice.md)
