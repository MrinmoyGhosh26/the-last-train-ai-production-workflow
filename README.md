# The Last Train — AI Video Production Workflow

A short-form AI video project where I experimented with turning a simple story idea into a complete, shot-by-shot production workflow.

The goal wasn't just to generate a video. I wanted to explore how a generative-video workflow could be used to create a consistent cinematic sequence while dealing with the limitations of current AI video models.

## The Story

A man waits alone at an almost-empty metro station late at night.

His phone vibrates.

A message appears:

> **DON'T LOOK BACK.**

He looks around and sees someone who looks exactly like him.

The two characters stare at each other while a metro train passes along the side of the platform.

The video ends on a final message:

> **I TOLD YOU NOT TO LOOK.**

## What I Built

I broke the story into individual shots instead of trying to generate the entire sequence at once.

The workflow was:

**Story → Character Reference → Shot Breakdown → AI Generation → Review → Iteration → Editing → Sound Design**

Each shot was generated separately and reviewed before moving on to the next one.

## Tools Used

- **ChatGPT** — story development, shot planning and prompt iteration
- **LoreMotion / LTX** — AI video generation
- **CapCut** — visual editing and compositing
- **GitHub** — workflow documentation
- **Sound Design** — collaborative post-production with a sound engineer

## What I Learned

One of the biggest things I noticed was that AI video generation works better when the actions are kept simple.

For example, complicated hand movements and phone interactions sometimes produced inconsistent results. Instead of repeatedly generating the same failed shot, I simplified the action and changed the shot design.

I also found that asking the model to generate exact readable text wasn't reliable enough for the final video. So I generated the visual phone interaction and added the exact notification text during editing.

Another challenge was spatial continuity. When I tried to create a complicated relationship between two metro platforms, the model interpreted the scene incorrectly. I simplified the blocking instead of continuing to add more instructions.

## Shot Breakdown

### Shot 1 — Establishing

The character stands alone at the metro station.

A slow camera push establishes the location and isolated atmosphere.

### Shot 2 — Phone

The phone vibrates.

He takes it out and looks at it.

### Shot 3 — Warning

The character looks at the phone and reacts to the warning.

The exact notification text is added during post-production:

> **DON'T LOOK BACK.**

### Shot 4 — Reaction

He looks up from the phone and looks toward the side of the platform.

His expression changes from confusion to uneasiness.

### Shot 5 — The Double

He turns and sees a mysterious man standing several meters away.

The mysterious man looks exactly like him — same face, hairstyle, clothing and overall appearance.

The two characters remain still and stare at each other.

### Shot 6 — The Train

A metro train passes along the side of the platform while the two characters continue staring at each other.

The video ends while the train is still passing, leaving the encounter unresolved.

The final message is added during editing:

> **I TOLD YOU NOT TO LOOK.**

The video then cuts to black.

## Quality Checks

For every shot, I checked:

- Character consistency
- Clothing consistency
- Environment continuity
- Camera framing
- 9:16 aspect ratio
- Unwanted objects or people
- Facial and anatomical errors
- Object and hand continuity
- Unnatural motion
- Whether the shot communicated the intended story beat

## Iteration Approach

When something didn't work, I tried to identify *why* before generating another version.

### Example 1 — Hand and Phone Movement

**Problem:** Complex phone and hand movement produced inconsistent results.

**Change:** Simplified the hand action and controlled which hand interacted with the phone.

### Example 2 — Spatial Continuity

**Problem:** The model misunderstood the positioning of characters across metro platforms.

**Change:** Simplified the scene and changed the blocking rather than continuing to add more instructions.

### Example 3 — AI-Generated Text

**Problem:** Generated phone-screen text was inconsistent and unreliable.

**Change:** Kept the phone interaction visual and added the exact notification text during post-production.

This became an important part of the workflow:

> **If the model repeatedly fails at an action, simplify or redesign the shot instead of blindly regenerating it.**

## Sound Design

The final sound design was created collaboratively with a sound engineer.

The audio direction was built around the visual story, with emphasis on:

- Realistic metro-station ambience
- Phone notification cues
- Gradually increasing tension
- Space and silence around the double reveal
- The passing train as the main sound event
- A restrained ending rather than an exaggerated horror effect

The sound was designed to support the visuals without overpowering them.

## Post-Production

The final visual assembly was completed in CapCut.

Post-production was used for:

- Shot trimming
- Shot sequencing
- Notification text
- Final title treatment
- Black-screen ending
- Visual pacing

Exact text was added during editing instead of relying on AI-generated typography.

## Final Result

The final video is a small experiment, but the main focus of the project is the workflow behind it.

It demonstrates how I approached:

- AI-assisted storytelling
- Shot planning
- Prompt iteration
- Character consistency
- Generative-video limitations
- Visual quality control
- Post-production decisions
- Collaboration with a sound specialist

The same basic process can be reused for other short-form narrative or branded video projects.
