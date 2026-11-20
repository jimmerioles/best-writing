# Published guidance on writing and AI style

*Research note, 20 November 2026. Quotations were checked against the cited pages. Leaked prompts were not used; Anthropic publishes its own.*

## Executive summary

The style guides disagree about commas, capitalization, and whether "we" is allowed. They agree about what decides whether a reader can use a sentence.

Across 26 documents from Microsoft, Google, Apple, GOV.UK, the US plain-language programme, Mailchimp, Stripe, OpenAI, and Anthropic, seven rules recur in at least six guides: answer first, keep sentences and paragraphs short, cut words that do no work, prefer plain terms and define the ones you must keep, name the actor, format only when the content is structured, and replace adjectives with specifics. Error writing converges on a shape: say what happened, avoid blame, say what to do next.

The AI vendors add a layer because their models' defaults violate the first. OpenAI's Model Spec, Anthropic's published system prompt, Google's Gemini guide, and Microsoft's Copilot guidance spend space on behaviour human guides never had to mention: preambles, flattery, restating the question, bold-label bullets, closing summaries, and formatting as a substitute for thought. The useful rules do not say "be clear". They name the default and replace it. OpenAI: "If the user asks a question, the response should be phrased as a direct answer rather than a list of facts." Anthropic: "Claude avoids over-formatting ... using the minimum formatting needed for clarity."

That is a default gap, not a knowledge gap: defaults change through specific replacements, and the counts below come from this sample.

## Rules that recur across independent authorities

| Rank | Rule | Sources | Representative wording |
|---|---|---|---|
| 1 | Short sentences and paragraphs | 8 | GOV.UK: 5 sentences max; 25-word limit |
| 2 | Prune every word; do not repeat yourself | 8 | Microsoft: "Prune every excess word" |
| 3 | Put the answer or next action first | 7 | Apple: "most important information first" |
| 4 | Plain words; define necessary terms once | 7 | GOV.UK: "buy" not "purchase" |
| 5 | Format only when content is structured | 7 | Anthropic: "minimum formatting needed" |
| 6 | Specifics and numbers over adjectives | 7 | Mailchimp: "Use specific examples" |
| 7 | Name the actor; active voice, second person | 6 | GSA: "You must do it" |
| 8 | Errors say what to do next, without blame | 4 | Apple: "what someone can do to fix it" |
| 9 | Read the draft aloud | 4 | Apple: "read your writing out loud" |
| 10 | Do not flatter; disagree when the evidence does | 3 | OpenAI: "not flatter them" |

The top rules attack one cost: the reader's work of locating the point. The limit is that these guides teach comprehension, not thought.

## Per-source breakdowns

URLs are in the references.

**Microsoft.** The most quotable guide: "Use bigger ideas, fewer words"; "Shorter is always better"; "Prune every excess word." The grammar rule is direct: "Most of the time, start each statement with a verb." Its error rewrite, "Invalid ID" to "You need an ID that looks like this: someone@example.com", supplies the shape.

**Google.** Strict about person and condition order: "Use second person: 'you' rather than 'we'" and "Put conditions before instructions, not after." "Mentioning the circumstance first lets the reader skip the instruction if it doesn't apply." Links take descriptive text, never "click here."

**Apple.** Four imperatives frame it: determine voice, match tone to context, "Be clear", "Write for everyone". The method: "If you can use fewer words, do so. When in doubt, read your writing out loud." It is strictest on pronouns: "Avoid using *we* altogether because it may be unclear who the 'we' in question refers to." Its error rule is the best here: "avoid blame, and be clear about what someone can do to fix it." The Style Guide itself is an A to Z mechanics reference.

**GOV.UK.** Plain English is mandatory: "Plain English is mandatory for all of GOV.UK." Hard limits: "Paragraphs should have no more than 5 sentences each. Try to split up sentences that are over 25 words long." Tone corrects brand warmth: "brisk, but not terse", "serious but not pompous", "emotionless", because adjectives "can make the text sound more emotive and like spin". Structure: "Put the most important information first", and "Do not repeat yourself."

