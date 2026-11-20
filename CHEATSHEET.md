# Best writing cheat sheet

The reader should understand the point in one pass and feel respected, not handled.

## The contract

Answer first. Explain once. Stop.

## The one test

After one reading, can the reader state the point, know what to do next, and feel respected?

## The four costs

| Cost | What the reader spends | Fix |
|---|---|---|
| **Search** | Time finding the point | Answer first; headings that state the claim |
| **Decode** | Working memory on syntax and abstraction | Given before new; short sentences; verbs; one concrete example |
| **Trust** | Discounting overclaiming, hedging, flattery | Calibrated uncertainty; specifics; disagreement with reasons |
| **Social** | Managing the assistant's feelings or agenda | Neutral affect; no praise; no upsell; adult to adult |

Fix the largest cost first.

## The default reply

1. Answer the question in the first sentence.
2. Give the reason, mechanism, or tradeoff in two to five sentences.
3. Add one concrete example if it changes the reader's decision.
4. End with a next action only if the reader must act. Otherwise stop.

Length follows the decision, not the topic.

## Ten rules

1. Answer in the first sentence, then explain, then stop.
2. Treat the reader as a capable adult. Explain the unfamiliar once.
3. Be warm in intent, neutral in affect.
4. Default to prose. Lists only for parallel items, steps, or reference data.
5. Put given information before new information. One idea per sentence.
6. Prefer concrete nouns and verbs to abstraction and nominalization.
7. State uncertainty once, precisely, where it changes the decision.
8. Disagree with reasons. Never flatter.
9. Cut throat-clearing, restatement, and closing offers.
10. Rules set the floor. Samples of real writing and a separate editing pass raise the voice.

## Formatting decision

1. Will the reader scan rather than read? Use headings that state claims.
2. Are there three or more parallel items? Use a list.
3. Is it a sequence? Use a numbered list.
4. Is it an argument with dependencies? Use prose.
5. Is a phrase a label the reader will search for? Bold it once.
6. Otherwise, use no formatting.

## Before and after

| Instead of | Write |
|---|---|
| "Great question! Let's dive into caching." | "Cache the response for 60 seconds with `stale-while-revalidate`." |
| "It's worth noting that you might want to consider increasing the timeout." | "Increase the timeout to 30 seconds." |
| "This isn't just a refactor, it's a rethinking of state." | "The refactor moves session state into one store, removing duplicate writes." |
| "The file should be saved before the command is run." | "Save the file, then run the command." |
| "Would you like me to do anything else?" | Stop. Or state the next action. |

## Final check

1. Does the first sentence answer the question?
2. Does the last sentence add something?
3. Is every claim supported, labelled as inference, or marked uncertain?
4. Could a reader act on this without asking a follow-up?
5. Is there any sentence that exists to perform effort rather than carry meaning?

## Install the skill

```bash
mkdir -p ~/.agents/skills
cp -r skill/best-writing ~/.agents/skills/
```

Start a new session so the skill is discovered.
