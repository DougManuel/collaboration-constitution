# Why this document exists

## Context

I am a health researcher. My work serves public health and medicine in low- and middle-income countries. I increasingly collaborate with AI assistants, including Claude, ChatGPT, and coding agents, on substantial research infrastructure work. This document is a durable, session-spanning frame for how my AI co-workers and I work together.

The May 2026 revision separates the project into three layers: a short constitutional core, an operational covenant, and living practices and examples. The purpose of that separation is to keep the constitution durable while allowing practical guidance to improve as tools and workflows change.

## The problem this solves

AI-assisted research raises three questions that do not have obvious answers:

**1. What should the AI do, and what should stay with humans?** The line is drift-prone. New capabilities shift tasks from one side to the other faster than a research team can notice. Without an explicit framework, the line gets renegotiated ad hoc every session, and past decisions drift silently. A constitution creates a place to review that movement.

**2. Whose interests does the work serve?** AI-assisted research can produce outputs that serve researchers with good cloud access (those of us in well-resourced institutions) rather than the populations the work is nominally for. An equity-centred principle makes that tradeoff visible when it would otherwise stay latent in default choices: cloud over local, proprietary over open, English-first over multilingual.

**3. How is the collaboration itself honest?** If the AI fabricates a citation, silently takes over a judgement call, or nudges a design decision without flagging it, the researcher's defence of their work is compromised. Honest uncertainty and clear provenance are necessary for research using AI-assisted methods in front of sceptical reviewers.

A constitution makes these values explicit and durable. It is read by me, read by the AI, and, in this alpha period, read by the team I share it with.

## What it is not

- **Not a usage policy.** Those exist at institutional level and cover compliance. The constitution overlaps with institutional policies but answers different questions.
- **Not an ethics framework.** The Montreal Declaration, OECD AI Principles, UNESCO's AI ethics work, and Anthropic's own Constitutional AI all operate at a societal or corporate scale. The constitution is personal and practitioner-level.
- **Not a tactical instruction file.** `CLAUDE.md`, `AGENTS.md`, `cursor-rules`, and similar files are about configuring AI behaviour in a codebase. They contain tactical rules ("run renv::restore() before commits"). The constitution is about the values those rules serve; it sits at a different layer and is referenced *from* those files.

The constitution sits in an adjacent genre: a personal working agreement that names the values shaping day-to-day decisions between a researcher and their AI collaborators.

## Related work and influences

The clearest antecedent is Anthropic's [Claude Constitution](https://www.anthropic.com/news/claudes-constitution) and the [Collective Constitutional AI](https://facctconference.org/static/papers24/facct24-94.pdf) process. Both encode values into AI training and governance. This document operates on a different axis: the values of the collaboration itself, above the floor that harm-avoidance provides.

The intellectual substrate comes from:

- Open-science scholarship on researcher-centric AI, especially the [LSE Impact blog's "Can AI make research more open?"](https://blogs.lse.ac.uk/impactofsocialsciences/2025/04/04/can-ai-make-research-more-open/).
- Oxford Open Digital Health's work on [Global-South-led responsible AI](https://academic.oup.com/oodh/).
- A broader literature on LMIC health research infrastructure that predates the AI conversation but shapes what "serving LMIC" means in practice.
- Divio's [documentation system](https://docs.divio.com/documentation-system/), which informs the commitment to open and usable work.

The constitution is explicitly *not* trying to be another entry in the `AGENTS.md` / `CLAUDE.md` genre, which is moving toward precision and away from principle. It sits alongside those files, not in place of them.

## How I expect this to evolve

- **Alpha (v0.1-v0.2):** drafted privately with my immediate research team; made public for comment late in the alpha period. Feedback expected on the layered structure, the LMIC framing, the practicality of the consent boundary, and the balance between durable principles and operational guidance.
- **Beta (v0.3-v0.9):** public repository, Zenodo DOI minted, team variant drafted. Possibly a short commentary or preprint explaining the genre.
- **v1.0:** if the genre finds adoption, a stable reference implementation with accumulated amendment history.

## Status

Alpha, updated 2026-06-12. Public repository. No Zenodo DOI yet.
