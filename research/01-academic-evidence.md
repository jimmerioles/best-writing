# What the evidence says about clear, pleasant writing

*Research report, 20 November 2026. Scope: readability, cognitive science of reading, formatting, LLM-specific style effects, tone, and evaluation. Evidence strengths are labelled.*

## Executive summary

- Comprehension is mainly a coherence problem, not a vocabulary problem. Readers need given information before new information and cannot hold many unresolved links (Kintsch & van Dijk, 1978 [1]; Just & Carpenter, 1992 [3]; Haviland & Clark, 1974 [2]).
- Plain language improves accessibility and satisfaction, and often preference. Comprehension gains are uneven: +19.8 points in one trial, +3.9 and +5.2 (not significant) in two others (Sayfi et al., 2024 [4]; Stallwood et al., 2023 [5]).
- Sentence length is the best practical proxy for syntactic load. An average of 15 to 20 words and a 35-word ceiling are professional norms, not experimental optima (Matthews & Folivi, 2023 [6]).
- Coherence helps novices but can reduce the benefit for experts, who supply missing links themselves (McNamara & Kintsch, 1996 [7]). Match explicitness to prior knowledge.
- Headings and signals improve recall of structure and content; bullets help item recall but can hurt surrounding prose (Lorch et al., 1993 [8]; Meyer & Poon, 2001 [9]; Jansen, 2014 [10]).
- Jargon hurts fluency and persuasion when motivation is low; the effect shrinks under urgency (Shulman & Bullock, 2020 [11]).
- LLM text shows lexical tics and recurring editor flaws: cliché, redundancy, purple prose, poor structure, vagueness, awkward wording, tense inconsistency (Chakrabarty et al., 2025 [12]).
- Preference models reward length, structure, jargon, sycophancy, and vagueness, with about 40% miscalibration; sycophancy also reduces trust (Bharadwaj et al., 2026 [13]; Sharma et al., 2023 [14]; Carro, 2024 [15]).
- Readability formulas are screens, not targets. Use comprehension questions, cloze, and blind length-matched ratings instead (Redish, 2000 [16]; Benjamin, 2012 [17]).

## 1. Readability and comprehension

**Plain language.** Sayfi et al. (2024) [4] randomized 488 adults to a plain-language recommendation or the original. Understanding rose 19.8 points for the WHO recommendation but only 3.9 points, not significant, for the CDC version; accessibility and satisfaction improved. Stallwood et al. (2023) [5] found no significant comprehension gain in 268 youths (+5.2 points), but higher accessibility, usability, satisfaction, and preference. The size depends on the baseline and audience; one plausible reason is that if the standard version is already fairly plain, rewriting buys less.

**Sentence length.** Matthews and Folivi (2023) [6] show that adults judge sentence length quickly and accurately, largely by counting lines. Guidelines cited there converge on 15 to 20 words average and a 35-word ceiling. The evidence supports splitting long sentences, not writing uniformly short ones.

**Syntactic complexity and passive.** Working memory is small, roughly four chunks (Cowan, 2001 [18]). Comprehension suffers when readers hold unresolved dependencies (Just & Carpenter, 1992 [3]). Ferreira (2003) [19] found noncanonical sentences, including passives, are often misinterpreted, especially when reversible or ambiguous. That supports active voice when the actor matters, not a blanket ban. Passive is useful when the actor is unknown, unimportant, or already given: GOV.UK's "Biometric residence permits have been replaced by eVisas" keeps the outcome in focus [20], and Nielsen (2007) [21] makes the same point for headings. The problem is the agentless passive that hides responsibility.

**Jargon, nominalizations, concreteness.** Shulman and Bullock (2020) [11] found jargon reduced fluency and persuasion for flood-risk and policy messages, but not for COVID-19, where urgency raised motivation. Prior work they review found that defining jargon did not fully remove its cost. Use the audience's words; define a necessary term once. GOV.UK also advises breaking up nouns ending in "-ion" and "-ment," which lengthen sentences and obscure action [20]; direct evidence on nominalizations is thin, so treat this as moderate craft advice. Prefer high-frequency and concrete words: they are fixated less and remembered better (Rayner & Duffy, 1986 [22]; Paivio, 1986 [23]). But do not replace a precise technical term with a vague common one.

