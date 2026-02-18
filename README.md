<img src="docs/screenshots/hero.png" width="100%" alt="Voicecraft" />

<div align="center">

# Voicecraft

**NPC voice builder for tabletop performers**

</div>

---

I gave an NPC a Scottish accent in session one. By session three, he was inexplicably French. Nobody corrected me. That's the problem — keeping NPC voices consistent across a campaign is nearly impossible when you're running a dozen characters off memory alone. Voicecraft lets you build a voice profile for every NPC, then gives you coaching prompts so you can actually reproduce it at the table.

For GMs, actual play performers, streamers, and anyone who voices characters and needs them to stay consistent. Works for any system — voices don't have edition numbers.

---

## What You Get

- **Voice profile mixer** — Adjust pitch, tempo, volume, and voice quality per NPC. Combine them into something distinct and repeatable
- **12 dialect options** — Cockney to Elvish, each with pronunciation guides and sample phrases. Not just a label — actual coaching on how to do it
- **8 speech patterns** — Formal, casual, archaic, clipped, flowery, mumbling, booming, whispering. Layer these on top of the dialect for more dimension
- **Coaching prompts** — Auto-generated performance tips based on the voice config. "Speak slower, drop your pitch on emphasized words, clip your consonants." Actual direction you can follow
- **Sample lines** — Editable dialogue showing how each NPC would sound in character. Practice material
- **Voice packs** — Pre-built template collections for quick assignment. 8 templates across 2 packs when you need an NPC voice in thirty seconds
- **Side-by-side comparison** — View multiple voice profiles next to each other so your NPCs don't all sound the same

---

## Screenshots

<img src="docs/screenshots/feature-1.png" width="100%" alt="Voice profile dashboard with NPC cards" />

*Voice profiles — every NPC with their voice parameters at a glance*

<img src="docs/screenshots/feature-2.png" width="100%" alt="Campaign NPC roster with voice summaries" />

*NPC roster with voice summaries and coaching hints*

<img src="docs/screenshots/mobile.png" width="50%" alt="Voicecraft on mobile" />

*Mobile — pull up an NPC's voice profile mid-session*

---

<details>
<summary>Under the Hood</summary>

<br>

**Stack:** Next.js 16, TypeScript, React 19, Tailwind CSS, Prisma 6, SQLite

- Voice profile mixer combines 5+ independent parameters into unique coaching prompts
- Campaign, NPC, VoiceProfile, SampleLine, VoicePack, and Template models in Prisma
- 12 API routes covering campaigns, NPCs, voice profiles, sample lines, voice packs, and templates
- Component architecture separates mixer controls, coaching display, and sample line editing

</details>

---

## Part of the Toolkit

Voicecraft is one of seven tools I built for people who run imaginary worlds. See the full set on [my profile](https://github.com/CandyFlex).

*Every NPC deserves a voice you can actually remember next week.*
