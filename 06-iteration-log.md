# Iteration Log — The Last Train

This project involved several iterations because the AI video
model did not always interpret actions, spatial relationships
or camera instructions as intended.

Instead of treating failed generations as random errors, I used
them to adjust the shot design and generation approach.

## Iteration 1 — Hand and Phone Interaction

### Problem

During the first attempt, the character was taking his phone
out of his pocket. The generated hand movement was inconsistent
and the phone appeared to change between hands.

### What I Learned

Complex hand-object interactions were difficult for the model
to maintain consistently.

### Change

The later version simplified the phone interaction and made the
intended hand movement more explicit.

---

## Iteration 2 — Phone Notification

### Problem

The phone was visible, but the generated video did not reliably
show readable notification text.

### What I Learned

Generating exact typography inside an AI video was unreliable.

### Change

The phone interaction was generated without depending on
readable AI-generated text.

The exact notification was added during post-production.

---

## Iteration 3 — Character Reaction

### Problem

Some generations added unnecessary movement while the character
was supposed to remain relatively still.

### What I Learned

The model performed more reliably when the action was limited
to one clear movement.

### Change

The prompts were simplified to focus on the intended reaction,
such as looking at the phone or looking toward the platform.

---

## Iteration 4 — Platform Geometry

### Problem

An attempt to place the protagonist and his double on separate
metro platforms produced incorrect spatial relationships.

The model sometimes placed the double on the same platform or
interpreted the railway area incorrectly.

### What I Learned

Adding more spatial instructions did not necessarily make the
generation more accurate.

### Change

The scene was simplified instead of continuing to add
instructions.

The final version focused on the two characters staring at each
other on the platform while the metro train passes along the
side.

---

## Iteration 5 — Aspect Ratio

### Problem

During some camera movements, the model attempted to change the
composition toward a wider cinematic frame.

### What I Learned

Camera instructions can sometimes conflict with the desired
output framing.

### Change

The prompts explicitly reinforced the vertical 9:16 format and
camera movement was kept simpler.

---

## Iteration 6 — Final Sequence

After several iterations, the shots were selected based on
whether they communicated the story clearly and maintained
reasonable visual consistency.

The final workflow prioritized:

- Simple actions
- Controlled camera movement
- Character consistency
- Clear visual storytelling
- Post-production
