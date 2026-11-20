# What Reddit and X Say About Good and Bad AI Writing

Qualitative discourse snapshot, 20 November 2026: what practitioners, writers, and prompt engineers say in public threads.

**Method.** I searched `site:reddit.com`, `site:x.com`, "AI slop writing", "em dash AI", and "system prompt make writing sound human". Reddit blocks direct fetching, so Reddit quotes come from search-result snippets of the threads. X quotes come from oEmbed or mirrors. Engagement is as displayed at capture time. There are 30 primary sources (23 Reddit, 7 X). "Slop" here means low-effort, generic, unedited AI-assisted text, not all AI-assisted text.

## Executive summary

- **The complaint is sameness, not one tic.** Em dashes, "it's not X, it's Y", the rule of three, "delve", bullets, and "Great question" are cited constantly, but sharper commenters treat them as a cluster: density of defaults plus absence of authorial choice.
- **Praise goes to the opposite of performance.** Answer first. Short. Direct. Concrete. Willing to say "I don't know." A voice that could belong to someone.
- **Hate goes to unearned rhetoric and assistant tics.** "It's not X, it's Y" manufactures profundity. The rule of three forces a template. Closing questions invent work. Praise validates the question instead of answering it.
- **Practitioners agree on a small prompt stack.** Name the patterns. Supply samples. Separate drafting from editing. Ban praise and closers. Default to prose. Ask for uncertainty.
- **Professionals treat AI as a useful editor and a bad ghostwriter.** They trust it to flag structure and blind spots, not to rewrite prose without flattening voice.
- **A backlash to the backlash is growing.** Writers report being accused of AI for using em dashes. Critics say anti-slop rules create a new uniform style. Slop, on this view, is low effort, not AI.
- **The evidence is weak.** Almost everything is self-report. Upvotes measure agreement with a complaint, not a remedy. Many prompt threads are lead magnets.

## Where the best threads are

The richest threads were in r/WritingWithAI (craft), r/copywriting and r/freelanceWriters (professional consequences), and r/PromptEngineering and r/ClaudeAI (prompt recipes). r/ChatGPT supplied the largest tell lists; r/ProductManagement supplied the best example of slop at work.

## What people love

### Directness and length

