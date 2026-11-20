# Laws of Motion — Deep Dive

> The methods that make dynamics fast: the free-body-diagram discipline, the "system then part" trick for
> connected bodies, the assume-check-correct loop for friction, choosing inertial vs non-inertial frames,
> and the radial/tangential split for circular motion. Read once you're comfortable with the
> [Concepts](./01-concepts.md).

<!-- RENDERING: inside math use \cdot (not ·), \perp as plain words, \to for arrows. g = 10 m/s². -->

---

## 📑 Index

1. [The free-body diagram is the whole game](#1-fbd)
2. [Connected bodies: system first, then isolate](#2-connected)
3. [Friction: the assume–check–correct loop](#3-friction)
4. [Inertial vs non-inertial: when to use pseudo-forces](#4-frames)
5. [Circular motion: radial and tangential](#5-circular)
6. [Momentum and impulse viewpoint](#6-momentum)
7. [Exam traps checklist](#7-exam-traps)

Related: [Concepts](./01-concepts.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="1-fbd"></a>
## 1. The free-body diagram is the whole game

Almost every mistake in this chapter is a **missing or wrong force** on the FBD. The discipline:

1. **Isolate one body.** Draw only the forces *on* it (never forces it exerts on others).
2. **Name each force by its source:** gravity ($mg$ down), each contact surface ($N$ perpendicular, $f$ along), each string ($T$ away along the string), applied forces.
3. **Choose axes** that make one direction the motion direction (tilt for inclines).
4. Write $\sum F_x = ma_x$, $\sum F_y = ma_y$.

> [!IMPORTANT]
> The **normal force is a variable**, not automatically $mg$. On an incline $N = mg\cos\theta$; in a lift
> $N = m(g\pm a)$; when you push down at an angle, $N$ grows. Solve for $N$ from the perpendicular
> equation — many friction errors are really wrong-$N$ errors.

---

<a id="2-connected"></a>
## 2. Connected bodies: system first, then isolate

For blocks joined by strings/contact that share one acceleration:

- **System method** (fast acceleration): treat everything as one mass. $a = \dfrac{F_{\text{net,external}}}{M_{\text{total}}}$. Internal tensions/contact forces **cancel** here.
- **Isolation method** (internal forces): draw an FBD of a single body and write $F = ma$ for it — the only unknown left is the tension/contact force.

$$a = \frac{F_{\text{ext}}}{\sum m}, \qquad T_{\text{on a body}} = m_{\text{body}}\,a \ (\text{if that string only pulls that body})$$

> [!TIP]
> To find a particular string tension, isolate the part of the chain on **one side** of that string and
> apply $F = ma$ to just that sub-system. The string tension equals (mass of that sub-system) × (shared
> acceleration), plus/minus any external force on it. This beats solving the full simultaneous set.

---

<a id="3-friction"></a>
## 3. Friction: the assume–check–correct loop

Static friction is a *range* ($0 \le f_s \le \mu_s N$), so you can't plug a number in blindly. The routine:

1. **Assume no sliding.** Compute the friction force *required* for equilibrium / shared motion.
2. **Check** it against the maximum $\mu_s N$.
3. If required $\le \mu_s N$: the body stays/moves together, and $f_s$ = the required value (**not** $\mu_s N$).
4. If required $> \mu_s N$: it slides; switch to $f_k = \mu_k N$ and redo with kinetic friction.

> [!WARNING]
> Do **not** set $f = \mu_s N$ when the body isn't on the verge of slipping — static friction only equals
> its maximum at the point of impending motion. A block in equilibrium under a $3\ \mathrm{N}$ push with
> $\mu_s N = 8\ \mathrm{N}$ has $f_s = 3\ \mathrm{N}$, not $8\ \mathrm{N}$.

**Key inclined-plane results** (angle $\theta$): stays if $\tan\theta \le \mu_s$; sliding down
$a = g(\sin\theta - \mu_k\cos\theta)$; pushed up $a = g(\sin\theta + \mu_k\cos\theta)$ (deceleration).

---

<a id="4-frames"></a>
## 4. Inertial vs non-inertial: when to use pseudo-forces

You may solve any problem in the **ground (inertial) frame** using only real forces. Choosing an
**accelerating frame** (the lift, the wedge, the turning car) can be simpler — but then you must add a
pseudo-force $-m\vec a_0$ to every body.

| Frame | Forces to include | When it's easier |
|---|---|---|
| Inertial (ground) | real forces only | always valid; default |
| Non-inertial (accelerating) | real + pseudo-force $-m\vec a_0$ | when the body is *at rest in that frame* |

> [!IMPORTANT]
> The giveaway that a pseudo-force helps: the body is **stationary relative to the accelerating object**
> (bob fixed in the car, block riding on the wedge). In that frame the body is in equilibrium, so you just
> balance real forces + pseudo-force — no acceleration terms. Both frames give identical answers; never mix
> them (no centrifugal force in the ground frame).

---

<a id="5-circular"></a>
## 5. Circular motion: radial and tangential

Resolve every real force into two directions at each instant:
$$\underbrace{\sum F_{\text{radial (inward)}} = \frac{mv^2}{r}}_{\text{changes direction}}, \qquad \underbrace{\sum F_{\text{tangential}} = m a_t}_{\text{changes speed}}$$

- **Uniform circular motion:** $a_t = 0$; only the radial equation matters.
- **Vertical circle:** speed varies, so use **energy conservation** for $v$ at each point, then the radial
  equation for the tension/normal force. Critical speeds: $v_{\text{top}} = \sqrt{gr}$, $v_{\text{bottom}} = \sqrt{5gr}$.
- **Banking:** the normal force tilts, so its horizontal component helps turn the car. Frictionless design
  speed $\tan\theta = v^2/rg$; with friction you get a speed *range*.

> [!TIP]
> "Centripetal force" is a **requirement**, not a source. Always ask *which real force(s) point inward* —
> tension, gravity, normal, friction — and set their inward sum to $mv^2/r$. If you ever write "centrifugal
> force" in the ground frame, you've double-counted.

---

<a id="6-momentum"></a>
## 6. Momentum and impulse viewpoint

The $\vec F = d\vec p/dt$ form is more general than $F = ma$ and is the right tool when:
- **Mass changes** (rockets, falling chains, conveyor belts): $F = v\dfrac{dm}{dt} + m\dfrac{dv}{dt}$.
- **Large force, short time** (collisions, kicks): use impulse $\vec J = \int \vec F\,dt = \Delta\vec p$; the *average* force is $\Delta p/\Delta t$.
- **No external force:** total momentum is conserved — recoil, explosions, collisions.

> [!NOTE]
> Impulse = area under the force–time graph. A soft catch (longer $\Delta t$) reduces the average force for
> the same $\Delta p$ — why we bend our knees on landing and why airbags work.

---

<a id="7-exam-traps"></a>
## 7. Exam traps checklist

> [!WARNING]
> - **Action–reaction act on different bodies** — they never cancel on one FBD.
> - **Normal force is not always $mg$** — solve for it (incline, lift, angled push).
> - **Static friction $\ne \mu_s N$ unless on the verge** — it self-adjusts up to that max.
> - **"Centripetal force" is the net inward force**, supplied by real forces; no centrifugal force in the ground frame.
> - **Tension is uniform only in a massless string** over an ideal pulley.
> - **Check the direction of motion** before deciding whether friction (or gravity on an incline) adds or subtracts.
> - **Vertical circle:** use energy conservation for speed, then the radial equation — don't assume constant speed.
> - **Lift problems:** $N = m(g + a)$ for up-acceleration, $m(g - a)$ for down; $N = 0$ in free fall.
