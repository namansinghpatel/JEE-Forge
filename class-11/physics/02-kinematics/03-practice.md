# Kinematics — Practice Range

> **35 problems to solve yourself**, split **Basic (10) · Medium (15) · Advanced (10)** across
> rectilinear motion, projectiles and relative velocity. Each has a **💡 Approach hint** (*how to
> think* — reveal only if stuck) and a **collapsible answer**. Attempt with pen and paper first.

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. Take g = 10 m/s² unless stated. -->

> **Convention:** $g = 10\ \mathrm{m/s^2}$ unless stated; fix a positive direction before using the equations.

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

**P1.** A body moves 6 m east then 8 m north. Find distance and displacement.

<details><summary>💡 Approach hint</summary>

Distance = sum of path; displacement = straight-line (Pythagoras).
</details>

<details><summary>✅ Answer</summary>

Distance $= 14$ m; displacement $= \sqrt{36+64} = \mathbf{10\ m}$.
</details>

---

**P2.** A car accelerates from rest at $3\ \mathrm{m/s^2}$. Find its speed after 6 s.

<details><summary>💡 Approach hint</summary>

$v = u + at$.
</details>

<details><summary>✅ Answer</summary>

$v = 0 + 3(6) = \mathbf{18\ m/s}$.
</details>

---

**P3.** How far does a body (rest, $a = 3\ \mathrm{m/s^2}$) travel in 6 s?

<details><summary>💡 Approach hint</summary>

$s = ut + \tfrac12 at^2$.
</details>

<details><summary>✅ Answer</summary>

$s = \tfrac12(3)(36) = \mathbf{54\ m}$.
</details>

---

**P4.** A stone is dropped from rest. Find its speed after falling 45 m.

<details><summary>💡 Approach hint</summary>

$v^2 = u^2 + 2gh$, $u=0$.
</details>

<details><summary>✅ Answer</summary>

$v = \sqrt{2(10)(45)} = \sqrt{900} = \mathbf{30\ m/s}$.
</details>

---

**P5.** A ball is thrown up at $30\ \mathrm{m/s}$. Find the maximum height.

<details><summary>💡 Approach hint</summary>

$H = u^2/2g$.
</details>

<details><summary>✅ Answer</summary>

$H = 900/20 = \mathbf{45\ m}$.
</details>

---

**P6.** Find the time of flight for a ball thrown up at $30\ \mathrm{m/s}$.

<details><summary>💡 Approach hint</summary>

$T = 2u/g$.
</details>

<details><summary>✅ Answer</summary>

$T = 60/10 = \mathbf{6\ s}$.
</details>

---

**P7.** A projectile is launched at $30\ \mathrm{m/s}$, $45°$. Find the range.

<details><summary>💡 Approach hint</summary>

$R = u^2\sin2\theta/g$; $\sin90°=1$.
</details>

<details><summary>✅ Answer</summary>

$R = 900/10 = \mathbf{90\ m}$.
</details>

---

**P8.** A projectile launched at $40\ \mathrm{m/s}$, $30°$. Find the horizontal component of velocity.

<details><summary>💡 Approach hint</summary>

$u_x = u\cos\theta$.
</details>

<details><summary>✅ Answer</summary>

$u_x = 40\cos30° = 20\sqrt3 \approx \mathbf{34.6\ m/s}$.
</details>

---

**P9.** Two cars approach head-on at $25$ and $15\ \mathrm{m/s}$. Find their relative speed.

<details><summary>💡 Approach hint</summary>

Opposite directions → add.
</details>

<details><summary>✅ Answer</summary>

$25 + 15 = \mathbf{40\ m/s}$.
</details>

---

**P10.** A boat does $4\ \mathrm{m/s}$ in still water; river flows at $3\ \mathrm{m/s}$. If the boat heads straight across, what is its speed relative to ground?

<details><summary>💡 Approach hint</summary>

Perpendicular vectors → resultant by Pythagoras.
</details>

<details><summary>✅ Answer</summary>

$\sqrt{4^2+3^2} = \mathbf{5\ m/s}$ (at an angle downstream).
</details>

---

<a id="medium"></a>
## 🟡 Medium (P11–P25)

