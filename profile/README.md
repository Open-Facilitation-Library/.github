# Open Facilitation Library

Open-source building blocks for agentic facilitation.

## What is OFL?

AI is starting to facilitate real group conversations: deliberation, research interviews, dispute resolution, innovation workshops. OFL is the open commons for doing it well, so teams don't each rebuild the facilitator from scratch.

The core artifact is the **method spec**: a portable, forkable definition of a facilitation method that any capable runtime can execute. Harmonica is the reference implementation, but method specs run anywhere and the evals speak [weval](https://weval.org)'s open format, so nothing is locked to one platform. Every spec has two halves:

- **Protocol** — the method itself: stages, roles, facilitator prompts, and what carries between them.
- **Evals** — how you know it ran well: open rubrics calibrated by expert facilitators, interoperable with weval's eval format.

Around the specs sits the research and reference they draw on: **patterns** (facilitation methods described with the Why-How-Who framework), **teardowns** (how real platforms facilitate today), and a shared **knowledge base**.

## Repositories

- **[evals](https://github.com/Open-Facilitation-Library/evals)** — the Why-How-Who evaluation framework and the eval commons; human-calibrated judging of facilitator performance.
- **[synthesis](https://github.com/Open-Facilitation-Library/synthesis)** — knowledge base, research watchlist, and automated paper discovery.
- **[cross-pollination](https://github.com/Open-Facilitation-Library/cross-pollination)** — opinion-exposure algorithms and experiments for surfacing disagreement.
- **[workflows](https://github.com/Open-Facilitation-Library/workflows)** — teardowns of how real platforms orchestrate AI facilitation agents.
- **[skills](https://github.com/Open-Facilitation-Library/skills)** — executable agent skills (Agent Skills specification).

## Related work

- **[weval](https://weval.org)** (Collective Intelligence Project) — an open, CC0 platform for public LLM evals. OFL's eval specs interoperate, so facilitation evals can run as shared, public-domain blueprints.

## Links

[Wiki](https://wiki.openfac.org) · [Substack](https://openfac.substack.com) · [Giveth](https://giveth.io/project/open-facilitation-library)
