# VexLife Assortment — Reference / Evolution Surface Contract

Status: DESIGN FOUNDATION
Origin: Round 1 / Index 06
Scope: Home/Terrain experimentation without regressing accepted behavior

## Core rule

REFERENCE = the currently accepted/live product projection.
EVOLUTION = an experimental projection over the same semantic screen/context.

Evolution must begin from Reference behavior and declare bounded deltas. It must not silently replace the live surface or fork semantic ownership.

REFERENCE_SURFACE + EVOLUTION_DELTA -> EVOLUTION_SURFACE

## Skeleton preservation

The following current Home/Terrain capabilities are treated as baseline skeleton behaviors until source-grounded review says otherwise:

- Global Root Hub / current semantic center
- Up one layer
- Reset layout
- Vex surface/presence affordance
- Terrain details
- zoom / enter / parent controls
- auto-enter layers
- Full journey
- current-context centering
- open conversation
- adaptive layout + undo adaptation
- language selection
- projection/surface switching
- access to existing surfaces such as Health/source truth, Living Journal, Projects, Purpose Workspace, Experience Gallery, Render Lab, Vex Birth Lab where currently available

The Evolution view may reposition or visually simplify these affordances, but it must not deprecate or sever their rightful behavior/action owners merely to achieve a new layout.

## Baseline evidence

The Round 1 / Index 06 discussion supplied three visual references:

1. prior proposed Home Field concept
2. current Reference Home/Terrain screen
3. current surface drawer showing the Reference/Evolution projection mechanism

These images are discussion evidence. Their GitHub asset keys remain pending binary sync until the image bytes are placed in round-1/assets.

## Delta model

Each Evolution experiment should record only what changes from Reference:

- added node/surface
- removed or hidden presentation element
- moved presentation element
- changed visual treatment
- changed depth/entry behavior
- new projection
- changed action availability
- changed navigation/recovery behavior

Anything not declared as a delta is inherited from Reference.

## Promotion gate

Evolution may replace/update Reference only after:

- skeleton behavior parity is checked;
- no rightful semantic/effect owner is silently changed;
- navigation/back/recovery remain coherent;
- action bindings remain valid or intentional changes are explicitly reviewed;
- human comparison of Reference vs Evolution is completed;
- the accepted delta set is recorded;
- source implementation/proof is complete in a separate implementation occupancy.

## Node visual state must be data-derived

Do not use dotted/solid styling as decoration.

Candidate infrastructure axes:

subjectKind
  PROJECT | FEATURE | RELATIONSHIP | SURFACE | THREAD | WORLD | etc.

lifecycleState
  CANDIDATE | HONING | PLANNED | ACTIVE | ACCEPTED | PARKED | SUPERSEDED

implementationPosture
  LIVE_REFERENCE | EVOLUTION_IMPLEMENTED | DECLARED_UNIMPLEMENTED | HELD

placementState
  PLACED | MULTI_HOME | UNPLACED | HELD

runtime axes
  currentness / visibility / reachability / availability / attention / recovery

Suggested visual mapping:

- solid border = source-backed implementation exists in the currently viewed projection
- dotted border = declared/planned but not implemented in that projection
- muted/ghosted = HELD or unavailable
- glow/emphasis = current context / attention, not implementation maturity
- lifecycle/state chip = explicit textual state
- semantic-kind label = PROJECT / THREAD / etc.

This Project should be modeled as semantic kind PROJECT. Frontier is a projection/index for unplaced candidate seeds, not the owner/class of This Project.

When This Project is actually implemented in the Evolution projection, it earns solid source-backed styling there even if product-wide promotion to Reference is not yet accepted.