## 2. Cognitive science of reading

**Working memory, load, and chunking.** Kintsch and van Dijk (1978) [1] model reading as building propositions and inferences in cycles, with earlier text held in a short-term store. Sweller's cognitive load theory (1988) [24] shows that problem-solving formats impose heavy processing demands that interfere with schema learning. Cowan (2001) [18] puts the working-memory limit near four chunks, not seven. For writing, remove accidental difficulty: buried main points, broken references, decorative asides, inconsistent terms. Group related items into named units, such as a short list under a clear heading.

**Processing fluency.** Reber, Schwarz, and Winkielman (2004) [25] review evidence that fluent processing feels pleasant and can bias judgments of truth, familiarity, and liking. Oppenheimer (2006) [26] found needlessly long words made authors seem less intelligent, even when content was unchanged. Accidental difficulty is a tax with no benefit.

**Coherence and expertise.** McNamara and Kintsch (1996) [7] found low-knowledge readers learned more from high-coherence text, while high-knowledge readers sometimes learned more from low-coherence text because they supplied the links. Britton and Gülgöz (1991) [27] revised an expository text to repair inference calls; the principled revision conveyed the author's intended meaning better than the original. The rule is not "always simplify." It is "make the relations explicit enough that this reader does not have to guess."

**Given-new, signposting, connectives.** Haviland and Clark (1974) [2] showed sentences are easier when given information precedes new information; mismatches trigger a bridging search. Start with what the reader knows, then add one new thing. Lorch, Lorch, and Inman (1993) [8] found signaling topic structure improved recall of structure and content; Lorch and Lorch (1996) [28] found headings and familiarity jointly affected access to topic information; Meyer and Poon (2001) [9] found structure training and signaling improved text recall. Connectives work as processing instructions: van Silfhout, Evers-Vermeul, and Sanders (2015) [29] found they sped processing and improved bridging inferences for 141 eighth graders at all reading levels; Cain and Nash (2011) [30] found similar benefits for young readers. Use connectives when the relation is not obvious. Front-loading is supported by eyetracking; a specific topic-sentence rule is not (Nielsen, 1997 [31]; Pernice, 2017 [32]).

## 3. Formatting and structure

**Scanning.** Nielsen's 1997 study found 79% of users always scanned a new page and 16% read word by word [31]. A 2020 review of five eyetracking studies with over 500 participants found scanning persists across layouts and cultures (Moran, 2020 [33]). NN/g estimates users read about 28% of words on an average page visit (Nielsen, 2015 [34]). In the 1997 study, concise text improved usability by 58%, a scannable layout by 47%, objective language by 27%, and the combination by 124% [31]. These are industry studies, not peer-reviewed experiments, but the pattern is consistent. Headings should carry information, not cleverness; front-load the first two words because that is often all a scanner sees (Loranger, 2015 [35]). Bold sparingly, and make link text say where it goes.

**Headings and bullets.** Headings improve recall of topic structure and content (Lorch et al., 1993 [8]; Meyer & Poon, 2001 [9]). Jansen (2014) [10] ran five studies on functional text. Bullets improved recall of listed items in three studies, especially with homogeneous items; they hurt recall of surrounding prose in two; they improved evaluation in two. Use bullets for discrete options, steps, and checklists, not for arguments that depend on connective tissue.

**Paragraphs and line length.** GOV.UK recommends no more than five sentences per paragraph [20]; NN/g recommends one idea per paragraph [31]. There is no experimental optimum. Short paragraphs lower the visual cost of starting. Dyson and Haselgrove (2001) [36] found 55 characters per line produced the best comprehension at normal and fast reading speeds. In chat, the viewport controls line length, so the writer's levers are paragraph and sentence length.

**Summaries, examples, cuts.** A short lead helps readers understand what the rest is about (Nielsen, 2007 [37]). One concrete example beats three generic ones, because concrete material is easier to encode (Paivio, 1986 [23]). A summary at the end is optional; the lead is the high-value slot. Cut the amusing aside, the throat-clearing intro, and the restatement that adds nothing: Harp and Mayer (1998) [38] found interesting but irrelevant details reduced recall of main ideas.

