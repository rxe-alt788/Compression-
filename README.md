# Dependency Compression
### Identify what must be true. Remove what merely happens next.

Dependency Compression is a general-purpose method for understanding and reducing the dependencies that constrain an outcome.

It applies across organisations, public services, projects, institutions and everyday processes. The starting point is not the inherited checklist or the sequence people are accustomed to following. It is the target state.

For every apparent dependency, ask:

**If this never happened, could the target state still occur?**

That counterfactual separates a necessary condition from a preferred pathway, a convention or an assumption.

## The working distinctions

- **Required state** — a condition that must be true for the target outcome to be true.
- **Pathway** — one route by which a required state might be achieved. There may be several.
- **Assumption** — a step treated as necessary because it is familiar, customary or embedded in a process, but which has not passed the counterfactual test.
- **Unresolved item** — a possible dependency that needs evidence or further testing.

The distinction matters. A process can contain many steps without containing many true dependencies. Treating every step as mandatory creates queues, delays and artificial scarcity.

## Current implementation

[Dependency Field](https://github.com/rxe-alt788/dependency-field) is the current local-first prototype for applying the method. It captures an outcome, converts it into a target state, classifies candidate items, visualises the resulting dependency field and supports JSON export/import.

The prototype is a research instrument and field-test candidate. It is not yet a validated general-purpose decision engine.

## Research and development

Current questions include:

1. How reliably can ordinary-language outcomes be converted into testable target states?
2. Can users distinguish required states from pathways and inherited assumptions consistently?
3. How should uncertainty and unresolved dependencies be represented?
4. How can dependency maps expose sequencing constraints without turning into another task-management system?
5. Where can the method reduce waiting, coordination cost or unnecessary process without weakening safety, quality or accountability?

The work should be tested against real cases, with claims tied to observed outcomes rather than attractive diagrams.

## Related work

- [Dependency Field prototype](https://github.com/rxe-alt788/dependency-field)
- [Observatory](https://github.com/rxe-alt788/Observatory) — the experimental environment from which related spatial and dependency work emerged.
- [TrinityCo research note: The Queue That Shouldn't Exist](https://trinityco-ai.co/the-queue-that-shouldnt-exist-sequencing-inefficiency-and-dependency-compression/)
- [Trinity Collective research index](https://github.com/rxe-alt788/META)

## Status

**Research framework / prototype implementation in development.**

The method is intended to remain domain-agnostic. No claim is made here that a universal compression algorithm or validated commercial product already exists.

## Contact

John Dunn · [john@trinityco-ai.co](mailto:john@trinityco-ai.co)
