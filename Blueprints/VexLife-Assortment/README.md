# VexLife Assortment — discussion continuity scaffold

Purpose: preserve Victor ↔ ChatGPT design exploration as an inspectable, source-controlled sequence of text + visual references without pretending the discussion itself is canonical product truth.

## Continuity identity

- Project: `VexLife Assortment`
- Round: increment when a discussion arc closes and a fresh thread/instance takes over.
- Index: one paired Victor + ChatGPT exchange inside a round.
- Bootstrap: `index-00-bootstrap.txt` establishes a round's protocol/context before ordinary indices begin.
- Rolling logs: `range-1-30.txt`, then `range-31-60.txt`, etc.

## Capture rules

1. Preserve Victor's prompt/question verbatim when practical.
2. If Victor pastes a large prior ChatGPT answer, replace that quoted block with its existing `[VexLife Assortment][Round N][Index NN]` reference instead of duplicating it.
3. Preserve ChatGPT's response text and any generated visual references under the same index.
4. When Victor reuses or crops an earlier visual, preserve both the original source visual and the reused/cropped visual when they materially affect the discussion.
5. Assets are named with round/index affinity, for example `r1-i03-home-field.png`.
6. Discussion records may classify conclusions as `QUESTION`, `DESIGN_CANDIDATE`, `CONFIRMED`, `HELD`, `REJECTED`, or `SUPERSEDED`.
7. Discussion continuity is evidence/provenance; it does not automatically become product/source authority.
8. `CURRENT.txt` is the lightweight fresh-instance orientation pointer.

## Round handoff

At the end of a round:

- summarize accepted/held/rejected design directions;
- record the last index;
- merge/close the round PR when appropriate;
- create the next round from current main;
- `[Round N+1][Index 01]` begins with a compact summary of the prior round before new work continues.

Suggested resume phrase in a fresh thread:

`Resume [VexLife Assortment][Round N] from the current GitHub continuity pointer.`

## Repository placement

This directory is intended to live at:

`Blueprints/VexLife-Assortment/`

The starter ZIP is structured so it can be extracted from the VexLife repository root.
