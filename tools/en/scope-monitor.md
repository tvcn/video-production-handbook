---
id: tools.capability.scope-monitor.en
site: tools
type: tool
lang: en
translation_key: tools.capability.scope-monitor
translation_status: reviewed
title: 'Scope Monitor: Exposure and Color Together'
summary: A scope monitor shows exposure and color together; a histogram alone misses
  skin drift.
slug: scope-monitor
aliases:
- scope-monitor
canonical_site: tools
canonical_path: /en/article/scope-monitor/
status: published
diagram: /images/diagrams/en/scope-monitor.svg
diagram_alt: 'Structure diagram for Scope Monitor: Exposure and Color Together.'
diagram_caption: Watch “Switch the scope to waveform and vectorscope.” and “Shoot
  a gray card.”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.tutorial.set-mediabay, tools.capability.shotgun-mic, shoot.camera.composition]
source_kind: experience
---
<p>A scope reads signal, not composition or performance. Treating the waveform as the only proof of “correct exposure” protects highlights while leaving the face without direction.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/scope-monitor.svg" alt="Structure diagram for Scope Monitor: Exposure and Color Together.">
  <figcaption>Watch “Switch the scope to waveform and vectorscope.” and “Shoot a gray card.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">What to compare first</h2><ul><li><strong>Waveform and vector:</strong> it must show luma waveform and vectorscope together; a histogram alone cannot judge skin or black level.</li><li><strong>Inputs and zoom:</strong> confirm 3G/6G/12G SDI or HDMI version, and whether it can magnify a critical area to 1:1 pixels.</li><li><strong>Power and brightness:</strong> it must run from mains or long batteries on set; screen brightness must survive exteriors, not only a dark room.</li></ul><h2 id="section-2">What it cannot do</h2></section><section><h2 id="section-3">On set</h2><p>Switch the scope to waveform and vectorscope and shoot a grey card. Black at 0, white at 100, skin line on target.</p></section><section><h2 id="section-4">Do this</h2><p>A scope monitor shows exposure and color together; a histogram alone misses skin shift.</p><ol><li>Switch the scope to waveform and vectorscope.</li><li>Shoot a gray card.</li><li>Black at 0, white at 100, skin on the target line.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not read the histogram alone; skin can go green while the histogram looks perfect.</p></section>
<h2>Check</h2><ul><li>Both waveform and vectorscope are used.</li><li>Gray card reads black at 0 and white at 100.</li><li>Skin sits near the target line and any shift is named.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note: this page draws on 3 gear trial and playback reviews under the listed model and firmware, once indoors and once outdoors; it discusses “Scope Monitor: Exposure and Color Together”; no external laboratory test was run, and the conclusion may not transfer when conditions change.
<!-- SOURCES_END -->

