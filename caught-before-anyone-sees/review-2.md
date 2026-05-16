**Thesis (lean):** What AI replaced wasn't the lesson — it was the shared language a team builds by failing together in public.

**Proposed shape:**
1. The Friday post-mortem: nine engineers in a room, learning not the fix but the *names* for the fix.
2. AI lets each of us learn the fix privately — and walk away with a different vocabulary for the same problem.
3. Correct, but disparate: a team of solo experts can't debug a 2am outage together because they don't share the shorthand.
4. What's lost isn't the knowledge. It's the company we kept while gaining it.

---

**Diagnosis:**

1. **Title contradicts thesis** — "Caught Before Anyone Sees" frames private failure as the goal, but the entire piece argues the opposite: being caught *publicly* was the load-bearing event. The title pre-empts the argument and reads as the AI-fluency cliché the piece is pushing against. Rename around the shared-language move (e.g. something pointing at vocabulary, debrief, or the room of nine).

2. **Repeated claim** — the central insight is restated four times in different costumes: "teaching them how to *talk* about the fix" / "tribunal wisdom passed through a communal ritual" / "Wisdom is communication-shaped" / "the language we built around the lesson" / "no two teammates carry the same reference back." Pick the strongest phrasing (the "*talk* about the fix" line is doing the most work) and cut the rest. The "Knowledge without a shared language" section is mostly this loop.

3. **Sentimentality stack at the close** — the ending piles three borrowed gestures at profundity on top of each other: the Bernard of Chartres section header, the destination-vs-journey cliché framed as a rhetorical question, and the one-word reveal ("It's the company"). Each one alone could land; stacked, they read as reaching for depth the piece already earned earlier. Pick one. The "company" beat is the strongest — let it stand alone without the cliché setup.

---

**Working:** "I wasn't just teaching them the fix. I was teaching them how to *talk* about the fix" — that's the spine of the piece. Everything before it is warmup; everything after it is variation. Lead with it, or with the room of nine engineers that produced it.

---

**Watchlist notes:**
- *AI-tells / em-dash:* the em-dash + restatement pattern ("X — actually Y") fires in nearly every paragraph and starts to read as machine-cadence. Convert two or three to periods. The tricolon "anyone can build anything, anyone can learn anything, anyone can *be* anything" is the most AI-flavoured line in the draft.
- *Voice consistency:* "circa 2019 BE (Before Claude)" is the voice working — keep. "a tribunal wisdom passed through a communal ritual" slips into essayistic register that the rest of the piece doesn't sustain (also: probably "tribal," not "tribunal").
- *Originality:* "AI makes us individually smarter but collectively dumber" is not original. The *mechanism* you're naming — that shared post-mortem language is the substrate AI dissolves — is. The piece is original *only if* that mechanism is the spine; right now it's a buried middle paragraph competing with the broader take. Make it the whole piece.

---

**Iteration notes (post-pushback):**

*On the title.* Sheng pushed back: "Caught Before Anyone Sees" is ironic — diagnosing the present (AI catches it before the room does), not framing private failure as the goal. Conceded. The title works *if* the opening earns the ironic read inside the first three sentences (the room of nine vs. the solo prompt). Currently the opening — "AI hustle culture says we can be anything" — lets the title float as aspirational. Fix the cue, keep the title.

*Cleanup plan for the repeated claim:*

- **Keep:** "I wasn't just teaching them the fix. I was teaching them how to *talk* about the fix. The names we gave the bug. The story we told about it. The shorthand that would, a year later, let any one of us debug a 2am outage by speaking a sentence and a half to each other." This is the spine. Don't touch.
- **Cut:** "In a way, it was a tribunal wisdom passed through a communal ritual." — same claim in essayist register; slips voice. The fire/wisdom epigraph after it is doing the same work — pick one or drop both.
- **Cut or merge:** "Knowledge without a shared language" opens with "Wisdom is communication-shaped. Knowledge alone is not." — that's the spine in abstract clothing. The section only earns its keep from "no two teammates carry the same reference back. Different prompts, different agents, different patched understandings of the same problem." Lead the section with that line; cut the abstract opener and the "So what?" framing.

*Test after collapsing:* the spine line appears once. Every following paragraph adds something it can't say — the *consequence* (fragmented vocabulary, debugging at 2am, correct-but-disparate). If a paragraph rephrases the spine, cut it.
