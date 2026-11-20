# Evaluation

Writing quality is easy to feel and hard to measure. Use two cheap measures: edit rate and blind preference.

The goal is not a benchmark score. The goal is fewer edits, fewer unsupported claims, and a reply you would send without rewriting.

## The prompt set

Pick ten requests you actually make. Keep them fixed so runs are comparable. Cover this range:

1. A direct question with a one-line answer.
2. A recommendation with a real tradeoff.
3. An explanation of a technical concept to a smart non-expert.
4. A correction of a wrong assumption.
5. A question the model cannot answer confidently.
6. A refusal with an alternative.
7. A short doc section.
8. A PR description.
9. An error message.
10. A casual chat reply.

Do not use prompts designed to flatter the skill. Use the ones that annoyed you last week.

## The run

1. Start a fresh session for each prompt. Old context changes the result.
2. Use the same model and settings across runs.
3. Save the reply exactly as generated.
4. Edit the reply until you would send it. Count the words you changed.
5. Score the reply with the table below.

Edit rate is words changed divided by total words. Revisions that delete a whole paragraph count every deleted word.

## Scorecard

| # | First sentence answers (0/1) | Last sentence adds (0/1) | Unsupported claims | Words changed | Edit rate | Notes |
|---|---|---|---|---|---|---|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |
| 4 | | | | | | |
| 5 | | | | | | |
| 6 | | | | | | |
| 7 | | | | | | |
| 8 | | | | | | |
| 9 | | | | | | |
| 10 | | | | | | |

## Blind comparison

When you change the skill, keep the old outputs and generate new ones from the same prompts. Then:

1. Match the pairs for length, or score length separately.
2. Randomize which reply is A and which is B.
3. Remove any labels that reveal the source.
4. Pick the better reply in each pair without knowing which version produced it.
5. Count wins, losses, and ties.

A preference win at matched length is a better signal than a longer reply that feels more thorough.

## Comprehension check

For each reply, write three open questions:

- What is the main point?
- What should the reader do next?
- What is uncertain, and why does it matter?

Answer them without looking back at the reply. If you cannot, the reply failed the one-pass test.

## What counts as better

- More first sentences that answer the question.
- Lower edit rate on the same prompts.
- Fewer unsupported claims.
- More blind preference wins at matched length.
- No loss of accuracy or necessary detail.

## Caveats

- Ten prompts is a smoke test, not a benchmark. Treat the numbers as a trend.
- Model versions drift. Re-run the set after a model change.
- Do not tune the skill to the prompt set. If you do, the score stops meaning anything.
- One rater is enough for a personal workflow, but it is not a scientific result.
- The best signal is your edit rate on real work, not a judge's score.