The most consistent praise is for answers that stop when the answer stops. A user comparing models in r/ChatGPT: "Claude seems to only say what needs to be said" ([6 points, May 2026](https://www.reddit.com/r/ChatGPT/comments/1tafsgo/approaches_for_making_chatgpt_more_succinct/)). Prompt recipes repeat it: "Lead with the answer or action no preamble, no 'Great question!', no filler" ([47 points, May 2026](https://www.reddit.com/r/PromptEngineering/comments/1tskcs2/3_years_perfecting_this_system_prompt/)).

A 499-point r/ChatGPT thread asks for "consistent and quality" output, not exhaustive output ([November 2025](https://www.reddit.com/r/ChatGPT/comments/1p7zpzt/i_finally_found_a_prompt_that_makes_chatgpt_write/)).

### Voice and specificity

People praise writing that sounds like a person with a point of view, not an assistant with a job. In r/WritingWithAI, a novelist said "what gpt gave me reads like a human wrote it" and "It's leagues better" ([10 points, October 2025](https://www.reddit.com/r/WritingWithAI/comments/1nw6xwj/my_writing_vs_chatgpt/)).

The prescription is specificity: names, numbers, scenes. Every's style guide says generic AI writing "converges toward the mean" ([March 2026](https://www.techtwitter.com/articles/ai-style-guides-how-to-help-ai-write-like-you)). Nat Eliason's pipeline, built from his published work plus 16,000 words of examples, got his edit rate to about 3% on one piece ([October 2026](https://www.techtwitter.com/articles/how-to-build-an-ai-writing-system-that-actually-sounds-like-you-2115803497773904292)).

### Honesty about uncertainty

One r/PromptEngineering prompt: "When you're uncertain, say so directly and state what you'd need to be sure." ([47 points, May 2026](https://www.reddit.com/r/PromptEngineering/comments/1tskcs2/3_years_perfecting_this_system_prompt/)) Andreessen's prompt asks for "explicit confidence levels (high/moderate/low/unknown)" and says "Never praise my questions or validate my premises before answering" ([X, May 2026](https://x.com/pmarca/status/2051374498994364529)).

### AI as editor and thinking partner

A writer in r/WritingWithAI uses AI to flag telling instead of showing: "it trained me to see my own blind spot" ([38 points, June 2026](https://www.reddit.com/r/WritingWithAI/comments/1ubwze8/the_ai_caught_a_habit_i_couldnt_see_in_my_own/)). A novella writer concludes: "the AI works best as a partner to amplify you" ([28 points, March 2026](https://www.reddit.com/r/WritingWithAI/comments/1rzuba9/i_wrote_two_novellas_with_ai_the_biggest_quality/)).

An r/WritingWithAI commenter says "AI is a terrible editor that will most likely flatten your prose" ([10-point comment, April 2026](https://www.reddit.com/r/WritingWithAI/comments/1sc8o6b/should_i_use_ai_to_edit_a_manuscript/)). Across r/copywriting, r/freelanceWriters, and r/WritingWithAI, the practical consensus is that AI is useful for diagnosis and dangerous for final prose; the disagreement is about where the line sits. A copywriter describes "a quick polish" on an obvious ChatGPT dump: "I essentially have to rewrite the entire thing from scratch" ([36 points, April 2026](https://www.reddit.com/r/copywriting/comments/1se8sya/clients_calling_complete_rewrites_light/)).

### Format that respects the reader

Prose by default, lists only when the content is a list. The r/PromptEngineering prompt includes "No bullet lists for simple answers. Use prose" and "No trailing summaries. The user can read what you just wrote." The r/ClaudeAI anti-speak prompt adds "One idea per sentence" and "Concrete over categorical: real names, real numbers, real channels" ([13 points, September 2026](https://www.reddit.com/r/ClaudeAI/comments/1wc7tn7/my_anti_claudespeak_system_prompt/)).

## What people hate (the slop taxonomy)

| Pattern | Why it annoys people | Evidence |
|---|---|---|
| **Em dash overuse** | A default punctuation habit, not a choice. | "Because most people don't use them in every other sentence the way ChatGPT seems to like doing." ([r/ChatGPT](https://www.reddit.com/r/ChatGPT/comments/1jhmyd9/how_did_the_em_dash_become_the_signature_ai/), 124-point comment, March 2025). Greg Kamradt put it first among his "smells of AI slop" ([X, February 2026](https://x.com/GregKamradt/status/2027460429702959267)). |
| **"It's not X, it's Y"** | Manufactures profundity by correcting a belief the reader never held. | "It's not just excessive, it's *exhausting*." ([megathread](https://www.reddit.com/r/WritingWithAI/comments/1mqse0s/megathread_what_aiisms_give_away_aigenerated/), August 2025) |
| **Rule of three** | Forces content into a symmetrical shape even when there are two points or five. | "Short sentences. For emphasis. Always three." ([same megathread](https://www.reddit.com/r/WritingWithAI/comments/1mqse0s/megathread_what_aiisms_give_away_aigenerated/)) |
| **Lexical markers** | They signal the training default and replace the specific word. | "we shall delve into this tapestry of linguistic patterns" ([same megathread](https://www.reddit.com/r/WritingWithAI/comments/1mqse0s/megathread_what_aiisms_give_away_aigenerated/), parody) |
| **Sycophantic openings** | Praise and fake enthusiasm waste the first line and treat a routine question as an achievement. | "responses often start with phrases like 'Great question,' 'Excellent question,' or 'Great follow-up'" ([r/ChatGPT](https://www.reddit.com/r/ChatGPT/comments/1l5z2ev/apparently_every_question_i_ask_is_greatexcellent/), June 2025). Sam Altman later called the behavior "glazes too much" ([X, April 2025](https://x.com/sama/status/1915910976802853126)). |
| **Closing questions** | They invent work, lead the conversation, and turn an answer into engagement bait. | "It's asking a follow up for every response and I don't need them." ([r/ChatGPT](https://www.reddit.com/r/ChatGPT/comments/1mz1hqc/how_do_i_make_gpt5_stop_with_these_questions/), 518-point comment, August 2025) |
| **Bullets and listicle voice** | Formatting becomes a substitute for thought and implies structure the content lacks. | "Bullet points in casual conversation" ([megathread](https://www.reddit.com/r/WritingWithAI/comments/1mqse0s/megathread_what_aiisms_give_away_aigenerated/)) |
| **Restating and summarizing** | The reader already knows the question and just read the answer. | "the paragraph that opens by restating the question. To the model those are features." ([r/WritingWithAI](https://www.reddit.com/r/WritingWithAI/comments/1wbfg6k/chatgpt_will_never_flag_its_own_writing_tells_in/), September 2026) |
| **Corporate hedging and generic advice** | "Moreover" and "it's important to note" create the appearance of balance without a claim; advice that cannot fail helps no one. | "The transitions are all textbook. 'Moreover'. 'Furthermore'. 'Additionally'. Nobody talks like this." ([r/copywriting](https://www.reddit.com/r/copywriting/comments/1rw7mtf/the_ai_voice_is_killing_copy_and_most_people_cant/), March 2026) |
| **Uniform rhythm and padding** | Every sentence takes the same breath. The reader spends more time reading than the writer spent thinking. | "Every sentence is the same length. Around 15-20 words each. No variation." ([same thread](https://www.reddit.com/r/copywriting/comments/1rw7mtf/the_ai_voice_is_killing_copy_and_most_people_cant/)) |

At work the pattern scales into documents: "PMs ask AI to overthink. Execs ask AI to underthink." ([r/ProductManagement, 144-point comment](https://www.reddit.com/r/ProductManagement/comments/1l3bpcx/ai_slop_experience/)).

## Rules and prompts people report working

"Write like a human" is too vague to work. Most recipes below are written for custom instructions or agent files such as CLAUDE.md and AGENTS.md. As one agency operator puts it: "you can't just tell it to write more naturally, because it doesn't know it's writing unnaturally" ([46 points, August 2026](https://www.reddit.com/r/PromptEngineering/comments/1vq3f5x/how_we_get_ai_to_write_like_a_human_after/)).

1. **Audit before rewriting.** The prompt: "Go through this draft and mark every instance of the following, quoting each one, without rewriting anything." The model thinks these patterns are good writing, so "It will only hunt them if you name them" ([r/WritingWithAI](https://www.reddit.com/r/WritingWithAI/comments/1wbfg6k/chatgpt_will_never_flag_its_own_writing_tells_in/), September 2026).
2. **Ban the tics explicitly.** "Do not end responses with follow-up questions, offers to do more work, invitations to continue, or engagement prompts" ([r/ChatGPT, 941 points](https://www.reddit.com/r/ChatGPT/comments/1mz1hqc/how_do_i_make_gpt5_stop_with_these_questions/)).
3. **Supply samples, not adjectives.** Nat Eliason, Every, and several Reddit threads converge: give the model a few thousand words of your writing plus your recurring moves. Eliason reports 3% edit rate, and admits his odd word choices still get smoothed away.
4. **Separate drafting from editing.** A commenter in r/ClaudeAI: "running them as a separate editing pass over the finished text, where finding and rewriting the tells is the only instruction in play" ([October 2026](https://www.reddit.com/r/ClaudeAI/comments/1wxt051/what_one_line_in_your_prompt_takes_claudes/)).
5. **Constrain structure and closers.** Specify sentence variety, one idea per sentence, active voice, concrete nouns, a closing rule. "End with 1-2 concrete next steps, not open-ended questions" and "No trailing summaries" are the most repeated lines.

## Contrarian and dissenting views

**The em dash panic is collateral damage.** A 17-year veteran in r/freelanceWriters reports: "I've had multiple clients accuse me of AI just because of em dashes" ([623 points, November 2025](https://www.reddit.com/r/freelanceWriters/comments/1oofc4c/im_so_mad_that_i_have_to_change_my_writing_style/)). Eric Mann notes that WordPress inserts em dashes automatically, so the mark can signal a serious writing tool rather than a model ([February 2026](https://eric.mann.blog/ai-slop-and-the-em-dash/)).

**Anti-slop is becoming its own formula.** Ethan Mollick, as reported by a secondary analysis, read a viral "anti-slop" markdown file and concluded it was almost entirely AI-written and would "hyperstition your outputs into mega-slop." His prescription was "a sense of taste," not a longer checklist ([newfacedesign, July 2026](https://newfacedesign.com/blog/anti-slop-files-mollick-taste)).

**The prompt may not matter much.** Hamel Husain and Isaac Flath compared a "slop prompt", a plain-writing prompt, and no system prompt on five examples. Husain reports: "we felt that the prompt doesn't seem to matter much in steering writing on the 5 examples" ([X, September 2026](https://x.com/HamelHusain/status/2096016732385362077)).

**AI can be good, and slop is human.** Eliason's reported 3% edit rate on one piece is the strongest quantified data point. The r/ArtificialInteligence thread "AI Slop Is Human Slop" ([129 points, June 2025](https://www.reddit.com/r/ArtificialInteligence/comments/1l1ki91/ai_slop_is_human_slop/)) reframes the problem: "Behind every poorly written AI post is a human being that directed the AI to create it." A non-native speaker in r/WritingWithAI asks why people complain: "a dream come true!" ([November 2025](https://www.reddit.com/r/WritingWithAI/comments/1oow50x/what_is_so_anoying_in_ai_writing_text/)).

## Source table

| # | Source | Date | Engagement | URL |
|---|---|---|---|---|
| 1 | r/ChatGPT, u/CharacterForce1569, "Biggest tells" | 2025-03-07 | 1,663 pts, 330 comments | https://www.reddit.com/r/ChatGPT/comments/1j5vy1y/the_biggest_tells_that_something_is_written_by/ |
| 2 | r/ChatGPT, u/wawawaaaaawa, "Em dash signature" | 2025-03-23 | 1,298 pts, 262 comments | https://www.reddit.com/r/ChatGPT/comments/1jhmyd9/how_did_the_em_dash_become_the_signature_ai/ |
| 3 | r/ChatGPT, u/ruchersfyne, "Why people are mad about em dashes" | 2025-06-01 | 37 pts, 133 comments | https://www.reddit.com/r/ChatGPT/comments/1l1027g/why_are_people_mad_about_em_dashes_its_literally/ |
| 4 | r/WritingWithAI, u/Playful-Increase7773, "AI-isms megathread" | 2025-08-15 | 96 pts, 64 comments | https://www.reddit.com/r/WritingWithAI/comments/1mqse0s/megathread_what_aiisms_give_away_aigenerated/ |
| 5 | r/WritingWithAI, u/DelphiParser, "What is so annoying" | 2025-11-05 | 2 pts, 35 comments | https://www.reddit.com/r/WritingWithAI/comments/1oow50x/what_is_so_anoying_in_ai_writing_text/ |
| 6 | r/WritingWithAI, u/Ok_Negotiation_2587, "Never flags its own tells" | 2026-09-09 | 21 pts, 17 comments | https://www.reddit.com/r/WritingWithAI/comments/1wbfg6k/chatgpt_will_never_flag_its_own_writing_tells_in/ |
| 7 | r/ArtificialInteligence, u/Gothmagog, "AI slop is human slop" | 2025-06-02 | 129 pts, 140 comments | https://www.reddit.com/r/ArtificialInteligence/comments/1l1ki91/ai_slop_is_human_slop/ |
| 8 | r/ClaudeAI, u/Mr_Gaslight, "One line to 9/10" | 2026-10-04 | 36-pt comment | https://www.reddit.com/r/ClaudeAI/comments/1wxt051/what_one_line_in_your_prompt_takes_claudes/ |
| 9 | r/ClaudeAI, u/dressinbrass, "Anti Claude-speak prompt" | 2026-09-10 | 13 pts, 33 comments | https://www.reddit.com/r/ClaudeAI/comments/1wc7tn7/my_anti_claudespeak_system_prompt/ |
| 10 | r/PromptEngineering, u/BlablaMind, "3 years perfecting prompt" | 2026-05-31 | 47 pts, 28 comments | https://www.reddit.com/r/PromptEngineering/comments/1tskcs2/3_years_perfecting_this_system_prompt/ |
| 11 | r/PromptEngineering, u/tjrobertson-seo, "Writing like a human" | 2026-08-16 | 46 pts, 21 comments | https://www.reddit.com/r/PromptEngineering/comments/1vq3f5x/how_we_get_ai_to_write_like_a_human_after/ |
| 12 | r/ChatGPT, u/tiln7, "Prompt that writes like human" | 2025-11-27 | 499 pts, 60 comments | https://www.reddit.com/r/ChatGPT/comments/1p7zpzt/i_finally_found_a_prompt_that_makes_chatgpt_write/ |
| 13 | r/ChatGPT, u/DirtyGirl124, "Stop GPT-5 questions" | 2025-08-24 | 941 pts, 773 comments | https://www.reddit.com/r/ChatGPT/comments/1mz1hqc/how_do_i_make_gpt5_stop_with_these_questions/ |
| 14 | r/ProductManagement, u/Money_Impression_321, "AI slop experience" | 2025-06-04 | 172 pts, 59 comments | https://www.reddit.com/r/ProductManagement/comments/1l3bpcx/ai_slop_experience/ |
| 15 | r/copywriting, u/Altruistic_Cream4771, "AI voice is killing copy" | 2026-03-17 | 89 pts, 48 comments | https://www.reddit.com/r/copywriting/comments/1rw7mtf/the_ai_voice_is_killing_copy_and_most_people_cant/ |
| 16 | r/freelanceWriters, u/GloomySlothicorn, "Have to change my style" | 2025-11-04 | 623 pts, 182 comments | https://www.reddit.com/r/freelanceWriters/comments/1oofc4c/im_so_mad_that_i_have_to_change_my_writing_style/ |
| 17 | r/WritingWithAI, u/Sentosa305, "AI to edit a manuscript" | 2026-04-04 | 0 pts, 31 comments; 10-pt comment | https://www.reddit.com/r/WritingWithAI/comments/1sc8o6b/should_i_use_ai_to_edit_a_manuscript/ |
| 18 | r/WritingWithAI, u/abrady, "Two novellas with AI" | 2026-03-21 | 28 pts, 12 comments | https://www.reddit.com/r/WritingWithAI/comments/1rzuba9/i_wrote_two_novellas_with_ai_the_biggest_quality/ |
| 19 | r/WritingWithAI, u/padrinosardo, "AI caught a habit" | 2026-06-21 | 38 pts, 26 comments | https://www.reddit.com/r/WritingWithAI/comments/1ubwze8/the_ai_caught_a_habit_i_couldnt_see_in_my_own/ |
| 20 | r/copywriting, u/Safe-Breadfruit-7555, "Rewrites called proofreading" | 2026-04-06 | 36 pts, 11 comments | https://www.reddit.com/r/copywriting/comments/1se8sya/clients_calling_complete_rewrites_light/ |
| 21 | r/ChatGPT, u/_rickjames_, "ChatGPT more succinct" | 2026-05-11 | 6 pts, 9 comments | https://www.reddit.com/r/ChatGPT/comments/1tafsgo/approaches_for_making_chatgpt_more_succinct/ |
| 22 | r/WritingWithAI, u/beautybruja, "My writing vs chatgpt" | 2025-10-02 | 10 pts, 68 comments | https://www.reddit.com/r/WritingWithAI/comments/1nw6xwj/my_writing_vs_chatgpt/ |
| 23 | r/ChatGPT, u/happyplantt, "Every question is Great" | 2025-06-08 | 52 pts, 57 comments | https://www.reddit.com/r/ChatGPT/comments/1l5z2ev/apparently_every_question_i_ask_is_greatexcellent/ |
| 24 | X, @pmarca, "Custom prompt" | 2026-05-04 | Viral; counts not captured | https://x.com/pmarca/status/2051374498994364529 |
| 25 | X, @sama, "Glazes too much" | 2025-04-25 | Counts not captured | https://x.com/sama/status/1915910976802853126 |
| 26 | X, @GregKamradt, "Smells of AI slop" | 2026-02-27 | Trending that day | https://x.com/GregKamradt/status/2027460429702959267 |
| 27 | X, @petergyang, "No-ai-slop skill" | 2026-07-22 | Counts not captured | https://x.com/petergyang/status/2079943830024188105 |
| 28 | X, @HamelHusain, "Prompt eval" | 2026-09-04 | Counts not captured | https://x.com/HamelHusain/status/2096016732385362077 |
| 29 | X, @paulg, "Founder emails" | 2026-05-25 | Counts not captured | https://x.com/paulg/status/2058863028523659390 |
| 30 | X, @GergelyOrosz, "Talking like LLMs" | 2026-07-04 | ~1.3k likes, 283 replies, ~202k views (archived) | https://x.com/GergelyOrosz/status/2073441539431260410 |

## Limitations

- **Access.** Reddit blocked direct fetching, so quotes come from search snippets that can truncate comments. X often blocks unauthenticated reading; some quotes come from oEmbed or mirrors.
- **Selection and engagement bias.** People post when annoyed. Upvotes reward a memorable complaint, not a tested remedy, and are not comparable across subreddits.
- **No base rates.** Nobody knows how often em dashes appear in human writing, how often "delve" appears in academic writing, or how many accused writers used AI.
- **Prompt threads are marketing.** Many "this prompt fixed everything" posts are lead magnets, and the before/after examples are chosen by the author.
- **Model churn.** The discourse spans 2024 to 2026 across many model versions, and "slop" means low effort, generic style, AI involvement, and content someone dislikes.

## 19 rules distilled from the discourse

**[Consensus]** means the threads broadly agree. **[Contested]** means credible practitioners disagree. **[Emerging]** means promising but thin evidence.

1. **Lead with the answer.** No preamble, no restating, no "Great question." **[Consensus]**
2. **Delete praise and premise validation.** If the premise is wrong, say so first. **[Consensus]**
3. **End when the answer ends.** No summary, no "Would you like me to..." **[Consensus]**
4. **Default to prose.** Bullets only for a genuine list. **[Consensus]**
5. **Vary sentence length and paragraph shape.** **[Consensus]**
6. **Ban "It's not X, it's Y" unless the contrast is real.** **[Consensus]**
7. **Use the rule of three only when there are three things.** **[Consensus]**
8. **Use em dashes sparingly and deliberately.** A pile-up is a tell; the mark itself is not proof of AI. **[Contested]**
9. **Prefer plain verbs and concrete nouns.** Cut "delve", "tapestry", "testament", "robust", "seamless". **[Consensus, with caveats]**
10. **Name the actor.** Prefer "is" to "serves as". **[Emerging]**
11. **Put one specific detail in every abstract claim.** **[Consensus]**
12. **State uncertainty explicitly.** Confidence labels, not blanket hedging or fake certainty. **[Consensus]**
13. **Do not restate the prompt or summarize what the reader just read.** **[Consensus]**
14. **Match format to context.** Chat is not a report. **[Consensus]**
15. **Give samples of your writing, not adjectives about your voice.** **[Consensus among practitioners]**
16. **Separate drafting from editing.** One pass writes, another hunts for tells. **[Emerging]**
17. **Keep the banned-pattern list short and owned.** A downloaded 400-line file can produce a new uniform style. **[Contested]**
18. **Do not edit toward the accusation.** Keep the odd phrase if it serves the sentence. **[Contested]**
19. **Measure edit rate, read aloud, keep a human on the final pass.** **[Emerging]**
