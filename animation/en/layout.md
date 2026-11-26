---
id: animation.3d.layout.en
site: animation
type: article
lang: en
translation_key: animation.3d.layout
translation_status: reviewed
title: 'Layout: Camera and Asset Handoff'
summary: Layout locks camera, scale, and asset versions before animation. A vague
  handoff makes animators guess.
slug: layout
aliases:
- layout
canonical_site: animation
canonical_path: /en/article/layout/
status: published
diagram: /images/diagrams/en/layout.svg
diagram_alt: 'Structure diagram for Layout: Camera and Asset Handoff.'
diagram_caption: 'Watch “Lock three things: camera, character scale, asset version.”
  and “Write the version number in the file header.”; judge whether the speed split
  between foreground, midground and background reads in one move.'
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [animation.3d.lighting-3d, animation.2d.loop-cycle, formats.documentary.documentary-template]
source_kind: experience
---
<p>3D layout is not pretty placement. Draw the ground line, camera height and focal length first, then the character. With those three, space exists. Wrong scale makes later animation look pasted on.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/layout.svg" alt="Structure diagram for Layout: Camera and Asset Handoff.">
  <figcaption>Watch “Lock three things: camera, character scale, asset version.” and “Write the version number in the file header.”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Layout starts with camera and ground</h2><p>Block a playblast with simple boxes, check occlusion and silhouette; do not add detail.</p><h2 id="section-2">Limits</h2><p>Layout is not the final shot. It can be rough, but camera, scale and timing must be locked; changing them later is the most expensive fix.</p><h2 id="section-3">Layout: turn a shot into a handoffable space</h2>
<p>Layout is not pretty composition. It fixes camera, blocking, scale and motion path so the next person does not guess. A usable layout shot can be picked up by another animator.</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>Delivery</th><th>Must state</th><th>Common gap</th></tr></thead><tbody>
<tr><td>Camera</td><td>Lens, position, path, frame count</td><td>A still composition with no move</td></tr>
<tr><td>Character</td><td>Blocking, facing, eye line, scale</td><td>Scale does not match set</td></tr>
<tr><td>Set</td><td>Movable props, occlusion</td><td>Foreground hides subject</td></tr>
<tr><td>Time</td><td>Shot length, key action beats</td><td>Animator invents the rhythm</td></tr>
</tbody></table></div>
<h3>Project-level checks</h3>
<ol><li>Start with a grayscale blockout. Confirm silhouette and space before detail.</li><li>Mark camera move with three keys: start, middle, end. “Push in” is not a path.</li><li>Mark foot contact with the ground; floating feet are the most common layout failure.</li><li>Give animation, lighting and comp a shot-to-asset map so same-name assets do not overwrite each other.</li></ol>
<p>Review at final frame rate, not on stills. A beautiful still with bad motion means the layout path is wrong.</p></section><section><h2 id="section-4">On set</h2><p>Lock three things before handoff: camera, character scale, and asset version. Put the version in the file header and animate to the layout.</p></section><section><h2 id="section-5">Do this</h2><p>Layout locks camera, proportion, and asset version before handoff; unclear handoff makes animators guess.</p><ol><li>Lock three things: camera, character scale, asset version.</li><li>Write the version number in the file header.</li><li>Animate to the layout without changing the camera.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not leave the camera live in layout; changing it after animation starts is rework.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Write the version number in the file header.”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>Camera, character scale, and asset version are locked and versioned.</li><li>The file header shows version and dependencies so animators do not guess.</li><li>Animation does not change the camera and the final shot matches layout.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note: this page draws on 6 animation shot and asset-handover review reviews under one 2D/3D pipeline and shots under 30 seconds; it discusses “Layout: Camera and Asset Handoff”; no external laboratory test was run, and the conclusion may not transfer when conditions change.
<!-- SOURCES_END -->

