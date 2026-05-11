# Log Extraction v0

## Scope

This protocol applies to conversational logs produced through online AI systems.

Exocortex can receive many kinds of notes, fragments and documents.
However, this v0 focuses on GPT-like conversations and AI chat logs.

## Goal

The goal is not to summarize a conversation.

The goal is to extract what can nourish the thinking environment:
decisions, concepts, tensions, movements, structural candidates, emergence points and next actions.

## Process

1. Identify the main axis of the log.
2. Extract useful fragments.
3. Identify thinking movements.
4. Extract stable decisions.
5. Detect emerging concepts.
6. Detect open tensions.
7. Mark strong emergence moments when they exist.
8. Add brief conceptual or historical references when relevant.
9. Propose system destinations.
10. Define the next operational gesture.

## Output template

- Source:
- Axis:
- Useful fragments:
- Thinking movements:
- Stable decisions:
- Emerging concepts:
- Strong emergence moments:
- Conceptual / historical references:
- Open tensions:
- Border markers:
- Excluded material:
- System destinations:
- Validation status:
- Integration decision:
- Next gesture:

## Strong emergence moments

A strong emergence moment is a passage where the conversation produces more than clarification.

It may include:
- a new distinction,
- a shift in level,
- a concept becoming operative,
- a structural decision,
- a new architecture becoming visible,
- or a future method appearing from the material.

These moments should be extracted only when they are actually present.

## Conceptual / historical references

References must remain brief.

Two types are allowed:

1. Invoked references:
   references explicitly present in the log.

2. Suggested references:
   references not present in the log, but useful to situate an emergence point.

Suggested references must be marked as suggested.

## Border markers

Use `#border` only for rare moments where the material exceeds ordinary classification and opens a structurally significant threshold.

A passage may be marked `#border` when at least two of the following are true:

- an unusual distinction appears,
- a concept changes status,
- a new architecture becomes visible,
- a strong bifurcation opens,
- a rare relation becomes productive,
- the material resists available categories,
- the passage has high future generativity.

Do not use `#border` for merely interesting passages.

## Excluded material

Some material should be ignored or kept out of extraction.

Examples:
- terminal noise,
- repeated commands,
- accidental paste fragments,
- export artifacts,
- irrelevant assistant reasoning,
- private content not useful for the project.

## Validation status

Possible statuses:

- raw
- reviewed
- corrected
- accepted
- rejected

## Integration decision

Possible decisions:

- private only
- update repo
- update internal memory
- add to backlog
- use as test material
- discard

## Principle

A log extraction is not a final interpretation.

It prepares conversational material so that Exocortex can later use it as memory, transformation, structure or action.