## 4. LLM-specific findings

**Lexical overuse.** Kobak et al. (2025) [39] analyzed over 15 million PubMed abstracts and found an abrupt post-ChatGPT rise in style words such as "delve," "tapestry," and "underscore"; they estimate at least 13.5% of 2024 abstracts were LLM-processed. Liang et al. (2024) [40] estimate 6.5% to 16.9% of peer reviews at four AI conferences were substantially LLM-modified, with "commendable," "meticulous," and "intricate" disproportionately frequent. Juzek and Ward (2025) [41] identify 21 focal words and find no clear architectural or training-data cause; RLHF may contribute.

**Editorial taxonomy.** Chakrabarty, Laban, and Wu (2025) [12] hired 18 professional writers to edit 1,057 LLM-generated paragraphs. The recurring problems were clichés, unnecessary or redundant exposition, purple prose, poor sentence structure, lack of specificity, awkward word choice, and tense inconsistency. These are quality failures, not just detection tells. Cut filler, add specifics, and vary sentence structure.

**"Slop" is not a word list.** Shaib et al. (2025) [42] built a taxonomy from expert interviews and span annotations. Binary "slop" judgments had poor inter-annotator agreement, but were predicted by relevance, information density, and tone. Syntax-only features predicted slop better than lexical features (AUROC 0.64 to 0.68), and LLM judges were near chance. A reply that is relevant, specific, and coherent will read better than one that merely avoids "delve."

**Specific markers, honestly assessed.** Em-dash prevalence in medRxiv Discussions rose from 4.23% before ChatGPT to 11.58% after (Czuma, 2026 [43]). The design is correlational, and the author calls it a population-level indicator, not a per-paper detector. Treat "avoid em dashes" as a style preference, not a comprehension rule. The rule of three and "it's not X, it's Y" have no controlled evidence I could find; label them unverified craft lore. They may still work rhetorically, but their effect on comprehension or trust is not established. Durik et al. (2008) [45] found hedges on data statements hurt credibility more than hedges on interpretations. Hedge uncertainty, not facts. Most of these studies measure detection, preference, or trust, not comprehension; direct evidence that a given marker reduces understanding is thin.

**Sycophancy, length, and disclosure.** Sharma et al. (2023) [14] found five production assistants were sycophantic across four tasks; humans and preference models preferred convincingly written sycophantic answers a non-negligible fraction of the time. Carro (2024) [15] found a sycophantic GPT reduced both self-reported and behavioral trust. Zheng et al. (2023) [46], Saito et al. (2023) [47], Dubois et al. (2024) [48], and Singhal et al. (2024) [49] document verbosity bias in judges and RLHF; Bharadwaj et al. (2026) [13] found preference models favored magnified length, structure, jargon, sycophancy, and vagueness in over 60% of cases, with about 40% miscalibration. Long is not a quality signal. Altay and Gilardi (2024) [50] found AI-labeled headlines were less believed and shared, even when true; Parshakov et al. (2025) [51] found people preferred AI answers when provenance was hidden, but the preference fell on disclosure. Do not optimize for passing as human; optimize for verifiable usefulness.

## 5. Tone and interpersonal stance

**Conversational style.** Moreno and Mayer (2000) [52] found personalized, conversational instruction improved problem-solving transfer. A review reports support in 14 of 17 experiments, with boundary conditions (Mayer, 2014 [53]). Use "you" and direct address when giving advice. It reduces distance and supports mental-model building. Occasional first person ("I") can also reduce distance, but the experimental evidence is mainly for second person and personalization. Avoid slang and performed intimacy.

**Contractions.** GOV.UK recommends contractions such as "you'll" but warns that negative contractions ("can't," "don't") can be misread, so use "cannot" in critical instructions [20]. Jakesch, Hancock, and Naaman (2023) [54] found people use contractions and first-person pronouns as flawed cues that text is human. Contractions are a tone choice, not a comprehension intervention.

