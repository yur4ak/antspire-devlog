# Antspire

<img width="640" height="360" alt="ants" src="https://github.com/user-attachments/assets/80f5c422-e78a-4050-bd9c-4e6e45612bd4" />


A single queen lands, sheds her wings, and burrows. You grow her colony downward
through soil, sand, water tables and bedrock. Nothing is scripted — the disasters
are physics.

## What's simulated

- **Granular matter** — sand, spoil, food and water fall, flow and pile
- **Structural bearing** — every material has a load capacity; overloaded ground gives way
- **Rigid bodies** — boulders fall, roll and crush as whole objects, never per-cell
- **Moisture** — water dampens neighboring soil; wet soil is weak
- **Conservation** — excavated earth doesn't vanish. Spoil is carried and dumped.

## Status

Early development.

## Try it

soon

## Built with

TypeScript · Vite · Vitest · WebGL2 · no engine

-- 6 Aug 2026
## Phase 0 — Scope lock ✅ *(complete)*
### Extraction (ARCHITECTURE §10 steps 1–4c)
### Colony extraction (§10 step 5, in progress)
### Boundaries (§10 step 6)
## In progress
- [ ] **ARCHITECTURE §10 step 5 — extract colony + AI**
## Next — to exit Phase 1
## Phase 1 — Foundation *(~4–6 weeks)* 🚧 *(in progress)*
Turn the prototype into a testable codebase. **No new gameplay features.** This is the
phase that is most tempting to skip and most fatal to skip.
## LLM:
>in two sentences summarize what was done today
Claude> Extracted the first two slices of the colony/AI migration — sim/colony/ (caste table, ant entity, stepDir/stepToward) and sim/ai/pathfind.ts — with 32 new tests, 251 green, typecheck clean and the golden checksum unmoved, plus a TODO.md tracker and a corrected §10 step 6 that was already done. Settled two design questions in the docs ahead of the code: the queen's founding spoil now becomes a visible surface mound rather than a written-down P1 exemption (DESIGN §6.2/§10.6), and the founding control ladder is recorded in §6.5 — which forced amending §10.5's "never gated" promise to begin at founding.
