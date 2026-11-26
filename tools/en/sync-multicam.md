---
id: tools.tutorial.sync-multicam.en
site: tools
type: article
lang: en
translation_key: tools.tutorial.sync-multicam
translation_status: reviewed
title: 'Multicam Sync: Timecode and Clap'
summary: Sync timecode first, clap as backup; with both, the edit can cut confidently.
slug: sync-multicam
aliases:
- sync-multicam
canonical_site: tools
canonical_path: /en/article/sync-multicam/
status: published
diagram: /images/diagrams/en/sync-multicam.svg
diagram_alt: 'Structure diagram for Multicam Sync: Timecode and Clap.'
diagram_caption: Watch “Sync timecode, then clap once more.” and “Build a multicam
  clip in the edit.”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.test.test-protocols, tools.capability.timecode, shoot.camera.composition]
source_kind: experience
---
<p>Without timecode, use a clap, a line or a flash seen by every camera. Align by audio waveform in the edit; do not drag by “looks close.”</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/sync-multicam.svg" alt="Structure diagram for Multicam Sync: Timecode and Clap.">
  <figcaption>Watch “Sync timecode, then clap once more.” and “Build a multicam clip in the edit.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Give multicam one shared event</h2><p>Match frame rate, shutter and audio sample rate before rolling. Mixed frame rates force speed changes that break sound sync.</p><h2 id="section-2">Limits</h2><p>Syncing once is not syncing forever. Long takes drift; re-sync every twenty to thirty minutes or use timecode.</p><h2 id="section-3">Multi-camera sync: timecode first, clap as backup</h2>
<p>The fear is “looks aligned but is two frames off.” Jam timecode if available; if not, clap on every camera. Align waveforms first, then trim frames.</p>
<ol><li>Set one frame rate and timecode before rolling. Do not mix frame rates on one timeline.</li><li>Clap three times, one second apart, on every camera. Align on the first clap in post.</li><li>After sync, pick a random action and check each camera. One frame is acceptable; two or more means drift.</li></ol>
<p>Acceptance: all cameras film a stopwatch, pause on the same frame; readings should match. If not, return to timecode or frame rate.</p></section><section><h2 id="section-4">On set</h2><p>Sync timecode and clap once more. Build a multicam clip and switch using the camera map.</p></section><section><h2 id="section-5">Do this</h2><p>Multicam sync uses timecode first and a clap as backup; with both, the edit dares to cut.</p><ol><li>Sync timecode, then clap once more.</li><li>Build a multicam clip in the edit.</li><li>Switch by the camera map, not memory.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not rely on timecode alone; one camera off-code throws the whole multicam group.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>every spec maps to one concrete shooting problem</li><li>weight, power and connections hold on a real rig</li><li>a 60-second test leaves one comparable number</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>specs without connections, power or weight</li><li>batteries, storage or body do not match after purchase</li><li>no 60-second test, so the problem arrives on the shoot</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Run a 60-second test with the gear you already own, measuring only “Sync timecode, then clap once more.”. Record two numbers: what you need and what the gear actually gives.</p></section>
<h2>Check</h2><ul><li>All cameras share timecode with a clap backup.</li><li>A multicam clip exists with the correct camera count.</li><li>Switching follows the camera map and every shot's source is nameable.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note: this page draws on 5 gear trial and playback reviews under the listed model and firmware, once indoors and once outdoors; it discusses “Multicam Sync: Timecode and Clap”; no external laboratory test was run, and the conclusion may not transfer when conditions change.
<!-- SOURCES_END -->

