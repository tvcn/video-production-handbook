---
id: main.method.method-dark-footage.en
site: main
type: template
lang: en
translation_key: main.method.method-dark-footage
translation_status: reviewed
title: The Shadows Are Dirty
summary: Lower ISO, add ambient light, and do not lift shadows hard; lifted black
  is noise.
slug: method-dark-footage
aliases:
- method-dark-footage
canonical_site: main
canonical_path: /en/article/method-dark-footage/
status: published
diagram: /images/diagrams/en/method-dark-footage.svg
diagram_alt: Structure diagram for The Shadows Are Dirty.
diagram_caption: Watch “Set ISO to its native base; accept a” and “Add a quarter stop
  to the shadow with”; judge whether the symptom can be restated as one observable
  sentence.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Editorial
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [main.method.method-deadline, main.method.method-ending-weak, context.history.16mm]
verified: 2026-11-23
source_kind: experience
---
<p>Noisy shadows: lower ISO, add a little ambient light, and do not force the shadows up. Lifted blacks are noise.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/method-dark-footage.svg" alt="Structure diagram for The Shadows Are Dirty.">
  <figcaption>Watch “Set ISO to its native base; accept a” and “Add a quarter stop to the shadow with”; judge whether the symptom can be restated as one observable sentence.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">On set</h2><p>Drop to native ISO, add a small ambient light, and do not lift the shadows hard. Let some black stay.</p></section><section><h2 id="section-2">Do this</h2><ol><li>Set ISO to its native base; accept a slightly darker image.</li><li>Add a quarter stop to the shadow with a small lamp or reflector; do not light the face straight on.</li><li>Lift shadows only slightly in post and keep blacks black; do not excavate the noise.</li></ol></section><section><h2 id="section-3">Avoid</h2><p>Do not use “cinematic” as an excuse for underexposure; crushed shadows do not come back.</p></section><section><h2 id="section-4">Three causes</h2><p>For “The Shadows Are Dirty”, check three directions first. Change one variable, record a 30-second comparison, and see which link the change follows.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Cause</th><th>Signal on set</th><th>Five-minute test</th></tr></thead><tbody><tr><td>Underexposure + high ISO</td><td>Lifting shadows reveals noise and grey colour</td><td>Drop ISO one stop and add face light</td></tr><tr><td>Log not transformed</td><td>The image is flat and black is not black</td><td>Apply the correct colour transform first</td></tr><tr><td>Heavy compression</td><td>Shadow blocking and smearing appear</td><td>Use a higher bitrate or a ProRes intermediate</td></tr></tbody></table></div></section><section><h2 id="section-5">On-set diagnosis</h2><ol><li>Open the waveform: check black level and whether shadows hold more than 5% detail.</li><li>Judge after transforming Log, not on the flat image.</li><li>Compare high and low bitrate versions to see whether blocking is compression or noise.</li></ol></section><section><h2 id="section-6">Fix</h2><p>Dirty shadows usually mean too little light on set and too much lifting in post. Expose skin first, then decide how black the shadows should be.</p><ol><li>Add soft light to the face; let the background go dark before underexposing skin.</li><li>Drop to native ISO and use ND to control highlights.</li><li>Apply the correct LUT/transform before judging black level.</li><li>Denoise shadows only until blocking disappears; keep some grain.</li></ol></section><section><h2 id="section-7">Failure cases</h2><p>With “The Shadows Are Dirty”, these three moves make it worse. Pick one replacement action and do not change three variables at once.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Failure</th><th>Why it gets worse</th><th>Replace with</th></tr></thead><tbody><tr><td>Lift the whole image</td><td>Noise and blocking grow together</td><td>Raise midtones and hold black</td></tr><tr><td>Maximum denoise</td><td>Skin turns plastic and hair smears</td><td>Local denoise; keep texture</td></tr><tr><td>Use high ISO</td><td>Shadows get dirtier and highlights clip sooner</td><td>Add light instead of gain</td></tr></tbody></table></div></section><section><h2 id="section-8">Acceptance table</h2><p>Acceptance is not “it feels better”; all four must be identifiable, playable and logged.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Log</th></tr></thead><tbody><tr><td>Skin exposure</td><td>The face is readable, not underexposed</td><td>Waveform 60–70%</td></tr><tr><td>Black level</td><td>Black sits at 0–5%, not grey</td><td>Waveform/scope</td></tr><tr><td>Noise</td><td>No obvious blocking in shadows</td><td>100% playback</td></tr><tr><td>Colour</td><td>Skin is not green or magenta after transform</td><td>Colour chart or skin reference</td></tr></tbody></table></div></section><section><h2>Boundary</h2><p>This page only covers “The Shadows Are Dirty”; it does not replace There Is No Time, The Ending Has No Force, 16mm: Cinema Left the Theater. When the problem belongs to one of those pages, use that page instead of adding more parameters here.</p></section><section><h2>Alternative</h2><p>If “Set ISO to its native base; accept a slightly darker image” is not the main problem, start with “Add a quarter stop to the shadow with a small lamp or reflector; do not light the face straight on”; only upgrade after both hold.</p></section><section><h2>60-second test</h2><p>Run one 60-second test against check 1: ISO is at its native base and shadows show no chroma noise. If check 2 (The shadow got a little fill but blacks remain black) does not change, do not add gear or budget.</p></section>
<h2>Check</h2><ul><li>ISO is at its native base and shadows show no chroma noise.</li><li>The shadow got a little fill but blacks remain black.</li><li>Post lifts shadows only slightly and does not excavate noise.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note:This page draws on 7 projects with one lead and a two-to-three-person crew, a fixed budget and schedule; it covers the decision order for “The Shadows Are Dirty”, not an external laboratory test, multi-camera, union crews, stunts or high-risk sets.
<!-- SOURCES_END -->

