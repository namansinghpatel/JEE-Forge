# Trigonometric Functions — Formula Recap

> One-page revision sheet. Everything from [Concepts](./01-concepts.md) condensed to formulas and the cue for
> each. Pair with the flash sheet ([`flash.html`](./flash.html)) the night before a test.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

---

## 🔵 Fundamentals

| Item | Formula |
|---|---|
| Radian–degree | $\pi$ rad $= 180°$; $\theta_{\text{rad}} = \tfrac{\pi}{180}\theta_{\text{deg}}$ |
| Arc / sector | $\ell = r\theta$; area $= \tfrac12 r^2\theta$ |
| Pythagorean | $\sin^2\theta + \cos^2\theta = 1$ |
|  | $1 + \tan^2\theta = \sec^2\theta$ |
|  | $1 + \cot^2\theta = \csc^2\theta$ |
| Signs (ASTC) | Q1 all + · Q2 sin + · Q3 tan + · Q4 cos + |
| Periods | $\sin, \cos, \sec, \csc$: $2\pi$; $\tan, \cot$: $\pi$ |

**Standard values:**

| $\theta$ | $0$ | $30°$ | $45°$ | $60°$ | $90°$ |
|---|---|---|---|---|---|
| $\sin$ | $0$ | $\tfrac12$ | $\tfrac1{\sqrt2}$ | $\tfrac{\sqrt3}2$ | $1$ |
| $\cos$ | $1$ | $\tfrac{\sqrt3}2$ | $\tfrac1{\sqrt2}$ | $\tfrac12$ | $0$ |
| $\tan$ | $0$ | $\tfrac1{\sqrt3}$ | $1$ | $\sqrt3$ | $\infty$ |

---

## 🟢 Compound angles

$$\sin(A \pm B) = \sin A\cos B \pm \cos A\sin B$$
$$\cos(A \pm B) = \cos A\cos B \mp \sin A\sin B$$
$$\tan(A \pm B) = \frac{\tan A \pm \tan B}{1 \mp \tan A\tan B}$$

---

## 🟡 Multiple angles

| Quantity | Formula |
|---|---|
| $\sin 2A$ | $2\sin A\cos A = \dfrac{2t}{1+t^2}$ |
| $\cos 2A$ | $1 - 2\sin^2 A = 2\cos^2 A - 1 = \dfrac{1-t^2}{1+t^2}$ |
| $\tan 2A$ | $\dfrac{2\tan A}{1 - \tan^2 A}$ |
| $\sin 3A$ | $3\sin A - 4\sin^3 A$ |
| $\cos 3A$ | $4\cos^3 A - 3\cos A$ |
| Power reduction | $\sin^2 A = \tfrac{1-\cos 2A}{2},\ \cos^2 A = \tfrac{1+\cos 2A}{2}$ |

($t = \tan A$.)

---

## 🟣 Sum ↔ product

$$\sin C + \sin D = 2\sin\tfrac{C+D}2\cos\tfrac{C-D}2, \qquad \sin C - \sin D = 2\cos\tfrac{C+D}2\sin\tfrac{C-D}2$$
$$\cos C + \cos D = 2\cos\tfrac{C+D}2\cos\tfrac{C-D}2, \qquad \cos C - \cos D = -2\sin\tfrac{C+D}2\sin\tfrac{C-D}2$$
$$2\sin A\cos B = \sin(A+B) + \sin(A-B), \quad 2\cos A\cos B = \cos(A+B) + \cos(A-B)$$

---

## ⚫ Advanced tools

| Tool | Formula / method |
|---|---|
| General: sine | $\sin\theta = \sin\alpha \Rightarrow \theta = n\pi + (-1)^n\alpha$ |
| General: cosine | $\cos\theta = \cos\alpha \Rightarrow \theta = 2n\pi \pm \alpha$ |
| General: tangent | $\tan\theta = \tan\alpha \Rightarrow \theta = n\pi + \alpha$ |
| $R$-form | $a\cos\theta + b\sin\theta = R\cos(\theta - \phi),\ R = \sqrt{a^2+b^2}$ |
| Range of $a\cos\theta + b\sin\theta$ | $[-\sqrt{a^2+b^2},\ \sqrt{a^2+b^2}]$ |
| Weierstrass | $t = \tan\tfrac\theta2$: $\sin\theta = \tfrac{2t}{1+t^2},\ \cos\theta = \tfrac{1-t^2}{1+t^2}$ |
| $A+B+C = \pi$ | $\tan A + \tan B + \tan C = \tan A\tan B\tan C$ |

---

## 🎯 Exam cues

> [!TIP]
> - **"Prove the identity"** → convert all to sin/cos, work one side.
> - **"Max / min / range of $a\sin\theta + b\cos\theta$"** → $R = \sqrt{a^2+b^2}$.
> - **"Solve ... general solution"** → reduce to one ratio, factor, apply the three general forms.
> - **$1 \pm \cos\theta$ or $1 \pm \sin\theta$** → half-angle.
> - **$\sin\pm\sin$ / $\cos\pm\cos$** → sum-to-product (then factor).
> - **Angles of a triangle** → use $C = \pi - (A+B)$ for conditional identities.
> - **$\sin, \cos$ appear linearly** → $t = \tan(\theta/2)$ makes it algebraic.

---

📄 **Google Drive source:** [`notes/scans/Class_11_MT_Trigonometry_Formula.png`](./notes/scans/Class_11_MT_Trigonometry_Formula.png) — the chapter formula sheet (vector PDF alongside).

**Back to:** [Concepts](./01-concepts.md) · [Flash sheet](./flash.html)
