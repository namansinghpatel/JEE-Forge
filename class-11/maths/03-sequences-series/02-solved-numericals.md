# Sequences & Series — Solved Numericals

> **35 worked problems**, split **Basic (10) · Medium (15) · Advanced (10)**, spanning AP, GP, infinite GP,
> means and the AM–GM inequality, special-power sums, telescoping and AGP. Every problem marks the
> **❓ Question** and **✅ Answer**; Medium and Advanced carry a **🧭 Strategy** block.

<!-- RENDERING: inside math use \cdot (not ·), \to, \sum, \frac, \geq/\leq. -->

> **Key formulas:** AP $a_n=a+(n-1)d$, $S_n=\tfrac n2[2a+(n-1)d]$; GP $a_n=ar^{n-1}$, $S_n=a\tfrac{r^n-1}{r-1}$, $S_\infty=\tfrac{a}{1-r}$ ($|r|<1$); $\sum k=\tfrac{n(n+1)}2$, $\sum k^2=\tfrac{n(n+1)(2n+1)}6$, $\sum k^3=[\tfrac{n(n+1)}2]^2$.

---

## 📑 Index

- [Basic (B1–B10)](#basic) — AP/GP terms & sums, means, standard sums
- [Medium (M1–M15)](#medium) — infinite GP, inserting means, AM–GM, S_n↔a_n, HP
- [Advanced (A1–A10)](#advanced) — AGP, telescoping, Vₙ method, AM–GM optimisation
- [⭐ JEE Questions by Me](#jee-questions-by-me)

Related: [Concepts](./01-concepts.md) · [Practice Range](./03-practice.md) · [Formula Recap](./05-formula-recap.md)

---

<a id="basic"></a>
## 🟢 Basic (B1–B10)

<a id="b1"></a>
### B1

> ❓ **Question.** Find the 10th term of the AP $3, 7, 11, \dots$

**✅ Answer.** $a_{10} = 3 + 9(4) = \boxed{39}$.

---

<a id="b2"></a>
### B2

> ❓ **Question.** Find the sum of the first 20 terms of $3, 7, 11, \dots$

**✅ Answer.** $S_{20} = \tfrac{20}{2}[2(3) + 19(4)] = 10(82) = \boxed{820}$.

---

<a id="b3"></a>
### B3

> ❓ **Question.** Find the 6th term of the GP $2, 6, 18, \dots$

**✅ Answer.** $a_6 = 2\cdot3^5 = 2(243) = \boxed{486}$.

---

<a id="b4"></a>
### B4

> ❓ **Question.** Sum the first 5 terms of the GP $2, 6, 18, \dots$

**✅ Answer.** $S_5 = 2\dfrac{3^5 - 1}{3 - 1} = 2\dfrac{242}{2} = \boxed{242}$.

---

<a id="b5"></a>
### B5

> ❓ **Question.** Find the sum to infinity of $1 + \tfrac12 + \tfrac14 + \dots$

**✅ Answer.** $S_\infty = \dfrac{1}{1 - \tfrac12} = \boxed{2}$.

---

<a id="b6"></a>
### B6

> ❓ **Question.** Find the AM of 4 and 16.

**✅ Answer.** $\dfrac{4 + 16}{2} = \boxed{10}$.

---

<a id="b7"></a>
### B7

> ❓ **Question.** Find the GM of 4 and 16.

**✅ Answer.** $\sqrt{4\cdot16} = \sqrt{64} = \boxed{8}$.

---

<a id="b8"></a>
### B8

> ❓ **Question.** Find $\sum_{k=1}^{10} k$.

**✅ Answer.** $\dfrac{10(11)}{2} = \boxed{55}$.

---

<a id="b9"></a>
### B9

> ❓ **Question.** Find $\sum_{k=1}^{5} k^2$.

**✅ Answer.** $\dfrac{5(6)(11)}{6} = \boxed{55}$.

---

<a id="b10"></a>
### B10

> ❓ **Question.** Find the HM of 2 and 6.

**✅ Answer.** $\dfrac{2\cdot2\cdot6}{2 + 6} = \dfrac{24}{8} = \boxed{3}$.

---

<a id="medium"></a>
## 🟡 Medium (M1–M15)

<a id="m1"></a>
### M1

> ❓ **Question.** The 4th term of an AP is 11 and the 7th is 20. Find the first term and common difference.

> [!TIP]
> 🧭 **Strategy.** Set up $a + 3d = 11$, $a + 6d = 20$; subtract.

**Steps.** $3d = 9 \Rightarrow d = 3$; $a = 11 - 9 = 2$.

**✅ Answer.** $a = 2$, $d = 3$.

---

<a id="m2"></a>
### M2

> ❓ **Question.** Find three numbers in AP whose sum is 15 and product is 80.

> [!TIP]
> 🧭 **Strategy.** Take them as $a-d, a, a+d$: sum $= 3a = 15 \Rightarrow a = 5$.

**Steps.** $a = 5$; product $(5-d)(5)(5+d) = 80 \Rightarrow 25 - d^2 = 16 \Rightarrow d^2 = 9 \Rightarrow d = 3$.

**✅ Answer.** $2, 5, 8$.

---

<a id="m3"></a>
### M3

> ❓ **Question.** Find the sum to infinity of $\dfrac23 + \dfrac29 + \dfrac{2}{27} + \dots$

> [!TIP]
> 🧭 **Strategy.** GP with $a = \tfrac23$, $r = \tfrac13$; $S_\infty = \tfrac{a}{1-r}$.

**Steps.** $S_\infty = \dfrac{2/3}{1 - 1/3} = \dfrac{2/3}{2/3} = 1$.

**✅ Answer.** $1$.

---

<a id="m4"></a>
### M4

> ❓ **Question.** Insert 3 arithmetic means between 2 and 18.

> [!TIP]
> 🧭 **Strategy.** 5 terms total (AP); $d = \frac{18 - 2}{4}$.

**Steps.** $d = 4$; means are $6, 10, 14$.

**✅ Answer.** $6, 10, 14$.

---

<a id="m5"></a>
### M5

> ❓ **Question.** The sum of the first $n$ terms of a series is $S_n = 3n^2 + 2n$. Find the $n$-th term.

> [!TIP]
> 🧭 **Strategy.** $a_n = S_n - S_{n-1}$.

**Steps.** $a_n = (3n^2 + 2n) - (3(n-1)^2 + 2(n-1)) = 6n - 1$.

**✅ Answer.** $a_n = 6n - 1$ (an AP).

---

<a id="m6"></a>
### M6

> ❓ **Question.** Find three numbers in GP whose sum is 14 and product is 64.

> [!TIP]
> 🧭 **Strategy.** Take $\frac ar, a, ar$: product $= a^3 = 64 \Rightarrow a = 4$.

**Steps.** $a = 4$; sum $\frac4r + 4 + 4r = 14 \Rightarrow 4r^2 - 10r + 4 = 0 \Rightarrow 2r^2 - 5r + 2 = 0 \Rightarrow r = 2$ or $\tfrac12$.

**✅ Answer.** $2, 4, 8$.

---

<a id="m7"></a>
### M7

> ❓ **Question.** Prove $x + \dfrac1x \ge 2$ for $x > 0$, and state when equality holds.

> [!TIP]
> 🧭 **Strategy.** AM–GM on $x$ and $\tfrac1x$.

**Steps.** $\dfrac{x + 1/x}{2} \ge \sqrt{x\cdot\tfrac1x} = 1$, so $x + \tfrac1x \ge 2$; equality at $x = \tfrac1x \Rightarrow x = 1$.

**✅ Answer.** $x + \tfrac1x \ge 2$, equality at $x = 1$.

---

<a id="m8"></a>
### M8

> ❓ **Question.** Find $\sum_{k=1}^{n} k(k+1)$ in closed form.

> [!TIP]
> 🧭 **Strategy.** Expand: $\sum(k^2 + k) = \sum k^2 + \sum k$.

**Steps.** $\dfrac{n(n+1)(2n+1)}{6} + \dfrac{n(n+1)}{2} = \dfrac{n(n+1)(2n+1) + 3n(n+1)}{6} = \dfrac{n(n+1)(2n+4)}{6}$.

**✅ Answer.** $\dfrac{n(n+1)(n+2)}{3}$.

---

<a id="m9"></a>
### M9

> ❓ **Question.** How many terms of the AP $9, 17, 25, \dots$ sum to 636?

> [!TIP]
> 🧭 **Strategy.** $S_n = \tfrac n2[2a + (n-1)d] = 636$; solve the quadratic in $n$.

**Steps.** $\tfrac n2[18 + 8(n-1)] = 636 \Rightarrow n(8n + 10) = 1272 \Rightarrow 4n^2 + 5n - 636 = 0 \Rightarrow n = 12$.

**✅ Answer.** $12$ terms.

---

<a id="m10"></a>
### M10

> ❓ **Question.** The 2nd term of a GP is 6 and the 5th is 48. Find the GP.

> [!TIP]
> 🧭 **Strategy.** $ar = 6$, $ar^4 = 48$; divide to get $r^3 = 8$.

**Steps.** $r^3 = 8 \Rightarrow r = 2$; $a = 3$.

**✅ Answer.** $3, 6, 12, 24, \dots$

---

<a id="m11"></a>
### M11

> ❓ **Question.** If the AM of two numbers is 10 and the GM is 8, find the numbers.

> [!TIP]
> 🧭 **Strategy.** They are roots of $x^2 - 2(\text{AM})x + \text{GM}^2 = 0$.

**Steps.** $x^2 - 20x + 64 = 0 \Rightarrow (x - 4)(x - 16) = 0$.

**✅ Answer.** $4$ and $16$.

---

<a id="m12"></a>
### M12

> ❓ **Question.** Find the sum $\dfrac{1}{1\cdot2} + \dfrac{1}{2\cdot3} + \dots + \dfrac{1}{n(n+1)}$.

> [!TIP]
> 🧭 **Strategy.** Partial fractions → telescoping: $\frac{1}{k(k+1)} = \frac1k - \frac1{k+1}$.

**Steps.** Sum $= 1 - \dfrac{1}{n+1}$.

**✅ Answer.** $\dfrac{n}{n+1}$.

---

<a id="m13"></a>
### M13

> ❓ **Question.** The terms $a, b, c$ are in HP. Express $b$ in terms of $a$ and $c$.

> [!TIP]
> 🧭 **Strategy.** HP → reciprocals in AP: $\frac1b = \frac12(\frac1a + \frac1c)$.

**Steps.** $\frac2b = \frac1a + \frac1c = \frac{a+c}{ac} \Rightarrow b = \frac{2ac}{a+c}$.

**✅ Answer.** $b = \dfrac{2ac}{a + c}$ (the HM of $a$ and $c$).

---

<a id="m14"></a>
### M14

> ❓ **Question.** Find the sum of the first 15 terms of $1^2 + 2^2 + 3^2 + \dots$

> [!TIP]
> 🧭 **Strategy.** $\sum k^2 = \frac{n(n+1)(2n+1)}{6}$.

**Steps.** $\dfrac{15(16)(31)}{6} = \dfrac{7440}{6}$.

**✅ Answer.** $1240$.

---

<a id="m15"></a>
### M15

> ❓ **Question.** A GP has first term 5 and sum to infinity 20. Find the common ratio.

> [!TIP]
> 🧭 **Strategy.** $S_\infty = \frac{a}{1-r} = 20$.

**Steps.** $\frac{5}{1-r} = 20 \Rightarrow 1 - r = \tfrac14 \Rightarrow r = \tfrac34$.

**✅ Answer.** $r = \tfrac34$.

---

<a id="advanced"></a>
## 🔴 Advanced (A1–A10)

<a id="a1"></a>
### A1

> ❓ **Question.** Sum the infinite AGP $1 + 2x + 3x^2 + 4x^3 + \dots$ for $|x| < 1$.

> [!TIP]
> 🧭 **Strategy.** Multiply-by-$x$ and subtract; the middle becomes a GP.

**Steps.** $S = 1 + 2x + 3x^2 + \dots$; $xS = x + 2x^2 + \dots$; $S - xS = 1 + x + x^2 + \dots = \frac{1}{1-x}$, so $S(1-x) = \frac{1}{1-x}$.

**✅ Answer.** $S = \dfrac{1}{(1-x)^2}$.

---

<a id="a2"></a>
### A2

> ❓ **Question.** Find $\sum_{k=1}^{n} k(k+1)(k+2)$.

> [!TIP]
> 🧭 **Strategy.** Vₙ method: $k(k+1)(k+2) = \frac14[k(k+1)(k+2)(k+3) - (k-1)k(k+1)(k+2)]$, telescopes.

**Steps.** Sum $= \dfrac{n(n+1)(n+2)(n+3)}{4}$.

**✅ Answer.** $\dfrac{n(n+1)(n+2)(n+3)}{4}$.

---

<a id="a3"></a>
### A3

> ❓ **Question.** Minimise $S = a + b + c$ given $abc = 27$ ($a, b, c > 0$).

> [!TIP]
> 🧭 **Strategy.** AM–GM: $\frac{a+b+c}{3} \ge \sqrt[3]{abc}$, equality when $a=b=c$.

**Steps.** $\frac{S}{3} \ge \sqrt[3]{27} = 3 \Rightarrow S \ge 9$, equality at $a = b = c = 3$.

**✅ Answer.** Minimum $S = 9$ (at $a=b=c=3$).

---

<a id="a4"></a>
### A4

> ❓ **Question.** Sum $\sum_{k=1}^{n} \dfrac{1}{k(k+2)}$.

> [!TIP]
> 🧭 **Strategy.** Partial fractions: $\frac{1}{k(k+2)} = \frac12(\frac1k - \frac1{k+2})$, telescopes with a 2-step gap.

**Steps.** $\frac12\left(1 + \frac12 - \frac1{n+1} - \frac1{n+2}\right) = \frac12\left(\frac32 - \frac1{n+1} - \frac1{n+2}\right)$.

**✅ Answer.** $\dfrac34 - \dfrac12\left(\dfrac1{n+1} + \dfrac1{n+2}\right)$.

---

<a id="a5"></a>
### A5

> ❓ **Question.** If $a, b, c$ are in AP and also $a, b, c$ are in GP, show $a = b = c$.

> [!TIP]
> 🧭 **Strategy.** AP: $2b = a + c$; GP: $b^2 = ac$; combine.

**Steps.** From AP, $c = 2b - a$; sub into $b^2 = a(2b - a) \Rightarrow b^2 - 2ab + a^2 = 0 \Rightarrow (b - a)^2 = 0 \Rightarrow b = a$, hence $c = a$.

**✅ Answer.** $a = b = c$ (the only way to be both AP and GP).

---

<a id="a6"></a>
### A6

> ❓ **Question.** Find the sum of the series $1 + \dfrac{3}{2} + \dfrac{5}{4} + \dfrac{7}{8} + \dots$ to infinity.

> [!TIP]
> 🧭 **Strategy.** AGP with numerator AP $(2k-1)$ and ratio $r = \tfrac12$. Multiply-by-$r$, subtract.

**Steps.** $S = \sum_{k\ge1}\frac{2k-1}{2^{k-1}}$; $\frac S2 = \sum\frac{2k-1}{2^k}$; $S - \frac S2 = 1 + \sum_{k\ge2}\frac{2}{2^{k-1}} = 1 + 2 = 3$ (after summing the GP), so $\frac S2 = 3$.

**✅ Answer.** $S = 6$.

---

<a id="a7"></a>
### A7

> ❓ **Question.** The sum of $n$ terms of an AP is $2n^2 + 3n$. Find the 10th term.

> [!TIP]
> 🧭 **Strategy.** $a_n = S_n - S_{n-1}$.

**Steps.** $a_n = (2n^2 + 3n) - (2(n-1)^2 + 3(n-1)) = 4n + 1$; $a_{10} = 41$.

**✅ Answer.** $a_{10} = 41$.

---

<a id="a8"></a>
### A8

> ❓ **Question.** If $S_1, S_2, S_3$ are sums of $n$ terms of three APs with the same first term 1 and common differences 1, 2, 3, find $S_1 + S_3$ in terms of $S_2$.

> [!TIP]
> 🧭 **Strategy.** Write each $S = \frac n2[2 + (n-1)d]$ and combine.

**Steps.** $S_1 + S_3 = \frac n2[2 + (n-1)] + \frac n2[2 + 3(n-1)] = \frac n2[4 + 4(n-1)] = n[2 + 2(n-1)] = 2S_2$.

**✅ Answer.** $S_1 + S_3 = 2S_2$.

---

<a id="a9"></a>
### A9

> ❓ **Question.** Find the sum $\sum_{k=1}^{n} \dfrac{k}{2^k}$ (an AGP).

> [!TIP]
> 🧭 **Strategy.** Multiply-by-$\tfrac12$ and subtract; sum the resulting GP.

**Steps.** For the infinite case $\sum_{k\ge1}\frac{k}{2^k} = \frac{1/2}{(1-1/2)^2} = 2$ (AGP formula $\frac{a}{1-r} + \frac{dr}{(1-r)^2}$ with $a=d=\tfrac12$, $r=\tfrac12$, or directly). The finite sum is $2 - \frac{n+2}{2^n}$.

**✅ Answer.** Finite: $2 - \dfrac{n+2}{2^n}$; infinite ($n\to\infty$): $2$.

---

<a id="a10"></a>
### A10

> ❓ **Question.** If $a, b, c$ are positive and in GP, prove $\log a, \log b, \log c$ are in AP.

> [!TIP]
> 🧭 **Strategy.** GP: $b^2 = ac$; take logs.

**Steps.** $b^2 = ac \Rightarrow 2\log b = \log a + \log c$, which is the AP condition for $\log a, \log b, \log c$.

**✅ Answer.** $\log a, \log b, \log c$ are in AP (taking logs turns a GP into an AP).

---

<a id="jee-questions-by-me"></a>
## ⭐ JEE Questions by Me

> **How to use this section.** Paste your own problems here (from coaching sheets, PYQs, test
> series). I'll add a full **🧭 Strategy + step-by-step solution** in the same style, and tag each
> with its difficulty and sub-topic (AP / GP / means / special-sums / AGP / telescoping).

> [!NOTE]
> _No questions added yet._ Drop a problem in `notes/scans/` (photo) or paste the text, and it will
> be solved and logged here with the date.

<!--
TEMPLATE for each entry — copy below when adding one:

### Q1 · <short title> · <🟢/🟡/🔴> · <ap/gp/means/sums/agp/telescoping>
> ❓ **Question.** <your question text, added YYYY-MM-DD>

> [!TIP]
> 🧭 **Strategy.** <how to approach>

**Steps.**
1. ...

**✅ Answer.** <boxed result>
-->

---

**Next:** [Practice Range →](./03-practice.md) · [Formula Recap →](./05-formula-recap.md)
