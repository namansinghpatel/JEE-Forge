# Topic Template

Copy this whole `TOPIC_TEMPLATE/` folder to start a new topic, rename it to the
chapter slug (e.g. `06-gravitation/`), and fill in each file. This mold reflects all
decisions made so far.

## Files in a topic

| File | Purpose |
|---|---|
| `01-concepts.md` | First-principles concepts — LaTeX + Mermaid + SVG. Has an index. |
| `02-solved-numericals.md` | 10 basic · 15 medium · 10 advanced, fully worked. Clear **Q / Solution / ✅ Answer**; medium & advanced also have **🧭 Strategy** + numbered **Steps**. Ends with a **⭐ JEE Questions by Me** section. Has an index. |
| `03-practice.md` | 10 basic · 15 medium · 10 advanced. Each has a **💡 Hint (approach)** = how to *think*, plus a collapsible **✅ Answer & Solution**. Category index. |
| `04-deep-dive.md` | JEE Advanced depth, traps, PYQ patterns. Has an index. |
| `05-formula-recap.md` | One-page cheat sheet. Has a compact index. |
| `notes/notes.md` | Entry point: plain-English quick summary + "what I learned" + doubts. |
| `notes/README.md` | Index of all notes for the topic. |
| `notes/scans/` | Raw scanned/handwritten notes go here for Claude to rewrite. |
| `assets/` | SVG diagrams. |

## ⚠️ Rendering rules (so GitHub math never errors)

GitHub renders math with KaTeX. Inside `$…$` or `$$…$$`, **never paste these Unicode
symbols** — they throw `ParseError`. Use the LaTeX command instead:

| Don't type in math | Use instead | For |
|---|---|---|
| `·` | `\cdot` | multiplication dot / units (`\mathrm{kg\cdot m^2}`) |
| `⟂` | `\perp` | perpendicular |
| `→` `↔` | `\to` `\leftrightarrow` | arrows |
| `×` | `\times` | cross product |
| `−` (en/em dash) | `-` | minus |

- Write units as `\mathrm{...}`, e.g. `\mathrm{N\cdot m}`, `\mathrm{rad/s^2}`.
- Unicode symbols are fine in **plain prose** (outside `$…$`) — only math mode is strict.
- Use GitHub alert callouts for colour: `> [!NOTE]`, `> [!TIP]`, `> [!WARNING]`, `> [!IMPORTANT]`.
- Diagrams: **committed SVG for everything**, including the concept map — GitHub serves SVG as an image and always renders it.
- **Avoid Mermaid for anything that must show on GitHub.** GitHub's Mermaid support is unreliable and often fails with "Unable to render rich display" even on valid, quoted diagrams. Use an SVG instead (see `05-rotational-motion/assets/concept-map.svg`). If you want an editable Mermaid source too, keep it in a ` ```text ` block (not ` ```mermaid `) so GitHub never tries to render it.

## Conventions

- Difficulty tiers everywhere: **Basic** (board/foundation) · **Medium** (JEE Main) · **Advanced** (JEE Advanced).
- Every long page starts with a `📑 Index`. Use HTML anchors (`<a id="..."></a>`) for reliable links.
- Explain in **plain English** first, then the formula.