**P11.** A car moving at $30\ \mathrm{m/s}$ brakes to rest in 6 s. Find the braking distance.

<details><summary>💡 Approach hint</summary>

Average velocity × time, or $v^2 = u^2 + 2as$.
</details>

<details><summary>✅ Answer</summary>

$\bar v \cdot t = 15 \times 6 = \mathbf{90\ m}$.
</details>

---

**P12.** A body starts from rest, $a = 4\ \mathrm{m/s^2}$. Find the distance in the 3rd second.

<details><summary>💡 Approach hint</summary>

$s_n = u + \tfrac{a}{2}(2n-1)$.
</details>

<details><summary>✅ Answer</summary>

$s_3 = 0 + 2(5) = \mathbf{10\ m}$.
</details>

---

**P13.** A ball thrown up from the ground at $25\ \mathrm{m/s}$. At what times is it 20 m high?

<details><summary>💡 Approach hint</summary>

$20 = 25t - 5t^2$; solve the quadratic (two times).
</details>

<details><summary>✅ Answer</summary>

$5t^2 - 25t + 20 = 0 \Rightarrow t^2 - 5t + 4 = 0 \Rightarrow t = 1\ \text{s}, 4\ \text{s}$.
</details>

---

**P14.** A stone thrown **down** at $10\ \mathrm{m/s}$ from a 60 m tower. Find the time to reach the ground.

<details><summary>💡 Approach hint</summary>

Down positive: $60 = 10t + 5t^2$.
</details>

<details><summary>✅ Answer</summary>

$5t^2 + 10t - 60 = 0 \Rightarrow t^2 + 2t - 12 = 0 \Rightarrow t = -1+\sqrt{13} \approx \mathbf{2.6\ s}$.
</details>

---

**P15.** A projectile: $u = 50\ \mathrm{m/s}$, $\theta = 53°$ ($\sin53°=0.8$, $\cos53°=0.6$). Find max height and range.

<details><summary>💡 Approach hint</summary>

$H = u^2\sin^2\theta/2g$, $R = u^2\sin2\theta/g$ with $\sin2\theta = 2\sin\theta\cos\theta$.
</details>

<details><summary>✅ Answer</summary>

$H = 2500(0.64)/20 = 80$ m; $\sin106° = \sin74° = 0.96$, $R = 2500(0.96)/10 = 240$ m.
</details>

---

**P16.** A ball thrown horizontally at $20\ \mathrm{m/s}$ from a 45 m cliff. Find where it lands (horizontal distance).

<details><summary>💡 Approach hint</summary>

$t = \sqrt{2h/g}$, then $x = u_x t$.
</details>

<details><summary>✅ Answer</summary>

$t = \sqrt{9} = 3$ s; $x = 20(3) = \mathbf{60\ m}$.
</details>

---

**P17.** A river is 120 m wide, flows at $5\ \mathrm{m/s}$; boat $13\ \mathrm{m/s}$ in still water. To cross straight across, find the crossing time.

<details><summary>💡 Approach hint</summary>

Across speed $= \sqrt{13^2 - 5^2}$.
</details>

<details><summary>✅ Answer</summary>

$\sqrt{169-25} = 12\ \mathrm{m/s}$; time $= 120/12 = \mathbf{10\ s}$.
</details>

---

**P18.** Rain falls vertically at $12\ \mathrm{m/s}$; a man runs at $5\ \mathrm{m/s}$. At what angle from the vertical must he hold the umbrella?

<details><summary>💡 Approach hint</summary>

$\tan\theta = v_{\text{man}}/v_{\text{rain}}$.
</details>

<details><summary>✅ Answer</summary>

$\theta = \tan^{-1}(5/12) \approx \mathbf{22.6°}$ from vertical.
</details>

---

**P19.** From a $v$–$t$ graph: $0 \to 15\ \mathrm{m/s}$ in 3 s, constant for 4 s, then to rest in 2 s. Find total displacement.

<details><summary>💡 Approach hint</summary>

Area = triangle + rectangle + triangle.
</details>

<details><summary>✅ Answer</summary>

$\tfrac12(3)(15) + 15(4) + \tfrac12(2)(15) = 22.5 + 60 + 15 = \mathbf{97.5\ m}$.
</details>

---

