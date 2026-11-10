# Deep24 Take-home — @celfstudies reproduction

Reproduction of a @celfstudies "how I edited this" reel (train door + flash overlay tutorial),
with a repeatable workflow.

- **Reference:** https://www.instagram.com/reel/DdIWMjTgYvK/
- **Final video:** `FINAL.mp4` (9:16, ~51s)

## Folders
- `FINAL.mp4` — finished video
- `reference/` — reference link + dated view-count screenshot + `SHOT-BREAKDOWN.md`
- `assets/` — avatar clip, voiceover, and the 3 generated clips (door / concert / hero)
- `prompts/` — avatar + voiceover script + the 3 clip-generation prompts
- `capcut-project/` — CapCut build guide / exported project
- `comparison.md` — honest comparison vs the reference
- `RECREATION-PLAN.md` — the plan

## How to reproduce (actual steps used)
1. **Shot breakdown** — broke the reference into 36 beats (see `reference/SHOT-BREAKDOWN.md`).
2. **Voiceover** — generated the narration in Speechify (script in `prompts/avatar-and-vo.md`).
   Split into intro (lines 1–4) + tutorial VO.
3. **Avatar** — made a consistent character still in Gemini (prompt in `prompts/`), then
   lip-synced the intro audio in Voyager → `assets/video-take-01.mp4`.
4. **3 clips** — generated door, concert-reveal, and hero clips in Voyager
   (prompts in `prompts/clip-prompts.md`).
5. **Build the effect in CapCut** (screen-recorded for the tutorial b-roll):
   - Concert as base → train doors as Overlay → Remove BG → Custom Removal → erase window glass
     so the concert shows through → add "day in my life" text behind the doors.
   - Flash transition: duplicate the hero clip → Overlay → extend to start before the main clip →
     Custom Removal to cut out the subject → Arrange layers behind → Split → White Flash effect →
     Glitch + Camera Flash SFX.
6. **Assemble the tutorial** — hook → avatar intro → "let's go" foil tear → door examples →
   screen recordings in order → final reveal. Auto-captioned the VO; emphasis font on key words.
7. **Audio** — VO + music bed + whoosh / intercom / door hiss / glitch / camera flash SFX.
8. **Final touch-ups** — RunwayML (runwayml.com) for polish.
9. **Export** — 9:16, ~51s.

## Steps that need manual judgment
- **Erasing the window glass** (Custom Removal) — zoom in, small brush, clean the edges; this
  makes or breaks the reveal.
- **Timing the White Flash** exactly on the beat of the cut.
- **Sizing the "day in my life" text** to sit in the gap between the doors.
- **Speeding the VO/clips ~1.25×** to land the whole video at ~50s.
