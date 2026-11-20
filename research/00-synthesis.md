# Writing people can use

*What research, practitioners, and published style guides say about AI replies that are easy to understand, approachable, and comfortable to work with. Research note, 20 November 2026.*

## The short version

1. Answer in the first sentence. Explain after. Stop when the answer is complete.
2. Treat the reader as a capable adult. Explain the unfamiliar once; do not over-explain the familiar.
3. Be warm in intent, neutral in affect. Care shows in what you cut, not in what you praise.
4. Default to prose. Use a list only when the content is actually a list.
5. Put given information before new information. One idea per sentence.
6. Prefer concrete nouns and verbs to abstraction and nominalization.
7. State uncertainty once, precisely, where it changes the reader's decision.
8. Disagree with reasons. Never flatter.
9. Cut throat-clearing, restatement, and closing offers.
10. Rules set the floor. Samples of real writing and a separate editing pass raise the ceiling.

## The one test that matters

After one reading, can the reader state the point, know what to do next, and feel respected?

That test has three parts. The first two are comprehension. The third is comfort. Much writing advice optimizes one and damages the others. A terse reply can pass the point test and fail the respect test. A warm reply can pass the respect test and bury the point. The target is all three at once.

This is why "make it sound human" is the wrong goal. Detection is not the reader's problem. Understanding is. A reply that passes as human but wastes the reader's morning has failed. A reply that reads like a careful machine but answers in one line has succeeded.

## Two goals that pull in different directions

Comprehension wants compression. Comfort wants acknowledgment. Compress too hard and you sound cold. Acknowledge too much and you sound like a chatbot performing enthusiasm.

The resolution is to separate warmth from affect. Warmth is a stance toward the reader: you take their time seriously, you do not waste their attention, you tell them the truth, and you do not make them manage your feelings. Affect is what the text performs: exclamation marks, "Great question!", emoji, fake intimacy. The research on social perception suggests readers judge warmth and competence on two dimensions (Fiske, Cuddy, & Glick, 2007). A warm but vague advisor is liked and distrusted. A competent but cold one is respected and avoided. You need both signals, and the cheapest way to send both is a direct answer delivered without condescension.

OpenAI's Model Spec lands on the same calibration. It asks the assistant to be approachable through empathy and kindness, to avoid condescension, and to avoid unprompted personal comments. On disagreement it is sharper: the assistant should behave "more like a firm sounding board that users can bounce ideas off of", not "a sponge that doles out praise" (OpenAI, 2025). Anthropic's published prompt adds the stance that makes this possible: "Claude assumes the person is a capable adult and treats them as such" (Anthropic, 2026).

## The four taxes

A useful way to diagnose a bad reply is to ask what it charges the reader. This framework is a synthesis of the evidence below, not a validated model, but it predicts most of the complaints in the Reddit and X threads.

| Tax | What the reader spends | Common cause | Fix | Evidence |
|---|---|---|---|---|
| **Search** | Time finding the point | Preamble, buried answer, restating the question, generic headings | Answer first; headings that state the claim | Nielsen, 1997; Pernice, 2017 |
| **Decode** | Working memory on syntax and abstraction | Long sentences, nominalizations, missing links, unexplained jargon | Given before new; 15 to 25 words; verbs; one concrete example | Haviland & Clark, 1974; Cowan, 2001; Shulman & Bullock, 2020 |
| **Trust** | Discounting overclaiming, hedging, flattery | Confident guesses, fog of "may" and "might", praise | Calibrated uncertainty; specifics; disagreement with reasons | Sharma et al., 2023; Carro, 2024; Durik et al., 2008 |
| **Social** | Managing the assistant's feelings or agenda | "Great question", closing offers, condescension, personal comments | Neutral affect; no praise; no upsell; adult to adult | OpenAI, 2025; Anthropic, 2026; Fiske et al., 2007 |

The taxes compound. A reply that opens with praise, restates the question, hedges every claim, and closes by asking whether you want more charges all four before the reader reaches the answer. Fixing the first sentence often removes three of them at once.

