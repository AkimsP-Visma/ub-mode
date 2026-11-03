# ub-mode

`ub-mode` is an agent skill that enforces disciplined software engineering principles when writing or changing code. It is loosely based on portions of [@poteto](https://github.com/poteto)'s rules (`poteto-mode` / `pstack`), reduced to three phases:

1. **First Make it Work** — Laziness Protocol, Foundational Thinking, TDD, Redesign From First Principles, Attack the Premise, Subtract Before You Add, Outcome-Oriented Execution, Build the Lever, and Architecture (Model the Domain, Boundary Discipline, Type System Discipline, Make Operations Idempotent, Separate Before Serializing Shared State).
2. **Then Make it Right** — Fix Root Causes, Sequence Work into Verifiable Units, Test Behavior (Not Implementation), and Refactoring.
## Companion Tool Repositories

`ub-mode` pairs with this visualization tool:

- [unclebob/uml-viewer](https://github.com/unclebob/uml-viewer) — Visualizes components, coverage, CRAP, mutation scores, and dependency directions.

## Installation

Copy `SKILL.md` into your agent's skills directory as `ub-mode/SKILL.md` (for example `~/.grok/skills/ub-mode/SKILL.md`, `~/.claude/skills/ub-mode/SKILL.md`, or `~/.cursor/skills/ub-mode/SKILL.md`), then invoke `/ub-mode`.