**P20.** A car covers equal **time** intervals at $40$ and $60\ \mathrm{km/h}$. Find the average speed.

<details><summary>💡 Approach hint</summary>

Equal times → arithmetic mean (contrast equal distances → harmonic mean).
</details>

<details><summary>✅ Answer</summary>

$(40+60)/2 = \mathbf{50\ km/h}$.
</details>

---

**P21.** Two trains 120 m and 80 m long move the **same** way at $25$ and $15\ \mathrm{m/s}$. Time for the faster to overtake the slower completely?

<details><summary>💡 Approach hint</summary>

Same direction → relative speed subtracts; distance = sum of lengths.
</details>

<details><summary>✅ Answer</summary>

Relative $= 10\ \mathrm{m/s}$; distance $= 200$ m; time $= \mathbf{20\ s}$.
</details>

---

**P22.** A particle's velocity is $v = 4t^3$ (SI). Find the distance covered from $t=0$ to $t=2$ s.

<details><summary>💡 Approach hint</summary>

$x = \int v\,dt$.
</details>

<details><summary>✅ Answer</summary>

$x = \int_0^2 4t^3\,dt = t^4\big|_0^2 = \mathbf{16\ m}$.
</details>

---

**P23.** A projectile's range is 80 m and time of flight is 4 s. Find the launch speed and angle.

<details><summary>💡 Approach hint</summary>

$u_x = R/T$; $u_y = gT/2$; then $u = \sqrt{u_x^2+u_y^2}$, $\theta = \tan^{-1}(u_y/u_x)$.
</details>

<details><summary>✅ Answer</summary>

$u_x = 20$, $u_y = 20$; $u = 20\sqrt2 \approx 28.3\ \mathrm{m/s}$, $\theta = 45°$.
</details>

---

**P24.** An aeroplane flies east at $200\ \mathrm{km/h}$; wind blows north at $50\ \mathrm{km/h}$. Find the ground speed and direction.

<details><summary>💡 Approach hint</summary>

Vector add plane + wind (perpendicular).
</details>

<details><summary>✅ Answer</summary>

$\sqrt{200^2+50^2} \approx 206\ \mathrm{km/h}$, at $\tan^{-1}(50/200) \approx 14°$ north of east.
</details>

---

**P25.** A ball dropped from a height takes the last 1 s to cross the final 25 m. Find the total height. (g=10)

<details><summary>💡 Approach hint</summary>

Let total time $T$; distance in last second $= \tfrac12 g T^2 - \tfrac12 g (T-1)^2 = 25$.
</details>

<details><summary>✅ Answer</summary>

$5T^2 - 5(T-1)^2 = 25 \Rightarrow 10T - 5 = 25 \Rightarrow T = 3$ s; height $= 5(9) = \mathbf{45\ m}$.
</details>

---

<a id="advanced"></a>
## 🔴 Advanced (P26–P35)

**P26.** A particle has $a = -kv$ with $k = 2\ \mathrm{s^{-1}}$, starting at $v_0 = 8\ \mathrm{m/s}$. Find the total distance before it stops.

<details><summary>💡 Approach hint</summary>

Use $a = v\,dv/dx = -kv \Rightarrow dv = -k\,dx$; integrate to $v=0$.
</details>

<details><summary>✅ Answer</summary>

$\int_{8}^{0} dv = -k\int_0^X dx \Rightarrow -8 = -2X \Rightarrow X = \mathbf{4\ m}$.
</details>

---

**P27.** A particle moves with $v = 3x$ (SI). Find its acceleration at $x = 2$ m.

<details><summary>💡 Approach hint</summary>

$a = v\,dv/dx$.
</details>

<details><summary>✅ Answer</summary>

$dv/dx = 3$; $a = (3x)(3) = 9x = \mathbf{18\ m/s^2}$ at $x=2$.
</details>

---

**P28.** A projectile is launched at $20\ \mathrm{m/s}$, $53°$ to the horizontal ($\sin53°=0.8$). Find the radius of curvature at the launch point.

<details><summary>💡 Approach hint</summary>

$r = v^2/a_\perp$; at launch $v=u$ and $a_\perp = g\cos53°$.
</details>

<details><summary>✅ Answer</summary>