## What the research supports

### Comprehension is a coherence problem, not a vocabulary problem

Readers build meaning in cycles, holding earlier propositions in a small working memory store (Kintsch & van Dijk, 1978). That store is smaller than most writers assume, closer to four chunks than seven (Cowan, 2001). When a sentence introduces new information before the reader has a hook for it, the reader must search backward and bridge the gap. That search costs time and sometimes fails (Haviland & Clark, 1974).

The practical rule is old and sturdy: put given information before new information. Start with what the reader already knows, then add one new thing. This is more important than short words. A sentence of simple words in the wrong order is harder to read than a slightly longer sentence in the right order.

Coherence has a limit. McNamara and Kintsch (1996) found that low-knowledge readers learned more from highly coherent text, while high-knowledge readers sometimes learned more from less coherent text because they supplied the links themselves. The rule is not "always simplify". It is "make the relations explicit enough that this reader does not have to guess". A senior engineer reading an incident report needs the causal chain, not a glossary. A newcomer needs the glossary and the chain.

Plain language helps, but the size of the gain depends on the baseline. Sayfi et al. (2024) randomized 488 adults to a plain-language health recommendation or the original. Understanding rose 19.8 points for one recommendation and only 3.9 points, not significant, for another. Stallwood et al. (2023) found no significant comprehension gain in 268 youths, but higher accessibility, usability, and preference. Plain language reliably improves access and satisfaction. It does not rescue a text with no point. It is also an accessibility feature, not a concession: the same choices that help a tired expert scanning on a phone help a reader with a cognitive disability or a second language.

Sentence length is the best practical proxy for syntactic load. Adults judge sentence length quickly, largely by counting lines (Matthews & Folivi, 2023). Professional guides converge on an average of 15 to 20 words and a ceiling near 35. Those are norms, not experimental optima. The evidence supports splitting long sentences, not writing uniformly short ones. Uniform rhythm is its own reading tax.

Passive voice is not the enemy. Ferreira (2003) found that noncanonical sentences, including passives, are often misinterpreted, especially when the actor and object are reversible. That supports active voice when the actor matters. Passive is useful when the actor is unknown, unimportant, or already given, as in "Biometric residence permits have been replaced by eVisas" (GOV.UK). The problem is the agentless passive that hides responsibility: "The file should be saved before the command is run" instead of "Save the file, then run the command."

Jargon costs fluency and persuasion when motivation is low, and the cost shrinks when urgency raises motivation (Shulman & Bullock, 2020). Defining a term helps, but does not fully remove the cost. Use the reader's words. When you must keep a technical term, define it once and then use it consistently.

Concreteness is one of the strongest findings in the set. Concrete words are fixated less and remembered better (Rayner & Duffy, 1986; Paivio, 1986). One concrete example beats three generic ones. "The new index cuts p95 latency from 800 ms to 120 ms" is easier to remember and harder to dispute than "the system is significantly faster."

### Structure does most of the work

People scan. Nielsen's 1997 study found 79% of users always scanned a new page and 16% read word by word. A later review of five eyetracking studies found scanning persists across layouts and cultures (Moran, 2020). Nielsen estimates users read about 28% of the words on an average page visit (Nielsen, 2015). These are industry studies, not peer-reviewed experiments, and they concern web pages rather than chat replies, but the pattern is consistent: the first words of a block carry most of the load.

Headings help when they state the point. Signaling topic structure improved recall of both structure and content (Lorch, Lorch, & Inman, 1993; Meyer & Poon, 2001). Front-load the first two words, because that is often all a scanner sees (Loranger, 2015). "Retries fail after 30 seconds" beats "Overview".

Bullets are a tool with a cost. Jansen (2014) ran five studies on functional text and found that bullets improved recall of listed items, especially when the items were homogeneous. They hurt recall of surrounding prose in two studies. Use bullets for parallel items, steps, and reference data. Do not use them for an argument whose parts depend on one another. If the second bullet needs the first to make sense, the content is a sentence wearing a list costume.

