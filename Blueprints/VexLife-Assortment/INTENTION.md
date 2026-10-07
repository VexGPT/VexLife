# VexLife Assortment — Foundation Intent

Status: DESIGN FOUNDATION / revisitability anchor
Scope: VexLife Assortment design lane
Authority: design intent and continuity only; not canonical product/source authority

## Why this file exists

The Round/Index ledger preserves *what was discussed and why*. CURRENT.txt preserves *where to resume*. This file preserves the slower-moving *design intention that should survive many rounds* so revisitability does not require replaying the whole conversation.

This file should change only when a material foundation is confirmed, narrowed, superseded, or rejected. It is not a per-turn transcript.

## Recovered Home / Terrain intention

- Home/Terrain is a contextual semantic field, not a fixed app menu.
- CENTER = current semantic context.
- Vex is primarily persistent companion/co-navigator; Vex may also become an inspected subject.
- Continue is a derived resumable path/projection, not another content store.
- Candidate Home districts currently include:
  Vex, Continue, Projects, Journal, Relationships, Library, Worlds, Online, Frontier.
- Candidate districts do not have to appear as equal permanent first-layer nodes.
- Multiple projections over one subject do not create multiple sources of truth.
- Nodes may progressively reveal preview -> engaged surface -> deeper/source detail.
- UNPLACED != ORPHANED.
- Visual grammar such as projection / subject / seed colors remains provisional until separately confirmed.

## Meta-use of the VexLife model

The Assortment lane is intentionally using the same distinctions it is designing:

FRONTIER
  captures candidate/unplaced ideas without forcing implementation.

JOURNAL-LIKE PROVENANCE
  Round/Index records preserve what happened, questions, decisions, rejections and why.

CONTINUE
  CURRENT.txt provides the exact resumable frontier without replaying the full history.

PROJECT / WORK
  begins only when a candidate earns an executable bounded work definition and implementation ownership.

SOURCE / GIT / EVIDENCE
  canonical implementation truth remains in rightful product source and proof, not in the discussion ledger.

These are analogous uses of the product grammar, not claims that the Assortment discussion files themselves are canonical implementations of those VexLife systems.

## Seed / Frontier -> Project promotion map

A candidate should not become an implementation project merely because discussion is long.

Suggested lifecycle:

SEED / CANDIDATE
  idea is preserved and addressable
  placement may be UNPLACED

        ↓ enough understanding to investigate

HONING
  human intention is being clarified
  alternatives, constraints and owner boundaries are explored
  visual/design experiments may occur

        ↓ promotion gate earned

PLANNED
  rightful semantic/product owner is identified
  intended human outcome is stable enough to name
  scope + non-goals are bounded
  current source/dependencies are grounded
  placement/surface hypothesis is explicit
  first finite implementation increment is defined
  proof/review criteria are defined
  wake predicate / why-now is clear

        ↓ implementation writer admitted

ACTIVE PROJECT / FEATURE WORK
  create a fresh implementation branch/PR from current main
  product/source mutation occurs under the rightful owner
  the Assortment design PR remains provenance and links to the implementation occupancy

        ↓ proof + human review

REVIEW
  compare built behavior against intention and current product truth

        ↓

ACCEPTED | NARROWED | HELD | REJECTED | SUPERSEDED

PARKED is valid from SEED/HONING/PLANNED when the wake predicate is not currently true.

## PR / checkpoint model

The active Assortment Round PR is a design-discussion/provenance PR, not an implementation PR.

Use it to accumulate one coherent design phase across many indices.

Checkpoint / close a Round when one or more are true:
- a meaningful design foundation has stabilized;
- the Round has become too broad to review as one coherent phase;
- an implementation promotion boundary is earned;
- a major unresolved branch of inquiry should become a new Round;
- a clean successor summary would materially improve navigation.

At Round close:
1. summarize confirmed / held / rejected / superseded foundations;
2. update this INTENTION.md if foundation intent changed;
3. update CURRENT.txt to the terminal Round state;
4. merge the design-doc PR when appropriate;
5. start the next Round from fresh current main without reopening old decisions by default.

Implementation rule:
DESIGN PR != IMPLEMENTATION PR

When implementation is earned, open a fresh bounded implementation PR from current main. Link both directions:
- design Round -> implementation PR/issue
- implementation PR -> originating Assortment Round/Index/intent

## Revisitability layers

INTENTION.md
  = slow-moving design foundation

CURRENT.txt
  = exact present continuation pointer

round-N/range-*.txt
  = chronological discussion / decision provenance

round-N/assets/*
  = durable visual evidence by stable asset key/path

implementation issue/PR
  = bounded source-change occupancy

canonical VexLife source
  = current product truth

This separation is intended to keep long-running design exploration scalable without turning one PR or one file into the entire history of the product.
