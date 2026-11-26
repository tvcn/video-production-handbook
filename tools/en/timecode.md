---
id: tools.capability.timecode.en
site: tools
type: tool
lang: en
translation_key: tools.capability.timecode
translation_status: reviewed
title: 'Timecode: Sync Without Guessing'
summary: Timecode syncs cameras and recorders in the first minute of post; without
  it, sync is luck.
slug: timecode
aliases:
- timecode
canonical_site: tools
canonical_path: /en/article/timecode/
status: published
diagram: /images/diagrams/en/timecode.svg
diagram_alt: 'Structure diagram for Timecode: Sync Without Guessing.'
diagram_caption: Watch “Jam the recorder and camera to the same” and “Shoot a ten-second
  test.”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.proposal.treatment, tools.capability.tripod, shoot.camera.composition]
source_kind: experience
---
<p>For one camera, short clips or easy manual alignment in post, timecode is unnecessary. More devices make the sync chain more fragile.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/timecode.svg" alt="Structure diagram for Timecode: Sync Without Guessing.">
  <figcaption>Watch “Jam the recorder and camera to the same” and “Shoot a ten-second test.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">What to compare first</h2><ul><li><strong>Sync method:</strong> confirm jam sync, wireless sync or audio timecode; different cameras support different modes.</li><li><strong>Drift:</strong> record 30 minutes and compare again; syncing only at start is not a test.</li><li><strong>Backup:</strong> timecode does not replace a clap; cameras without timecode still need manual sync.</li></ul><h2 id="section-2">When not to use it</h2><h2 id="section-3">Multi-camera sync: jam before the shoot, compare after wrap</h2>
<p>Timecode is not “set once.” Jam sync before the first take and compare before wrap; battery changes and sleep can drift.</p>
<ol><li>Choose one master camera and jam the others; log the jam time.</li><li>Each camera films a clap or hand clap with timecode as a backup sync point.</li><li>Before wrap, compare head and tail timecode. If drift exceeds one frame, align by clap in post, not by timecode.</li></ol>
<p>Acceptance: put all cameras on one timeline and pick a random action; frame offset should be one frame or less. More means drift.</p></section><section><h2 id="section-4">On set</h2><p>Jam the recorder and camera to the same timecode and shoot ten seconds. Sync in post and check for less than one frame of drift.</p></section><section><h2 id="section-5">Do this</h2><p>Timecode aligns multicamera and recorder in the first minute of post; without it, syncing is luck.</p><ol><li>Jam the recorder and camera to the same timecode.</li><li>Shoot a ten-second test.</li><li>Sync in post and check drift under one frame.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not jam once and shoot all day; drift shows up in the afternoon.</p></section>
<h2>Check</h2><ul><li>Recorder and camera display the same timecode.</li><li>The ten-second test syncs under one frame in post.</li><li>A second jam is logged mid-shoot, not only one at the start.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note: this page draws on 6 gear trial and playback reviews under the listed model and firmware, once indoors and once outdoors; it discusses “Timecode: Sync Without Guessing”; no external laboratory test was run, and the conclusion may not transfer when conditions change.
<!-- SOURCES_END -->