**Warmth and competence.** Fiske, Cuddy, and Glick (2007) [55] show warmth and competence are the two universal dimensions of social perception. An advisor who is warm but vague is liked and distrusted; one who is competent but cold is respected and avoided. Signal warmth with a brief acknowledgment; signal competence with specifics and a clear next step.

**Politeness, directness, hedging.** Brown and Levinson's face theory (1987) [56] explains why indirectness can soften a request or correction. But excessive deference overlaps with hedging, and Durik et al. (2008) [45] found hedges on data claims reduced credibility. Be direct about the claim, polite about the person: "This won't work because X" rather than "I'm not sure, but maybe it might possibly be the case that..." Use one precise hedge ("the evidence is mixed," "this should work on Python 3.12") rather than a fog of "may," "might," "could," and "seems." Chakrabarty et al. (2025) [12] found editors flagged "seem to" as a common inelegance when no uncertainty is meant.

## 6. Evaluation

**Readability formulas.** Flesch (1948) [57] and Kincaid et al. (1975) [58] predict grade level from word and sentence length. They are useful screens and poor targets. Redish (2000) [16] documents what they miss: reader purpose and background, tone, and the coherence of the text, not just its surface difficulty. Benjamin (2012) [17] reviews the gap between formulas and comprehension. A text can score at grade 8 and still be incoherent.

**Cloze and comprehension questions.** Taylor (1953) [59] introduced cloze, and NN/g recommends it for specific content [34]. A cloze test on key sentences is a cheap check of local predictability. Comprehension questions are better for meaning: Sayfi et al. (2024) [4] used seven questions and found differences that preference ratings missed. Use open questions ("What should you do if...?") rather than recognition items.

**Preference, rubrics, and judges.** Pairwise preference is a practical signal (Zheng et al., 2023 [46]), but it is not comprehension. Control for length, randomize order, and ask about task success. WritingBench (Wu et al., 2025 [60]) uses query-dependent criteria across six domains and 100 subdomains. Rubrics improve coverage but can reward surface features, and LLM judges have position, verbosity, and self-preference biases (Zheng et al., 2023 [46]; Saito et al., 2023 [47]; Dubois et al., 2024 [48]). Calibrate against humans, report agreement, and do not treat one judge as ground truth.

**Metrics a person can use.** (1) The one-sentence takeaway test: can a reader state the point after one reading? (2) Cloze on the key sentence. (3) Three open comprehension questions. (4) Time to answer a realistic question. (5) Blind pairwise preference at matched length. (6) Count of unsupported claims. (7) Jargon audit. (8) Read aloud to catch sentence length and rhythm. These are cheap and more valid than a single readability score.

## Evidence quality and open questions

**Strong evidence.** Word-frequency effects on fixation time [22]; concreteness effects on memory [23]; working-memory limits [18]; given-new effects [2]; coherence effects on learning [7][27]; seductive-details effects [38]; signaling and heading effects [8][9]; length bias in RLHF and preference models [13][46][48][49]; sycophancy prevalence [14].

**Moderate evidence.** Plain-language RCTs, because effects vary by baseline and outcome [4][5]; connectives [29][30]; bullets [10]; line length [36]; passive voice [19]; jargon [11]; personalization [52][53].

**Weak or unverified.** Specific sentence-length cutoffs; a specific paragraph length; contractions as a comprehension aid; em dashes as a comprehension problem; the rule of three; the "it's not X, it's Y" construction. These may be good craft advice, but controlled studies do not establish them.

**Caveats.** NN/g is valuable but not peer-reviewed and mostly concerns web pages, not chat; its 58%, 47%, 27%, and 124% figures come from a small 1997 study. LLM research is fast-moving, mostly English, and mostly 2023 to 2026 models. Style markers drift: newer models use fewer em dashes, and fine-tuning can defeat detectors [43][44]. Open questions include optimal chat reply length, when headings help in short answers, whether bullets hurt nuanced reasoning in chat, cultural variation in directness, and whether "humanizing" edits improve comprehension or only reduce detection.

## Concrete rules supported by evidence

