# Antspire

<img width="640" height="360" alt="ants" src="https://github.com/user-attachments/assets/80f5c422-e78a-4050-bd9c-4e6e45612bd4" />


*Dwarf Fortress in an anthill, rendered in falling-sand voxels.*

A single queen lands, sheds her wings, and burrows. You grow her colony downward
through soil, sand, water tables and bedrock. Nothing is scripted — the disasters
are physics.

## What's simulated

- **Granular matter** — sand, spoil, food and water fall, flow and pile
- **Structural bearing** — every material has a load capacity; overloaded ground gives way
- **Rigid bodies** — boulders fall, roll and crush as whole objects, never per-cell
- **Moisture** — water dampens neighbouring soil; wet soil is weak
- **Conservation** — excavated earth doesn't vanish. Spoil is carried and dumped.

## Status

Early development. Phase 1 of 6 — migrating the prototype to a tested, headless
simulation core. See [ROADMAP.md](docs/ROADMAP.md).

## Try it

<link, once there's a hosted build>

## Built with

TypeScript · Vite · Vitest · WebGL2 · no engine
