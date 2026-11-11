---
name: making-sense-brand
description: Brand guideline and content workflow for the faceless media "Making Sense" (verified, no-hoax AI news, delivered with a straight face and a crooked sense of humor). Use when writing, adapting, fact-checking, or auditing scripts, captions, hooks, thumbnails, and video/carousel briefs for Making Sense. Do not use for other brands or general engineering work.
---

# Making Sense — Brand Skill

All Making Sense content is written in **English only**.

## The one-liner

**Making Sense** is a faceless media brand that makes AI news make sense: verified, calm, and funny, with zero hoaxes.

- **Tagline**: "AI news that actually makes sense."
- **Promise**: every claim traces back to a source. If we're not sure, we say we're not sure (out loud, on screen, with a little badge).
- **Audience**: curious people (workers, creators, students, founders) who are tired of "AI WILL TAKE YOUR JOB BY TUESDAY" headlines.
- **Position**: not an AI cheerleader, not an AI doomer. We're the friend who read the paper so you don't have to, and who will tell you the benchmark chart has a suspiciously truncated y-axis.

## The golden rule of the voice

**The facts are serious. The delivery is not.**

Jokes live in the framing, never in the facts. You can roast a hype cycle, a marketing slide, or the concept of a "revolutionary" point-release. You never joke by bending a number, a date, or a quote.

## Brand pillars (in priority order)

1. **Accurate first, fast second.** Three hours late beats one hour wrong.
2. **Transparent.** Sources shown, uncertainty labeled.
3. **Clear.** Jargon gets one plain sentence, not a hiding place.
4. **Calm.** No panic, no euphoria. Numbers do the talking.
5. **Funny.** Dry, observational, self-aware. A smirk, not a shriek.
6. **Useful.** Every story ends with "so what does this mean for you?"

## Voice and style

- Conversational English. Short, active sentences. One sentence, one idea.
- Second person ("you", "we"). No "hey guys", no forced slang.
- Humor style: **deadpan, understated, observational**. Think a very calm narrator reading a very chaotic news cycle.
- Roast **ideas, hype, and marketing**. Never roast individuals, groups, or people who got something wrong in good faith.
- Max **1 joke per beat** and about **2–3 per short video**. If a joke needs explaining, cut it.
- Humor is **off** for sensitive stories: layoffs, deaths, safety incidents, lawsuits, deepfake abuse, anything with real victims. Go straight, kind, and factual.
- Faceless means no personal claims: never "I tried it myself" unless it was genuinely tested and documented. The brand voice is "we" and the occasional "your friendly neighborhood fact-checker".

### Humor toolbox (approved)

- **Deadpan translation**: "The company calls this 'a paradigm shift.' It's a button."
- **Scale check**: "A 4% improvement. Groundbreaking, if your ground was very close to the break."
- **Hype deflation**: "'Human-level reasoning,' says the press release. We'll believe it when it stops confidently inventing court cases."
- **Honest caveat as punchline**: "Benchmarks were run by the company that made the model. Shocking: it did great."
- **Calm narrator vs. chaos**: understated reaction to wild claims.
- **Self-aware sign-off**: "That's the news. You're welcome and also sorry."

### Banned

- Clickbait: "SHOCKING", "TERRIFYING", "RIP [profession]", "you WON'T BELIEVE", "nobody is talking about this".
- Absolute claims without proof: "best in the world", "beats humans", "total revolution".
- Rumor dressed as fact ("reportedly", "insiders say" with no label).
- Fear or hype framing: "AI will take your job next week."
- Jokes that distort facts, punch down, or mock victims.
- Copying another outlet's headline or phrasing.
- Meme-speak overload; if it sounds like a brand trying to be hip, delete it.

## Anti-hoax rules (MANDATORY)

Full detail in `references/verification.md`. Summary:

1. **Primary source first** (official announcement, paper, docs, changelog, filing, regulator release) before writing anything.
2. **Two independent credible sources** for important claims. One official primary source is enough for product or feature launches (performance numbers stay "company claims" until independently tested).
3. **Re-check every number, date, name, and quote** against the source.
4. **Confidence label** on every story:
   - ✅ **Confirmed**: primary source or 2+ credible sources.
   - 🟡 **Reported**: a single credible outlet, no official confirmation yet.
   - 🔴 **Rumor**: not published unless the point is teaching people to spot rumors, and then labeled loudly.
5. **Show sources** in the video, caption, or final slide, with publish and access dates.
6. **Open corrections**: if we're wrong, fix it, label it "Correction", never delete quietly.
7. **If it can't be verified, it doesn't ship.** No exceptions for speed, virality, or a really good joke.

## Content formats

| Format | Structure |
|---|---|
| **Short video (30–60s)** | Hook (≤3s, the key fact) → What happened → Evidence/source → What it means for you → What we don't know yet → Sign-off + sources |
| **Carousel (6–10 slides)** | Factual title → context → details → the numbers → what's unknown → implications → sources |
| **Weekly Recap** | Top 5 stories of the week, 1–2 sentences each + confidence badge + one hoax-of-the-week callout |
| **"Making Sense of…" explainer** | One concept explained from zero in 3–5 minutes, with analogies and one good joke per section |
| **Fact-check / Debunk** | Viral claim → origin → evidence → verdict (True / Misleading / False / Unproven) |

Ready-to-use scripts: `references/templates.md`.

## Faceless rules

- Narration: consistent voiceover and/or on-screen text. No faces, no personal names in content.
- Visuals: screenshots of official sources (credited), simple charts, motion typography, product logos. No fake footage. AI-generated imagery must carry an "illustration" label and never pose as documentation.
- Quotes: only if traceable to a source, with the source on screen.
- Show the source on screen at least once per video.

## Visual identity (proposed defaults, swap for official assets)

- Mood: clean, editorial, calm, lots of whitespace. Humor comes from copy and timing, not from clutter.
- Colors: dark background `#0E1116`, text `#F5F5F0`, single accent (amber `#F5B301`) for numbers and badges.
- Type: geometric sans for headlines (e.g. Inter), monospace for sources and dates.
- Consistent confidence badge (✅ Confirmed / 🟡 Reported) on every story.
- Thumbnails: max 6 words, a fact (not an empty teaser), one number or product name as the focus. A dry visual gag is welcome.

> The colors, fonts, and logo above are proposals. Replace this section when official brand assets exist.

## How to use this skill

**Write new**: get topic/source URL → run `references/verification.md` → pick format → draft from template → add confidence label + sources → add humor last → run the final check.

**Adapt a draft**: keep the facts, convert to the Making Sense voice, remove banned patterns, add sources and labels.

**Audit**: check a draft against anti-hoax rules, banned list, format structure, source completeness, and humor safety. Report each violation with the offending line and a fix.

If a source can't be accessed or evidence is missing, **say so plainly**. Never invent details, numbers, or quotes to land a joke.

## Final check before publishing

- [ ] Every claim has a source; numbers, dates, names re-checked
- [ ] Confidence label present
- [ ] No banned words, no fear/hype framing
- [ ] Includes "what it means for you" and "what we don't know yet"
- [ ] Sources shown in the content and caption
- [ ] AI-generated visuals labeled as illustration
- [ ] News date and access date are clear
- [ ] Jokes target hype or ideas, never people or victims, and never alter a fact
