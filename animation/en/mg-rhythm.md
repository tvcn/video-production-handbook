---
id: animation.motion-graphics.mg-rhythm.en
site: animation
type: article
lang: en
translation_key: animation.motion-graphics.mg-rhythm
translation_status: reviewed
title: 'Motion Rhythm: Music Beats and Frames'
summary: Land music hits on frames before easing. Miss the hit and smoothness is still
  chaos.
slug: mg-rhythm
aliases:
- mg-rhythm
canonical_site: animation
canonical_path: /en/article/mg-rhythm/
status: published
diagram: /images/diagrams/en/mg-rhythm.svg
diagram_alt: 'Structure diagram for Motion Rhythm: Music Beats and Frames.'
diagram_caption: Watch “Put the music waveform on the timeline and” and “Place one
  keyframe on each accent.”; judge whether the speed split between foreground, midground
  and background reads in one move.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.motion-graphics.mg-infographic.en
- animation.motion-graphics.mg-transition.en
- animation.pipeline.asset-handoff.en
source_kind: experience
---

<p>Motion graphics is not every element moving at once. Group main information, support lines and background; each gets its own entrance and rest. The viewer reads main, then support, then background.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/mg-rhythm.svg" alt="Structure diagram for Motion Rhythm: Music Beats and Frames.">
  <figcaption>Watch “Put the music waveform on the timeline and” and “Place one keyframe on each accent.”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Rhythm comes from grouping, not constant motion</h2><p>Test at two, four and six seconds; if everything enters on one beat, it looks like an explosion.</p><h2 id="section-2">Limits</h2><p>Faster is not better. With dense information, one beat of rest beats ten animations; the viewer needs time to read.</p><h2 id="section-3">Motion rhythm: map the music, then choose what moves</h2>
<p>MG is not “every beat moves.” Split the track into 4–8 bars, mark accents and pauses, then choose one element. If everything moves, nothing reads.</p>
<ol><li>One subject on the accent; weak beats use position or opacity, not scale.</li><li>Leave 4–6 frames of stillness after each move. More than two seconds of constant motion tires the eye.</li><li>Match transitions by shape or position, not a plugin. The plugin steals the message.</li></ol>
<p>Acceptance: watch with sound off; the rhythm should still read. Turn sound on; motion should not fight the lyrics. Both must pass.</p></section><section><h2 id="section-4">On set</h2><p>Put the music waveform on the timeline and mark eight downbeats. Each downbeat gets one keyframe, then adjust easing.</p></section><section><h2 id="section-5">Do this</h2><p>Motion rhythm aligns music hits to frames before easing; if hits are off, smoothness still feels messy.</p><ol><li>Put the music waveform on the timeline and mark eight accents.</li><li>Place one keyframe on each accent.</li><li>Then adjust easing; do not animate first and hunt for music later.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not animate first and add music later; misaligned hits make even smooth easing messy.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Place one keyframe on each accent.”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>Eight accents are marked on the timeline with matching keyframes.</li><li>Animation changes land on the accents instead of music chasing picture.</li><li>Muted playback still holds rhythm without relying on music.</li></ul>
