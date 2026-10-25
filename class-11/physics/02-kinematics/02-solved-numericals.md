# Kinematics — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning rectilinear
> motion, projectiles and relative velocity. Every problem marks the **❓ Question** and **✅ Answer**;
> Medium and Advanced carry a **🧭 Strategy** block explaining *how to attack it in the exam*.

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. Take g = 10 m/s² unless stated. -->

> **Convention:** take $g = 10\ \mathrm{m/s^2}$ throughout unless a problem says otherwise, and state your positive direction before plugging into $v=u+at$ etc.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — definitions, equations of motion, free fall, basic projectile & relative
- [Medium (M1–M15)](#medium) — mixed rectilinear, projectile, river/rain, graphs
- [Advanced (A1–A10)](#advanced) — calculus kinematics, incline projectile, radius of curvature, closest approach
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** A person walks 4 m east, then 3 m north. Find the distance and the magnitude of displacement.

**✅ Answer.** Distance $= 4+3 = 7$ m. Displacement $= \sqrt{4^2+3^2} = \boxed{5\ \text{m}}$ (north-east).

---

<a id="b2"></a>
### B2

> ❓ **Question.** A body starts from rest with acceleration $2\ \mathrm{m/s^2}$. Find its velocity after 5 s.

**✅ Answer.** $v = u + at = 0 + 2(5) = \boxed{10\ \mathrm{m/s}}$.

---

<a id="b3"></a>
### B3

> ❓ **Question.** For the same body (rest, $a=2\ \mathrm{m/s^2}$), find the distance in 5 s.

**✅ Answer.** $s = ut + \tfrac12 at^2 = 0 + \tfrac12(2)(25) = \boxed{25\ \text{m}}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** A body accelerates from rest at $2\ \mathrm{m/s^2}$ over 25 m. Find its final velocity.

**✅ Answer.** $v^2 = u^2 + 2as = 0 + 2(2)(25) = 100 \Rightarrow v = \boxed{10\ \mathrm{m/s}}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** A stone is dropped from rest. How far does it fall in 3 s?

**✅ Answer.** $h = \tfrac12 g t^2 = \tfrac12(10)(9) = \boxed{45\ \text{m}}$.

---

<a id="b6"></a>
### B6

> ❓ **Question.** A ball is thrown straight up at $20\ \mathrm{m/s}$. Find the maximum height.

**✅ Answer.** $H = \dfrac{u^2}{2g} = \dfrac{400}{20} = \boxed{20\ \text{m}}$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** For that ball ($u = 20\ \mathrm{m/s}$ up), find the total time of flight back to the hand.

**✅ Answer.** $T = \dfrac{2u}{g} = \dfrac{40}{10} = \boxed{4\ \text{s}}$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** A projectile is launched at $20\ \mathrm{m/s}$ at $45°$. Find its horizontal range.

**✅ Answer.** $R = \dfrac{u^2\sin 2\theta}{g} = \dfrac{400\sin 90°}{10} = \boxed{40\ \text{m}}$.

---

<a id="b9"></a>
### B9

> ❓ **Question.** A projectile is launched at $20\ \mathrm{m/s}$, $30°$ above horizontal. What is its speed at the highest point?

**✅ Answer.** At the top only the horizontal component survives: $u\cos\theta = 20\cos30° = 10\sqrt3 \approx \boxed{17.3\ \mathrm{m/s}}$.

---

<a id="b10"></a>
### B10

> ❓ **Question.** Two cars move the same way at $60$ and $40\ \mathrm{km/h}$. How fast does the faster approach the slower?

**✅ Answer.** $v_{AB} = 60 - 40 = \boxed{20\ \mathrm{km/h}}$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** A car decelerates uniformly from $20\ \mathrm{m/s}$ to rest in 5 s. How far does it travel?

> [!TIP]
> 🧭 **Strategy.** Constant acceleration → use the equations of motion. With a start and end velocity
> and a time, the fastest route is average velocity $\times$ time (avoids finding $a$).

**Steps.** Average velocity $= \dfrac{20+0}{2} = 10\ \mathrm{m/s}$; distance $= 10 \times 5$.

**✅ Answer.** $\boxed{50\ \text{m}}$.

---

<a id="m2"></a>
### M2

> ❓ **Question.** A body starts from rest with $a = 2\ \mathrm{m/s^2}$. Find the distance travelled in the 5th second.

> [!TIP]
> 🧭 **Strategy.** "Distance in the $n$th second" is a *specific* interval (1 s long), not the total —
> use $s_n = u + \tfrac{a}{2}(2n-1)$, not $s=ut+\tfrac12 at^2$.

**Steps.** $s_5 = 0 + \tfrac{2}{2}(2\cdot5 - 1) = 1 \times 9$.

**✅ Answer.** $\boxed{9\ \text{m}}$.

---

<a id="m3"></a>
### M3

> ❓ **Question.** A stone dropped from a tower reaches the ground in 4 s. Find the tower's height.

> [!TIP]
> 🧭 **Strategy.** Dropped → $u=0$; use $h = \tfrac12 g t^2$.

**Steps.** $h = \tfrac12(10)(16)$.

**✅ Answer.** $\boxed{80\ \text{m}}$.

---

<a id="m4"></a>
### M4

> ❓ **Question.** A ball is thrown up from the ground at $20\ \mathrm{m/s}$. At what times is it at height 15 m?

> [!TIP]
> 🧭 **Strategy.** Use $y = ut - \tfrac12 gt^2$ (up positive) and solve the quadratic — **two** times
> (going up and coming down) are expected.

**Steps.** $15 = 20t - 5t^2 \Rightarrow t^2 - 4t + 3 = 0 \Rightarrow (t-1)(t-3)=0$.

**✅ Answer.** $t = 1\ \text{s}$ (rising) and $t = 3\ \text{s}$ (falling).

---

<a id="m5"></a>
### M5

> ❓ **Question.** A stone is thrown **up** at $20\ \mathrm{m/s}$ from the top of a 25 m tower. How long until it hits the ground?

> [!TIP]
> 🧭 **Strategy.** Take up as positive; the ground is at $-25$ m from the launch point. Solve
> $-25 = 20t - 5t^2$ and keep the positive root.

**Steps.** $5t^2 - 20t - 25 = 0 \Rightarrow t^2 - 4t - 5 = 0 \Rightarrow (t-5)(t+1)=0$.

**✅ Answer.** $t = \boxed{5\ \text{s}}$.

---

<a id="m6"></a>
### M6

> ❓ **Question.** A projectile is fired at $20\ \mathrm{m/s}$, $30°$ to the horizontal. Find its maximum height and range.

> [!TIP]
> 🧭 **Strategy.** Plug into the standard projectile formulas; keep $\sin30°=0.5$, $\sin60°\approx0.866$.

**Steps.**
- $H = \dfrac{u^2\sin^2\theta}{2g} = \dfrac{400(0.25)}{20} = 5$ m.
- $R = \dfrac{u^2\sin 2\theta}{g} = \dfrac{400\sin60°}{10} = 40(0.866)$.

**✅ Answer.** $H = 5\ \text{m}$, $R \approx 34.6\ \text{m}$.

---

<a id="m7"></a>
### M7

> ❓ **Question.** A projectile has $u = 50\ \mathrm{m/s}$, $\theta = 37°$ ($\sin37° = 0.6$). Find the time of flight.

> [!TIP]
> 🧭 **Strategy.** $T = \dfrac{2u\sin\theta}{g}$ — only the vertical component matters for flight time.

**Steps.** $T = \dfrac{2(50)(0.6)}{10} = \dfrac{60}{10}$.

**✅ Answer.** $\boxed{6\ \text{s}}$.

---

<a id="m8"></a>
### M8

> ❓ **Question.** A ball is thrown **horizontally** at $15\ \mathrm{m/s}$ from a 80 m cliff. Find the time to land and the horizontal distance.

> [!TIP]
> 🧭 **Strategy.** Horizontal and vertical are independent. The fall time comes from the **vertical**
> drop alone ($u_y=0$); the horizontal distance is then $u_x \times t$.

**Steps.** $t = \sqrt{\dfrac{2h}{g}} = \sqrt{\dfrac{160}{10}} = 4$ s; $x = 15 \times 4$.

**✅ Answer.** $t = 4\ \text{s}$, $x = 60\ \text{m}$.

---

<a id="m9"></a>
### M9

> ❓ **Question.** A river flows at $3\ \mathrm{m/s}$; a boat moves at $5\ \mathrm{m/s}$ relative to the water. To cross straight over a 100 m-wide river, at what angle (to the bank-normal) must it head, and how long does it take?

> [!TIP]
> 🧭 **Strategy.** "Straight across" (zero drift) → the upstream component must cancel the current:
> $\sin\theta = v_{\text{river}}/v_{\text{boat}}$. The effective crossing speed is the perpendicular
> component $\sqrt{v_{\text{boat}}^2 - v_{\text{river}}^2}$.

**Steps.** $\sin\theta = \tfrac35 \Rightarrow \theta = 37°$ upstream. Crossing speed $= \sqrt{25-9} = 4\ \mathrm{m/s}$; time $= 100/4$.

**✅ Answer.** $37°$ upstream from straight-across; time $= 25\ \text{s}$.

---

<a id="m10"></a>
### M10

> ❓ **Question.** Rain falls vertically at $10\ \mathrm{m/s}$. A man walks horizontally at $10\ \mathrm{m/s}$. At what angle to the vertical should he tilt his umbrella, and what is the rain's speed relative to him?

> [!TIP]
> 🧭 **Strategy.** The umbrella points along $\vec{v}_{\text{rain}} - \vec{v}_{\text{man}}$. Build that
> vector: vertical component $10$ (down), horizontal component $10$ (opposite to walking).

**Steps.** Tilt angle $= \tan^{-1}\!\dfrac{v_{\text{man}}}{v_{\text{rain}}} = \tan^{-1}(1) = 45°$; relative speed $= \sqrt{10^2+10^2} = 10\sqrt2$.

**✅ Answer.** $45°$ from vertical (toward his motion); relative speed $\approx 14.1\ \mathrm{m/s}$.

---

<a id="m11"></a>
### M11

> ❓ **Question.** From a $v$–$t$ graph: an object accelerates from rest to $20\ \mathrm{m/s}$ in 4 s, then moves at constant $20\ \mathrm{m/s}$ for 6 s. Find the total displacement.

> [!TIP]
> 🧭 **Strategy.** Displacement = **area under the $v$–$t$ graph**. Split into a triangle (accelerating
> part) and a rectangle (constant part).

**Steps.** Triangle $= \tfrac12(4)(20) = 40$; rectangle $= 20\times6 = 120$.

**✅ Answer.** $40 + 120 = \boxed{160\ \text{m}}$.

---

<a id="m12"></a>
### M12

> ❓ **Question.** A car covers the first half of a distance at $30\ \mathrm{km/h}$ and the second half at $60\ \mathrm{km/h}$. Find the average speed.

> [!TIP]
> 🧭 **Strategy.** Equal **distances** → average speed is the **harmonic mean**
> $\dfrac{2v_1v_2}{v_1+v_2}$, *not* the arithmetic mean. (Equal *times* would give the arithmetic mean.)

**Steps.** $\bar v = \dfrac{2(30)(60)}{30+60} = \dfrac{3600}{90}$.

**✅ Answer.** $\boxed{40\ \mathrm{km/h}}$.

---

<a id="m13"></a>
### M13

> ❓ **Question.** Two trains, 100 m and 150 m long, move toward each other at $20$ and $30\ \mathrm{m/s}$. How long to completely cross each other?

> [!TIP]
> 🧭 **Strategy.** Work in one train's frame: relative speed (opposite directions) $= 20+30$. The
> distance to clear is the **sum of lengths**.

**Steps.** Relative speed $= 50\ \mathrm{m/s}$; distance $= 100+150 = 250$ m; time $= 250/50$.

**✅ Answer.** $\boxed{5\ \text{s}}$.

---

<a id="m14"></a>
### M14

> ❓ **Question.** Show that launch angles $30°$ and $60°$ give the same range (take $u = 20\ \mathrm{m/s}$).

> [!TIP]
> 🧭 **Strategy.** $R \propto \sin 2\theta$, and $\sin 2(30°) = \sin60° = \sin120° = \sin2(60°)$ —
> complementary angles share a range.

**Steps.** Both give $R = \dfrac{400\sin120°}{10} = \dfrac{400\sin60°}{10} = 40(0.866)$.

**✅ Answer.** Both $\approx 34.6\ \text{m}$ — equal, as $30°+60°=90°$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** A particle starts from rest at the origin with acceleration $a = 6t\ \mathrm{m/s^2}$. Find its velocity and position at $t = 2$ s.

> [!TIP]
> 🧭 **Strategy.** $a$ depends on **time**, so the constant-$a$ equations don't apply. Integrate:
> $v = \int a\,dt$, then $x = \int v\,dt$.

**Steps.** $v = \int_0^t 6t\,dt = 3t^2$; at $t=2$, $v = 12$. $x = \int_0^t 3t^2\,dt = t^3$; at $t=2$, $x = 8$.

**✅ Answer.** $v = 12\ \mathrm{m/s}$, $x = 8\ \text{m}$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** A particle moves with acceleration $a = -0.5\,v$ (velocity-dependent). It starts at $v_0 = 10\ \mathrm{m/s}$. How long until its speed halves?

> [!TIP]
> 🧭 **Strategy.** $a = f(v)$ → use $\dfrac{dv}{dt} = -0.5v$ and separate variables:
> $\dfrac{dv}{v} = -0.5\,dt$. This gives exponential decay.

**Steps.** $\int_{10}^{5}\dfrac{dv}{v} = -0.5\int_0^t dt \Rightarrow \ln\tfrac{5}{10} = -0.5t \Rightarrow t = 2\ln2$.

**✅ Answer.** $t = 2\ln2 \approx \boxed{1.39\ \text{s}}$.

---

<a id="a2"></a>
### A2

> ❓ **Question.** A particle moves so that its velocity is $v = \sqrt{x}$ (SI units). Find its acceleration.

> [!TIP]
> 🧭 **Strategy.** $v$ is a function of **position**, so use $a = v\dfrac{dv}{dx}$ — don't differentiate
> with respect to $t$.

**Steps.** $\dfrac{dv}{dx} = \dfrac{1}{2\sqrt{x}}$; $a = v\dfrac{dv}{dx} = \sqrt{x}\cdot\dfrac{1}{2\sqrt{x}} = \tfrac12$.

**✅ Answer.** $a = 0.5\ \mathrm{m/s^2}$ (constant — a neat result).

---

<a id="a3"></a>
### A3

> ❓ **Question.** A projectile is launched at $20\ \mathrm{m/s}$ at $30°$ **to an incline** that itself rises at $30°$. Find the range along the incline (up the slope).

> [!TIP]
> 🧭 **Strategy.** Use the inclined-plane range formula
> $R = \dfrac{2u^2\sin\theta\cos(\theta+\alpha)}{g\cos^2\alpha}$ with $\theta$ measured from the incline
> and $\alpha$ the incline angle. (It comes from resolving $g$ along/perpendicular to the slope.)

**Steps.** $R = \dfrac{2(400)\sin30°\cos60°}{10\cos^230°} = \dfrac{800(0.5)(0.5)}{10(0.75)} = \dfrac{200}{7.5}$.

**✅ Answer.** $R \approx \boxed{26.7\ \text{m}}$ up the incline.

---

<a id="a4"></a>
### A4

> ❓ **Question.** A projectile is launched at $20\ \mathrm{m/s}$, $60°$ to the horizontal. Find the radius of curvature of its path at the highest point.

> [!TIP]
> 🧭 **Strategy.** At any point $r = \dfrac{v^2}{a_\perp}$, where $a_\perp$ is the component of $g$
> perpendicular to the velocity. At the top the velocity is horizontal, so $a_\perp = g$ and
> $v = u\cos\theta$.

**Steps.** $v = 20\cos60° = 10\ \mathrm{m/s}$; $r = \dfrac{v^2}{g} = \dfrac{100}{10}$.

**✅ Answer.** $r = \boxed{10\ \text{m}}$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** Particle A is at the origin moving at $3\ \mathrm{m/s}$ along $+x$. Particle B is at $(0, 10)$ m moving at $4\ \mathrm{m/s}$ along $-y$. Find their closest approach and when it occurs.

> [!TIP]
> 🧭 **Strategy.** Switch to A's frame: B then moves in a straight line with relative velocity
> $\vec{v}_{BA} = \vec{v}_B - \vec{v}_A$. The closest approach is the perpendicular distance from A to
> that line; use $d_{\min} = \dfrac{|\vec{r}\times\vec{v}_{BA}|}{|\vec{v}_{BA}|}$ and
> $t = -\dfrac{\vec{r}\cdot\vec{v}_{BA}}{|\vec{v}_{BA}|^2}$.

**Steps.**
1. $\vec{v}_{BA} = (0,-4) - (3,0) = (-3,-4)$, $|\vec{v}_{BA}| = 5$. Initial $\vec{r}_{BA} = (0,10)$.
2. $t = -\dfrac{(0)(-3) + (10)(-4)}{25} = \dfrac{40}{25} = 1.6$ s.
3. $|\vec{r}\times\vec{v}_{BA}| = |0\cdot(-4) - 10\cdot(-3)| = 30$; $d_{\min} = 30/5 = 6$.

**✅ Answer.** Closest approach $= 6\ \text{m}$ at $t = 1.6\ \text{s}$.

---

<a id="a6"></a>
### A6

> ❓ **Question.** A particle has acceleration $a = -4x$ (SI), and at $x=0$ its speed is $10\ \mathrm{m/s}$. Find its speed at $x = 3$ m and the farthest point it reaches.

> [!TIP]
> 🧭 **Strategy.** $a = f(x)$ → use $v\,dv = a\,dx$ and integrate from the known state. (This is SHM;
> the body stops where $v=0$.)

**Steps.** $\int_{10}^{v} v\,dv = \int_0^x -4x\,dx \Rightarrow \dfrac{v^2-100}{2} = -2x^2 \Rightarrow v^2 = 100 - 4x^2$.
- At $x=3$: $v^2 = 100 - 36 = 64 \Rightarrow v = 8$.
- Farthest point: $v=0 \Rightarrow x^2 = 25 \Rightarrow x = 5$.

**✅ Answer.** $v = 8\ \mathrm{m/s}$ at $x=3$; it turns around at $x = 5\ \text{m}$ (amplitude).

---

<a id="a7"></a>
### A7

> ❓ **Question.** For a projectile, find the launch angle at which the range equals twice the maximum height.

> [!TIP]
> 🧭 **Strategy.** Write both in terms of $u,\theta$, set $R = 2H$, and the $u^2/g$ cancels — leaving a
> trig equation in $\theta$.

**Steps.** $\dfrac{u^2\sin2\theta}{g} = 2\cdot\dfrac{u^2\sin^2\theta}{2g} \Rightarrow \sin2\theta = \sin^2\theta \Rightarrow 2\sin\theta\cos\theta = \sin^2\theta \Rightarrow \tan\theta = 2$.

**✅ Answer.** $\theta = \tan^{-1}2 \approx \boxed{63.4°}$.

---

<a id="a8"></a>
### A8

> ❓ **Question.** A particle starts from rest; its acceleration grows as $a = 2t\ \mathrm{m/s^2}$. Find the distance covered in the first 3 s.

> [!TIP]
> 🧭 **Strategy.** Integrate twice: $v = \int a\,dt$, $x = \int v\,dt$, both from rest/origin.

**Steps.** $v = \int_0^t 2t\,dt = t^2$; $x = \int_0^3 t^2\,dt = \dfrac{t^3}{3}\Big|_0^3 = 9$.

**✅ Answer.** $x = \boxed{9\ \text{m}}$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** A 200 m-wide river flows at $4\ \mathrm{m/s}$; a boat does $5\ \mathrm{m/s}$ in still water. Compare the **shortest-time** and **shortest-path** crossings (time taken, and downstream drift in each).

> [!TIP]
> 🧭 **Strategy.** Two *different* optimisations. Shortest time → head straight across (full speed used
> across, current causes drift). Shortest path → aim upstream to kill drift (slower effective crossing).

**Steps.**
- **Shortest time:** head perpendicular; $t = 200/5 = 40$ s; drift $= 4\times40 = 160$ m.
- **Shortest path:** aim upstream, $\sin\theta = 4/5$; across speed $= \sqrt{25-16} = 3\ \mathrm{m/s}$; $t = 200/3 \approx 66.7$ s; drift $= 0$.

**✅ Answer.** Shortest time $40$ s (drift $160$ m); shortest path $\approx 66.7$ s (zero drift).

---

<a id="a10"></a>
### A10

> ❓ **Question.** Ball A is dropped from a height of 100 m. At the same instant, ball B is thrown straight up from the ground at $25\ \mathrm{m/s}$. When and where do they meet?

> [!TIP]
> 🧭 **Strategy.** Both have the **same** acceleration $g$ downward, so in one ball's frame the other
> moves at **constant** relative velocity — the gap closes at a steady rate. Time to meet = initial
> gap ÷ relative speed.

**Steps.**
1. Relative approach speed $= 25\ \mathrm{m/s}$ (A starts at rest, B at $25$ up; the $g$ terms cancel). Gap $= 100$ m $\Rightarrow t = 100/25 = 4$ s.
2. Height of B at $t=4$: $25(4) - \tfrac12(10)(16) = 100 - 80 = 20$ m. (Check A: $100 - 80 = 20$ m. ✓)

**✅ Answer.** They meet after $4\ \text{s}$, at $20\ \text{m}$ above the ground.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style, and tag each
> with its difficulty and sub-topic (rectilinear / projectile / relative).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <rectilinear/projectile/relative>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
