# Kinematics — Deep Dive

> The methods that make kinematics fast: reading graphs as calculus, the three "which relation do I
> use" cases for non-uniform acceleration, projectiles as vectors, and the frame-switching trick for
> relative motion. Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. g = 10 m/s². -->

---

## 📑 Index

1. [Graphs are calculus in disguise](#1-graphs-are-calculus)
2. [Non-uniform acceleration: the decision table](#2-non-uniform-acceleration)
3. [Projectiles as vectors](#3-projectiles-as-vectors)
4. [Radius of curvature anywhere on a path](#4-radius-of-curvature)
5. [Relative motion: switch frames and win](#5-relative-motion)
6. [River and rain, systematically](#6-river-and-rain)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-graphs-are-calculus"></a>
## 1. Graphs are calculus in disguise

Every graph relationship in kinematics is a derivative (slope) or an integral (area):

$$v = \frac{dx}{dt}\ (\text{slope of } x\text{–}t), \qquad a = \frac{dv}{dt}\ (\text{slope of } v\text{–}t)$$
$$\Delta x = \int v\,dt\ (\text{area under } v\text{–}t), \qquad \Delta v = \int a\,dt\ (\text{area under } a\text{–}t)$$

> [!TIP]
> Fast reads that win marks:
> - A **straight** $x$–$t$ line = constant velocity; a **curved** one = acceleration (concave up → speeding up in $+x$).
> - On a $v$–$t$ graph, **area below the time axis is negative displacement** — so "distance" needs the areas added as positive, while "displacement" keeps the signs.
> - The point where a $v$–$t$ curve **crosses zero** is where the body reverses — split distance calculations there.

---

<a id="2-non-uniform-acceleration"></a>
## 2. Non-uniform acceleration: the decision table

When $a$ isn't constant, pick the relation by **what the acceleration depends on**:

| $a$ given as… | Start from | Separate as | Integrate to get |
|---|---|---|---|
| $a = f(t)$ | $a = \dfrac{dv}{dt}$ | $dv = f(t)\,dt$ | $v(t)$, then $x(t)$ |
| $a = f(x)$ | $a = v\dfrac{dv}{dx}$ | $v\,dv = f(x)\,dx$ | $v(x)$ |
| $a = f(v)$ | $a = \dfrac{dv}{dt}$ or $v\dfrac{dv}{dx}$ | $\dfrac{dv}{f(v)} = dt$ or $\dfrac{v\,dv}{f(v)} = dx$ | $v(t)$ or $v(x)$ |

> [!IMPORTANT]
> The relation $a = v\dfrac{dv}{dx}$ (from $\dfrac{dv}{dt} = \dfrac{dv}{dx}\dfrac{dx}{dt}$) is the one
> students forget — it's the *only* clean route when acceleration depends on position. Carry definite
> limits (initial → final) instead of chasing an integration constant.

**Worked idea — drag $a = -kv$:** $\dfrac{dv}{v} = -k\,dt \Rightarrow v = v_0 e^{-kt}$ (exponential
decay, never quite zero in time). For stopping *distance*, use $v\,dv/dx = -kv \Rightarrow dv = -k\,dx$,
giving a **finite** distance $x = v_0/k$ — a classic "it stops in finite distance but infinite time."

---

<a id="3-projectiles-as-vectors"></a>
## 3. Projectiles as vectors

Write the whole motion as two independent 1D motions, then recombine:
$$\vec{r}(t) = (u\cos\theta)\,t\,\hat{i} + \left(u\sin\theta\,t - \tfrac12 g t^2\right)\hat{j}$$
$$\vec{v}(t) = u\cos\theta\,\hat{i} + (u\sin\theta - gt)\,\hat{j}$$

- **Speed at time $t$:** $|\vec v| = \sqrt{(u\cos\theta)^2 + (u\sin\theta - gt)^2}$.
- **Direction:** $\tan\phi = \dfrac{u\sin\theta - gt}{u\cos\theta}$ (angle of velocity with horizontal; negative while descending).
- **Trajectory (eliminate $t$):** $y = x\tan\theta - \dfrac{g x^2}{2u^2\cos^2\theta}$ — a downward parabola. The $x^2$ coefficient fixes how "tight" it is.

> [!NOTE]
> Because horizontal velocity is constant, two projectiles launched with the **same horizontal
> component** stay vertically above/below each other for all time. And the velocity vector is tangent
> to the path — its perpendicular component of $g$ is what curves the trajectory (Section 4).

---

<a id="4-radius-of-curvature"></a>
## 4. Radius of curvature anywhere on a path

At any instant a curved path has an instantaneous circle of radius $r$. The component of acceleration
**perpendicular to the velocity** is the centripetal acceleration of that circle:
$$a_\perp = \frac{v^2}{r} \quad\Rightarrow\quad \boxed{r = \frac{v^2}{a_\perp}}$$

For a projectile, the only acceleration is $g$ (down), so $a_\perp = g\cos\phi$ where $\phi$ is the
velocity's angle with the horizontal.
- **At the top** of a ground-to-ground projectile: $\phi = 0$, $v = u\cos\theta$, so $r = \dfrac{u^2\cos^2\theta}{g}$.
- **At launch:** $\phi = \theta$, $v = u$, so $r = \dfrac{u^2}{g\cos\theta}$.

> [!TIP]
> Decompose acceleration into **tangential** ($a_\parallel$, changes speed) and **normal**
> ($a_\perp$, changes direction). Only $a_\perp$ enters the radius of curvature. This split is the
> bridge from kinematics to circular motion.

---

<a id="5-relative-motion"></a>
## 5. Relative motion: switch frames and win

The one idea: to analyse A relative to B, **sit on B**. In B's frame, B is at rest and A moves with
$$\vec v_{AB} = \vec v_A - \vec v_B.$$

This turns "two bodies both moving" into "one fixed point and one body moving in a straight line,"
so **minimum-distance, collision, and interception problems become geometry:**
- **Closest approach** = perpendicular distance from the fixed body to the relative-velocity line:
  $d_{\min} = \dfrac{|\vec r_0 \times \vec v_{AB}|}{|\vec v_{AB}|}$, reached at
  $t = -\dfrac{\vec r_0 \cdot \vec v_{AB}}{|\vec v_{AB}|^2}$ (with $\vec r_0$ the initial separation).
- **They collide** iff $\vec r_0$ is antiparallel to $\vec v_{AB}$ (relative velocity points straight at the body).

> [!IMPORTANT]
> If the frame-switch gives a $t < 0$ for closest approach, the bodies are already separating — the
> minimum distance is the *current* separation. Always check the sign of $t$.

---

<a id="6-river-and-rain"></a>
## 6. River and rain, systematically

**River crossing — know which question is being asked:**

| Goal | Heading | Crossing time | Drift |
|---|---|---|---|
| Minimum **time** | straight across (perpendicular) | $d/v_b$ | $v_r \cdot d/v_b$ |
| Minimum **path** (zero drift) | upstream, $\sin\theta = v_r/v_b$ | $d/\sqrt{v_b^2 - v_r^2}$ | $0$ |

(Zero-drift crossing is only possible if $v_b > v_r$.)

**Rain:** the apparent rain velocity is $\vec v_{\text{rain, man}} = \vec v_{\text{rain}} - \vec v_{\text{man}}$;
tilt the umbrella along it. If rain is vertical ($v_r$) and you move horizontally ($v_m$), the tilt
from vertical is $\tan^{-1}(v_m/v_r)$ and the apparent speed is $\sqrt{v_r^2 + v_m^2}$.

> [!WARNING]
> "Shortest time" and "shortest path" are **different** crossings with different headings — mixing
> them up is the single most common river-boat error. Decide which the question wants *before* drawing.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **Distance vs displacement** (and speed vs velocity): watch for direction reversals.
> - **Constant-$a$ equations misused** when $a$ varies — switch to calculus.
> - **$s$ in $v^2 = u^2 + 2as$ is displacement**, not path length; split at the turning point if the body reverses.
> - **Sign convention:** choose $+$ direction once; give $u, v, a, s$ their signs consistently.
> - **Projectile:** range is max at $45°$; complementary angles share a range; horizontal velocity is constant.
> - **"$n$th second" distance** uses $s_n = u + \tfrac a2(2n-1)$, not the full $s=ut+\tfrac12at^2$.
> - **Relative motion:** subtract vectors; check the sign of the closest-approach time.
> - **$g$ value:** confirm whether the problem wants $9.8$ or $10\ \mathrm{m/s^2}$.