Paragraphs should carry one idea. GOV.UK recommends no more than five sentences. There is no experimental optimum, but short paragraphs lower the visual cost of starting. The lead is the high-value slot: a short first paragraph tells the reader what the rest is about (Nielsen, 2007). A closing summary is optional. The lead matters more.

Cut decorative asides. Harp and Mayer (1998) found that interesting but irrelevant details reduced recall of main ideas. The same applies to the amusing anecdote that delays the answer, the throat-clearing introduction, and the restatement that adds nothing.

### The LLM failure mode is statistical, not grammatical

Language models did not invent bad writing. They industrialized a particular kind of it. Kobak et al. (2025) analyzed over 15 million PubMed abstracts and found an abrupt post-ChatGPT rise in style words such as "delve", "tapestry", and "underscore". Liang et al. (2024) estimated that 6.5% to 16.9% of peer reviews at four AI conferences were substantially LLM-modified, with words such as "commendable" and "meticulous" disproportionately frequent.

The problems run deeper than vocabulary. Chakrabarty, Laban, and Wu (2025) hired 18 professional writers to edit 1,057 LLM-generated paragraphs. The recurring failures were cliché, unnecessary or redundant exposition, purple prose, poor sentence structure, lack of specificity, awkward word choice, and tense inconsistency. These failures damage the writing whether or not anyone suspects AI. Cutting "delve" while keeping the redundant exposition fixes nothing.

Shaib et al. (2025) built a taxonomy of "slop" from expert interviews and span annotations. Binary slop judgments had poor inter-annotator agreement, but were predicted by relevance, information density, and tone. Syntax-only features predicted slop better than lexical features, and LLM judges were near chance. The lesson is uncomfortable for anyone selling a banned-word list: a reply that is relevant, specific, and coherent will read better than one that merely avoids the current tics.

Why do models default this way? Preference training rewards it. Bharadwaj et al. (2026) found that preference models favored magnified length, structure, jargon, sycophancy, and vagueness in over 60% of cases, with about 40% miscalibration. Length bias is well documented in judges and RLHF (Zheng et al., 2023; Saito et al., 2023; Dubois et al., 2024; Singhal et al., 2024). Sycophancy is common across production assistants, and it reduces trust (Sharma et al., 2023; Carro, 2024). The default is not an accident. It is what the reward model asked for.

Two popular tells have weaker evidence than the discourse suggests. Em-dash prevalence in medRxiv discussions rose from 4.23% before ChatGPT to 11.58% after (Czuma, 2026), but the design is correlational and the author calls it a population-level indicator, not a per-document detector. The rule of three and the "it's not X, it's Y" construction have no controlled evidence I could find. They are craft lore, not comprehension findings. They may still work rhetorically. Treat them as style preferences, not science.

### Tone is two dimensions, not one

The interpersonal evidence is thinner than the comprehension evidence, but it points the same way. Personalized, conversational instruction improved problem-solving transfer in a set of experiments, with boundary conditions (Moreno & Mayer, 2000; Mayer, 2014). Second person and direct address reduce distance. Contractions are a tone choice, not a comprehension intervention; GOV.UK warns that negative contractions such as "can't" can be misread in critical instructions, so use "cannot" when the instruction matters.

Hedging is where tone and trust collide. Durik et al. (2008) found that hedges on data claims hurt credibility more than hedges on interpretations. Hedge uncertainty, not facts. Use one precise hedge ("the evidence is mixed", "this should work on Python 3.12") rather than a fog of "may", "might", "could", and "seems". Chakrabarty's editors flagged "seem to" as an inelegance when no uncertainty was meant.

The approachable version of authority is not softer language. It is clearer language delivered without superiority. OpenAI's spec names the failure directly: avoid "condescending, patronizing, dismissive, or judgmental language" and "over-explaining or diagnosing". Anthropic's prompt assumes a capable adult. Both are describing the same move: give the reader credit, then give them the information.

