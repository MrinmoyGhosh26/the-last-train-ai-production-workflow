# AI Generation Workflow — The Last Train

The video was created as a sequence of individual AI-generated
shots rather than one continuous generation.

The main goal was to maintain visual consistency while keeping
each generation simple enough for the video model to handle
reliably.

## 1. Create the Character Reference

A dedicated character reference image was created first.

This became the visual anchor for the main character and was
used when generating subsequent shots.

Reference:

[Character Reference](references/character-reference.png)

## 2. Break the Story Into Shots

The story was divided into six shots.

Each shot was given a specific purpose, camera direction,
character action and environment description.

This made it easier to identify problems and regenerate only
the shot that needed improvement.

## 3. Generate the Shots

The shots were generated using LoreMotion with reference images
and detailed prompts.

Prompts focused on:

- Character appearance
- Environment
- Camera position
- Camera movement
- Character action
- Lighting
- Mood
- 9:16 vertical framing
- Important continuity requirements

## 4. Keep Actions Simple

One of the biggest lessons from the generation process was that
complex actions were less reliable.

For example, phone and hand interactions sometimes caused:

- Incorrect hand positioning
- Sudden changes between hands
- Unnatural object movement
- Unwanted character movement

Instead of continuing to add instructions to an already
unreliable action, the shot was simplified when necessary.

## 5. Use Previous Results as References

When a generated shot had the correct character appearance or
environment, that successful result was used as a reference for
the next generation whenever possible.

This helped maintain:

- Facial identity
- Hairstyle
- Clothing
- Environment
- Lighting
- Overall visual style

## 6. Review Every Generation

Each generated clip was reviewed before moving forward.

The review focused on:

- Character consistency
- Hand and object movement
- Facial quality
- Camera movement
- Environment continuity
- Composition
- Aspect ratio
- Unwanted objects or people
- Whether the action matched the prompt

## 7. Iterate Instead of Blindly Regenerating

When a generation failed, the problem was identified first.

For example:

**Problem:** The model produced unreliable hand movement while
the character was taking out the phone.

**Response:** Simplify the action and make the intended hand
movement more explicit.

Another example was the metro-platform scene. The model
misunderstood the spatial relationship between the characters
and the platforms.

**Response:** Simplify the blocking and reduce the number of
simultaneous spatial instructions.

## 8. Add Exact Text During Editing

The video model was not relied on for the final readable phone
notification.

Instead, the visual phone interaction was generated first and
the exact message was added later during post-production.

The notification used in the final edit was:

> **DON'T LOOK BACK.**

The final message was:

> **I TOLD YOU NOT TO LOOK.**

## 9. Assemble the Sequence

After the individual shots were approved, they were assembled
in CapCut in the following order:

**Shot 1 → Shot 2 → Shot 3 → Shot 4 → Shot 5 → Shot 6**

The visual edit focused on clean cuts and maintaining the
narrative flow rather than using heavy transitions.

## 10. Sound Design

Sound design was handled collaboratively with a sound engineer.

The audio was designed around the visual edit, including metro
ambience, notification cues, tension and the passing metro train.

## Overall Workflow

**Character Reference**
↓
**Story Breakdown**
↓
**Shot Design**
↓
**Prompt + Reference**
↓
**AI Generation**
↓
**Quality Check**
↓
**Iteration**
↓
**CapCut Assembly**
↓
**Sound Design**
↓
**Final Export**

## Key Takeaway

The generation process worked best when each shot had one clear
purpose and the prompts described only the important elements.

The workflow became less about trying to force the AI model to
perform complex sequences and more about designing shots that
the model could reliably execute.