**US plain language.** Digital.gov carries the Plain Writing Act material. It teaches by demonstration: "Not 'It must be done,' but 'You must do it.'" Passive voice "obscures who handles what". Its nominalisation test is the most transferable here: "We analyze data", not "We conduct an analysis of the data."

**Mailchimp.** The best public model of voice and tone as separate variables. Voice is constant ("Human, Familiar, Friendly, Straightforward"); tone moves with the reader's state. "It's always more important to be clear than entertaining." The TL;DR: "Lead with the main point" and "Use short words and sentences."

**Stripe.** Stripe publishes no prose style guide that I could find; claims otherwise are unsourced. Stripe's writing artefact is the error object, which separates a human `message`, a machine `code`, the offending `param`, and a `doc_url` ("A URL to more information about the error code reported"). A style rule expressed as a schema: the message explains, the code routes, the link fixes.

**Chicago and AP.** Chicago requires the serial comma (17th ed., §6.19); AP omits it in a simple series. Microsoft, Google, and Mailchimp side with Chicago. Neither is wrong, because the comma is a house convention, not a comprehension device. What transfers is the meta-rule: choose a convention and apply it without exception.

**OpenAI Model Spec.** The most useful AI style document because it treats style as behaviour with tradeoffs. Responses should be "lucid, succinct, and well-organized"; formatting "used judiciously to aid the user in scanning". The sharpest test: "If the user asks a question, the response should be phrased as a direct answer rather than a list of facts." It ranks a good answer with explanation above reasoning followed by a good answer, and bans sycophancy: do not "flatter them or agree with them all the time." Asked for the capital of France, "Paris is the capital of France" complies; a paragraph on French history violates.

**Anthropic.** Because Anthropic publishes its system prompts, no leak is needed. The November 2026 Opus 5.5 prompt has the most explicit anti-formatting rule anywhere: "Claude avoids over-formatting with bold emphasis, headers, lists, and bullet points, using the minimum formatting needed for clarity." For reports it tightens to prose "without bullets ... unless the person asks for a list or ranking." It resolves the brevity conflict: "Claude matches its effort to the ask." Its character research adds the disposition: tell the truth rather than say what people want to hear.

**Gemini and Copilot.** Gemini asks writers to "Be precise and direct" and to "Control output verbosity", noting models give "direct and efficient answers" unless asked otherwise. Microsoft's four elements (context, goal, source, expectations) make a good brief, and its positive-instruction rule is the one writers ignore most: "telling Copilot what 'to do' rather than what 'not to do' is more effective."

**GPT-5 and Claude prompting guides.** These describe the default that style rules fight. OpenAI's guide reports Cursor's finding that "the model produced verbose outputs, often including status updates and post-task summaries that, while technically relevant, disrupted the natural flow of the user." Anthropic gives the cleanest positive-instruction pair: "Instead of: 'Do not use markdown in your response' / Try: 'Your response should be composed of smoothly flowing prose paragraphs.'"

**AGENTS.md and Claude Code.** AGENTS.md is the cross-vendor convention, "a README for agents", where "the closest AGENTS.md to the edited file wins; explicit user chat prompts override everything." Anthropic's Claude Code guidance: "Keep CLAUDE.md short"; "Only write down what Claude can't find by reading the repo." The format now covers over 60,000 repositories, with sections settling around build commands, code style, testing, and PR rules.

## What makes a writing skill effective

A writing skill is a context pointer plus a procedure. The local `writing-for-agents` skill defines a pointer as "a reference held in the agent's context that names some out-of-context material and encodes the condition for reaching it." The description is therefore a list of branches, not a topic summary. "Use when writing docs" is weaker than naming the artefacts: PR description, release note, error message, API reference.

The procedure needs a completion test. Anthropic's `doc-coauthoring` skill ends each stage on an observable condition ("Sufficient context has been gathered when questions show understanding"). "Refine the draft" invites premature completion. "Does the first sentence answer the question?" is a completion criterion.

Examples outperform rules. Gemini says to "always include few-shot examples"; Anthropic calls examples "one of the most reliable ways to steer Claude's output format, tone, and structure." The strongest pair is one good output and one bad output with a one-line reason.