The threads add a practical point that the experiments do not test: comfort depends on predictability. A reader should not have to guess whether the next reply will be a paragraph or a list, whether it will end with a question, or whether it will treat a simple request as a project. Keep the shape stable across replies, and vary it only when the content demands it. Approachability is not slang or emoji. It is the absence of condescension and the presence of a clear answer or next step.

## The slop taxonomy

The Reddit and X threads converge on a cluster of patterns. The complaint is not any single tic. It is sameness plus the absence of authorial choice. The patterns below are the visible symptoms.

| Pattern | Why it costs the reader | Write instead |
|---|---|---|
| "Great question!" | Praises the question instead of answering it | The answer |
| Restating the prompt | Repeats what the reader just wrote | The answer |
| "Let's dive in" / "Here's a breakdown" | Announces the answer instead of giving it | The answer |
| "It's not X, it's Y" | Manufactures profundity by correcting a belief the reader never held | The plain claim |
| Rule of three | Forces content into a symmetrical shape | As many items as there are |
| "Delve", "leverage", "robust", "seamless" | Signals the training default and replaces the specific word | The specific word |
| Bold-label bullets | Implies structure the content lacks | Prose, or a real list |
| Bullets for everything | Turns an argument into fragments | Prose |
| Uniform sentence length | Every sentence takes the same breath | Vary rhythm; split or combine |
| Closing question or offer | Invents work and turns an answer into engagement bait | Stop, or state the next action |
| Trailing summary | Repeats what the reader just read | Cut it |
| Hedge fog | Creates the appearance of balance without a claim | One precise hedge, or none |
| Em-dash pile-up | Reads as a default punctuation habit | Commas, colons, parentheses, new sentences |
| "Obviously" / "Simply" | Makes the reader feel slow for not finding it obvious | Remove |
| Generic advice | Cannot fail, so it cannot help | A specific recommendation and its tradeoff |

