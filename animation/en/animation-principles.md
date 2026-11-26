---
id: animation.principles.animation-principles.en
site: animation
type: article
lang: en
translation_key: animation.principles.animation-principles
translation_status: reviewed
title: 'The Twelve Principles: Use One at a Time'
summary: The twelve principles are not filters. Use one to explain one action; otherwise
  the audience sees noise.
slug: animation-principles
aliases:
- animation-principles
canonical_site: animation
canonical_path: /en/article/animation-principles/
status: published
diagram: /images/diagrams/en/animation-principles.svg
diagram_alt: 'Structure diagram for The Twelve Principles: Use One at a Time.'
diagram_caption: 'Watch “Choose one action: a character reaches for a” and “Use only
  anticipation and ease in/out: five frames”; judge whether the speed split between
  foreground, midground and background reads in one move.'
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.timing.animation-timing, animation.2d.animation-walk, formats.brand.brand-film]
depth: deep
deep_minutes: 6
sources:
- S62
- S63
- S12
- S59
test_context: 'Review setup: Windows 11; public Blender 4.x / After Effects 2025 workflows;
  not every version behaves the same.'
known_failures: 'Known failures: plugin/version gaps break rigs or renders; font and
  asset licenses need separate checks.'
verified: 2026-11-22
source_kind: sourced
---
<p>The twelve principles are diagnostic tools, not a checklist. Read weight, arc and timing first, then decide whether squash and stretch is needed. Using all of them turns the action into a rubber toy.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/animation-principles.svg" alt="Structure diagram for The Twelve Principles: Use One at a Time.">
  <figcaption>Watch “Choose one action: a character reaches for a” and “Use only anticipation and ease in/out: five frames”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Use two or three principles at a time</h2><p>Fix the key pose before discussing follow-through and overlap. If the pose is wrong, more principles only animate the error more smoothly.</p><h2 id="section-2">Limits</h2><p>Realistic animation does not need exaggerated squash. Principles serve weight and intention, not “looking like animation.”</p></section><section><h2 id="section-3">On set</h2><p>Pick one action: a character reaches for a cup. Use anticipation and ease in and out only: five frames of anticipation, three of action, four of settle. Do not add squash and stretch at the same time.</p></section><section><h2 id="section-4">Do this</h2><p>The twelve principles are not twelve filters; use one principle per action so the audience can read it.</p><ol><li>Choose one action: a character reaches for a cup.</li><li>Use only anticipation and ease in/out: five frames of anticipation, three of action, four of settle.</li><li>Do not add squash and stretch at the same time; test one principle per pass.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not apply all twelve principles at once; the action becomes a spasm.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Use only anticipation and ease in/out: five frames”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>One action uses one main principle and you can say what it solves.</li><li>Anticipation, action, and settle have written frame counts, not random drawing.</li><li>Remove the principle and the action reads worse, proving it mattered.</li></ul>

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 6 minutes.</strong> The twelve principles are not twelve boxes to tick. Pick three per shot and make the action clear.</p>
### Pick three
<p>Choose three per shot: squash and stretch for material, anticipation for intention, follow-through for inertia. If three tell the action, stop.</p><p>Using all twelve over-explains the action; the audience sees technique, not character. Principles are tools, not an exam.</p>
### Anticipation and follow-through pair
<p>Crouch before a jump, pull back before a punch, lower before a run. Anticipation tells the audience what is coming. After landing, hair, cloth, and props keep moving; follow-through gives weight.</p><p>Too much anticipation deflates; too little surprises. Try two to four frames; do not guess.</p>
### Exaggerate from a baseline
<p>Draw a normal-proportion version first, then decide what to push: face, hands, speed. Push one thing so the audience sees the contrast.</p><p>Exaggeration is not distortion; it enlarges the key information. If the audience cannot tell what is exaggerated, return to the normal version and cut the effect.</p>
### Five-minute drill: three principles, one action
<p>Animate a door opening with only three principles: anticipation, squash and stretch, follow-through. The handle turns, the body leans back, the cloth settles after the door opens. Write one line for each.</p><p>Remove one and see if the action still works. If it does, that principle was decoration; if not, it was structure.</p>
### When the principles are used right
<p>Remove one principle: if the action still works, it was decoration; if it collapses, it was structure. A principle is used right when you can name the problem it solves.</p><p>If the audience says what the character is thinking, not “the animation is impressive,” the principles are inside the action, not on top of it.</p>
### Watch the anticipation again
<p>Play the anticipation alone: can the audience guess the direction half a second early? If not, add two reverse frames; if too early, remove one. Anticipation is not more; it is just enough to make the next move believable.</p>
### Ten principle checks
<ul><li>Three principles per shot</li><li>Squash and stretch for material</li><li>Anticipation for intention</li><li>Follow-through for inertia</li><li>Crouch before jump, pull before punch</li><li>Hair and cloth continue after landing</li><li>Anticipation tested at two to four frames</li><li>Normal proportions first</li><li>Push one thing only</li><li>Remove one and test the action</li></ul><p>Right principles show what the character is thinking. Too many show you showing off.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S62] [Blender Foundation: Blender Manual](https://docs.blender.org/manual/en/latest/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“The twelve principles are not filters. Use one to explain on”) against Modelling, rigging, animation and rendering; not a substitute for an on-set test.
- [S63] [Toon Boom: Documentation](https://docs.toonboom.com/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“The twelve principles are not filters. Use one to explain on”) against 2D animation, rigging and production pipeline; not a substitute for an on-set test.
- [S12] [Animation](https://www.britannica.com/art/animation) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“The twelve principles are not filters. Use one to explain on”) against Encyclopedia entry on animation principles, techniques and industry history; not a substitute for an on-set test.
- [S59] [Adobe: After Effects User Guide](https://helpx.adobe.com/after-effects/user-guide.html) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“The twelve principles are not filters. Use one to explain on”) against Compositing, keyframes, tracking and export; not a substitute for an on-set test.
<!-- SOURCES_END -->

