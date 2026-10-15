# Forever Jung

The structured body of Jungian depth psychology behind [foreverju.ng](https://foreverju.ng), released so you can bring it to an AI of your own.

> **If you are in crisis**, call or text **988** in the US (the 988 Suicide & Crisis Lifeline), or text **HOME** to **741741**. Outside the US, your local crisis line is a search away. These files are not a crisis service, and neither is any AI you paste them into. Dreams can wait. You matter more.

## What this is

Seventeen JSON files, written and audited by Andrew Christison, that together hold a working method for reading dreams and inner life the way Jung did, in plain language first and full depth one layer down:

- **51 concepts** (archetypes, processes, structures, typology), each with a plain-language entry, a depth tier, what it looks like in practice, recognition patterns, related symbols, Jung's own sources, and a note where the idea is contested
- **90 dream symbols** with contextual variations, recognition terms, and the concepts each one tends to carry
- **7 narrative frameworks** (68 stages) with the psychological function of every stage, and **33 bridge mappings** that argue the connections between the frameworks and the concepts
- **36 stories** from 18 myth entries across traditions on five continents, each tied to the concept it embodies
- **A ten-step analysis protocol**, a longitudinal tracking protocol, **12 integration practices**, and dream patterns for recovery, grief, lifespan, relationships, lucid dreaming, nightmares, and recurring dreams
- **Boundaries and Jung's limitations** stated plainly, interpretive humility, body and contemplative context, and the living system: the companion voice, onboarding, and dream incubation

The same files render every page at foreverju.ng. The site is the reference. The companion, described below, is the full method running on your own AI.

## What this is not

Not therapy. Not a diagnostic tool, a treatment, a crisis service, a medical or clinical tool, or a predictive system, and not a substitute for professional mental health care. The files say this themselves (`integrity.json`), and the companion prompt carries it into whatever AI you use.

One caution worth repeating. When you paste these files into an arbitrary model, none of the site's guardrails come with them except what the companion prompt carries. Keep its YOUR LIMITS section intact. It holds the crisis handling and the distinction between a symbolic nightmare and a dream that replays real trauma, which belongs with someone trained in trauma work and not with a reading practice.

## Bring it to your own AI

1. **Get the files.** Download `knowledge-graph/`, or the zip attached to the [latest release](https://github.com/andrewschristison/forever-jung-graph/releases).
2. **Paste the instructions.** Copy the prompt from [`companion/SYSTEM_PROMPT.md`](companion/SYSTEM_PROMPT.md) into your AI's project or system instructions.
3. **Attach the files as knowledge**, then tell it a dream.

Guides for [Claude Projects](companion/claude-projects.md), [ChatGPT](companion/chatgpt.md), [Gemini](companion/gemini.md), [NotebookLM](companion/notebooklm.md), and [local models](companion/local-models.md), plus a one-message check that the limits survived, are in [`companion/`](companion/README.md).

The honest framing: the companion's memory, limits, and privacy are those of the AI you chose, not of this repository or the site. Nothing you type at foreverju.ng leaves your browser. What you type into the companion goes to whichever service runs it.

## The files

| File | What it holds |
|---|---|
| `meta.json` | Version, philosophy, architecture, inventory |
| `concepts.json` | 51 Jungian concepts with plain-language accessibility, depth tiers, and contested flags |
| `symbols.json` | 90 dream symbols with recognition terms, variations, and plain-language meanings |
| `frameworks.json` | 7 narrative frameworks (68 stages) with psychological function annotations |
| `bridge.json` | 33 cross-reference mappings between Jungian concepts and narrative frameworks |
| `myths.json` | 18 story references, 36 stories, 33 tradition labels |
| `assessment.json` | 8 guided reflection prompts for archetypal profiling |
| `analysis-protocol.json` | 10-step dream analysis methodology with 4 analysis modes |
| `series-protocol.json` | Longitudinal tracking: 6 dimensions, 8 milestones, reporting cadence |
| `dream-patterns.json` | Recovery, grief, lifespan, relationships, lucid, nightmares, recurring |
| `integration-practices.json` | 12 practices across 5 types for working with dream content |
| `integrity.json` | Therapeutic boundaries, ethical commitments, Jung's limitations, referral framework |
| `interpretive-wisdom.json` | Validation framework, interpretive humility, post-Jungian voices |
| `contextual-frameworks.json` | Body-dream connections, special populations, contemplative practice |
| `living-system.json` | System prompt, onboarding journey, voice library, dream incubation |
| `user-facing-features.json` | Browsable dictionary spec, dream telling methodology, story analyzer |
| `schema-normalization.json` | Canonical schemas, cross-reference manifest, validation rules |

`schema-normalization.json` describes the shapes and the cross-reference rules; every concept and symbol id referenced anywhere resolves. Some fields are written for the AI rather than for a reader (descriptions, scoring logic, internal framing from Forever Jung's original design as a journaling app). They are left as they are.

## Versions

The data is at graph version `5.0.0-production` (see `meta.json`). Release v1.0 of this repository ships that version. Corrections land at foreverju.ng first and are mirrored here with a new release.

Found an error, a misattribution, or a story told wrong? Open an issue. Accuracy is the point.

## Attribution and license

Built by [Andrew Christison](https://andrewchristison.com). The site is at [foreverju.ng](https://foreverju.ng).

- **Data and companion text** (everything in `knowledge-graph/` and `companion/`, and this README) are licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](LICENSE) (CC BY-NC-SA 4.0). You may use, share, and adapt them for non-commercial purposes, with attribution, and your adaptations carry the same license.
- **Code snippets** (anything in a fenced code block, and any scripts added later) are licensed under [MIT](LICENSE-CODE).

In practice: personal use, teaching, research, study groups, and a free companion for yourself or a friend are all fine. Selling access to these files or to a product built on them is not, without permission. Ask through andrewchristison.com.

A suggested attribution line: *Forever Jung by Andrew Christison, foreverju.ng, CC BY-NC-SA 4.0.*

Jung's own works are cited by title in `jung_sources` fields and summarized in Forever Jung's own words. The epigraph in `meta.json` is a short quotation from the Collected Works, volume 9, part 1.