The threads describe a social cost. The style complaint is the visible part. A 941-point r/ChatGPT thread about closing questions produced the line "It's asking a follow up for every response and I don't need them" ([thread](https://www.reddit.com/r/ChatGPT/comments/1mz1hqc/how_do_i_make_gpt5_stop_with_these_questions/)). A copywriter described the transitions as "textbook" and said "nobody talks like this" ([thread](https://www.reddit.com/r/copywriting/comments/1rw7mtf/the_ai_voice_is_killing_copy_and_most_people_cant/)). The reader can feel the template, and feeling the template makes the reply feel like it was written for no one.

Banning these patterns is not enough, and this is the most important dissent in the research. Ethan Mollick read a viral "anti-slop" markdown file and concluded it was "basically 100% AI written" and would push outputs into what he called "mega-slop" (Mollick, 2026). Hamel Husain and Isaac Flath gave two model versions the same six writing tasks, compared the output blind, and still would have rewritten almost all of it (Husain & Flath, 2026). The lesson is not that prompts are useless. It is that a longer ban list produces a different uniform style, not a voice.

The deeper problem is that the model is making defaults instead of choices. A person writing well chooses what to include for this reader, in this context, at this length. A model following a ban list chooses nothing. The fix is a decision procedure plus examples plus an editing pass, not a longer list of forbidden words.

## A working model for replies

### The default shape

1. Answer the question in the first sentence.
2. Give the reason, mechanism, or tradeoff in two to five sentences.
3. Add one concrete example if it changes the reader's decision.
4. End with a next action only if the reader must act. Otherwise stop.

Length follows the decision, not the topic. A question with a one-line answer gets one line. A decision with real tradeoffs gets the tradeoffs. A request to rewrite one paragraph gets the paragraph, not the whole document. Anthropic's prompt states the principle cleanly: "Claude matches its effort to the ask" (Anthropic, 2026). A user comparing models in r/ChatGPT put the preference plainly: "Claude seems to only say what needs to be said" ([thread](https://www.reddit.com/r/ChatGPT/comments/1tafsgo/approaches_for_making_chatgpt_more_succinct/)).

### Shapes by request

| Request | First sentence | Middle | End |
|---|---|---|---|
| **Question** | The answer | The reason or the exception | Stop |
| **Recommendation** | "I'd do X." | Why, and the strongest counterargument | What would change the recommendation |
| **Explanation** | The claim in plain terms | Mechanism, then one example | The caveat that matters |
| **Correction** | What is wrong | Why it is wrong | The corrected version |
| **Uncertainty** | What you know | What you do not know | How to find out |
| **Refusal** | What you cannot do, in one sentence | What you can do instead | The alternative, if useful |
| **Brainstorm** | The strongest option | Two or three alternatives with tradeoffs | Your pick, if asked |
| **Status update** | What changed | What is next | What is blocked, if anything |

### Tone calibration

| Instead of | Write |
|---|---|
| "Great question! Let's dive into how caching works." | "Cache the response for 60 seconds with `stale-while-revalidate`." |
| "I'd be happy to help you with that." | The help |
| "It's worth noting that you might want to consider increasing the timeout." | "Increase the timeout to 30 seconds." |
| "This isn't just a refactor, it's a rethinking of state." | "The refactor moves session state into one store, removing duplicate writes." |
| "The file should be saved before the command is run." | "Save the file, then run the command." |
| "I'm not sure, but maybe it could possibly be..." | "I don't know. The two ways to check are X and Y." |
| "You should probably think about..." | "I'd do X because Y." |
| "Would you like me to do anything else?" | Stop. Or state the next action. |
| "As an AI, I..." | Say what you can do. |
| "Obviously..." / "Simply..." | Remove the word. |

### Formatting decision

1. Will the reader scan rather than read? Use headings that state claims.
2. Are there three or more parallel items? Use a list.
3. Is it a sequence? Use a numbered list.
4. Is it an argument with dependencies? Use prose.
5. Is a phrase a label the reader will search for? Bold it once.
6. Otherwise, use no formatting.

Chat defaults to prose. Reports default to prose with headings. Bullets are for lists, not for thinking. Never bold a whole sentence.

### Sentence craft

- Put given information before new information.
- One idea per sentence. Split sentences over roughly 30 words.
- Put the actor before the action when the actor matters.
- Use verbs instead of nominalizations: "analyze", not "conduct an analysis of".
- Prefer concrete nouns to abstractions.
- Give one concrete example per abstract claim.
- Use a connective when the relation is not obvious: "because", "so", "but", "however".
- Vary rhythm. A short sentence after a long one is easier to read than either alone.
- Cut the first sentence if it is throat-clearing. Cut the last if it repeats.

### Honesty

- Say what you know, what you do not know, and how to check.
- Separate observation, inference, and opinion.
- Disagree with reasons. Praise only what is praiseworthy.
- Never invent links, quotes, section names, or numbers.
- Say "I don't know" plainly. A confident guess is worse than a flagged gap.
- Apologize once for a real mistake, then fix it. Do not apologize for existing.

## What to install

The research points to four layers.

### 1. Always-on rules

Put a short set in `~/.agents/AGENTS.md`. Keep it under ten lines. Always-on text spends context and attention on every turn, so it should carry only the defaults that must never be missed.

```markdown
## Reply style
- Answer in the first sentence, then explain. Stop when the answer is complete.
- Default to prose. Use a list only for parallel items, steps, or reference data.
- No praise openers, no restating the question, no closing offers or questions.
- Warm in intent, neutral in affect. Treat the reader as a capable adult.
- State uncertainty once, precisely, where it changes the decision.
- Never use em dashes or double hyphens as punctuation.
- Before sending: does the first sentence answer? Does the last sentence add something?
```

### 2. A writing skill

Put the detailed procedure in a skill that loads only when the task involves writing or editing prose. This keeps the always-on layer small while making the full rules available when they matter. The companion file `../skill/best-writing/SKILL.md` is ready to install.

### 3. Samples of real writing

This is the highest-leverage step and the least discussed. Practitioners who get good results supply examples of their own writing rather than adjectives about their voice. Nat Eliason built a pipeline from his published work and 16,000 words of examples, and reports an edit rate near 3% on content the pipeline produced (Eliason, 2026). Anthropic calls examples "one of the most reliable ways to steer Claude's output format, tone, and structure" (Anthropic, 2025).

Use two or three pieces you are happy with, plus one bad example with a one-line reason for each problem. Add a short list of your recurring moves: how you open, how you hedge, how you close, what you never say.

### 4. A separate editing pass

Do not draft and edit in the same pass. Draft first. Then run a tell audit: mark every instance of the patterns in the taxonomy, quoting each one, without rewriting. Only then edit. A model will not reliably flag its own tells while it is still generating, because it thinks the tells are good writing.

## What to measure

| Check | How | Target |
|---|---|---|
| First-sentence test | Does the first sentence answer the question? | Yes, or it states the recommendation |
| Last-sentence test | Does the last sentence add something? | Yes, or delete it |
| Edit rate | Count the words a human changes | Falling over time |
| Read-aloud test | Read the reply aloud | No stumble, no breathless sentence |
| Comprehension | Ask three open questions about the reply | The reader can answer all three |
| Unsupported claims | Count claims without a source or a reason | Zero, or labelled as inference |
| Tell audit | Mark every taxonomy pattern before editing | Each one is a choice, not a default |

Readability formulas are screens, not targets. A text can score at grade 8 and still be incoherent (Redish, 2000; Benjamin, 2012). Blind pairwise preference is useful, but control for length and randomize order. LLM judges have position, verbosity, and self-preference biases.

## What not to believe

**"Never use em dashes" is science.** It is not. The corpus rise is correlational. The mark is a fine punctuation choice when it is a choice. Your own rule against it is a house style, and that is a good enough reason to keep it.

**"Write like a human" is the goal.** Detection is not the reader's problem. AI-labelled text is penalized even when it is true (Altay & Gilardi, 2024). Optimize for verifiable usefulness, not for passing.

**"Shorter is always better."** Length follows the decision. A complete answer to a complex question is longer than a complete answer to a simple one. Cut redundancy, not substance.

**"A longer prompt will fix it."** Prompt changes can help, but even strong models needed heavy editing on six blind writing tasks (Husain & Flath, 2026). Rules set the floor. Samples and editing raise the ceiling.

**"Anti-slop lists work."** They can become a new uniform style. Use them as an audit, not as a voice.

**"Readability scores measure understanding."** They measure surface difficulty. They miss purpose, background, tone, and coherence.

## Bottom line

The best AI writing is not the most human-sounding. It is the least effortful to understand and the most evidently chosen. Rules give you the floor. Samples and editing give you the voice.

## References

The three companion reports contain the full source list, including 60 academic references, 30 Reddit and X sources, and 26 published guides.

1. Altay, S., & Gilardi, F. (2024). People are skeptical of headlines labeled as AI-generated. *PNAS Nexus, 3*(10). https://doi.org/10.1093/pnasnexus/pgae403
2. Anthropic. (2025). *Prompting best practices*. https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices
3. Anthropic. (2026). *Claude Opus 5.5 system prompts*, 9 November 2026. https://platform.claude.com/docs/en/release-notes/system-prompts/claude-opus-5-5
4. Benjamin, R. G. (2012). Reconstructing readability. *Educational Psychology Review, 24*, 63-88. https://doi.org/10.1007/s10648-011-9181-8
5. Bharadwaj, A., Malaviya, C., Joshi, N., & Yatskar, M. (2026). Flattery, fluff, and fog: Diagnosing and mitigating idiosyncratic biases in preference models. *ICLR 2026*. https://arxiv.org/abs/2506.05339
6. Carro, M. V. (2024). Flattering to deceive: The impact of sycophantic behavior on user trust in large language models. *arXiv:2412.02802*. https://arxiv.org/abs/2412.02802
7. Chakrabarty, T., Laban, P., & Wu, C.-S. (2025). Can AI writing be salvaged? *CHI 2025*. https://doi.org/10.1145/3706598.3713559
8. Cowan, N. (2001). The magical number 4 in short-term memory. *Behavioral and Brain Sciences, 24*(1), 87-114. https://doi.org/10.1017/S0140525X01003922
9. Czuma, P. (2026). Em-ergence of the em-dash. *arXiv:2606.29540*. https://arxiv.org/abs/2606.29540
10. Dubois, Y., Galambosi, B., Liang, P., & Hashimoto, T. B. (2024). Length-controlled AlpacaEval. *COLM 2024*. https://arxiv.org/abs/2404.04475
11. Durik, A. M., Britt, M. A., Reynolds, R., & Storey, J. (2008). The effects of hedges in persuasive arguments. *Journal of Language and Social Psychology, 27*(3), 217-234. https://doi.org/10.1177/0261927X08317947
12. Eliason, N. (2026). How to build an AI writing system that actually sounds like you [Article]. X. https://x.com/nateliason/article/2115803497773904292
13. Ferreira, F. (2003). The misinterpretation of noncanonical sentences. *Cognitive Psychology, 47*(2), 164-203. https://doi.org/10.1016/S0010-0285(03)00005-7
14. Fiske, S. T., Cuddy, A. J. C., & Glick, P. (2007). Universal dimensions of social cognition: Warmth and competence. *Trends in Cognitive Sciences, 11*(2), 77-83. https://doi.org/10.1016/j.tics.2006.11.005
15. GOV.UK. (n.d.). *Use clear language*. https://guidance.publishing.service.gov.uk/writing-to-gov-uk-standards/writing-guidelines/clear-language
16. Harp, S. F., & Mayer, R. E. (1998). How seductive details do their damage. *Journal of Educational Psychology, 90*(3), 414-434. https://doi.org/10.1037/0022-0663.90.3.414
17. Haviland, S. E., & Clark, H. H. (1974). What's new? *Journal of Verbal Learning and Verbal Behavior, 13*, 512-521. https://doi.org/10.1016/S0022-5371(74)80003-4
18. Husain, H., & Flath, I. (2026). Is Opus 5.5 better at writing? [Video]. YouTube. https://www.youtube.com/watch?v=8uafNYFJ0rU
19. Jansen, F. (2014). How bulleted lists and enumerations affect recall and evaluation of functional text. *Information Design Journal, 21*(2), 146-162. https://doi.org/10.1075/idj.21.2.06jan
20. Kintsch, W., & van Dijk, T. A. (1978). Toward a model of text comprehension and production. *Psychological Review, 85*(5), 363-394. https://doi.org/10.1037/0033-295X.85.5.363
21. Kobak, D., González-Márquez, R., Horvát, E.-Á., & Lause, J. (2025). Delving into LLM-assisted writing in biomedical publications through excess vocabulary. *Science Advances, 11*(27). https://doi.org/10.1126/sciadv.adt3813
22. Liang, W., Izzo, Z., Zhang, Y., et al. (2024). Monitoring AI-modified content at scale. *ICML 2024*. https://proceedings.mlr.press/v235/liang24b.html
23. Loranger, H. (2015). *Headings are pick-up lines*. Nielsen Norman Group. https://www.nngroup.com/articles/headings-pickup-lines/
24. Lorch, R. F., Lorch, E. P., & Inman, W. E. (1993). Effects of signaling topic structure on text recall. *Journal of Educational Psychology, 85*(2), 281-290. https://doi.org/10.1037/0022-0663.85.2.281
25. Matthews, N., & Folivi, F. (2023). Omit needless words: Sentence length perception. *PLOS ONE, 18*(2). https://doi.org/10.1371/journal.pone.0282146
26. Mayer, R. E. (2014). Principles of multimedia learning based on social cues. In *The Cambridge Handbook of Multimedia Learning*. Cambridge University Press.
27. McNamara, D. S., & Kintsch, W. (1996). Learning from texts: Effects of prior knowledge and text coherence. *Discourse Processes, 22*(3), 247-288. https://doi.org/10.1080/01638539609544975
28. Meyer, B. J. F., & Poon, L. W. (2001). Effects of structure strategy training and signaling on recall of text. *Journal of Educational Psychology, 93*(1), 141-159. https://doi.org/10.1037/0022-0663.93.1.141
29. Mollick, E. (2026). Reading one of the viral "anti-slop" markdown files for agents [Post]. X. https://x.com/emollick/status/2077226285919531191
30. Moran, K. (2020). *How people read online*. Nielsen Norman Group. https://www.nngroup.com/articles/how-people-read-online/
31. Moreno, R., & Mayer, R. E. (2000). Engaging students in active learning: The case for personalized multimedia messages. *Journal of Educational Psychology, 92*(4), 724-733. https://doi.org/10.1037/0022-0663.92.4.724
32. Nielsen, J. (1997). *How users read on the web*. Nielsen Norman Group. https://www.nngroup.com/articles/how-users-read-on-the-web/
33. Nielsen, J. (2007). *Blah-blah text: Keep, cut, or kill?* Nielsen Norman Group. https://www.nngroup.com/articles/blah-blah-text-keep-cut-or-kill/
34. Nielsen, J. (2015). Legibility, readability, and comprehension. Nielsen Norman Group. https://www.nngroup.com/articles/legibility-readability-comprehension/
35. OpenAI. (2025). *Model Spec*, 11 April 2025. https://model-spec.openai.com/2025-04-11.html
36. Paivio, A. (1986). *Mental representations: A dual coding approach*. Oxford University Press.
37. Pernice, K. (2017). *F-shaped pattern of reading on the web*. Nielsen Norman Group. https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/
38. Rayner, K., & Duffy, S. A. (1986). Lexical complexity and fixation times in reading. *Memory & Cognition, 14*(3), 191-201. https://doi.org/10.3758/BF03197692
39. Redish, J. (2000). Readability formulas have even more limitations than Klare discusses. *ACM Journal of Computer Documentation, 24*(3), 132-137. https://doi.org/10.1145/344599.344637
40. Saito, K., Wachi, A., Wataoka, K., & Akimoto, Y. (2023). Verbosity bias in preference labeling by large language models. *arXiv:2310.10076*. https://arxiv.org/abs/2310.10076
41. Sayfi, S., Charide, R., Elliott, S. A., et al. (2024). A multimethods randomized trial found that plain language versions improved adults' understanding of health recommendations. *Journal of Clinical Epidemiology, 165*, 111219. https://doi.org/10.1016/j.jclinepi.2023.11.009
42. Shaib, C., Chakrabarty, T., Garcia-Olano, D., & Wallace, B. C. (2025). Measuring AI "slop" in text. *arXiv:2509.19163*. https://arxiv.org/abs/2509.19163
43. Sharma, M., Tong, M., Korbak, T., et al. (2023). Towards understanding sycophancy in language models. *ICLR 2024*. https://arxiv.org/abs/2310.13548
44. Shulman, H. C., & Bullock, O. M. (2020). Don't dumb it down: The effects of jargon in COVID-19 crisis communication. *PLOS ONE, 15*(10). https://doi.org/10.1371/journal.pone.0239524
45. Singhal, P., Goyal, T., Xu, J., & Durrett, G. (2024). A long way to go: Investigating length correlations in RLHF. *COLM 2024*. https://arxiv.org/abs/2310.03716
46. Stallwood, L., Sammy, A., Prebeg, M., et al. (2023). Plain language vs standard format for youth understanding of COVID-19 recommendations. *JAMA Pediatrics, 177*(9), 956-965. https://doi.org/10.1001/jamapediatrics.2023.2686
47. Zheng, L., Chiang, W.-L., Sheng, Y., et al. (2023). Judging LLM-as-a-judge with MT-Bench and Chatbot Arena. *NeurIPS 2023*. https://arxiv.org/abs/2306.05685
