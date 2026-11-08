# Recreation Plan — reproducing the @celfstudies train-door tutorial

This reference is a **tutorial about an edit**, so you reproduce it in two builds:

- **Build A — the "finished" effect** (the train-door reveal + flash transition). You make
  this first, because the tutorial literally shows you making it.
- **Build B — the tutorial wrapper** (talking-head intro + screen recordings + captions +
  SFX). You screen-record yourself making Build A, then wrap it.

Everything is done in **CapCut** (the reference uses CapCut). The only thing CapCut can't make
is the talking-head shots — see the decision below.

---

## Decision: the face (do this first)
The brief *prefers an AI avatar* over using yourself.

- **Option 1 — AI avatar (stronger submission):** generate one consistent character in a cozy
  room, off-shoulder top, holding a plush toy as a "mic." Make ~4 short talking clips
  (lip-synced to the script) for the intro beats. Tools: an image model for the character
  still (Codex/ChatGPT image gen has generous limits), then an avatar/video model to animate +
  lip-sync. Bring clips into CapCut.
- **Option 2 — yourself on camera (faster):** film 4 short talking clips with the same bunny-mic
  prop. Allowed, but not preferred.

The intro is only ~7 seconds total, so either way it's a small amount of footage.

---

## Assets you need to gather (Build A)
1. **A "door opening" clip** — a train door, or ANY door/window/elevator that opens to reveal a
   scene. Film one, or generate one. (Reference used a BART train door at West Oakland.)
2. **A "reveal scene" clip** — what's seen *through* the doors. Reference used a concert +
   fireworks. Use your own concert/event footage, stock, or an AI-generated clip.
3. **A "main clip"** — a hero shot of the subject (reference: girl standing on the platform as a
   train blurs past). This is the payoff after the flash. Use your own footage or AI.
4. **"day in my life"** title text (or your own title).

> Subject can be anything (your own project, gghuman.ai, or no particular topic). Keep the
> 3-asset structure: **door → reveal → hero shot.**

---

## Build A — the train-door reveal (in CapCut)
1. Add the **reveal scene** clip (concert) to the main timeline.
2. Add the **door** clip as an **Overlay** on top, sized to fill frame.
3. Select the overlay → **Remove Background → Custom Removal** → **erase the window glass
   areas** so the reveal scene shows *through* the windows. Keep the door frame/body.
4. Add **Text** "day in my life". Open **layer controls → Arrange layers** and move the text
   **behind the door overlay**, so it reads as revealed between the doors.
5. **Flash transition into the hero shot:**
   a. Put the **main (hero) clip** on the timeline after the reveal.
   b. **Duplicate** it → turn the duplicate into an **Overlay**.
   c. **Extend** the overlay so it **starts slightly before** the main clip.
   d. On that overlay: **Remove Background → Custom Removal** → cut the **subject** out from the
      rest of the shot.
   e. **Arrange layers:** move the cutout **behind** the overlay; then **Split** the overlay.
   f. Apply the **White Flash** video effect at the cut.
   g. Add **Glitch** + **Camera flash** sound FX on the flash.
6. Add the sound bed: music + door **intercom** chime + **door hiss** + **whoosh** + the
   concert audio. (See SFX list in SHOT-BREAKDOWN.md.)

**Steps needing manual judgment:** erasing the glass cleanly (zoom in, small brush); timing the
flash exactly on the beat; matching the text size to the gap between the doors.

---

## Build B — the tutorial wrapper
1. **Screen-record** yourself performing each Build A step on your phone (this IS your b-roll).
   Capture the same moments the reference shows: import, overlay, remove bg, custom erase, add
   text, arrange layers, duplicate, white flash, add SFX, final reveal.
2. Record/generate the **talking-head intro** clips (avatar or you) for beats 2–5.
3. In a fresh CapCut project, assemble in the reference order (see SHOT-BREAKDOWN.md):
   HOOK (finished edit) → intro → "let's go" paper-tear → film-a-door examples → the screen
   recordings in sequence → final reveal.
4. **Captions:** auto-caption your VO, then style to match — rounded white sans for narration,
   a **hand-drawn marker font** for the emphasised ALL-CAPS words. Position centered-low.
5. **Transitions:** paper-tear after the intro; quick whooshes between steps; white flash at the
   reveal.
6. **Audio:** VO + music bed + the SFX set (whoosh, intercom, door hiss, glitch, camera flash,
   clicks).
7. Match **aspect ratio 9:16** and **~50s** duration. Export (reference used "AI UHD").

---

## Comparison checklist (fill in comparison.md)
- [ ] Hook shows the finished edit in-editor, same title caption
- [ ] Intro: avatar/you + bunny mic, 4 caption beats
- [ ] Paper-tear "let's go"
- [ ] Door examples (door/window/airplane)
- [ ] All screen-rec steps in order, captions matching
- [ ] White-flash transition into hero shot
- [ ] SFX: whoosh, intercom, door hiss, glitch, camera flash
- [ ] 9:16, ~50s, exported