$a_\perp = 10(0.6) = 6$; $r = 400/6 \approx \mathbf{66.7\ m}$.
</details>

---

**P29.** A projectile launched up a $30°$ incline, at $45°$ to the horizontal, $u = 20\ \mathrm{m/s}$. Find the range along the incline. (Angle to incline $= 15°$.)

<details><summary>💡 Approach hint</summary>

$R = \dfrac{2u^2\sin\theta'\cos(\theta'+\alpha)}{g\cos^2\alpha}$ with $\theta' = 15°$ (angle to incline), $\alpha = 30°$.
</details>

<details><summary>✅ Answer</summary>

$R = \dfrac{2(400)\sin15°\cos45°}{10\cos^230°} = \dfrac{800(0.259)(0.707)}{7.5} \approx \mathbf{19.5\ m}$.
</details>

---

**P30.** Find the launch angle for which the maximum height equals the range.

<details><summary>💡 Approach hint</summary>

Set $H = R$, cancel $u^2/g$.
</details>

<details><summary>✅ Answer</summary>

$\dfrac{\sin^2\theta}{2} = \sin2\theta = 2\sin\theta\cos\theta \Rightarrow \tan\theta = 4 \Rightarrow \theta \approx \mathbf{76°}$.
</details>

---

**P31.** A particle has $a = 6 - 2t$ (SI), starting from rest at the origin. Find when the velocity is maximum and its value.

<details><summary>💡 Approach hint</summary>

$v = \int a\,dt$; velocity is max when $a = 0$.
</details>

<details><summary>✅ Answer</summary>

$a=0$ at $t=3$ s; $v = \int_0^3(6-2t)\,dt = [6t - t^2]_0^3 = 18 - 9 = \mathbf{9\ m/s}$.
</details>

---

**P32.** Two particles: A at origin with velocity $(2, 0)\ \mathrm{m/s}$; B at $(0, 6)$ m with velocity $(0, -3)\ \mathrm{m/s}$. Find the closest approach.

<details><summary>💡 Approach hint</summary>

Relative velocity $\vec v_{BA} = \vec v_B - \vec v_A$; $d_{\min} = |\vec r \times \hat v_{BA}|$.
</details>

<details><summary>✅ Answer</summary>

$\vec v_{BA} = (-2,-3)$, $|\vec v_{BA}| = \sqrt{13}$; $\vec r_{BA} = (0,6)$; cross $= |0(-3) - 6(-2)| = 12$; $d_{\min} = 12/\sqrt{13} \approx \mathbf{3.33\ m}$.
</details>

---

**P33.** A river $90$ m wide flows at $3\ \mathrm{m/s}$; a swimmer does $5\ \mathrm{m/s}$. Find the minimum time to cross and the drift in that case.

<details><summary>💡 Approach hint</summary>

Minimum time → head straight across (full speed across).
</details>

<details><summary>✅ Answer</summary>

$t = 90/5 = 18$ s; drift $= 3(18) = \mathbf{54\ m}$.
</details>

---

**P34.** Ball A is dropped from 80 m; simultaneously ball B is thrown up from the ground at $20\ \mathrm{m/s}$. Where and when do they meet?

<details><summary>💡 Approach hint</summary>

Same $g$ → gap closes at constant relative speed $= 20\ \mathrm{m/s}$.
</details>

<details><summary>✅ Answer</summary>

$t = 80/20 = 4$ s; B's height $= 20(4) - 5(16) = 0$ — they meet at the ground at $t = 4$ s. (A: $80 - 80 = 0$ ✓.)
</details>

---

**P35.** A particle's position is $x = 2t^3 - 9t^2 + 12t$ (SI). Find the times when it is momentarily at rest and the total distance in the first 3 s.

<details><summary>💡 Approach hint</summary>

$v = dx/dt = 0$ gives rest times; distance adds the magnitudes of each leg (watch the direction reversal).
</details>

<details><summary>✅ Answer</summary>

$v = 6t^2 - 18t + 12 = 6(t-1)(t-2) = 0 \Rightarrow t = 1, 2$ s. $x(0)=0$, $x(1)=5$, $x(2)=4$, $x(3)=9$. Distance $= |5-0| + |4-5| + |9-4| = 5+1+5 = \mathbf{11\ m}$.
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
