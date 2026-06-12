# Practices and examples

This document is living commentary on the [Collaboration Constitution](../README.md) and [Operational Covenant](operational-covenant.md). It contains examples, edge cases, and interpretation. It can change as practice changes.

## Open and usable

Open work is not only a licence or a public repository. It also has to be usable.

Useful questions:

- Who would have trouble using this?
- Does the work require tools, accounts, compute, or bandwidth that collaborators may not have?
- Could a trainee or practitioner understand the next step?
- Is there a plain-language path as well as a technical path?
- Are the files and methods portable enough for someone else to adapt?

Examples:

- A CSV plus documented code is usually more reusable than an Excel-only workflow.
- A Quarto or Markdown document is easier to inspect and fork than a document locked in a proprietary platform.
- A cloud model may be useful, but a local or lower-cost path may be needed for collaborators with data residency, cost, or connectivity constraints.

## Humanistic

AI should strengthen human capacities, not replace them.

Good uses:

- clean up references so a researcher can focus on interpretation
- reformat data so a trainee can inspect patterns
- summarize a meeting so people can act on decisions
- check a draft for missing assumptions
- prepare alternatives that a human can compare and revise

Poor uses:

- replacing a student's chance to design, draw, write, or practise craft when learning or participation is the point
- using a human-looking avatar where people may mistake a system interaction for human care
- drafting a sensitive message before the human has decided what they mean
- turning every time saving into more work
- treating AI fluency as a substitute for understanding

Some work may need to start without AI: a first reading, a hard decision, a conversation about trust, or a moment where people need time to think.

## Consent boundaries

Usually reversible:

- edit a local Markdown draft
- create a proposed patch
- run a local test suite
- summarize a local document
- prepare release notes without publishing them

Externally consequential:

- push a branch to a shared remote
- open a pull request
- send an email or chat message
- post a public document
- delete shared data
- change production settings
- run a billable cloud job

When uncertain, name the uncertainty: "This looks local, but it may affect a shared service because..." Then ask.

## Critical thinking and judgement

AI collaboration should include active attention to assumptions.

Useful prompts:

- What perspective is missing?
- Who benefits from this default?
- Who would find this hard to use?
- What institutional incentive might be shaping the recommendation?
- Is the AI optimizing for completion when the task needs hesitation?
- Are we treating a well-resourced setting as normal?
- What human skill or relationship might this displace?

Bias is not only an AI problem. Human judgement, institutional routines, funding structures, and publication incentives also shape the work.

## Uncertainty reporting

Useful forms:

- "I verified this against the cited source."
- "I inferred this from the surrounding code; I did not find explicit documentation."
- "I am uncertain because the source and the implementation disagree."
- "This is a plausible interpretation, but it should be checked with the domain expert."
- "I found no evidence for this claim in the available files."

Avoid replacing uncertainty with fluent completion. In scientific work, an unresolved question is often a useful output.

## Persistent memory

Persistent memory is useful when it preserves agreed preferences and reduces repeated setup. It is risky when it silently converts inference into policy.

Good practice:

- put durable commitments in versioned documents
- put project-specific instructions in repository files
- keep temporary notes dated and separate
- periodically audit what the AI appears to assume
- correct inferred preferences when they become stale or wrong

## Layering example

The same issue can live at three levels:

- Constitution: AI-assisted work should preserve human responsibility.
- Operational covenant: opening a pull request requires explicit approval.
- Practice example: drafting pull request text locally is reversible; publishing it on GitHub is externally consequential.

Keeping the layers separate helps the constitution stay durable while the practical guidance improves.
