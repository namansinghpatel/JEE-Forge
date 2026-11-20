# Work, Energy & Power — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning work, the
> work–energy theorem, potential energy, conservation of energy, power and collisions. Every problem marks
> the **❓ Question** and **✅ Answer**; Medium and Advanced carry a **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. Take g = 10 m/s² unless stated. -->

> **Convention:** take $g = 10\ \mathrm{m/s^2}$ unless stated; prefer the work–energy theorem / energy conservation when time is not involved.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — work, KE, PE, power, simple collisions
- [Medium (M1–M15)](#medium) — work–energy theorem, friction loss, springs, conservation, restitution
- [Advanced (A1–A10)](#advanced) — variable force, vertical circle, spring+friction, 2D collisions, $F=-dU/dx$
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** A $10\ \mathrm{N}$ force moves a body $4\ \mathrm{m}$ in its own direction. Find the work done.

**✅ Answer.** $W = Fd\cos0° = 10(4) = \boxed{40\ \mathrm{J}}$.

---

<a id="b2"></a>
### B2

> ❓ **Question.** A force of $20\ \mathrm{N}$ acts at $60°$ to a displacement of $5\ \mathrm{m}$. Find the work.

**✅ Answer.** $W = 20(5)\cos60° = 100(0.5) = \boxed{50\ \mathrm{J}}$.

---

<a id="b3"></a>
### B3

> ❓ **Question.** Find the kinetic energy of a $2\ \mathrm{kg}$ body moving at $3\ \mathrm{m/s}$.

**✅ Answer.** $K = \tfrac12 m v^2 = \tfrac12(2)(9) = \boxed{9\ \mathrm{J}}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** A $5\ \mathrm{kg}$ body is lifted $2\ \mathrm{m}$. Find the gain in potential energy.

**✅ Answer.** $U = mgh = 5(10)(2) = \boxed{100\ \mathrm{J}}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** A spring of stiffness $200\ \mathrm{N/m}$ is stretched $0.1\ \mathrm{m}$. Find its stored energy.

**✅ Answer.** $U = \tfrac12 k x^2 = \tfrac12(200)(0.01) = \boxed{1\ \mathrm{J}}$.

---

<a id="b6"></a>
### B6

> ❓ **Question.** A machine does $600\ \mathrm{J}$ of work in $3\ \mathrm{s}$. Find its power.

**✅ Answer.** $P = W/t = 600/3 = \boxed{200\ \mathrm{W}}$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** A $4\ \mathrm{N}$ force drives a body at $5\ \mathrm{m/s}$ in the same direction. Find the instantaneous power.

**✅ Answer.** $P = Fv = 4(5) = \boxed{20\ \mathrm{W}}$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** A body falls freely from rest through $5\ \mathrm{m}$. Using energy, find its speed on landing ($m$ cancels).

**✅ Answer.** $mgh = \tfrac12 m v^2 \Rightarrow v = \sqrt{2gh} = \sqrt{100} = \boxed{10\ \mathrm{m/s}}$.

---

<a id="b9"></a>
### B9

> ❓ **Question.** A $2\ \mathrm{kg}$ ball at $5\ \mathrm{m/s}$ hits a $2\ \mathrm{kg}$ stationary ball elastically (1D, equal masses). Find the final velocities.

**✅ Answer.** Equal masses exchange velocities: moving ball stops, struck ball moves at $\boxed{5\ \mathrm{m/s}}$.

---

<a id="b10"></a>
### B10

> ❓ **Question.** A $3\ \mathrm{kg}$ and a $2\ \mathrm{kg}$ lump of putty move toward each other at $4$ and $6\ \mathrm{m/s}$ and stick. Find their common velocity.

**✅ Answer.** $v = \dfrac{3(4) - 2(6)}{5} = \dfrac{12-12}{5} = \boxed{0\ \mathrm{m/s}}$ (they stop).

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** A $2\ \mathrm{kg}$ block is pulled $5\ \mathrm{m}$ along a rough floor ($\mu_k = 0.2$) by a $10\ \mathrm{N}$ horizontal force. Find the net work and final speed (starting from rest).

> [!TIP]
> 🧭 **Strategy.** Net work = (applied − friction)×distance; then work–energy theorem $W_{\text{net}} = \tfrac12 mv^2$.

**Steps.** $f = 0.2(2)(10) = 4\ \mathrm{N}$; $W_{\text{net}} = (10-4)(5) = 30\ \mathrm{J}$; $30 = \tfrac12(2)v^2 \Rightarrow v^2 = 30$.

**✅ Answer.** $W_{\text{net}} = 30\ \mathrm{J}$, $v = \sqrt{30} \approx 5.48\ \mathrm{m/s}$.

---

<a id="m2"></a>
### M2

> ❓ **Question.** A $1\ \mathrm{kg}$ ball is thrown up at $20\ \mathrm{m/s}$. Using energy, find the height where its speed is $10\ \mathrm{m/s}$.

> [!TIP]
> 🧭 **Strategy.** Energy conservation: $\tfrac12 m u^2 = \tfrac12 m v^2 + mgh$.

**Steps.** $\tfrac12(400) = \tfrac12(100) + 10h \Rightarrow 200 - 50 = 10h$.

**✅ Answer.** $h = 15\ \mathrm{m}$.

---

<a id="m3"></a>
### M3

> ❓ **Question.** A block slides down a frictionless incline of height $5\ \mathrm{m}$. Find its speed at the bottom.

> [!TIP]
> 🧭 **Strategy.** Energy conservation; the incline angle is irrelevant: $mgh = \tfrac12 mv^2$.

**Steps.** $v = \sqrt{2gh} = \sqrt{100}$.

**✅ Answer.** $v = 10\ \mathrm{m/s}$.

---

<a id="m4"></a>
### M4

> ❓ **Question.** A $2\ \mathrm{kg}$ block slides down a rough incline (height $5\ \mathrm{m}$, length $10\ \mathrm{m}$, $\mu_k = 0.25$). Find its speed at the bottom.

> [!TIP]
> 🧭 **Strategy.** $mgh - f\cdot L = \tfrac12 mv^2$, with $f = \mu_k mg\cos\theta$ and $\cos\theta = \sqrt{L^2-h^2}/L$.

**Steps.** $\cos\theta = \sqrt{100-25}/10 = 0.866$; $f = 0.25(2)(10)(0.866) = 4.33\ \mathrm{N}$; $mgh = 100\ \mathrm{J}$; friction loss $= 4.33(10) = 43.3\ \mathrm{J}$; $\tfrac12(2)v^2 = 56.7 \Rightarrow v^2 = 56.7$.

**✅ Answer.** $v \approx 7.5\ \mathrm{m/s}$.

---

<a id="m5"></a>
### M5

> ❓ **Question.** A spring ($k = 500\ \mathrm{N/m}$) is compressed $0.2\ \mathrm{m}$ and released, launching a $1\ \mathrm{kg}$ block on a frictionless floor. Find the block's speed.

> [!TIP]
> 🧭 **Strategy.** Spring PE → KE: $\tfrac12 kx^2 = \tfrac12 mv^2$.

**Steps.** $\tfrac12(500)(0.04) = \tfrac12(1)v^2 \Rightarrow 10 = 0.5v^2 \Rightarrow v^2 = 20$.

**✅ Answer.** $v = \sqrt{20} \approx 4.47\ \mathrm{m/s}$.

---

<a id="m6"></a>
### M6

> ❓ **Question.** A pump raises $600\ \mathrm{kg}$ of water through $10\ \mathrm{m}$ in $1$ minute. Find its power.

> [!TIP]
> 🧭 **Strategy.** $P = \dfrac{mgh}{t}$.

**Steps.** $P = \dfrac{600(10)(10)}{60} = \dfrac{60000}{60}$.

**✅ Answer.** $P = 1000\ \mathrm{W} = 1\ \mathrm{kW}$.

---

<a id="m7"></a>
### M7

> ❓ **Question.** A car of mass $1000\ \mathrm{kg}$ moves at a constant $20\ \mathrm{m/s}$ against a resistive force of $500\ \mathrm{N}$. Find the engine power.

> [!TIP]
> 🧭 **Strategy.** Constant speed → driving force = resistance; $P = Fv$.

**Steps.** $P = 500(20)$.

**✅ Answer.** $P = 10000\ \mathrm{W} = 10\ \mathrm{kW}$.

---

<a id="m8"></a>
### M8

> ❓ **Question.** A $5\ \mathrm{kg}$ ball at $4\ \mathrm{m/s}$ collides head-on with a $3\ \mathrm{kg}$ ball at rest; they stick. Find the common velocity and the KE lost.

> [!TIP]
> 🧭 **Strategy.** Perfectly inelastic: momentum conservation for $v$; then $\Delta KE = KE_i - KE_f$.

**Steps.** $v = \dfrac{5(4)}{8} = 2.5\ \mathrm{m/s}$; $KE_i = \tfrac12(5)(16) = 40\ \mathrm{J}$; $KE_f = \tfrac12(8)(6.25) = 25\ \mathrm{J}$.

**✅ Answer.** $v = 2.5\ \mathrm{m/s}$; KE lost $= 15\ \mathrm{J}$.

---

<a id="m9"></a>
### M9

> ❓ **Question.** A ball dropped from $5\ \mathrm{m}$ rebounds to $3.2\ \mathrm{m}$. Find the coefficient of restitution with the floor.

> [!TIP]
> 🧭 **Strategy.** For a bounce off a fixed floor, $e = \sqrt{h_{\text{rebound}}/h_{\text{drop}}}$ (speed $\propto \sqrt h$).

**Steps.** $e = \sqrt{3.2/5} = \sqrt{0.64}$.

**✅ Answer.** $e = 0.8$.

---

<a id="m10"></a>
### M10

> ❓ **Question.** A $0.5\ \mathrm{kg}$ ball moving at $6\ \mathrm{m/s}$ is stopped by a wall in $0.02\ \mathrm{s}$. Find the average power delivered to the wall during impact.

> [!TIP]
> 🧭 **Strategy.** Energy removed $= \tfrac12 mv^2$; power $= $ energy$/$time.

**Steps.** $KE = \tfrac12(0.5)(36) = 9\ \mathrm{J}$; $P = 9/0.02$.

**✅ Answer.** $P = 450\ \mathrm{W}$.

---

<a id="m11"></a>
### M11

> ❓ **Question.** A bullet of mass $20\ \mathrm{g}$ at $200\ \mathrm{m/s}$ embeds in a $2\ \mathrm{kg}$ block on a frictionless floor. Find the block+bullet speed and the KE lost.

> [!TIP]
> 🧭 **Strategy.** Perfectly inelastic: momentum conservation; KE loss is large because mass ratio is large.

**Steps.** $v = \dfrac{0.02(200)}{2.02} = \dfrac{4}{2.02} \approx 1.98\ \mathrm{m/s}$; $KE_i = \tfrac12(0.02)(40000) = 400\ \mathrm{J}$; $KE_f = \tfrac12(2.02)(3.92) \approx 3.96\ \mathrm{J}$.

**✅ Answer.** $v \approx 1.98\ \mathrm{m/s}$; KE lost $\approx 396\ \mathrm{J}$ (almost all of it).

---

<a id="m12"></a>
### M12

> ❓ **Question.** A $2\ \mathrm{kg}$ block on a rough floor ($\mu_k = 0.3$) is given an initial speed of $6\ \mathrm{m/s}$. How far does it slide before stopping?

> [!TIP]
> 🧭 **Strategy.** Work–energy: friction work removes all the KE. $\mu_k mg\, d = \tfrac12 mv^2$ (mass cancels).

**Steps.** $d = \dfrac{v^2}{2\mu_k g} = \dfrac{36}{2(0.3)(10)}$.

**✅ Answer.** $d = 6\ \mathrm{m}$.

---

<a id="m13"></a>
### M13

> ❓ **Question.** A pendulum bob of length $1\ \mathrm{m}$ is released from the horizontal. Find its speed at the lowest point.

> [!TIP]
> 🧭 **Strategy.** Energy conservation; drop in height $= L$. $mgL = \tfrac12 mv^2$.

**Steps.** $v = \sqrt{2gL} = \sqrt{20}$.

**✅ Answer.** $v = \sqrt{20} \approx 4.47\ \mathrm{m/s}$.

---

<a id="m14"></a>
### M14

> ❓ **Question.** A $1\ \mathrm{kg}$ block moving at $4\ \mathrm{m/s}$ on a frictionless floor hits a spring ($k = 400\ \mathrm{N/m}$). Find the maximum compression.

> [!TIP]
> 🧭 **Strategy.** All KE → spring PE at maximum compression: $\tfrac12 mv^2 = \tfrac12 kx^2$.

**Steps.** $\tfrac12(1)(16) = \tfrac12(400)x^2 \Rightarrow x^2 = 16/400 = 0.04$.

**✅ Answer.** $x = 0.2\ \mathrm{m}$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** An elastic head-on collision: $m_1 = 2\ \mathrm{kg}$ at $6\ \mathrm{m/s}$ hits $m_2 = 4\ \mathrm{kg}$ at rest. Find both final velocities.

> [!TIP]
> 🧭 **Strategy.** Use the 1D elastic-collision formulas with $u_2 = 0$.

**Steps.** $v_1 = \dfrac{(2-4)(6)}{6} = -2\ \mathrm{m/s}$; $v_2 = \dfrac{2(2)(6)}{6} = 4\ \mathrm{m/s}$.

**✅ Answer.** $v_1 = -2\ \mathrm{m/s}$ (bounces back), $v_2 = 4\ \mathrm{m/s}$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** A force $F = 3x^2\ \mathrm{N}$ acts on a body as it moves from $x=0$ to $x=2\ \mathrm{m}$. Find the work done.

> [!TIP]
> 🧭 **Strategy.** Variable force → $W = \int F\,dx$ (area under $F$–$x$).

**Steps.** $W = \int_0^2 3x^2\,dx = [x^3]_0^2 = 8$.

**✅ Answer.** $W = 8\ \mathrm{J}$.

---

<a id="a2"></a>
### A2

> ❓ **Question.** The potential energy of a particle is $U(x) = 5x^2 - 4x\ \mathrm{J}$. Find the force at $x=1\ \mathrm{m}$ and the equilibrium position.

> [!TIP]
> 🧭 **Strategy.** $F = -dU/dx$; equilibrium where $F = 0$.

**Steps.** $F = -(10x - 4)$; at $x=1$: $F = -(10-4) = -6\ \mathrm{N}$. Equilibrium: $10x - 4 = 0 \Rightarrow x = 0.4$.

**✅ Answer.** $F = -6\ \mathrm{N}$ at $x=1$; equilibrium at $x = 0.4\ \mathrm{m}$ (stable, since $U$ is a minimum).

---

<a id="a3"></a>
### A3

> ❓ **Question.** A ball on a string does a vertical circle of radius $1\ \mathrm{m}$. Find the minimum speed at the **bottom** to just complete the loop.

> [!TIP]
> 🧭 **Strategy.** Minimum loop: $v_{\text{top}} = \sqrt{gr}$; energy conservation gives $v_{\text{bot}} = \sqrt{5gr}$.

**Steps.** $v_{\text{bot}} = \sqrt{5(10)(1)} = \sqrt{50}$.

**✅ Answer.** $v_{\text{bot}} = \sqrt{50} \approx 7.07\ \mathrm{m/s}$.

---

<a id="a4"></a>
### A4

> ❓ **Question.** A $2\ \mathrm{kg}$ block slides $4\ \mathrm{m}$ down a rough $30°$ incline ($\mu_k = 0.2$), then compresses a spring ($k = 500\ \mathrm{N/m}$) at the bottom. Find the maximum compression. (Ignore the small extra slide distance on the spring.)

> [!TIP]
> 🧭 **Strategy.** Energy: $mgh - \mu_k mg\cos\theta\,d = \tfrac12 kx^2$, with $h = d\sin\theta$.

**Steps.** $h = 4\sin30° = 2\ \mathrm{m}$; $mgh = 2(10)(2) = 40\ \mathrm{J}$; friction $= 0.2(2)(10)(0.866)(4) = 13.9\ \mathrm{J}$; energy into spring $= 26.1\ \mathrm{J}$; $\tfrac12(500)x^2 = 26.1 \Rightarrow x^2 = 0.104$.

**✅ Answer.** $x \approx 0.32\ \mathrm{m}$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** An elastic collision between equal masses, one at rest: the incoming ball ($4\ \mathrm{m/s}$) is deflected. Show the two balls move off at $90°$, and if the incoming ball goes off at $30°$, find both final speeds.

> [!TIP]
> 🧭 **Strategy.** Equal masses, elastic, one at rest → final velocities are perpendicular. With the angle given, use $v_1 = u\cos\theta$, $v_2 = u\sin\theta$.

**Steps.** $v_1 = 4\cos30° = 3.46\ \mathrm{m/s}$; $v_2 = 4\sin30° = 2\ \mathrm{m/s}$. Check KE: $3.46^2 + 2^2 = 12 + 4 = 16 = 4^2$ ✓.

**✅ Answer.** The two fly apart at $90°$; $v_1 \approx 3.46\ \mathrm{m/s}$ (at $30°$), $v_2 = 2\ \mathrm{m/s}$ (at $60°$).

---

<a id="a6"></a>
### A6

> ❓ **Question.** A chain of mass $m$ and length $L$ lies on a frictionless table with a length $\ell$ hanging over the edge. Find the speed of the chain as the last link leaves the table (released from rest). Use energy.

> [!TIP]
> 🧭 **Strategy.** The CM of the chain falls; equate the loss in gravitational PE (CM drop) to the final KE $\tfrac12 mv^2$. For a chain fully leaving, the CM falls by $L/2$ minus its initial CM height.

**Steps.** Taking the simplest case where the chain starts fully on the table and ends fully hanging, the CM falls $L/2$: $mg\tfrac{L}{2} = \tfrac12 mv^2 \Rightarrow v = \sqrt{gL}$.

**✅ Answer.** $v = \sqrt{gL}$ (for the start-on-table to fully-hanging case).

---

<a id="a7"></a>
### A7

> ❓ **Question.** A $1\ \mathrm{kg}$ block on a rough horizontal surface ($\mu_k = 0.2$) is pushed against a spring ($k = 200\ \mathrm{N/m}$), compressing it $0.5\ \mathrm{m}$, then released. Find the speed of the block as it leaves the spring (natural length).

> [!TIP]
> 🧭 **Strategy.** Spring PE → KE + friction work over the compression distance: $\tfrac12 kx^2 = \tfrac12 mv^2 + \mu_k mg\,x$.

**Steps.** $\tfrac12(200)(0.25) = 25\ \mathrm{J}$; friction $= 0.2(1)(10)(0.5) = 1\ \mathrm{J}$; $\tfrac12(1)v^2 = 24 \Rightarrow v^2 = 48$.

**✅ Answer.** $v = \sqrt{48} \approx 6.93\ \mathrm{m/s}$.

---

<a id="a8"></a>
### A8

> ❓ **Question.** A particle's PE is $U(x) = \dfrac{a}{x^2} - \dfrac{b}{x}$ (with $a, b > 0$). Find the equilibrium position.

> [!TIP]
> 🧭 **Strategy.** Equilibrium where $F = -dU/dx = 0$.

**Steps.** $\dfrac{dU}{dx} = -\dfrac{2a}{x^3} + \dfrac{b}{x^2} = 0 \Rightarrow \dfrac{b}{x^2} = \dfrac{2a}{x^3} \Rightarrow x = \dfrac{2a}{b}$.

**✅ Answer.** $x = \dfrac{2a}{b}$ (a stable equilibrium — the bottom of the well).

---

<a id="a9"></a>
### A9

> ❓ **Question.** A block of mass $m$ is released from the top of a frictionless hemispherical dome of radius $R$. At what height (above the centre) does it leave the surface?

> [!TIP]
> 🧭 **Strategy.** It leaves when the normal force $N = 0$. Use energy conservation for $v$ at angle $\theta$ from the top, and the radial equation $mg\cos\theta - N = mv^2/R$.

**Steps.** Energy: $v^2 = 2gR(1-\cos\theta)$. At $N=0$: $g\cos\theta = v^2/R = 2g(1-\cos\theta) \Rightarrow \cos\theta = 2/3$. Height above centre $= R\cos\theta = 2R/3$.

**✅ Answer.** It leaves at height $\dfrac{2R}{3}$ above the centre ($\cos\theta = 2/3$).

---

<a id="a10"></a>
### A10

> ❓ **Question.** A $4\ \mathrm{kg}$ body moving at $5\ \mathrm{m/s}$ collides with a $6\ \mathrm{kg}$ body at rest; $e = 0.5$. Find both final velocities.

> [!TIP]
> 🧭 **Strategy.** Two equations: momentum conservation and the restitution relation $v_2 - v_1 = e(u_1 - u_2)$.

**Steps.**
1. Momentum: $4(5) = 4v_1 + 6v_2 \Rightarrow 20 = 4v_1 + 6v_2$.
2. Restitution: $v_2 - v_1 = 0.5(5) = 2.5$.
3. Substitute $v_2 = v_1 + 2.5$: $20 = 4v_1 + 6v_1 + 15 \Rightarrow 10v_1 = 5 \Rightarrow v_1 = 0.5$, $v_2 = 3$.

**✅ Answer.** $v_1 = 0.5\ \mathrm{m/s}$, $v_2 = 3\ \mathrm{m/s}$.

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style, and tag each
> with its difficulty and sub-topic (work / energy / power / collisions).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <work/energy/power/collision>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
