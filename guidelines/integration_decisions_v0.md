# Integration Decisions v0

## Role

Integration decisions define what happens after a log extraction.

The extraction may produce rich material.
The integration decision selects what enters Exocortex, what remains private, what goes to backlog, and what is discarded.

## Position

log
→ extraction
→ integration decision
→ memory / repo / backlog / discard

## Possible decisions

### private only

The material remains outside the public repository.

Use when:
- the log contains private material,
- the extraction is still experimental,
- or the material is not yet stable enough.

### update internal memory

The material should be kept in an internal memory file or private note.

Use when:
- a project decision was made,
- a structural distinction emerged,
- or a useful context should be preserved.

### update repo

The material should modify a tracked file in the repository.

Use when:
- a protocol changes,
- a core primitive is clarified,
- a public guideline is improved,
- or a stable architectural decision affects the project.

### add to backlog

The material is useful but not immediately actionable.

Use when:
- an idea needs later review,
- a technical tool may be built later,
- or a domain/app/module is suggested but not ready.

### discard

The material should not be kept.

Use when:
- it is noise,
- accidental paste,
- terminal artifact,
- repetition,
- or non-useful export residue.

## Required fields

Each integration decision should include:

- decision:
- reason:
- destination:
- next gesture:

## Principle

Extraction can be rich.

Integration must remain selective.

The goal is not to push everything into the repository, but to let only stable or useful structures enter the system.
