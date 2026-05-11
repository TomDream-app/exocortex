# Log Extractor

## Role

The log extractor is the first transformation protocol for conversational material.

Exocortex can receive many kinds of notes, fragments and documents.
However, this v0 focuses on conversational logs produced through online AI systems.

Its role is not to summarize conversations.

Its role is to extract what can nourish the thinking environment:
movements, decisions, tensions, concepts, structures and next actions.

## Input

The first supported material is:

- GPT-like conversations
- AI chat logs
- exported discussions
- copied conversational fragments

Other types of notes may enter Exocortex, but they are not the primary focus of this extractor.

## Position

capture → memory → transformation → structure → action

The log extractor operates between capture and memory/transformation.

It receives conversational material and prepares it for later structuring.

## Extraction targets

A log extractor may identify:

- main axis of the conversation
- important fragments
- thinking movements
- stable decisions
- emerging concepts
- open tensions
- structural candidates
- destination in the system
- next operational gesture

## Technical treatment

A minimal treatment pipeline is:

1. receive a conversation log
2. identify its main axis
3. segment useful passages
4. extract decisions and concepts
5. detect open tensions
6. propose system destinations
7. produce a short structured output

## Output

The expected output is not a summary.

The expected output is a structured extraction that can feed:

- memory
- transformation
- structure
- action

## Principle

A conversational log is treated as a trace of thought in formation.

The extractor does not close the meaning of the log.
It prepares the material so that Exocortex can later transform it into structure.
