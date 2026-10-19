# Quadratic Equations — Formula Recap

> One-page revision sheet. Everything you need the night before a test.
> Full explanations in [01-concepts.md](./01-concepts.md).

<!-- RENDERING: inside math use \cdot, \to, \geq, \leq, \in. -->

---

## 📑 Index

[Solving](#solving) · [Discriminant](#discriminant--nature-of-roots) · [Sum & product](#sum--product-of-roots) · [Forming & transforming](#forming--transforming) · [Graph & extremes](#graph--extreme-value) · [Location & sign](#root-location--sign) · [Common roots](#common-roots)

---

## Solving

$$ax^2 + bx + c = 0,\ a \neq 0 \qquad\Rightarrow\qquad x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

---

## Discriminant & nature of roots

$$D = b^2 - 4ac$$

| $D$ | Roots (real coeffs) |
|---|---|
| $> 0$ | two distinct real |
| $= 0$ | one repeated real, $x = -\tfrac{b}{2a}$ |
| $< 0$ | complex conjugates |

Rational coeffs: $D$ a perfect square → rational roots; $D>0$ non-square → conjugate surds.

---

## Sum & product of roots

$$\alpha + \beta = -\frac{b}{a}, \qquad \alpha\beta = \frac{c}{a}$$
$$\alpha^2+\beta^2 = S^2 - 2P, \qquad \alpha^3+\beta^3 = S^3 - 3SP$$
$$\frac1\alpha + \frac1\beta = \frac{S}{P}, \qquad |\alpha - \beta| = \frac{\sqrt D}{|a|}$$
$$\text{Power sums: } p_n = S\,p_{n-1} - P\,p_{n-2},\ \ p_0=2,\ p_1=S$$

---

## Forming & transforming

$$\text{From roots: } x^2 - (\text{sum})x + (\text{product}) = 0$$

| New roots | New sum | New product |
|---|---|---|
| $k\alpha,\,k\beta$ | $kS$ | $k^2P$ |
| $\alpha+k,\,\beta+k$ | $S+2k$ | $P+kS+k^2$ |
| $\tfrac1\alpha,\,\tfrac1\beta$ | $S/P$ | $1/P$ |
| $\alpha^2,\,\beta^2$ | $S^2-2P$ | $P^2$ |

Reciprocal-root equation = **reverse the coefficients**.

---

## Graph & extreme value

Parabola $y = ax^2+bx+c$: opens **up** if $a>0$ (minimum), **down** if $a<0$ (maximum).
$$\text{Axis/vertex at } x = -\frac{b}{2a}, \qquad y_{\text{extreme}} = -\frac{D}{4a} = c - \frac{b^2}{4a}$$

---

## Root location & sign

For $f(x) = ax^2+bx+c$ ($a>0$):

- $t$ **between** the roots ⟺ $a\cdot f(t) < 0$; $t$ **outside** ⟺ $a\cdot f(t) > 0$.
- Both roots positive: $D\geq0$, sum $>0$, product $>0$.
- Both roots negative: $D\geq0$, sum $<0$, product $>0$.
- Both roots in $(p,q)$: $D\geq0$, $f(p)>0$, $f(q)>0$, $p < -\tfrac{b}{2a} < q$.
- $ax^2+bx+c > 0\ \forall x$ ⟺ $a>0$ and $D<0$.
- Sign: same sign as $a$ outside the roots, opposite between them.

---

## Common roots

- **One common root:** $(a_1c_2 - a_2c_1)^2 = (b_1c_2 - b_2c_1)(a_1b_2 - a_2b_1)$.
- **Both common:** $\dfrac{a_1}{a_2} = \dfrac{b_1}{b_2} = \dfrac{c_1}{c_2}$.
- A degree-2 equation with **3** distinct roots is an **identity** ($a=b=c=0$).
