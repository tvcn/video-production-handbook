---
id: animation.2d.2d-animation.en
site: animation
type: article
lang: en
translation_key: animation.2d.2d-animation
translation_status: reviewed
translation_reviewed: 2026-11-21
title: "2D Animation: Keyframes, Breakdowns, Loops"
summary: "2D is not about beautiful drawings. It is about controlling time with keys and breakdowns. Make one action read first."
slug: 2d-animation
aliases: [2d-animation]
canonical_site: animation
canonical_path: /en/article/2d-animation/
status: published
difficulty: beginner
stage: animate
format: short-film
tools: []
authors: ["TVCN Animation Desk"]
reviewers: [technical-reviewer]
cover: /images/animation/2d-animation.webp
diagram: /images/diagrams/en/2d-animation.png
diagram_alt: "2D animation: keys, breakdowns, loops"
diagram_caption: "2D is not about pretty drawings; it is about timing with keys and breakdowns. Make one action read before adding drawings."
last_verified: '2026-11-26'
review_due: '2027-02-26'
source_kind: sourced
related: [animation.2d.2d-camera, animation.2d.2d-compositing, formats.brand.brand-film]
depth: deep
deep_minutes: 7
sources:
- S62
- S63
- S12
- S59
test_context: "Review setup: Windows 11; public Blender 4.x / After Effects 2025 workflows; not every version behaves the same."
known_failures: "Known failures: plugin/version gaps break rigs or renders; font and asset licenses need separate checks."
verified: 2026-11-22
---
<!-- DIAGRAM_START -->
## Diagram

<figure>
  <img src="/images/diagrams/en/2d-animation.png" alt="2D animation: keys, breakdowns, loops">
  <figcaption>2D is not about pretty drawings; it is about timing with keys and breakdowns. Make one action read before adding drawings.</figcaption>
</figure>
<!-- DIAGRAM_END -->

2D is not about beautiful drawings. It is about controlling time with keys and breakdowns. Make one action read first.

## Keyframes

Draw the start, the turn, and the end of the action. Those three drawings are the keys. Do not draw every frame from first to last; you will lose timing.

A key must read: where is the hand, where is the weight, where is the gaze. Even in line art, another person should understand it.

## Breakdowns

Add breakdowns between keys to decide “fast–slow–fast” or “slow–fast–stop.” A breakdown is not just an in-between; it controls acceleration and weight.

Test an action in eight drawings before building three minutes. Eight drawings expose timing problems at the lowest cost.

## Loops

For loops (walk, breathe, rain), build eight or twelve frames and check whether the end connects to the start. The first and last drawings are not identical, but the motion must return seamlessly.

Loop length comes from the action, not the software. A step may take twelve frames; a breath may take forty-eight. Do not use one length for everything.

## Three checks

- An eight-drawing test reads start, turn, and end.
- Breakdowns change acceleration, not just fill inbetweens.
- The loop connects seamlessly.

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 7 minutes.</strong> 2D animation is not more drawings. It is keyframes that state the action, then inbetweens that control time.</p>
### Keys first, inbetweens second
<p>Block a scene with three keys: start, turn, end. If three drawings tell the action, add inbetweens. If the keys are unclear, more inbetweens only make it blurrier.</p><p>The turn key carries weight: foot contact, hand on the door, head turning. Draw contact first, then follow-through. Do not tween straight from the first drawing to the last.</p>
### Separate layers by function
<p>Separate body, hair, cloth, and props into layers. The body uses fewer frames; hair and hem lag. If everything moves on the same frame, it looks like stickers.</p><p>For a loop, draw four: contact, down, passing, up. Check for foot slide, then repeat. A loop is not the same drawing repeated; it is the same rhythm repeated.</p>
### Timing before detail
<p>Set the frame rate first: twelve frames per second for hand-drawn, twenty-four for smooth. One missing drawing at twelve changes the speed. Count frames before drawing detail.</p><p>A hold says more about weight than movement: two extra frames before lifting, two extra after landing. The audience feels time, not line quality.</p>
### Five-minute drill: four-drawing loop
<p>Draw a walk in place with four drawings: contact, down, passing, up. Change only feet and pelvis; keep the head. Play it at twelve frames and check for foot slide.</p><p>Draw a second version with one extra hold on the down. Compare which feels heavier. Write the result into the next loop's frame chart.</p>
### When the 2D shot works
<p>The shot works when, muted, the audience can say what the character does, why, and what they hit; feet do not slide, the center bounces, hair and cloth lag. All three pass.</p><p>If the audience needs a caption to read the action, return to the keys, not add inbetweens. Most 2D problems live in the keys, not in line detail.</p>
### Ten 2D animation checks
<ul><li>Three keys first</li><li>Keys tell the action</li><li>Contact drawn at the turn</li><li>Body, hair, cloth layered</li><li>Hair and hem lag</li><li>Four drawings for a loop</li><li>Foot slide checked</li><li>Frame rate before detail</li><li>Holds carry weight</li><li>Frame counts recorded</li></ul><p>2D craft is not fine drawing. It is whether keys and frame counts make the action true.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S62] [Blender Foundation: Blender Manual](https://docs.blender.org/manual/en/latest/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“2D is not about beautiful drawings. It is about controlling ”) against Modelling, rigging, animation and rendering; not a substitute for an on-set test.
- [S63] [Toon Boom: Documentation](https://docs.toonboom.com/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“2D is not about beautiful drawings. It is about controlling ”) against 2D animation, rigging and production pipeline; not a substitute for an on-set test.
- [S12] [Animation](https://www.britannica.com/art/animation) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“2D is not about beautiful drawings. It is about controlling ”) against Encyclopedia entry on animation principles, techniques and industry history; not a substitute for an on-set test.
- [S59] [Adobe: After Effects User Guide](https://helpx.adobe.com/after-effects/user-guide.html) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“2D is not about beautiful drawings. It is about controlling ”) against Compositing, keyframes, tracking and export; not a substitute for an on-set test.
<!-- SOURCES_END -->

