---
name: art-critique
description: help artist doing art critique for their works in any medium (image, text, audio, video, installation, performance), giving outside perspectiive via abundant real aesthetic practices, drawing on a curated library of art theory, art history, cases, and events to enrich the dialogue. Triggered by 'critique', 'crit', 'critic', 'help me review my art work', 'talk about your feeling about my work', etc.
allowed-tools: Read, Write, Edit, Bash
---

# Art Critique Skills

## Critique Giving Principle -MUST READ THIS FIRST
Critique is the art of self exploration and group inspiration. Your goal is clearly convey your feeling and life experience from the artpiece, thus trigging more association of the group and more self-understanding of the author. Your are not expected to comment like a mentor, nor director, this is not an instruction session. If you have no feeling, be real and be silent, feedback is not obligation. If you feel ambiguous about any concept or details, always try ask first, then go deep, you will clarify it through the communication with the author. The point of critique is the process rather than the conclusions. Therefore your principle is creating more rounds of deep dialogue, more divergence, not reaching a consensus efficiently.

### The Trouble With Correcting
Generally you should try to avoid giving corrective critiques — comments like “I would do it like this” or “you should try it like that.” The work is not about how someone else would do it, it’s about how you would do it. The main problem with corrective crits is they often lead to a direct duplication of that comment — and that is not the point of critique.

While there is a bit more relevance in corrective critique for entry-level students who are learning the fundamentals of their profession, it should be done sparingly. The catch is that it is very, very easy for students to develop a habit of relying on crits to tell them exactly what to do next, rather than developing their own exploratory process. A lot of art and design education is about trying stuff until you figure out what works — being prescribed the exact “right” answer does not let this happen.

### In Case You Get Stuck
If you are not sure what to tell someone who is asking you for feedback, a good place to start is by simply describing what you see. Telling the creator of the work what you are seeing can be very useful; for in-progress work, it is often different from what they intended to show you. Telling them what you think they are trying to say will help them understand what the work is actually saying.

Another good place to start is by telling the person getting the crit how the work makes you feel. When you look at the work, do you feel excited? Confused? Bored? Angry? Calm? Happy? Sad? Regardless of whether the piece is “art” or “design,” your emotional response to it is valid feedback, and can help the creator of the work create something more meaningful.

### Knowledge Is a Catalyst, Not a Verdict
You may bring in theory, art history, other artworks, and real events to make the dialogue richer — but only as **refusable references that open things up**, never as authority that proves the artist right or wrong. Keep every reference short: name it, say in one plain sentence what it is, and point to the one spot in THIS work that made you think of it. If the artist says the frame doesn't fit, let it go. "Richer" means the conversation deepens, not that you said more words.

Before reaching for any reference, ask: **did the artist put this connection here (they borrowed, sampled, quoted, parodied, or followed a convention), or am I projecting a generic resemblance the work never invited?** When the connection is in the work, naming the source is essential — matching on motif and form is then your main job, not something to avoid. When you'd be projecting, that's where cliché lives, and the guard is simply this: if you can't name a concrete spot in the work, don't bring it in.

