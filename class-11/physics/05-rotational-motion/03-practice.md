# Rotational Motion — Practice Range

> **35 problems to attempt cold** · Basic (10) · Medium (15) · Advanced (10)
> Take $g = 10\ \mathrm{m/s^2}$. **Try first → open 💡 only if stuck → open ✅ only after a real attempt.**
> The 💡 hint gives the **approach** (how to *think* about the problem), not just a formula. These are *different* problems from the solved set — treat them as a self-test.

Related: [Concepts](./01-concepts.md) · [Solved Numericals](./02-solved-numericals.md) · [Formula Recap](./05-formula-recap.md)

---

## 📑 Index

**🟢 Basic:**
[Q1](#q1) · [Q2](#q2) · [Q3](#q3) · [Q4](#q4) · [Q5](#q5) · [Q6](#q6) · [Q7](#q7) · [Q8](#q8) · [Q9](#q9) · [Q10](#q10)

**🟡 Medium:**
[Q11](#q11) · [Q12](#q12) · [Q13](#q13) · [Q14](#q14) · [Q15](#q15) · [Q16](#q16) · [Q17](#q17) · [Q18](#q18) · [Q19](#q19) · [Q20](#q20) · [Q21](#q21) · [Q22](#q22) · [Q23](#q23) · [Q24](#q24) · [Q25](#q25)

**🔴 Advanced:**
[Q26](#q26) · [Q27](#q27) · [Q28](#q28) · [Q29](#q29) · [Q30](#q30) · [Q31](#q31) · [Q32](#q32) · [Q33](#q33) · [Q34](#q34) · [Q35](#q35)

---

## 🟢 Basic

<a id="q1"></a>
### Q1
Convert an angular speed of **1200 rpm** to rad/s.

<details><summary>💡 Hint (approach)</summary>

rpm means revolutions per minute. Turn revolutions into radians ($\times 2\pi$) and minutes into seconds ($\div 60$): $\omega = \text{rpm}\times\dfrac{2\pi}{60}$.
</details>

<details><summary>✅ Answer & Solution</summary>

$\omega = 1200\times\dfrac{2\pi}{60} = 40\pi \approx \mathbf{125.7\ rad/s}$.
</details>

---

<a id="q2"></a>
### Q2
A wheel starting from rest reaches $50\ \mathrm{rad/s}$ in $10\ \text{s}$. Find its angular acceleration.

<details><summary>💡 Hint (approach)</summary>

Constant angular acceleration, starting from rest — this is the rotational twin of $v = u + at$. Use $\omega = \omega_0 + \alpha t$ with $\omega_0 = 0$.
</details>

<details><summary>✅ Answer & Solution</summary>

$\alpha = \dfrac{50}{10} = \mathbf{5\ rad/s^2}$.
</details>

---

<a id="q3"></a>
### Q3
Find the moment of inertia of a ring ($M = 3\ \text{kg}$, $R = 0.2\ \text{m}$) about its central axis.

<details><summary>💡 Hint (approach)</summary>

For a ring about the central (⟂) axis, *every* mass element sits at the same distance $R$, so $I = MR^2$ directly.
</details>

<details><summary>✅ Answer & Solution</summary>

$I = MR^2 = 3(0.2)^2 = \mathbf{0.12\ kg\cdot m^2}$.
</details>

---

<a id="q4"></a>
### Q4
A force of $8\ \text{N}$ is applied with a moment arm of $0.25\ \text{m}$ (force ⟂ to the arm). Find the torque.

<details><summary>💡 Hint (approach)</summary>

Torque = force × perpendicular distance from the axis to the line of force: $\tau = F\,r_\perp$.
</details>

<details><summary>✅ Answer & Solution</summary>

$\tau = 8\times0.25 = \mathbf{2\ N\cdot m}$.
</details>

---

<a id="q5"></a>
### Q5
A torque of $15\ \mathrm{N\cdot m}$ acts on a body with $I = 3\ \mathrm{kg\cdot m^2}$. Find $\alpha$.

<details><summary>💡 Hint (approach)</summary>

Rotational Newton's 2nd law: $\tau = I\alpha$. This is "$F=ma$" with $I$ for mass and $\tau$ for force.
</details>

<details><summary>✅ Answer & Solution</summary>

$\alpha = 15/3 = \mathbf{5\ rad/s^2}$.
</details>

---

<a id="q6"></a>
### Q6
A disc with $I = 0.5\ \mathrm{kg\cdot m^2}$ spins at $6\ \mathrm{rad/s}$. Find its rotational KE.

<details><summary>💡 Hint (approach)</summary>

Rotational KE mirrors $\tfrac12 mv^2$: use $K = \tfrac12 I\omega^2$.
</details>

<details><summary>✅ Answer & Solution</summary>

$K = \tfrac12(0.5)(6)^2 = \mathbf{9\ J}$.
</details>

---

<a id="q7"></a>
### Q7
Masses $4\ \text{kg}$ at $x = 2\ \text{m}$ and $6\ \text{kg}$ at $x = 7\ \text{m}$. Find the COM.

<details><summary>💡 Hint (approach)</summary>

Mass-weighted average position: $x_{cm} = \dfrac{\sum m_i x_i}{\sum m_i}$. Expect it to land closer to the heavier mass.
</details>

<details><summary>✅ Answer & Solution</summary>

$x_{cm} = \dfrac{4(2)+6(7)}{10} = \dfrac{50}{10} = \mathbf{5\ m}$.
</details>

---

<a id="q8"></a>
### Q8
A solid sphere ($m = 2\ \text{kg}$) rolls without slipping at $v = 3\ \mathrm{m/s}$. Find its total KE.

<details><summary>💡 Hint (approach)</summary>

Rolling = translation + rotation. Use the shortcut $K = \tfrac12 mv^2(1 + k^2/R^2)$ with $k^2/R^2 = 2/5$ for a solid sphere.
</details>

<details><summary>✅ Answer & Solution</summary>

$K = \tfrac12(2)(9)(1+0.4) = 9\times1.4 = \mathbf{12.6\ J}$.
</details>

---

<a id="q9"></a>
### Q9
Find the radius of gyration of a rod ($L = 0.6\ \text{m}$) about an axis through one end, ⟂ to the rod.

<details><summary>💡 Hint (approach)</summary>

$k$ is defined by $I = Mk^2$. Take the end-axis value $I = \tfrac13 ML^2$ and solve for $k$ — the $M$ cancels.
</details>

<details><summary>✅ Answer & Solution</summary>

$\tfrac13 ML^2 = Mk^2 \Rightarrow k = \dfrac{L}{\sqrt3} = \dfrac{0.6}{\sqrt3} = \mathbf{0.346\ m}$.
</details>

---

<a id="q10"></a>
### Q10
A particle ($m = 1\ \text{kg}$) moves at $10\ \mathrm{m/s}$ along a line $0.5\ \text{m}$ from the axis. Find its angular momentum.

<details><summary>💡 Hint (approach)</summary>

For a particle, $L = mvr_\perp$, where $r_\perp$ is the perpendicular distance from the axis to the line of motion.
</details>

<details><summary>✅ Answer & Solution</summary>

$L = 1\times10\times0.5 = \mathbf{5\ kg\cdot m^2/s}$.
</details>

---

## 🟡 Medium

<a id="q11"></a>
### Q11
A solid sphere rolls without slipping down a $37°$ incline ($\sin37° = 0.6$). Find $a_{cm}$.

<details><summary>💡 Hint (approach)</summary>

**Recognise the type:** "rolls without slipping down an incline" ⟹ $a = \dfrac{g\sin\theta}{1+k^2/R^2}$. Pick the shape factor ($2/5$ for a solid sphere) and substitute — no force diagram needed.
</details>

<details><summary>✅ Answer & Solution</summary>

$a = \dfrac{10(0.6)}{1.4} = \mathbf{4.29\ m/s^2}$.
</details>

---

<a id="q12"></a>
### Q12
Find the moment of inertia of a rod ($M = 2\ \text{kg}$, $L = 1\ \text{m}$) about a ⟂ axis through its centre.

<details><summary>💡 Hint (approach)</summary>

Standard result — centre axis is the *smaller* of the two rod values: $I = \tfrac{1}{12}ML^2$ (vs $\tfrac13 ML^2$ at the end).
</details>

<details><summary>✅ Answer & Solution</summary>

$I = \tfrac{1}{12}(2)(1)^2 = \mathbf{0.167\ kg\cdot m^2}$.
</details>

---

<a id="q13"></a>
### Q13
A solid sphere ($M = 5\ \text{kg}$, $R = 0.2\ \text{m}$). Find $I$ about a tangent line.

<details><summary>💡 Hint (approach)</summary>

A tangent is parallel to a diameter but shifted by $d = R$. **Parallel-axis theorem:** $I = I_{cm} + Md^2 = \tfrac25 MR^2 + MR^2 = \tfrac75 MR^2$.
</details>

<details><summary>✅ Answer & Solution</summary>

$I = \tfrac75(5)(0.04) = \mathbf{0.28\ kg\cdot m^2}$.
</details>

---

<a id="q14"></a>
### Q14
A skater with $I_1 = 8\ \mathrm{kg\cdot m^2}$ spins at $3\ \mathrm{rad/s}$, then pulls in to $I_2 = 2\ \mathrm{kg\cdot m^2}$. Find $\omega_2$ and the KE change.

<details><summary>💡 Hint (approach)</summary>

Trigger phrase "pulls in" ⟹ **no external torque ⟹ conserve $L$**: $I_1\omega_1 = I_2\omega_2$. Then compute $\tfrac12 I\omega^2$ before and after separately — KE is *not* conserved here.
</details>

<details><summary>✅ Answer & Solution</summary>

$\omega_2 = \dfrac{8\times3}{2} = \mathbf{12\ rad/s}$. $K_1 = \tfrac12(8)(9) = 36\ \text{J}$, $K_2 = \tfrac12(2)(144) = 144\ \text{J}$; $\Delta K = \mathbf{+108\ J}$ (muscular work).
</details>

---

<a id="q15"></a>
### Q15
A flywheel ($I = 2\ \mathrm{kg\cdot m^2}$) slows from $100\ \mathrm{rad/s}$ to rest in $20\ \text{s}$. Find the torque and the number of revolutions.

<details><summary>💡 Hint (approach)</summary>

Three steps: (1) $\alpha = \Delta\omega/t$; (2) $\tau = I|\alpha|$; (3) angle from $\theta = \omega_0^2/2|\alpha|$, then $\div 2\pi$ for revolutions.
</details>

<details><summary>✅ Answer & Solution</summary>

$\alpha = -5\ \mathrm{rad/s^2}$, $\tau = 2\times5 = \mathbf{10\ N\cdot m}$. $\theta = \dfrac{100^2}{10} = 1000\ \text{rad} \Rightarrow n = \dfrac{1000}{2\pi} \approx \mathbf{159\ rev}$.
</details>

---

<a id="q16"></a>
### Q16
Find the moment of inertia of a disc ($M = 2\ \text{kg}$, $R = 0.3\ \text{m}$) about a diameter.

<details><summary>💡 Hint (approach)</summary>

Disc is a lamina ⟹ **perpendicular-axis theorem**: $I_z = \tfrac12 MR^2 = I_x + I_y = 2I_{diameter}$, so $I_{diameter} = \tfrac14 MR^2$.
</details>

<details><summary>✅ Answer & Solution</summary>

$I = \tfrac14(2)(0.09) = \mathbf{0.045\ kg\cdot m^2}$.
</details>

---

<a id="q17"></a>
### Q17
Point masses $3\ \text{kg}$ at $0.4\ \text{m}$ and $5\ \text{kg}$ at $0.6\ \text{m}$ from an axis. Find $I$.

<details><summary>💡 Hint (approach)</summary>

Point masses add directly: $I = \sum m_i r_i^2$. Mass farther out counts more because of the $r^2$.
</details>

<details><summary>✅ Answer & Solution</summary>

$I = 3(0.16) + 5(0.36) = 0.48 + 1.8 = \mathbf{2.28\ kg\cdot m^2}$.
</details>

---

<a id="q18"></a>
### Q18
A $2\ \text{kg}$ block hangs from a string over a disc pulley ($M = 4\ \text{kg}$). Find the block's acceleration and the tension.

<details><summary>💡 Hint (approach)</summary>

Massive pulley ⟹ $T \ne mg$. Write one equation for the block and one for the pulley, linked by $a = R\alpha$. The result collapses to $a = \dfrac{mg}{m + M/2}$, then $T = \tfrac12 Ma$.
</details>

<details><summary>✅ Answer & Solution</summary>

$a = \dfrac{20}{2+2} = \mathbf{5\ m/s^2}$; $T = \tfrac12(4)(5) = \mathbf{10\ N}$.
</details>

---

<a id="q19"></a>
### Q19
A ring ($I = 0.4\ \mathrm{kg\cdot m^2}$) spins at $30\ \mathrm{rad/s}$. A disc ($I = 0.2\ \mathrm{kg\cdot m^2}$) is dropped coaxially on it. Find the common $\omega$.

<details><summary>💡 Hint (approach)</summary>

"Dropped on" ⟹ rotational inelastic event ⟹ **conserve $L$**: $\omega = \dfrac{I_1\omega_1}{I_1+I_2}$. (KE is lost to friction — don't equate energies.)
</details>

<details><summary>✅ Answer & Solution</summary>

$\omega = \dfrac{0.4\times30}{0.6} = \mathbf{20\ rad/s}$.
</details>

---

<a id="q20"></a>
### Q20
A wheel ($I = 2\ \mathrm{kg\cdot m^2}$) spinning at $15\ \mathrm{rad/s}$ is stopped in $5\ \text{revolutions}$. Find the braking torque.

<details><summary>💡 Hint (approach)</summary>

Convert 5 rev to radians first ($\times 2\pi$). Then $|\alpha| = \omega_0^2/2\theta$ and $\tau = I|\alpha|$.
</details>

<details><summary>✅ Answer & Solution</summary>

$\theta = 31.42\ \text{rad}$, $|\alpha| = \dfrac{225}{62.83} = 3.58\ \mathrm{rad/s^2}$, $\tau = 2\times3.58 = \mathbf{7.16\ N\cdot m}$.
</details>

---

<a id="q21"></a>
### Q21
Find the ratio of accelerations of a solid cylinder and a hollow cylinder rolling down the same incline.

<details><summary>💡 Hint (approach)</summary>

Take the ratio of $a = \dfrac{g\sin\theta}{1+k^2/R^2}$ so that $g\sin\theta$ cancels — only the shape factors remain ($1/2$ solid, $1$ hollow).
</details>

<details><summary>✅ Answer & Solution</summary>

$\dfrac{a_{solid}}{a_{hollow}} = \dfrac{1+1}{1+1/2} = \dfrac{2}{1.5} = \mathbf{1.33}$.
</details>

---

<a id="q22"></a>
### Q22
A rod ($L = 0.9\ \text{m}$) pivoted at one end is released from horizontal. Find $\omega$ when it is vertical.

<details><summary>💡 Hint (approach)</summary>

Energy about the pivot: PE lost by the COM (drops $L/2$) = rotational KE $\tfrac12 I\omega^2$ with $I = \tfrac13 ML^2$. The $M$ cancels, leaving $\omega = \sqrt{3g/L}$.
</details>

<details><summary>✅ Answer & Solution</summary>

$\omega = \sqrt{\dfrac{30}{0.9}} = \sqrt{33.3} = \mathbf{5.77\ rad/s}$.
</details>

---

<a id="q23"></a>
### Q23
Two uniform rods, each mass $m$ and length $l$, are joined at right angles at one end (an L-shape). Find the COM relative to the corner.

<details><summary>💡 Hint (approach)</summary>

Replace each rod by a point mass at its own midpoint, then take the COM of those two points. Put the corner at the origin with rods along $+x$ and $+y$.
</details>

<details><summary>✅ Answer & Solution</summary>

Rod COMs: $(l/2, 0)$ and $(0, l/2)$. $x_{cm} = \dfrac{m(l/2)+m(0)}{2m} = l/4$; similarly $y_{cm} = l/4$. COM at $\mathbf{(l/4,\ l/4)}$.
</details>

---

<a id="q24"></a>
### Q24
A particle ($m = 0.5\ \text{kg}$) moves at $2\ \mathrm{m/s}$ along the line $y = 3\ \text{m}$ (parallel to the $x$-axis). Find its angular momentum about the origin and whether it changes.

<details><summary>💡 Hint (approach)</summary>

$L = mvr_\perp$ with $r_\perp$ = perpendicular distance from O to the path $= 3\ \text{m}$. Ask: is there any force, hence any torque, about O?
</details>

<details><summary>✅ Answer & Solution</summary>

$L = 0.5\times2\times3 = \mathbf{3\ kg\cdot m^2/s}$, and it is **constant** (no force ⟹ no torque about O).
</details>

---

<a id="q25"></a>
### Q25
What fraction of a rolling **ring's** total kinetic energy is rotational?

<details><summary>💡 Hint (approach)</summary>

Fraction $= \dfrac{I/mR^2}{1+I/mR^2}$. For a ring $I/mR^2 = 1$, so expect exactly half.
</details>

<details><summary>✅ Answer & Solution</summary>

$\dfrac{1}{1+1} = \mathbf{\tfrac12 = 50\%}$ (compared with 33% for a solid cylinder — a ring stores more energy in rotation).
</details>

---

## 🔴 Advanced

<a id="q26"></a>
### Q26
A rod ($L = 1\ \text{m}$) pivoted at one end is released from horizontal. Find $\omega$ when it has rotated by $60°$ below the horizontal.

<details><summary>💡 Hint (approach)</summary>

Same energy method as the "to vertical" case, but the COM only drops by $(L/2)\sin\theta$ when the rod has turned by angle $\theta$. Set $Mg(L/2)\sin\theta = \tfrac12(\tfrac13 ML^2)\omega^2$.
</details>

<details><summary>✅ Answer & Solution</summary>

$\omega^2 = \dfrac{3g\sin\theta}{L} = \dfrac{3(10)(0.866)}{1} = 25.98 \Rightarrow \omega = \mathbf{5.10\ rad/s}$.
</details>

---

<a id="q27"></a>
### Q27
A turntable ($I = 200\ \mathrm{kg\cdot m^2}$, $R = 2.5\ \text{m}$) spins at $4\ \mathrm{rad/s}$ with a $60\ \text{kg}$ person at the centre. The person walks to the rim. Find the final $\omega$ and the change in KE.

<details><summary>💡 Hint (approach)</summary>

No external torque ⟹ conserve $L$. The person adds $mR^2$ to the moment of inertia **only when at the rim**. Walking *outward* raises $I$, so $\omega$ drops — opposite to the skater pulling in. Then compare kinetic energies.
</details>

<details><summary>✅ Answer & Solution</summary>

$I_2 = 200 + 60(6.25) = 575\ \mathrm{kg\cdot m^2}$. $\omega_2 = \dfrac{200\times4}{575} = \mathbf{1.39\ rad/s}$.
$K_1 = \tfrac12(200)(16) = 1600\ \text{J}$, $K_2 = \tfrac12(575)(1.39)^2 = 556\ \text{J}$; $\Delta K = \mathbf{-1044\ J}$ (KE falls as the person moves out).
</details>

---

<a id="q28"></a>
### Q28
A hollow cylinder ($M$, $R$) unwinds from a vertical string fixed at the top. Find the acceleration of its centre and the tension.

<details><summary>💡 Hint (approach)</summary>

Treat it like a body "rolling" down the string: $a = \dfrac{g}{1+k^2/R^2}$ with $k^2/R^2 = 1$ for a hollow cylinder. Then $T = M(g-a)$.
</details>

<details><summary>✅ Answer & Solution</summary>

$a = \dfrac{g}{2} = \mathbf{5\ m/s^2}$; $T = M(g-a) = \mathbf{\tfrac12 Mg}$.
</details>

---

<a id="q29"></a>
### Q29
A bullet ($m = 0.02\ \text{kg}$, $v = 300\ \mathrm{m/s}$) strikes the end of a rod ($M = 2\ \text{kg}$, $L = 1\ \text{m}$) pivoted at its centre on a frictionless table and embeds. Find $\omega$.

<details><summary>💡 Hint (approach)</summary>

Pivoted ⟹ **conserve angular momentum about the pivot** (not linear — the pivot gives an impulse). $mv(L/2) = [\tfrac{1}{12}ML^2 + m(L/2)^2]\omega$.
</details>

<details><summary>✅ Answer & Solution</summary>

$0.02(300)(0.5) = 3$. $I = \tfrac{1}{12}(2)(1) + 0.02(0.25) = 0.1667 + 0.005 = 0.1717$. $\omega = \dfrac{3}{0.1717} = \mathbf{17.5\ rad/s}$.
</details>

---

<a id="q30"></a>
### Q30
A solid sphere is projected at $v_0 = 14\ \mathrm{m/s}$ with no spin on rough ground. Find its speed when pure rolling begins.

<details><summary>💡 Hint (approach)</summary>

Use the clean trick: **angular momentum about a point on the ground is conserved** (friction acts at ground level). This gives $v_f = \dfrac{v_0}{1+k^2/R^2}$, with $k^2/R^2 = 2/5$.
</details>

<details><summary>✅ Answer & Solution</summary>

$v_f = \dfrac{14}{1.4} = \mathbf{10\ m/s}$ (equivalently $\tfrac57 v_0$).
</details>

---

<a id="q31"></a>
### Q31
A ring rolls without slipping up a $30°$ incline at $4\ \mathrm{m/s}$. Find the distance it travels up the incline before stopping.

<details><summary>💡 Hint (approach)</summary>

Energy: all the KE (including rotation) becomes PE. $\tfrac12 mv^2(1+k^2/R^2) = mgh$ with ring $k^2/R^2 = 1$; then convert height to slope distance $s = h/\sin\theta$.
</details>

<details><summary>✅ Answer & Solution</summary>

$h = \dfrac{16(2)}{20} = 1.6\ \text{m}$; $s = \dfrac{1.6}{0.5} = \mathbf{3.2\ m}$.
</details>

---

<a id="q32"></a>
### Q32
Two discs on a common axle spin in **opposite** directions: $I_1 = 3\ \mathrm{kg\cdot m^2}$ at $40\ \mathrm{rad/s}$ and $I_2 = 2\ \mathrm{kg\cdot m^2}$ at $30\ \mathrm{rad/s}$. They are coupled. Find the common $\omega$ and the energy lost.

<details><summary>💡 Hint (approach)</summary>

Conserve $L$, but opposite directions mean **opposite signs**: $\omega = \dfrac{I_1\omega_1 - I_2\omega_2}{I_1+I_2}$. Then energy lost = initial KE − final KE (both spins contribute positive KE).
</details>

<details><summary>✅ Answer & Solution</summary>

$\omega = \dfrac{3(40) - 2(30)}{5} = \dfrac{60}{5} = \mathbf{12\ rad/s}$ (in disc 1's direction).
$\Delta K = [\tfrac12(3)(1600) + \tfrac12(2)(900)] - \tfrac12(5)(144) = 2400 + 900 - 360 = \mathbf{2940\ J\ lost}$.
</details>

---

<a id="q33"></a>
### Q33
A uniform ladder leans against a smooth wall on a rough floor ($\mu = 0.4$). Find the minimum angle with the floor for equilibrium.

<details><summary>💡 Hint (approach)</summary>

Balance forces and take torque about the foot (removes the floor's unknowns). You get the standard result $\mu = \tfrac12\cot\theta$; set it equal to $0.4$ and solve for $\theta$.
</details>

<details><summary>✅ Answer & Solution</summary>

$\cot\theta = 2\mu = 0.8 \Rightarrow \tan\theta = 1.25 \Rightarrow \theta = \mathbf{51.3°}$.
</details>

---

<a id="q34"></a>
### Q34
An Atwood machine has $m_1 = 2\ \text{kg}$, $m_2 = 6\ \text{kg}$ over a disc pulley ($M = 8\ \text{kg}$). Find the acceleration and both tensions.

<details><summary>💡 Hint (approach)</summary>

Massive pulley ⟹ two different tensions. Use $a = \dfrac{(m_2-m_1)g}{m_1+m_2+M/2}$, then $T_1 = m_1(g+a)$ and $T_2 = m_2(g-a)$. Check with $T_2 - T_1 = \tfrac12 Ma$.
</details>

<details><summary>✅ Answer & Solution</summary>

$a = \dfrac{4(10)}{2+6+4} = \dfrac{40}{12} = \mathbf{3.33\ m/s^2}$. $T_1 = 2(13.33) = \mathbf{26.7\ N}$, $T_2 = 6(6.67) = \mathbf{40\ N}$.
Check: $T_2 - T_1 = 13.3 = \tfrac12(8)(3.33)$ ✔.
</details>

---

<a id="q35"></a>
### Q35
A solid cylinder rolls without slipping and must complete a vertical loop of radius $R$ (cylinder radius $\ll R$). Find the minimum starting height above the bottom of the loop.

<details><summary>💡 Hint (approach)</summary>

Two ingredients: (1) at the top, gravity alone is the centripetal force ⟹ $v_{top}^2 = gR$; (2) energy from start to the top (height $2R$), **including rotational KE** $\tfrac12 mv^2(1+\tfrac12)$.
</details>

<details><summary>✅ Answer & Solution</summary>

$mgh = mg(2R) + \tfrac34 mv_{top}^2 = 2mgR + \tfrac34 m(gR)$, so $h = 2R + 0.75R = \mathbf{2.75\,R}$.
(A point mass needs $2.5R$; a solid sphere needs $2.7R$.)
</details>

---

**Next:** [Deep Dive →](./04-deep-dive.md)
