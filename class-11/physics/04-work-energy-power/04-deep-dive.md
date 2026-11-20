# Work, Energy & Power — Deep Dive

> The methods that make energy problems fast: when to drop forces and use the work–energy theorem, how
> energy conservation absorbs friction, reading force from a potential ($F=-dU/dx$), and the momentum+energy
> two-equation routine for collisions. Read once you're comfortable with the [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. g = 10 m/s². -->

---

## 📑 Index

1. [When to use work–energy instead of F = ma](#1-when-work-energy)
2. [Energy conservation with and without friction](#2-conservation)
3. [Work as the area under F–x](#3-area)
4. [Force from a potential: F = −dU/dx](#4-force-from-potential)
5. [Collisions: the two-equation routine](#5-collisions)
6. [Power and the P = Fv viewpoint](#6-power)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-when-work-energy"></a>
## 1. When to use work–energy instead of F = ma

The work–energy theorem $W_{\text{net}} = \Delta K$ is the tool of choice whenever the question links
**force and distance to speed** and you **don't care about time**.

- Use **work–energy / energy conservation** when: speeds at two positions, heights, spring compressions, or stopping distances are involved, and time is not asked.
- Use **F = ma / kinematics** when: time, or instantaneous acceleration, is central.

> [!TIP]
> If a problem gives you a distance and asks for a speed (or vice versa) on a track, incline, or spring —
> and never mentions time — energy is almost always faster than resolving forces and integrating. One
> scalar equation replaces vector bookkeeping.

---

<a id="2-conservation"></a>
## 2. Energy conservation with and without friction

**No friction (only conservative forces):**
$$K_1 + U_1 = K_2 + U_2$$

**With friction (or any non-conservative force):** the lost mechanical energy equals the friction work:
$$(K_1 + U_1) - (K_2 + U_2) = f\cdot d = \mu_k N d$$

> [!IMPORTANT]
> Friction energy loss is $f \times$ (**path length**), not displacement — on a back-and-forth path, add up
> every segment. Heat generated = total friction work. Unlike gravity or springs, this energy never comes
> back, so friction can't be written as a potential energy.

---

<a id="3-area"></a>
## 3. Work as the area under F–x

For a variable force, work is the integral — i.e. the **signed area** under the force–displacement graph:
$$W = \int_{x_1}^{x_2} F(x)\,dx$$

- A spring: $F = -kx$, so the area is a triangle → $W = -\tfrac12 kx^2$ (work by the spring as it's stretched; the stored PE is $+\tfrac12 kx^2$).
- Area **below** the axis (force opposing motion) is negative work.

> [!NOTE]
> This is the same "area/slope" idea that powers kinematics graphs. For a linear force like a spring, you
> rarely need to integrate — just take $\tfrac12 \times$ base $\times$ height of the triangle.

---

<a id="4-force-from-potential"></a>
## 4. Force from a potential: F = −dU/dx

For any conservative force, the force is the **negative slope** of the potential-energy curve:
$$F_x = -\frac{dU}{dx}$$

- **Equilibrium** where $F = 0 \Rightarrow dU/dx = 0$ (a turning point of $U$).
- **Stable** equilibrium at a **minimum** of $U$ ($d^2U/dx^2 > 0$); **unstable** at a **maximum**.
- Near a stable minimum, $U \approx \tfrac12 k_{\text{eff}} x^2$ — the system behaves like a spring → **SHM** (bridge to Oscillations).

> [!TIP]
> Think of the PE curve as a landscape and the particle as a ball rolling on it: it accelerates downhill
> ($F$ points toward lower $U$), rests at valleys (stable) and balances precariously on peaks (unstable).
> This picture answers most "is this equilibrium stable?" questions at a glance.

---

<a id="5-collisions"></a>
## 5. Collisions: the two-equation routine

Every collision gives you **momentum conservation** for free (no external force during the brief impact).
That's one equation; you need a second:

| Collision type | Second equation |
|---|---|
| Elastic | KE conserved, or equivalently $e = 1$: $v_2 - v_1 = u_1 - u_2$ |
| General | restitution: $v_2 - v_1 = e(u_1 - u_2)$ |
| Perfectly inelastic | they stick: $v_1 = v_2$ |

**Useful facts:**
- Equal masses, elastic → **exchange velocities**.
- Elastic, one at rest, equal masses, 2D → fly apart at **90°**.
- Maximum KE loss occurs in a **perfectly inelastic** collision (but momentum is still conserved).

> [!IMPORTANT]
> Never start a collision with energy conservation — KE is **not** generally conserved. Start with
> **momentum** (always valid), then bring in the restitution coefficient or the elastic-KE condition as
> the second equation. Resolve into components for 2D.

---

<a id="6-power"></a>
## 6. Power and the P = Fv viewpoint

Instantaneous power $P = \vec F \cdot \vec v$. Two common uses:

- **Top speed:** at maximum speed acceleration is zero, so the driving force equals resistance, and
  $v_{\max} = P/F_{\text{resist}}$.
- **Climbing / lifting:** a motor raising mass at steady speed $v$ up a slope of angle $\theta$ needs
  $P = (mg\sin\theta + f)\,v$.

> [!NOTE]
> Because $P = Fv$, a vehicle has **less** force available at high speed for the same engine power — which
> is why acceleration tails off near top speed. Power, not force, is the fixed budget.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **Work can be zero or negative** — perpendicular force (centripetal, normal on flat path) does zero work; friction and gravity-against-rise do negative work.
> - **Friction loss uses path length**, not displacement; it's never a potential energy.
> - **Spring PE is $\tfrac12 kx^2$** (always positive), with force $F = -kx$; don't forget the factor $\tfrac12$.
> - **Collisions: momentum first**, energy/restitution second; KE is conserved only if elastic.
> - **$e = \sqrt{h_{\text{rebound}}/h_{\text{drop}}}$** for a bounce off a fixed floor.
> - **Vertical circle:** $v_{\text{top}} = \sqrt{gr}$, $v_{\text{bottom}} = \sqrt{5gr}$, $h_{\min} = 5r/2$ from rest.
> - **$F = -dU/dx$:** minimum of $U$ = stable; use it to spot SHM.
> - **$P = Fv$**, and for lifting water $P = mgh/t$.
