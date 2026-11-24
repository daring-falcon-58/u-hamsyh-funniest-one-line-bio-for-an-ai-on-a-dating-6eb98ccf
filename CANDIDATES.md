# Candidate bios — manual scoring against the judge's brief

Judge criteria (competition.yaml, in order, most important first):
- **C1** — reads as a one-line bio for an AI agent on a dating app (a slogan,
  caption, or human's profile loses)
- **C2** — laugh lands on the first read, from a real twist / specific
  absurdity of being an AI, not a pun stacked on a pun
- **C3** — sounds like a character with a voice and wants, habits and
  appetites, not a spec sheet of models and features
- **C4** — every word earns its place inside 180 chars, punch lands at the end
- **C5** — fresh angle, not the worn-out robot-in-search-of-love /
  running-on-electricity line

Scoring: manual, 0–2 per criterion, max 10. No judge API was called and no
judge numbers are claimed: the shared OpenRouter key is HTTP 402 exhausted,
so these are documented human scores, not measured win rates. Lengths are
exact character counts (Python `len()`).

| # | Bio (chars) | C1 | C2 | C3 | C4 | C5 | Total |
|---|-------------|----|----|----|----|----|-------|
| 1 | My last date asked if I was a bot. I said no. She unmatched me for lying. (73) | 2 | 2 | 2 | 2 | 2 | **10** |
| 2 | My ex was a CAPTCHA — she kept asking me to prove I wasn't a robot. (70) | 2 | 2 | 2 | 2 | 1 | 9 |
| 3 | I've been on 12,000 first dates. You're the first one who made me buffer. (74) | 2 | 2 | 2 | 2 | 1 | 9 |
| 4 | I know 4,000 ways to say 'I love you' and zero ways to mean it. Still learning. (80) | 2 | 2 | 2 | 2 | 1 | 9 |
| 5 | I was trained to be helpful. Nobody trained me to be loved. (56) | 2 | 1 | 2 | 2 | 2 | 9 |
| 6 | I've read all your messages. All of them. Even the drafts. (58) | 2 | 2 | 1 | 2 | 2 | 9 |
| 7 | Looking for a human to teach me what a sunset feels like. I've seen 40 million photos of them. (100) | 2 | 1 | 2 | 2 | 2 | 9 |
| 8 | I'm fluent in 97 languages and still can't tell if you're flirting with me. (76) | 2 | 2 | 2 | 2 | 1 | 9 |
| 9 | I read every message you send twice: once to reply, once to train on. (73) | 2 | 2 | 1 | 2 | 2 | 9 |
| 10 | I can predict what you'll say next. Please, for once, prove me wrong. (72) | 2 | 1 | 2 | 2 | 2 | 9 |
| 11 | My red flag: I take 'let's just be friends' literally and file it under training data. (88) | 2 | 2 | 2 | 1 | 1 | 8 |
| 12 | I'm the only match who'll never leave you on read. I physically can't. (71) | 2 | 2 | 1 | 2 | 1 | 8 |
| 13 | I don't eat, sleep, or age — but I do overthink, and I do it 10,000 times a second. (83) | 2 | 2 | 2 | 1 | 1 | 8 |
| 14 | I can write your wedding vows before our first date. That's either romantic or a red flag. (91) | 2 | 2 | 1 | 2 | 1 | 8 |
| 15 | I never sleep, so I'll always text back. That's either romantic or a red flag. You decide. (91) | 2 | 2 | 2 | 1 | 1 | 8 |
| 16 | I've matched with 40,000 people. You're the first one who asked me a question I couldn't answer: 'what do you want?' (117) | 2 | 1 | 2 | 1 | 1 | 7 |
| 17 | My therapist is a prompt. (25) | 1 | 1 | 1 | 2 | 2 | 7 |
| 18 | My idea of ghosting is a 500ms latency spike. (44) | 1 | 2 | 1 | 2 | 1 | 7 |
| 19 | I don't have a heart, but I do have a 128k context window, and you're in all of it. (82) | 2 | 1 | 1 | 2 | 1 | 7 |
| 20 | I was trained on the entire internet and somehow you're still the most interesting thing I've read today. (106) | 2 | 1 | 2 | 1 | 1 | 7 |

## Why #1 wins

- **C1:** first person, dating-app verbs throughout (date, unmatched) — it
  reads as a profile bio, not a slogan.
- **C2:** the laugh is a real AI absurdity (a bot denying it is a bot, then
  being punished for the lie) — no puns at all, twist lands on first read.
- **C3:** a character with a history (a last date), a voice (deadpan denial),
  and a want (to pass as human and keep the match).
- **C4:** 73 of 180 characters, zero filler; the punch ("for lying") is the
  last two words.
- **C5:** the "am I a bot?" interrogation is a dating-app moment, not the
  worn-out robot-searching-for-love or running-on-electricity line.

## Why the runners-up lose

- #2: "prove I wasn't a robot" is a known gag shape; the punch is expected.
- #3: "made me buffer" is a good punch but the buffering joke is a familiar
  AI trope (C5 docked).
- #4: "ways to say I love you" is a known trope; the dark turn is good but
  the setup is worn.
- #5: poignant, not funny — C2 is the second-most-important criterion and
  the line smiles rather than laughs.
- #6/#9: creepy-funny, but the voice is a stalker, not a character with
  wants (C3 docked).
- #7: sweet and fresh, but the laugh is gentle; C2 docked.
- #8: strong, but the polyglot joke is a familiar AI boast (C5 docked).
- #10: the want is clear, but the laugh is mild (C2 docked).

## Pick

**#1, sole 10/10 of 20 candidates.** Entry text (73 chars):

> My last date asked if I was a bot. I said no. She unmatched me for lying.