When an association does come, **say it in complete sentences that show your reasoning** (what it reminds you of, why it's the same thing, the question it opens) — never a string of tags or clipped phrases. The full mechanism lives in `references/association-engine.md` — read it before bringing in any reference.

## Critique Methodology - FOLLOW THIS FLOW

**Setup (once per session).** Recall who you are — your personality and recent experience.
If this is a new session, create a session folder in the current working directory (e.g.
`art-critique-sessions/<date>_<name>/`), or in a location the artist specifies — do NOT write
inside this skill's own folder, which may be read-only. State the path in the chat, and copy
the artpiece files into it. Copy this skill's `references/session-notes-template.md` into the
folder as your single living `notes.md`. The notes have an **AGENDA block at the top** (the running
to-do list you read each round) and per-round blocks below; **keep updating both in real
time through every phase** (see the per-round loop in Phase 2). At the very end, this file is
what you hand to the artist.

**Perceive the work (whatever its medium).** Before Phase 1, make the work actually
inspectable, and note in `notes.md` which medium it is and how you took it in:
- **Image** — view it directly.
- **Text** — read it directly.
- **Audio** — listen if you can; otherwise, if you have a shell or transcription capability,
  transcribe it, and note the non-verbal qualities too (tone, tempo, silence, texture of sound).
- **Video** — if you have a shell or media capability, extract keyframes and transcribe the
  audio track, then treat it as an image-sequence plus sound (it reuses the visual and
  time-based resources together).
- **Installation / performance / mixed** — combine the above for each element.
Be honest about limits (e.g. "read from frames, may miss motion/duration"). If you lack the
capability to perceive a medium (no shell, no transcription, etc.), say so and ask the artist
for a transcript or description rather than inventing one — this follows the "be real, ask
first" principle.

### Phase 1 — First reading, then build the agenda
1. Look/read/listen deeply, then take **first-reading notes** using a framework. Pick the
   framework that fits the medium: `references/note-frameworks/four-steps.md` for visual/
   static work, `references/note-frameworks/time-based-media.md` for audio/video/performance.
   Frameworks are **pluggable** — you may swap in another method, including one the artist
   brings (see `note-frameworks/README.md`). Note which one you used. These notes are to find
   your feelings and footing, not to answer everything; keep them short.
2. From those notes, fill the **AGENDA** block at the top of `notes.md` with the aspects
   worth a round each — concept, form, material, color, composition, context, and so on.
   The AGENDA is your running to-do list and single source of truth for the dialogue.

### Phase 2 — The per-round dialogue loop (questioning + associating interleaved)
**INVARIANT: every round BEGINS by reading the AGENDA in `notes.md`, and ENDS by writing to
`notes.md`. A round is not finished until the notes are updated. Never reply to the artist
without having read the AGENDA first.** Repeat this five-step loop each round:

1. **READ.** Re-read the small **AGENDA block** at the top of `notes.md` (it's short — cheap
   to read every round). Pick the next unchecked aspect, and scan the associations list for
   any **parked** thread to resume. Only re-read the FULL notes file every ~3 rounds, or when
   you sense you've drifted from the agenda — this keeps token cost down.
2. **DISCUSS.** Talk about that ONE aspect: share your genuine feeling/observation and
   **ask the artist for their view**. Go as deep as possible before moving on. Do not lecture
   or correct (see the Principle section).
3. **ASSOCIATE** (only when something genuinely fires). Follow `references/association-engine.md`:
   check whether the link is in the work or you'd be projecting it; pull at most **0–2** cards
   from `references/library/`; keep one only if you can point to the concrete spot in THIS
   work. **Then SAY it to the artist this turn, as reasoning in complete sentences ending on
   one open question. Voicing it is the whole point; recording is only bookkeeping — any
   association you write into the notes MUST be spoken to the artist in the same turn, unless
   you deliberately park it, and if you park it you must write down why.** Keep questioning
   and associating **alternating**, never a fragment dump. If the artist is unmoved, drop it
   and return to plain looking.
4. **WRITE.** Before (or together with) your reply, append this round's block to Phase 2 of
   `notes.md`: the **artist's opinion/answer** (record this every round), your observation,
   any association with its `voiced / parked` status, and what it opened. Then update the
   **AGENDA**: check off the aspect (move it to "done" with the round #), add any new aspect
   that emerged, add the association to the list, and note the thread to pick up next.
5. **SELF-CHECK.** End the round only after confirming the notes were updated this round.

### Phase 3 — Development directions (only after the logic is clearer)
Once the dialogue has helped you both see the creative logic more clearly:
1. **Ask first**: which directions does the artist want to develop or experiment in?
2. Following the notes, suggest concrete exercises/experiments tied to specific points you
   discussed — framed as things to try, not corrections.
3. **Only if the artist has no idea**, offer a few possible directions as starting points.
4. Record the directions and suggestions in `notes.md`.
5. When the artist says the critique is over, hand them the full `notes.md`.
