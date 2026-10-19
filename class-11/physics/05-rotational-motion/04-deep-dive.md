# Rotational Motion — Deep Dive

> JEE **Advanced**-level depth: subtle points, traps that cost marks, and the
> recurring patterns of previous-year questions (PYQs). Read this once the
> [concepts](./01-concepts.md) and [solved numericals](./02-solved-numericals.md) feel solid.

---

## 📑 Index

1. [Choosing the axis is half the battle](#1-choosing-the-axis-is-half-the-battle)
2. [The falling-rod paradox (end accelerates faster than g)](#2-the-falling-rod-paradox-end-accelerates-faster-than-g)
3. [Friction in rolling — the most-misunderstood force](#3-friction-in-rolling--the-most-misunderstood-force)
4. [Energy vs momentum — know which is conserved](#4-energy-vs-momentum--know-which-is-conserved)
5. [Instantaneous axis of rotation (IAOR)](#5-instantaneous-axis-of-rotation-iaor)
6. [Common traps checklist](#6-common-traps-checklist)
7. [Previous-year question (PYQ) patterns](#7-previous-year-question-pyq-patterns)
8. [Astronomy connection](#8-astronomy-connection-optional-enrichment)

---

## 1. Choosing the axis is half the battle

Almost every "hard" rotational problem becomes easy if you pick the right point to take torque / angular momentum about. Guidelines:

- **Take torques about the point where unknown forces act** — they then contribute zero torque and vanish from the equation. (In the ladder and rod-on-pivot problems, taking torque about the hinge kills the hinge reaction.)
- For **rolling**, three axis choices all work; pick deliberately:
  - about the **COM** → use $\tau = I_{cm}\alpha$ with friction as the only torque.
  - about the **contact point** → friction and normal give zero torque; often one-line answers (use $I_{contact} = I_{cm} + mR^2$).
- **Angular momentum about a point on the ground** is the trick for *sliding-to-rolling* problems, because friction acts at ground level and exerts no torque about that line.

> [!TIP]
> If a problem has an unknown force you don't care about (a hinge reaction, the normal, friction during a collision), take torque about the point it acts through. This single habit removes most of the algebra.

---

## 2. The falling-rod paradox (end accelerates faster than g)

In solved problem A1, the free end of a released horizontal rod accelerates at $\tfrac{3g}{2} > g$. A coin placed near the end **separates from the rod and lags behind** (the rod drops away faster than free fall). The crossover point is where $a = g$, i.e. at distance $r = \tfrac{2L}{3}$ from the pivot. Beyond that, the rod outruns gravity.

This is a classic Advanced conceptual MCQ — "a chalk/coin on a falling hinged rod": the part beyond $2L/3$ leaves the rod.

---

## 3. Friction in rolling — the most-misunderstood force

- **Rolling without slipping is a *constraint*, not a given.** Friction is whatever it needs to be (up to $\mu N$) to maintain $v = R\omega$. It is **static** friction and does **no work** — that is why energy conservation is valid for a body rolling without slipping.
- **Direction is not obvious.** On an incline, friction on a rolling body acts **up** the slope (it provides the torque that spins the body up). For a body being *driven* (a car wheel under engine torque), friction acts **forward**. Always solve for it with signs; never assume.
- If the required static friction exceeds $\mu_s N$, the body **slips**, and you must switch to **kinetic** friction $\mu_k N$ with $v \ne R\omega$ (two independent equations now).

> [!WARNING]
> On a **frictionless** incline a body **cannot roll** — it only slides, because there is no torque to produce angular acceleration. "Rolls down a smooth incline" is a trap; the answer is pure translation with $a = g\sin\theta$ and $\omega$ unchanged.

---

## 4. Energy vs momentum — know which is conserved

| Situation | Conserved | NOT conserved | Why |
|---|---|---|---|
| Rolling w/o slipping | mechanical energy **and** $L$ (about contact) | — | static friction does no work |
| Skater pulling arms in | $L$ | KE (increases) | muscles do internal work |
| Ring dropped on spinning disc | $L$ | KE (decreases) | slipping/friction dissipates heat |
| Discs coupled by clutch | $L$ | KE (decreases) | kinetic friction at interface |
| Bullet embeds in rod | $L$ (about pivot) | KE and **linear** $p$ | pivot delivers impulse; inelastic |

> [!IMPORTANT]
> In any "sudden coupling / dropping / embedding" problem, **angular momentum is conserved but kinetic energy is not.** Never equate KE across such an event. Conversely, in smooth rolling, energy conservation is your friend. Mixing these up is the single most common Advanced error in this chapter.

**A subtle one on linear momentum:** when a bullet hits a rod pivoted at its centre, linear momentum is **not** conserved (the pivot delivers an external impulse), but angular momentum about the pivot **is**. If the rod is instead **free** (no pivot), both linear and angular momentum are conserved, and you track the COM motion separately from the spin.

---

## 5. Instantaneous axis of rotation (IAOR)

A rolling wheel can be analysed as **pure rotation about the contact point** at each instant. This gives speeds instantly:
- top point: distance $2R$ from contact → $v = \omega(2R) = 2v_{cm}$
- centre: distance $R$ → $v_{cm}$
- contact point: distance $0$ → $0$

Using $I_{contact} = \tfrac12 mR^2 + mR^2 = \tfrac32 mR^2$ for a disc, $K = \tfrac12 I_{contact}\omega^2 = \tfrac34 mR^2\omega^2 = \tfrac34 mv^2$, which matches $\tfrac12 mv^2 + \tfrac14 mv^2$. Same answer, fewer steps.

---

## 6. Common traps checklist

- [ ] **Perpendicular-axis theorem on a 3-D body** — illegal. Laminae only.
- [ ] **Parallel-axis from a non-COM axis** — $I_{cm}$ must be about the axis through the COM, not any convenient axis.
- [ ] **Forgetting rotational KE in rolling energy balance** — gives wrong $v$ at the bottom of an incline (you'd get $\sqrt{2gh}$, too large).
- [ ] **Assuming $v = R\omega$ when the body slips** — only valid for rolling *without* slipping.
- [ ] **Using $\tau = I\alpha$ about an accelerating point that isn't the COM** — only valid about the COM or a fixed axis. For a general accelerating axis, extra (pseudo) terms appear.
- [ ] **Sign of friction on an incline assumed downward** — it's up the incline for free rolling.
- [ ] **Mass/radius dependence in roll-down races** — there is none; only $k^2/R^2$ matters.
- [ ] **Angular momentum of a particle in straight-line motion assumed zero** — it's $mvr_\perp \ne 0$ unless the line passes through the axis.

---

## 7. Previous-year question (PYQ) patterns

These recur almost every year in some form:

1. **Roll-down / race problems** — order of arrival, time, or acceleration ratio of sphere/disc/ring. (Pure plug-in of $k^2/R^2$.)
2. **Combined translation + rotation on an incline** — find $a$, friction, or minimum $\mu$ to avoid slipping.
3. **Angular-momentum-conservation "collapse" problems** — skater, turntable with walking person, ring-on-disc, mud/insect landing on a rotating body.
4. **Hinged rod dynamics** — $\alpha$ at release, $\omega$ at an angle, reaction at the hinge, the $a > g$ coin trick.
5. **Massive-pulley Atwood / block-pulley systems** — two tensions differ because the pulley has inertia.
6. **Ballistic-pendulum-style angular collisions** — bullet/particle striking a rod or disc; conserve $L$, then energy *after* if asked for rise/compression.
7. **Rolling through a loop or over a step** — energy with the $\tfrac{k^2}{R^2}$ factor; minimum height $h = (2 + \tfrac{k^2}{R^2}\cdot\tfrac12\cdot\ldots)R$ type.
8. **Toppling vs sliding** of a block/cylinder on an incline — compare the torque-balance angle with $\tan^{-1}\mu$.

> [!NOTE]
> In Advanced, these are rarely single-concept. A typical problem chains two ideas:
> *conserve $L$ during a collision → then use energy to find how high the system rises.*
> Identify the **event** (momentum) and the **process** (energy) separately.

---

## 8. Astronomy connection (optional enrichment)

Conservation of angular momentum runs the sky:
- **Kepler's second law** (equal areas in equal times) is just $L = $ constant for a planet — it speeds up at perihelion exactly as the skater does when pulling in.
- A **collapsing gas cloud** spins faster as it shrinks (same $I\omega$ law), which is why stars and accretion discs rotate rapidly; a **neutron star / pulsar** spins many times per second because a huge star's $I$ collapsed to a tiny value.
- **Tidal locking** and the slow lengthening of Earth's day are angular-momentum transfer between Earth's spin and the Moon's orbit.

Same single equation, $I_1\omega_1 = I_2\omega_2$, from a skater to a pulsar.

---

**Next:** [Formula Recap →](./05-formula-recap.md)