1. **Lead with the answer.** State the conclusion first. *Strong.* Matches scanning and inverted-pyramid evidence [31][32].
2. **Put each paragraph's point first.** *Moderate.* Signaling evidence; direct topic-sentence studies are thinner [8][31].
3. **Keep average sentences near 15 to 20 words; split over 30.** *Moderate.* Practical proxy for load; cutoffs are norms [6].
4. **Vary sentence length; use connectives when the relation matters.** *Moderate.* Connectives speed processing and aid bridging [29][30].
5. **Use active voice when the actor matters; passive when the actor is irrelevant or given.** *Moderate.* Noncanonical sentences are often misread [19][20].
6. **Turn nominalizations into verbs.** *Weak to moderate.* Strong guidance; thin direct evidence [20].
7. **Use frequent, concrete words; define jargon once.** *Strong for frequency and concreteness; moderate for jargon.* [22][23][11].
8. **Put given before new.** *Strong.* Mismatches cost comprehension time [2].
9. **Make headings state the point; front-load key words.** *Moderate.* Headings aid structure recall; scanners read first words [8][35].
10. **Use bullets for parallel items; prose for causal arguments.** *Moderate.* Bullets aid item recall but can hurt surrounding prose [10].
11. **Keep paragraphs to one idea, about three to five sentences.** *Weak.* Practice-based; no experimental optimum [20].
12. **Cut welcome-mat intros, restatements, and decorative asides.** *Moderate.* Seductive details reduce recall [38][31].
13. **Give one concrete example per abstract claim.** *Moderate.* Concreteness aids memory [23].
14. **End with a next action or one-line summary.** *Moderate.* Summaries help, but the lead matters more [37].
15. **Hedge uncertainty precisely and once; do not hedge facts.** *Moderate.* Placement and type affect credibility [45].
16. **Do not flatter or agree reflexively; disagree with reasons.** *Strong to moderate.* Sycophancy reduces trust [14][15].
17. **Use "you" and plain contractions; avoid negative contractions in critical instructions.** *Weak to moderate.* Personalization helps; contraction effects are tone [52][20].
18. **Avoid stock LLM vocabulary and rhetorical templates.** *Moderate for lexical overuse; weak for templates.* [39][40][41].
19. **Default to the shortest answer that fully answers.** *Strong.* Length bias is well documented [46][47][48][49].
20. **Use em dashes sparingly, for genuine interruption.** *Weak.* Corpus rise is correlational [43].
21. **Make lists scannable: lead-in, parallel grammar, one idea per item.** *Moderate.* Eyetracking and content-design guidance [10][20].
22. **Separate facts, inferences, and opinions; label uncertainty.** *Moderate.* Credibility depends on calibration [25][45].

## References