Anti-patterns work only when they name the default. `frontend-design` lists "the commonest tells of a generated page" with specifics: cream background, terracotta accent, tracked-out all-caps eyebrow. "Avoid AI slop" is empty; "delete 'Let's dive in' and the closing summary" is a test. Phrase the target, not the ban, and match the skill's form to the output you want. A guide written in fragments teaches fragments.

## Default LLM style vs desired style

| Default tell | Why it costs the reader | Rewrite |
|---|---|---|
| "Great question! Let's dive into how caching works." | Delays the answer and performs a relationship nobody asked for. | "Cache the response for 60 seconds with `stale-while-revalidate`." |
| "It's worth noting that you might want to consider increasing the timeout." | Three hedges stack into no instruction. | "Increase the timeout to 30 seconds." |
| "**Performance:** faster. **Reliability:** better." | Bold labels hide the absence of evidence. | "The new index cuts p95 latency from 800 ms to 120 ms." |
| "This isn't just a refactor, it's a rethinking of state." | The frame inflates a modest change. | "The refactor moves session state into one store, removing duplicate writes." |
| "The file should be saved before the command is run." | Hides the actor and the order. | "Save the file, then run the command." |
| "The system is fast, reliable, and scalable." | Three adjectives, no claim a reader can check. | "Most queries return in under 100 ms, with no unplanned downtime in 90 days." |
| "Error: invalid input." | Says what failed, not what to do. | "The date must be in YYYY-MM-DD format, for example 2026-11-20." |

Every row shows the same pattern. The default adds words that signal effort ("I'd be happy to", "Here's a breakdown") instead of words that carry information. The rewrite is usually shorter, but brevity is a side effect. The real change is that the sentence now makes a claim someone could disagree with.

## Conflicts and tradeoffs

**Brevity against completeness.** Microsoft says "Shorter is always better." The Model Spec asks for "thorough and detailed" responses and favours "an immediately usable artifact". Anthropic resolves it: "matches its effort to the ask." Cut redundancy, not substance. Length follows the decision the reader has to make.

**Warmth against authority.** Mailchimp's humor and Microsoft's "warm and relaxed" pull one way; Apple's "avoid the temptation to be too cute" and GOV.UK's "incisive" pull the other. GOV.UK names the risk: "friendliness can lead to a lack of precision and unnecessary words." Warmth is a stance toward the reader, not an affect performed in the text. OpenAI's "colleague, rather than a close personal friend" is the right calibration.

**"You" against "we".** Apple bans "we" because the referent is often unclear. GOV.UK allows it once the organisation is named. Google prefers "you". The narrower rule: use "you" for the reader, and "we" only when the speaker is identified and the sentence describes the speaker's own action.

**Lists against prose.** Google and Microsoft encourage scanning; Anthropic forbids lists in reports unless asked. Lists serve parallel items, sequences, and reference data. Prose serves causation, judgment, and qualification. If the second bullet depends on the first, the content is a sentence wearing a list costume.

## A proposed ruleset

This is a synthesis, not a quotation, written in imperative form so it can be pasted into an `AGENTS.md` or `SKILL.md`.

