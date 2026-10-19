# 🔨 JEE-Forge

> Forge the concepts. Drill them on the range.

A deep-preparation concept vault for **IIT-JEE (Main & Advanced)**, covering
Class 11 & 12 **Physics, Chemistry, and Mathematics**.

Every topic is built from first principles — concepts explained with LaTeX
math, Mermaid flowcharts, and SVG diagrams — then reinforced through solved
numericals, a graded practice range, deep-dive analysis, and a quick formula
recap. Add your own notes (typed or scanned) to any topic.

**Philosophy:** *learn and allow others to learn, nothing is mine* — built to be
useful to any student preparing for JEE, not just one.

---

## 📂 What's inside each topic

Every topic folder follows the same mold:

| File | Role | What's inside |
|---|---|---|
| `01-concepts.md` | **Forge** | First-principles explanations, derivations, diagrams (LaTeX + Mermaid + SVG) |
| `02-solved-numericals.md` | **Forge** | 10 basic · 15 medium · 10 advanced — fully worked |
| `03-practice.md` | **Range** | 10 basic · 15 medium · 10 advanced — with hints + collapsible solutions |
| `04-deep-dive.md` | **Forge+** | JEE Advanced depth, common traps, previous-year-question (PYQ) patterns |
| `05-formula-recap.md` | **Range** | One-page revision cheat sheet |
| `notes/` | *yours* | Your own notes — typed, or scanned notes rewritten into clean markdown |
| `assets/` | — | SVG diagrams for the topic |

---

## 🗂️ Master Index

### Class 11

| Physics | Chemistry | Maths |
|---|---|---|
| Units & Measurements | Some Basic Concepts (Mole Concept) | Sets, Relations & Functions |
| Kinematics | Structure of Atom | Complex Numbers & Quadratic Eqns |
| Laws of Motion | Classification & Periodicity | Sequences & Series |
| Work, Energy & Power | Chemical Bonding | Permutations & Combinations |
| System of Particles & Rotational Motion | Thermodynamics (chem) | Binomial Theorem |
| Gravitation | Equilibrium | Straight Lines |
| Mechanical Properties of Solids | Redox Reactions | Conic Sections |
| Mechanical Properties of Fluids | GOC (Organic basics) | Trigonometry |
| Thermal Properties of Matter | Hydrocarbons | Limits (intro) |
| Thermodynamics | | Statistics & Probability (basics) |
| Kinetic Theory of Gases | | |
| Oscillations | | |
| Waves | | |

### Class 12

| Physics | Chemistry | Maths |
|---|---|---|
| Electric Charges & Fields | Solutions | Matrices & Determinants |
| Electrostatic Potential & Capacitance | Electrochemistry | Relations & Functions (adv) |
| Current Electricity | Chemical Kinetics | Inverse Trigonometry |
| Moving Charges & Magnetism | The p-Block | Continuity & Differentiability |
| Magnetism & Matter | The d- & f-Block | Application of Derivatives |
| Electromagnetic Induction | Coordination Compounds | Integrals |
| Alternating Current | Haloalkanes & Haloarenes | Application of Integrals |
| Electromagnetic Waves | Alcohols, Phenols & Ethers | Differential Equations |
| Ray Optics | Aldehydes, Ketones & Carboxylic Acids | Vectors |
| Wave Optics | Amines | 3D Geometry |
| Dual Nature of Radiation & Matter | Biomolecules | Probability (adv) |
| Atoms | Solid State & Surface Chemistry | |
| Nuclei | | |
| Semiconductor Electronics | | |

> ✅ = topic built · ⬜ = planned. See each subject's `PROGRESS.md` for live status.

---

## ✍️ How to use

**Study a topic**

1. Read `01-concepts.md` top to bottom — don't skip the diagrams.
2. Work through `02-solved-numericals.md`, redoing each problem on paper before reading the solution.
3. Attempt `03-practice.md` cold. Use the hint only when stuck; check the answer only after a real attempt.
4. Read `04-deep-dive.md` once the basics feel solid.
5. Revise with `05-formula-recap.md` before any test.

**Add your own notes**

- Typed note → add a dated file in the topic's `notes/` folder, e.g. `notes/2026-10-25-friction-doubts.md`, and link it from `notes/README.md`.
- Scanned/handwritten note → drop the image or PDF into `notes/scans/`, then ask Claude to rewrite it into a clean, formatted markdown note dated alongside it.

**Rendering notes (GitHub-safe)**

- Math renders via GitHub's built-in LaTeX: `$inline$` and `$$block$$`.
- Flowcharts/concept maps use Mermaid (renders natively on GitHub).
- Figures are committed SVGs in each topic's `assets/`.
- Color is delivered through GitHub alert callouts (`> [!NOTE]`, `> [!TIP]`, `> [!WARNING]`) and inside the diagrams. For full text-highlight color, open the vault in Obsidian.

---

## 🧭 Conventions

- Chapters are numbered (`01-`, `02-`) so they sort in syllabus order.
- Topic folders use `kebab-case` slugs.
- One concept = one clear idea. Derivations are shown, not just stated.
- Difficulty tiers are consistent everywhere: **Basic** (board/foundation) · **Medium** (JEE Main) · **Advanced** (JEE Advanced).

---

*Built with care for deep understanding, not rote learning.*