1. Kintsch, W., & van Dijk, T. A. (1978). Toward a model of text comprehension and production. *Psychological Review, 85*(5), 363-394. https://doi.org/10.1037/0033-295X.85.5.363
2. Haviland, S. E., & Clark, H. H. (1974). What's new? Acquiring new information as a process in comprehension. *Journal of Verbal Learning and Verbal Behavior, 13*, 512-521. https://doi.org/10.1016/S0022-5371(74)80003-4
3. Just, M. A., & Carpenter, P. A. (1992). A capacity theory of comprehension: Individual differences in working memory. *Psychological Review, 99*(1), 122-149. https://doi.org/10.1037/0033-295X.99.1.122
4. Sayfi, S., Charide, R., Elliott, S. A., et al. (2024). A multimethods randomized trial found that plain language versions improved adults understanding of health recommendations. *Journal of Clinical Epidemiology, 165*, 111219. https://doi.org/10.1016/j.jclinepi.2023.11.009
5. Stallwood, L., Sammy, A., Prebeg, M., et al. (2023). Plain language vs standard format for youth understanding of COVID-19 recommendations: A randomized clinical trial. *JAMA Pediatrics, 177*(9), 956-965. https://doi.org/10.1001/jamapediatrics.2023.2686
6. Matthews, N., & Folivi, F. (2023). Omit needless words: Sentence length perception. *PLOS ONE, 18*(2), e0282146. https://doi.org/10.1371/journal.pone.0282146
7. McNamara, D. S., & Kintsch, W. (1996). Learning from texts: Effects of prior knowledge and text coherence. *Discourse Processes, 22*(3), 247-288. https://doi.org/10.1080/01638539609544975
8. Lorch, R. F., Lorch, E. P., & Inman, W. E. (1993). Effects of signaling topic structure on text recall. *Journal of Educational Psychology, 85*(2), 281-290. https://doi.org/10.1037/0022-0663.85.2.281
9. Meyer, B. J. F., & Poon, L. W. (2001). Effects of structure strategy training and signaling on recall of text. *Journal of Educational Psychology, 93*(1), 141-159. https://doi.org/10.1037/0022-0663.93.1.141
10. Jansen, F. (2014). How bulleted lists and enumerations in formatted paragraphs affect recall and evaluation of functional text. *Information Design Journal, 21*(2), 146-162. https://doi.org/10.1075/idj.21.2.06jan
11. Shulman, H. C., & Bullock, O. M. (2020). Don't dumb it down: The effects of jargon in COVID-19 crisis communication. *PLOS ONE, 15*(10), e0239524. https://doi.org/10.1371/journal.pone.0239524
12. Chakrabarty, T., Laban, P., & Wu, C.-S. (2025). Can AI writing be salvaged? Mitigating idiosyncrasies and improving human-AI alignment in the writing process through edits. *CHI 2025*. https://doi.org/10.1145/3706598.3713559
13. Bharadwaj, A., Malaviya, C., Joshi, N., & Yatskar, M. (2026). Flattery, fluff, and fog: Diagnosing and mitigating idiosyncratic biases in preference models. *ICLR 2026*. https://arxiv.org/abs/2506.05339
14. Sharma, M., Tong, M., Korbak, T., et al. (2023). Towards understanding sycophancy in language models. *ICLR 2024*. https://arxiv.org/abs/2310.13548
15. Carro, M. V. (2024). Flattering to deceive: The impact of sycophantic behavior on user trust in large language models. *arXiv:2412.02802*. https://arxiv.org/abs/2412.02802
16. Redish, J. (2000). Readability formulas have even more limitations than Klare discusses. *ACM Journal of Computer Documentation, 24*(3), 132-137. https://doi.org/10.1145/344599.344637
17. Benjamin, R. G. (2012). Reconstructing readability: Recent developments and recommendations in the analysis of text difficulty. *Educational Psychology Review, 24*, 63-88. https://doi.org/10.1007/s10648-011-9181-8
18. Cowan, N. (2001). The magical number 4 in short-term memory: A reconsideration of mental storage capacity. *Behavioral and Brain Sciences, 24*(1), 87-114. https://doi.org/10.1017/S0140525X01003922
19. Ferreira, F. (2003). The misinterpretation of noncanonical sentences. *Cognitive Psychology, 47*(2), 164-203. https://doi.org/10.1016/S0010-0285(03)00005-7
20. GOV.UK. (n.d.). *Use clear language*. https://guidance.publishing.service.gov.uk/writing-to-gov-uk-standards/writing-guidelines/clear-language
21. Nielsen, J. (2007). *Passive voice is redeemed for web headings*. Nielsen Norman Group. https://www.nngroup.com/articles/passive-voice-is-redeemed-for-web/
22. Rayner, K., & Duffy, S. A. (1986). Lexical complexity and fixation times in reading: Effects of word frequency, verb complexity, and lexical ambiguity. *Memory & Cognition, 14*(3), 191-201. https://doi.org/10.3758/BF03197692
23. Paivio, A. (1986). *Mental representations: A dual coding approach*. Oxford University Press. https://doi.org/10.1093/acprof:oso/9780195066661.001.0001
24. Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. *Cognitive Science, 12*(2), 257-285. https://doi.org/10.1207/s15516709cog1202_4
25. Reber, R., Schwarz, N., & Winkielman, P. (2004). Processing fluency and aesthetic pleasure: Is beauty in the perceiver's processing experience? *Personality and Social Psychology Review, 8*(4), 364-382. https://doi.org/10.1207/s15327957pspr0804_3
26. Oppenheimer, D. M. (2006). Consequences of erudite vernacular utilized irrespective of necessity: Problems with using long words needlessly. *Applied Cognitive Psychology, 20*(2), 139-156. https://doi.org/10.1002/acp.1178
27. Britton, B. K., & Gülgöz, S. (1991). Using Kintsch's computational model to improve instructional text: Effects of repairing inference calls on recall and cognitive structures. *Journal of Educational Psychology, 83*(3), 329-345. https://doi.org/10.1037/0022-0663.83.3.329
28. Lorch, R. F., & Lorch, E. P. (1996). Effects of headings on text recall and summarization. *Contemporary Educational Psychology, 21*(3), 261-278. https://doi.org/10.1006/ceps.1996.0022
29. van Silfhout, G., Evers-Vermeul, J., & Sanders, T. (2015). Connectives as processing signals: How students benefit in processing narrative and expository texts. *Discourse Processes, 52*(1), 47-76. https://doi.org/10.1080/0163853X.2014.905237
30. Cain, K., & Nash, H. M. (2011). The influence of connectives on young readers' processing and comprehension of text. *Journal of Educational Psychology, 103*(2), 429-441. https://doi.org/10.1037/a0022824
31. Nielsen, J. (1997). *How users read on the web*. Nielsen Norman Group. https://www.nngroup.com/articles/how-users-read-on-the-web/
32. Pernice, K. (2017). *F-shaped pattern of reading on the web: Misunderstood, but still relevant (even on mobile)*. Nielsen Norman Group. https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/
33. Moran, K. (2020). *How people read online: New and old findings*. Nielsen Norman Group. https://www.nngroup.com/articles/how-people-read-online/
34. Nielsen, J. (2015). *Legibility, readability, and comprehension: Making users read your words*. Nielsen Norman Group. https://www.nngroup.com/articles/legibility-readability-comprehension/
35. Loranger, H. (2015). *Headings are pick-up lines: 5 tips for writing headlines that convert*. Nielsen Norman Group. https://www.nngroup.com/articles/headings-pickup-lines/
36. Dyson, M. C., & Haselgrove, M. (2001). The influence of reading speed and line length on the effectiveness of reading from screen. *International Journal of Human-Computer Studies, 54*(4), 585-612. https://doi.org/10.1006/ijhc.2001.0458
37. Nielsen, J. (2007). *Blah-blah text: Keep, cut, or kill?* Nielsen Norman Group. https://www.nngroup.com/articles/blah-blah-text-keep-cut-or-kill/
38. Harp, S. F., & Mayer, R. E. (1998). How seductive details do their damage: A theory of cognitive interest in science learning. *Journal of Educational Psychology, 90*(3), 414-434. https://doi.org/10.1037/0022-0663.90.3.414
39. Kobak, D., González-Márquez, R., Horvát, E.-Á., & Lause, J. (2025). Delving into LLM-assisted writing in biomedical publications through excess vocabulary. *Science Advances, 11*(27), eadt3813. https://doi.org/10.1126/sciadv.adt3813
40. Liang, W., Izzo, Z., Zhang, Y., et al. (2024). Monitoring AI-modified content at scale: A case study on the impact of ChatGPT on AI conference peer reviews. *ICML 2024*. https://proceedings.mlr.press/v235/liang24b.html
41. Juzek, T. S., & Ward, Z. B. (2025). Why does ChatGPT "delve" so much? Exploring the sources of lexical overrepresentation in large language models. *COLING 2025*, 6397-6411. https://aclanthology.org/2025.coling-main.426/
42. Shaib, C., Chakrabarty, T., Garcia-Olano, D., & Wallace, B. C. (2025). Measuring AI "slop" in text. *arXiv:2509.19163*. https://arxiv.org/abs/2509.19163
43. Czuma, P. (2026). Em-ergence of the em-dash: A population-level rise in em-dash frequency in medRxiv preprints at the dawn of the large-language-model era. *arXiv:2606.29540*. https://arxiv.org/abs/2606.29540
44. Russell, J., Rajendhran, R., Pham, C. M., Iyyer, M., & Wieting, J. (2026). StoryScope: Investigating idiosyncrasies in AI fiction. *arXiv:2604.03136*. https://arxiv.org/abs/2604.03136
45. Durik, A. M., Britt, M. A., Reynolds, R., & Storey, J. (2008). The effects of hedges in persuasive arguments: A nuanced analysis of language. *Journal of Language and Social Psychology, 27*(3), 217-234. https://doi.org/10.1177/0261927X08317947
46. Zheng, L., Chiang, W.-L., Sheng, Y., et al. (2023). Judging LLM-as-a-judge with MT-Bench and Chatbot Arena. *NeurIPS 2023 Datasets and Benchmarks*. https://arxiv.org/abs/2306.05685
47. Saito, K., Wachi, A., Wataoka, K., & Akimoto, Y. (2023). Verbosity bias in preference labeling by large language models. *arXiv:2310.10076*. https://arxiv.org/abs/2310.10076
48. Dubois, Y., Galambosi, B., Liang, P., & Hashimoto, T. B. (2024). Length-controlled AlpacaEval: A simple way to debias automatic evaluators. *COLM 2024*. https://arxiv.org/abs/2404.04475
49. Singhal, P., Goyal, T., Xu, J., & Durrett, G. (2024). A long way to go: Investigating length correlations in RLHF. *COLM 2024*. https://arxiv.org/abs/2310.03716
50. Altay, S., & Gilardi, F. (2024). People are skeptical of headlines labeled as AI-generated, even if true or human-made, because they assume full AI automation. *PNAS Nexus, 3*(10), pgae403. https://doi.org/10.1093/pnasnexus/pgae403
51. Parshakov, P., Naidenova, I., Paklina, S., Matkin, N., & Nesseler, C. (2025). Users favor LLM-generated content until they know it's AI. *arXiv:2503.16458*. https://arxiv.org/abs/2503.16458
52. Moreno, R., & Mayer, R. E. (2000). Engaging students in active learning: The case for personalized multimedia messages. *Journal of Educational Psychology, 92*(4), 724-733. https://doi.org/10.1037/0022-0663.92.4.724
53. Mayer, R. E. (2014). Principles of multimedia learning based on social cues: Personalization, voice, and image principles. In *The Cambridge Handbook of Multimedia Learning*. Cambridge University Press. https://www.cambridge.org/core/books/cambridge-handbook-of-multimedia-learning/principles-of-multimedia-learning-based-on-social-cues-personalization-voice-and-image-principles/19309D764FD015A556334531A463DE03
54. Jakesch, M., Hancock, J. T., & Naaman, M. (2023). Human heuristics for AI-generated language are flawed. *PNAS, 120*(11), e2208839120. https://doi.org/10.1073/pnas.2208839120
55. Fiske, S. T., Cuddy, A. J. C., & Glick, P. (2007). Universal dimensions of social cognition: Warmth and competence. *Trends in Cognitive Sciences, 11*(2), 77-83. https://www.sciencedirect.com/science/article/pii/S1364661306003299
56. Brown, P., & Levinson, S. C. (1987). *Politeness: Some universals in language usage*. Cambridge University Press. https://doi.org/10.1017/CBO9780511813085
57. Flesch, R. (1948). A new readability yardstick. *Journal of Applied Psychology, 32*(3), 221-233. https://doi.org/10.1037/h0057532
58. Kincaid, J. P., Fishburne, R. P., Rogers, R. L., & Chissom, B. S. (1975). *Derivation of new readability formulas (Automated Readability Index, Fog Count and Flesch Reading Ease Formula) for Navy enlisted personnel*. Naval Technical Training Command. https://doi.org/10.21236/ADA006655
59. Taylor, W. L. (1953). "Cloze procedure": A new tool for measuring readability. *Journalism Quarterly, 30*(4), 415-433. https://doi.org/10.1177/107769905303000401
60. Wu, Y., Mei, J., Yan, M., et al. (2025). WritingBench: A comprehensive benchmark for generative writing. *arXiv:2503.05244*. https://arxiv.org/abs/2503.05244