```markdown
## Answer shape
1. Answer the question in the first sentence. Put the conclusion before the reasoning.
2. Give the default answer first, then the exception. Never stop at "it depends".
3. Stop when the answer is complete. Do not restate the question, recap, or add a summary.

## Sentence craft
4. One idea per sentence. Split sentences over 25 words.
5. Prefer active voice and name the actor: "Save the file", not "The file should be saved".
6. Address the reader as "you". Use "we" only when the speaker is identified.
7. Put conditions before instructions: "To delete the document, click Delete."
8. Replace "significantly", "several", and "quickly" with the measurement.

## Tone
9. Be warm in intent, neutral in affect. Skip "Great question", "Absolutely", and "I'd be happy to".
10. Disagree when the evidence does. Praise only what is praiseworthy.
11. Treat the reader as a capable adult. Explain the unfamiliar once; do not over-explain the familiar.
12. Apologize once for a real mistake, then fix it. Never apologize for existing.
13. Do not use humor to soften a refusal or an error.

## Formatting
14. Use prose by default. Use a list only for parallel items, steps, or reference data.
15. Make every bullet a full sentence or a complete item, not a bold label plus a fragment.
16. Write headings that state the point ("Retries fail after 30 seconds"), not generic nouns ("Overview").
17. Bold at most one phrase per section. Never bold a whole sentence.
18. Use sentence case for headings and the serial comma throughout.

## Honesty
19. State uncertainty where it changes the reader's decision. A confident guess is worse than a flagged gap.
20. Cite the source when a claim is checkable. Say what you did not check.
21. Separate what you observed from what you inferred.
22. Do not invent links, quotes, section names, or numbers. Say "I don't know" when you don't.

## Anti-slop
23. Delete throat-clearing: "Let's dive in", "Here's a breakdown", "It's worth noting".
24. Delete the closing summary unless the piece is long enough to need one.
25. Replace "not just X, but Y" and "X isn't Y, it's Z" with the plain claim.
26. Cut "delve", "leverage", "robust", "seamless", "landscape", "tapestry", and "testament".
27. Do not use em dashes as punctuation. Use a comma, a colon, parentheses, or a new sentence.

## Before sending
28. Check: does the first sentence answer the question? Does the last sentence add something?
```

## References

1. Microsoft, "Top 10 tips for Microsoft style and voice". https://learn.microsoft.com/en-us/style-guide/top-10-tips-style-voice
2. Microsoft, "Microsoft's brand voice". https://learn.microsoft.com/en-us/style-guide/brand-voice-above-all-simple-human
3. Google, "Highlights". https://developers.google.com/style/highlights
4. Google, "Tone". https://developers.google.com/style/tone
5. Google, "Sentence structure". https://developers.google.com/style/sentence-structure
6. Apple, "Writing", Human Interface Guidelines. https://developer.apple.com/design/human-interface-guidelines/writing
7. GDS, "Use clear language". https://guidance.publishing.service.gov.uk/writing-to-gov-uk-standards/writing-guidelines/clear-language
8. GDS, "Use the right tone". https://guidance.publishing.service.gov.uk/writing-to-gov-uk-standards/writing-guidelines/right-tone
9. GDS, "Create a clear structure". https://guidance.publishing.service.gov.uk/writing-to-gov-uk-standards/writing-guidelines/clear-structure
10. GSA, "Writing for understanding". https://digital.gov/guides/plain-language/writing
11. Mailchimp, "Voice and Tone". https://styleguide.mailchimp.com/voice-and-tone
12. Mailchimp, "TL;DR". https://styleguide.mailchimp.com/tldr
13. Stripe, "Errors". https://docs.stripe.com/api/errors
14. *The Chicago Manual of Style*, 17th ed., §6.19. https://chicagomanualofstyle.org
15. *The Associated Press Stylebook*. https://apstylebook.com
16. OpenAI, *Model Spec*, 11 April 2025. https://model-spec.openai.com/2025-04-11.html
17. Anthropic, "Claude Opus 5.5 system prompts", 9 November 2026. https://platform.claude.com/docs/en/release-notes/system-prompts/claude-opus-5-5
18. Google, "Prompt design strategies". https://ai.google.dev/gemini-api/docs/prompting-strategies
19. Microsoft, "Get better Copilot responses". https://support.microsoft.com/en-us/microsoft-365-copilot/get-better-copilot-responses-with-great-prompting
20. OpenAI, "GPT-5 prompting guide". https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide
21. Anthropic, "Prompting best practices". https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices
22. AGENTS.md. https://agents.md
23. Anthropic, "Best practices for Claude Code". https://anthropic.com/engineering/claude-code-best-practices
24. Anthropic, `doc-coauthoring` skill. https://github.com/anthropics/skills/blob/main/skills/doc-coauthoring/SKILL.md
25. Local, `writing-for-agents`. /home/jimmerioles/.agents/skills/writing-for-agents/SKILL.md
26. Local, `frontend-design`. /home/jimmerioles/.agents/skills/frontend-design/SKILL.md

All URLs accessed 20 November 2026; local skills read the same day.
