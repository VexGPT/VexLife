# VexLife Assortment — Frontier to Project Process Map

Status: DESIGN FOUNDATION
Origin: Round 1 / Index 07

## Why this exists

Frontier is not just "a place for ideas." It needs to demonstrate how an idea becomes organized, reviewed, placed, promoted, worked, and revisited.

The UI may resemble a kanban board in one projection, but the canonical model should be lifecycle records + semantic identities, not columns as truth.

KANBAN_VIEW != CANONICAL_STATE

## Core entities

FeatureSeed / BranchRecord
- origin context
- human intent
- candidate domains/owners
- placement state
- lifecycle state
- wake predicate
- next review
- related project/feature/source refs

Project
- a durable semantic work container
- owns bounded active/planned work after promotion
- may contain Features, work stages, sources, evidence, sessions, assets

Frontier
- contextual index/projection over candidate or unplaced seeds
- not the semantic owner of the idea
- not every Project must pass through a visible Frontier card

## Lifecycle

CAPTURED
-> CANDIDATE
-> HONING
-> PLANNED
-> ACTIVE
-> REVIEW
-> ACCEPTED | NARROWED | HELD | REJECTED | SUPERSEDED

PARKED may occur from CANDIDATE / HONING / PLANNED.

Placement is orthogonal:

UNPLACED | MULTI_HOME | PLACED | HELD

## Live practicum

Use a real seed from this design lane:

Seed:
  Home Construction Practicum

Origin:
  Round 1 / Index 05

Initial state:
  lifecycle=HONING
  placement=UNPLACED
  projectedIn=Frontier

Intent:
  prove Home node -> preview -> full Project surface using This Project

Promotion gate:
- intent is stable
- rightful design owner is known
- Reference/Evolution safety boundary exists
- first bounded proof is named
- review criteria are known

When earned:
  seed remains as provenance
  Project identity becomes/links to:
    VexLife Assortment / Home Blueprint

Then:
  Frontier may still show the originating seed/history,
  while Home/Projects shows the promoted Project.

PROMOTION != DELETE_SEED
PROMOTION != LOSE_ORIGIN_CONTEXT

## Candidate UI projection

Frontier / Work Queue view may show columns:

Ideas
Honing
Planned
Active
Review
Parked / Accepted

Cards are projections of records. Moving a card changes typed lifecycle state only through a valid transition.

## Transition contract

Each move should answer:
- what changed?
- who approved/caused it?
- why is the transition valid?
- what source/evidence supports it?
- what is the new placement?
- what wake/review condition comes next?

## First proof in Evolution

1. Show Home Construction Practicum as a dotted Frontier seed.
2. Open it and inspect origin, intent, state, next review.
3. Promote it through a simulated transition to PLANNED.
4. Create/link the This Project Project node.
5. Show the Project as solid only when implemented in Evolution.
6. Keep the seed's origin/provenance inspectable from the Project.
7. Do not mutate Reference until the Evolution proof is reviewed.

## Design goal

The user should be able to understand:

"Where did this project come from?"
"What stage is it in?"
"Why did it move?"
"What happens next?"
"Can I revisit the original idea?"
"Has this been implemented, or only planned?"

without reading Git history or raw internal registries.
