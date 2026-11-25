---
id: animation.3d.render.en
site: animation
type: article
lang: en
translation_key: animation.3d.render
translation_status: reviewed
title: 'Render: Samples and Noise'
summary: Samples and noise come before resolution; unresolved noise at 4K is just
  bigger dirt.
slug: render
aliases:
- render
canonical_site: animation
canonical_path: /en/article/render/
status: published
diagram: /images/diagrams/en/render.svg
diagram_alt: 'Structure diagram for Render: Samples and Noise.'
diagram_caption: Watch “Render at 50 percent resolution and low samples” and “Adjust
  light samples and material samples separately.”; judge whether the speed split between
  foreground, midground and background reads in one move.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.3d.lighting-3d.en
- animation.3d.layout.en
- animation.stop-motion.armature.en
source_kind: experience
---

<p>Confirm frame rate, resolution, color space and audio sample rate; render settings must match the delivery sheet. Do not edit while rendering; the file will not match.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/render.svg" alt="Structure diagram for Render: Samples and Noise.">
  <figcaption>Watch “Render at 50 percent resolution and low samples” and “Adjust light samples and material samples separately.”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Lock the timeline, then the settings</h2><p>Play three points after render: opening, mid action, end credits. Check black frames, freezes, audio dropouts and caption overflow. Verify size and duration.</p><h2 id="section-2">Limits</h2><p>Rendering is not delivery. A successful render proves the file exists, not that it is correct; QC is a separate pass.</p><h2 id="section-3">Rendering: lock samples before denoising</h2>
<p>Render noise is not something denoise “wipes away.” With too few samples, denoise flattens detail. With enough samples, denoise is the last 10%. Stabilize samples and light bounces first, then denoise.</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>Setting</th><th>Tune first</th><th>Symptom</th></tr></thead><tbody>
<tr><td>Samples</td><td>Start at 64, double up</td><td>Shadow noise, edge flicker</td></tr>
<tr><td>Bounces</td><td>3–4, by scene complexity</td><td>Crushed or washed shadows</td></tr>
<tr><td>Denoise</td><td>Last, preserve detail</td><td>Plastic skin, lost texture</td></tr>
<tr><td>Output</td><td>Multi-channel EXR</td><td>No separate light control in post</td></tr>
</tbody></table></div>
<h3>Project-level checks</h3>
<ol><li>Render a 50% test first to confirm composition, materials and light. Do not wait for 4K to discover a problem.</li><li>Double samples; noise should drop clearly. If it does not, the problem is lighting or materials, not samples.</li><li>Save before/after denoise and compare pores, cloth and hair. If detail disappears, lower the strength.</li><li>Output EXR with Beauty, Light, Reflection and Depth. Keep an adjustable version, not only the MP4.</li></ol>
<p>When the farm is queued, submit a low-sample preview to hold the shot, then render final. Do not use final settings as a test.</p></section><section><h2 id="section-4">On set</h2><p>Render at 50 percent resolution with low samples to see where noise lives. Raise light and material samples separately; do not just raise the total.</p></section><section><h2 id="section-5">Do this</h2><p>Rendering checks samples and noise before resolution; unresolved noise at 4K is just bigger dirt.</p><ol><li>Render at 50 percent resolution and low samples to see noise distribution.</li><li>Adjust light samples and material samples separately.</li><li>Do not only raise total samples; find which source causes the noise.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not brute-force noise with total samples; without the source, render time burns.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Adjust light samples and material samples separately.”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>A 50 percent low-sample pass shows whether noise comes from light or material.</li><li>Light and material samples were adjusted separately.</li><li>Final noise is traced to a specific source, not brute-forced.</li></ul>
