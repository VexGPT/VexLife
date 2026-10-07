# VexLife Assortment — durable design-discussion continuity

Purpose: preserve Victor ↔ ChatGPT VexLife design exploration as an inspectable, source-controlled sequence of text + visual references while keeping discussion provenance separate from canonical product truth.

## Human-burden rule

A fresh VexLife Assortment conversation must **not** require Victor to remember or paste a resume incantation, round/index number, branch, PR, or Relay procedure.

The ChatGPT Project Instructions own automatic fresh-instance boot. A fresh instance reads the installed Project Sources, discovers the current round/index from the current-state pointer, re-grounds mutable GitHub state, adopts the existing compatible occupancy, and then answers Victor's actual request.

```text
FRESH_THREAD != NEW_ROUND
FRESH_INSTANCE != NEW_WRITER
PROJECT_RELOCATION != LANE_RESET
```

## Continuity identity

- Project: `VexLife Assortment`
- Round: a deliberate design phase, **not** a conversation/thread boundary.
- Index: one material paired Victor + ChatGPT exchange inside a round.
- Bootstrap: `index-00-bootstrap.txt` establishes a round before ordinary indices.
- Rolling logs: `range-1-30.txt`, then `range-31-60.txt`, etc.
- `CURRENT.txt`: lightweight durable pointer; refresh mutable GitHub facts before effects.

## Automatic capture rules

1. Preserve Victor's prompt/question verbatim when practical.
2. If Victor pastes a large prior ChatGPT answer, replace that duplicated quoted block with its existing `[VexLife Assortment][Round N][Index NN]` reference.
3. Preserve ChatGPT's substantive response text or a complete bounded visual-response description.
4. Preserve generated/reintroduced visuals under the same index. If a crop materially changes the discussion, retain both original and crop.
5. Assets use round/index affinity, e.g. `r1-i03-home-field.png`.
6. Record dispositions such as `QUESTION`, `DESIGN_CANDIDATE`, `CONFIRMED`, `HELD`, `REJECTED`, or `SUPERSEDED`.
7. Discussion continuity is provenance/evidence; it does not automatically become product/source authority.
8. After each material exchange, update the active range log and `CURRENT.txt` through the exact available authorized GitHub effect.
9. If direct GitHub write is unavailable, select the governed Local Operations/VexRelay route rather than making Victor choose technical recovery.
10. A new round is formed only when the design phase deliberately transitions; a fresh chat continues the current round by default.

## GitHub / Relay rule

Use the exact connected GitHub provider effect directly when it exists and is authorized. Do **not** form VexRelay for an effect that can be performed connector-direct.

When a required effect cannot be performed directly and Relay is implicated, the operator must use the installed Local Vex Operations R3 policy, fetch the live `source.vexrelay.current-contract/v1`, lock the current route/adapter, and use the current named recipe/template/schema path as applicable.

Victor is not the technical message bus and does not choose scripts, branches, recovery routes, or logs.

## Repository placement

Durable Assortment discussion state lives at:

`Blueprints/VexLife-Assortment/`

The ChatGPT Project carries the automatic boot instructions and Local Vex Operations / VexRelay operating sources. The repository does not need to duplicate the complete normative manuals; `PROJECT-BOOTSTRAP-POINTER.md` explains the boundary.

## Fresh-instance behavior

After project installation, no special user command is required. On the first substantive turn a fresh instance should orient automatically and continue the current Round/Index while responding to Victor's actual request.
