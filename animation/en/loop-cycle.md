---
id: animation.2d.loop-cycle.en
site: animation
type: article
lang: en
translation_key: animation.2d.loop-cycle
translation_status: reviewed
title: 'Loop Cycle: Match the First and Last Frame'
summary: The first and last frames must match, or the loop twitches every cycle.
slug: loop-cycle
aliases:
- loop-cycle
canonical_site: animation
canonical_path: /en/article/loop-cycle/
status: published
diagram: /images/diagrams/en/loop-cycle.svg
diagram_alt: 'Structure diagram for Loop Cycle: Match the First and Last Frame.'
diagram_caption: Watch “Draw the same pose at the head and” and “Fill eight to twelve
  frames between them.”; judge whether the speed split between foreground, midground
  and background reads in one move.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.2d.run-cycle.en
- animation.2d.2d-compositing.en
- animation.principles.anticipation.en
sources:
- S12
- S23
source_kind: sourced
---

<p>Walk, run and breathing cycles must connect first and last frame invisibly. Build key poses, then in-betweens; overlap one frame at the seam so the loop does not pop.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/loop-cycle.svg" alt="Structure diagram for Loop Cycle: Match the First and Last Frame.">
  <figcaption>Watch “Draw the same pose at the head and” and “Fill eight to twelve frames between them.”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Loops live or die at the seam</h2><p>A loop is not identical repetition. Add one small variation per cycle—a hand higher, a step slower. Perfect sameness bores in three seconds.</p><h2 id="section-2">Limits</h2><p>Loop length comes from the action, not the music. Cutting before a step completes makes the foot slide; finish the action, then match the beat.</p></section><section><h2 id="section-3">On set</h2><p>Draw the same frame at both ends with eight to twelve frames between. Loop it and check for a jump from last to first.</p></section><section><h2 id="section-4">Do this</h2><p>A loop needs matching first and last frames, or it hiccups every cycle.</p><ol><li>Draw the same pose at the head and tail.</li><li>Fill eight to twelve frames between them.</li><li>Play on loop and check the last-to-first transition for a jump.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not leave a one-frame mismatch at the seam; repetition makes the hitch obvious.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Fill eight to twelve frames between them.”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>First and last frames are the same pose in position and shape.</li><li>Eight to twelve frames fill the middle at an even rhythm.</li><li>Ten loops play with no hitch or stick at the seam.</li></ul>

<!-- SOURCES_START -->
## Sources

- [S12] Britannica：动画; see the original link and use note in SOURCES.md.
- [S23] SMPTE 标准入口; see the original link and use note in SOURCES.md.

Full links and use notes: [`SOURCES.md`](../../about/).
<!-- SOURCES_END -->
