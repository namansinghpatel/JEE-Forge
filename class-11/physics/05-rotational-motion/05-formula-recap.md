# Rotational Motion — Formula Recap

> One-page revision sheet. Everything you need the night before a test.
> Full explanations in [01-concepts.md](./01-concepts.md).

---

## 📑 Index

[Angular kinematics](#angular-kinematics-constant-alpha) · [Centre of mass](#centre-of-mass) · [Torque, I, Newton's 2nd law](#torque-moment-of-inertia-newtons-2nd-law) · [Moment of inertia table](#moment-of-inertia-table-memorise) · [Energy, momentum, power](#energy-momentum-power) · [Rolling](#rolling-without-slipping) · [Standard results](#standard-results-worth-memorising) · [Linear→rotational dictionary](#the-dictionary-linear--rotational)

---

## Angular kinematics (constant $\alpha$)

$$\omega = \omega_0 + \alpha t \qquad \theta = \omega_0 t + \tfrac12\alpha t^2 \qquad \omega^2 = \omega_0^2 + 2\alpha\theta$$

**Linear ↔ angular links:** $\quad s = R\theta,\quad v = R\omega,\quad a_t = R\alpha,\quad a_c = \omega^2 R = \dfrac{v^2}{R}$

---

## Centre of mass

$$\vec r_{cm} = \frac{\sum m_i \vec r_i}{\sum m_i}, \qquad M\vec a_{cm} = \vec F_{ext}$$

| Body | COM |
|---|---|
| Semicircular ring | $2R/\pi$ from centre |
| Semicircular disc | $4R/3\pi$ |
| Solid hemisphere | $3R/8$ |

---

## Torque, moment of inertia, Newton's 2nd law

$$\vec\tau = \vec r\times\vec F,\quad |\tau| = rF\sin\theta = F r_\perp$$
$$I = \sum m_i r_i^2 = \int r^2\,dm, \qquad I = Mk^2,\qquad \boxed{\tau_{net} = I\alpha}$$

**Axis theorems**
$$I = I_{cm} + Md^2 \quad \text{(parallel axis)}, \qquad I_z = I_x + I_y \quad \text{(perpendicular axis; planar laminae only)}$$

---

## Moment of inertia table (memorise)

| Body | Axis | $I$ | $k^2/R^2$ |
|---|---|---|---|
| Rod | centre, ⟂ | $\tfrac{1}{12}ML^2$ | — |
| Rod | end, ⟂ | $\tfrac13 ML^2$ | — |
| Ring | centre, ⟂ | $MR^2$ | $1$ |
| Ring | diameter | $\tfrac12 MR^2$ | — |
| Disc | centre, ⟂ | $\tfrac12 MR^2$ | $1/2$ |
| Disc | diameter | $\tfrac14 MR^2$ | — |
| Solid sphere | diameter | $\tfrac25 MR^2$ | $2/5$ |
| Hollow sphere | diameter | $\tfrac23 MR^2$ | $2/3$ |
| Solid cylinder | central axis | $\tfrac12 MR^2$ | $1/2$ |
| Hollow cylinder | central axis | $MR^2$ | $1$ |

---

## Energy, momentum, power

$$K_{rot} = \tfrac12 I\omega^2 = \frac{L^2}{2I}, \qquad L = I\omega, \qquad \boxed{\tau_{ext} = \frac{dL}{dt}}$$
$$W = \tau\theta, \qquad P = \tau\omega$$

**Conservation of $L$:** $\quad \tau_{ext} = 0 \Rightarrow I_1\omega_1 = I_2\omega_2$

---

## Rolling without slipping

> Constraint: $v = R\omega$

$$K = \tfrac12 Mv^2\left(1 + \frac{k^2}{R^2}\right)$$
$$a_{incline} = \frac{g\sin\theta}{1 + k^2/R^2}, \qquad v_{bottom} = \sqrt{\frac{2gh}{1 + k^2/R^2}}$$
$$\mu_{min} = \frac{(k^2/R^2)\tan\theta}{1 + k^2/R^2}$$

**Points on a rolling wheel:** top $= 2v_{cm}$, centre $= v_{cm}$, contact $= 0$.

**Roll-down order (fastest → slowest):** solid sphere ($0.714\,g\sin\theta$) → disc/solid cylinder ($0.667$) → hollow sphere ($0.600$) → ring/hollow cylinder ($0.500$).

---

## Standard results worth memorising

| Situation | Result |
|---|---|
| Hinged rod released from horizontal | $\alpha = \dfrac{3g}{2L}$, end accel $= \dfrac{3g}{2}$, hinge force $= \dfrac{Mg}{4}$ |
| Rod falling, $\omega$ at vertical (pivot at end) | $\omega = \sqrt{3g/L}$ |
| Solid cylinder unwinding from string | $a = \dfrac{2g}{3}$, $T = \dfrac{Mg}{3}$ |
| Mass on string over disc pulley | $a = \dfrac{mg}{m + M/2}$ |
| Massive-pulley Atwood | $a = \dfrac{(m_2-m_1)g}{m_1+m_2+M/2}$ |
| Sliding sphere → rolling | $v_f = \dfrac{v_0}{1+k^2/R^2}$ |
| Rolling body completing a loop (radius $R$) | $h = \left(2 + \tfrac12\!\left(1+\tfrac{k^2}{R^2}\right)\right)R$ → sphere $2.7R$, cylinder $2.75R$ |
| Ladder, smooth wall + rough floor | $\mu_{min} = \tfrac12\cot\theta$ |

---

## The dictionary (linear → rotational)

$$m\to I,\quad F\to\tau,\quad a\to\alpha,\quad v\to\omega,\quad s\to\theta,\quad p\to L$$

Every linear law has a rotational twin. Learn the swap and the chapter collapses to a handful of ideas.
