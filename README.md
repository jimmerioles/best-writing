# Best writing research

Research and a ready-to-install skill for AI replies that are easy to understand, approachable, and comfortable to work with.

## The answer in one paragraph

Good AI writing is not the most human-sounding. It is the least effortful to understand and the most evidently chosen. Answer in the first sentence. Explain once, in prose, with given information before new information. Use concrete nouns and numbers. State uncertainty where it changes the decision. Never flatter. Stop when the answer is complete. Rules set the floor; samples of real writing and a separate editing pass raise the voice.

## Start here

- **[CHEATSHEET.md](CHEATSHEET.md)** is the two-minute version: the contract, the four costs, the ten rules, and before/after examples.
- **[research/00-synthesis.md](research/00-synthesis.md)** is the main report: the evidence, the four reader costs, the slop taxonomy, a reply model, and what to install.
- **[skill/best-writing/SKILL.md](skill/best-writing/SKILL.md)** is the installable skill. It turns the findings into a procedure with completion checks, examples, and anti-patterns.
- **[EVAL.md](EVAL.md)** is the ten-prompt protocol for measuring whether a change actually helps.

## Install the skill

```bash
mkdir -p ~/.agents/skills
cp -r skill/best-writing ~/.agents/skills/
```

Start a new session so the skill is discovered. Then ask for writing, editing, or a clearer reply and the skill should load on its own.

For always-on defaults, add the short block from the synthesis to `~/.agents/AGENTS.md`. Keep it under ten lines. Detail belongs in the skill, which loads only when writing is involved.

## The evidence

Three background reports sit behind the synthesis:

| File | Coverage |
|---|---|
| [research/01-academic-evidence.md](research/01-academic-evidence.md) | 60 references on readability, cognitive load, coherence, formatting, LLM-text perception, tone, and evaluation |
| [research/02-community-discourse.md](research/02-community-discourse.md) | 30 Reddit and X sources on what people love, what they hate, and which prompts practitioners report working |
| [research/03-published-guidance.md](research/03-published-guidance.md) | 26 guides and system prompts from Microsoft, Google, Apple, GOV.UK, OpenAI, Anthropic, and others |

## Method and limits

The academic report prioritizes peer-reviewed work and labels evidence strength. The community report is qualitative: Reddit blocked direct fetching, so quotes come from search snippets, and X quotes come from oEmbed or mirrors. Engagement counts are as displayed at capture time. The published-guidance report uses primary documentation and excludes leaked prompts.

Treat the community findings as hypotheses, not proof. The strongest claims in the synthesis are the ones supported by controlled studies and by independent style guides at the same time: answer first, short sentences, given before new, concrete words, prose by default, calibrated uncertainty, and no sycophancy.

## Next step

Add two or three samples of your own writing to `~/.agents/best-writing/voice/samples/`, then list them in `~/.agents/best-writing/voice/voice.md`. The skill reads that profile before drafting. After that, run the protocol in [EVAL.md](EVAL.md). Samples do more for voice than any adjective in a prompt, and edit rate is the most practical measure of whether the writing is getting better.
