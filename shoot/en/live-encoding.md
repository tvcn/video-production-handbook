---
id: shoot.live.live-encoding.en
site: shoot
type: article
lang: en
translation_key: shoot.live.live-encoding
translation_status: reviewed
title: "Live Encoding: Bitrate, Uplink, Backup"
summary: "Calculate uplink before bitrate, and always keep a local recording as backup."
slug: live-encoding
aliases: [live-encoding]
canonical_site: shoot
canonical_path: /en/live/live-encoding/
status: published
diagram: /images/diagrams/en/live-encoding.svg
diagram_alt: "Live Encoding: Bitrate, Uplink, Backup three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Calculate uplink before bitrate, and always keep a local recording as backup.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/live-encoding.svg" alt="Live Encoding: Bitrate, Uplink, Backup three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Measure upload speed first: you need 1.5 times the target bitrate for headroom. Set a primary stream and a hotspot backup, and record a local high-bitrate copy.</p>
<h2>Do this</h2>
<p>Live encoding starts with uplink bandwidth, then bitrate. Always keep a local recording as backup.</p><ol><li>Measure upload speed; 1.5 times the target bitrate is the safe margin.</li><li>Set a primary stream, a hotspot backup, and a high-bitrate local recording.</li><li>Rehearse a disconnection and record the dropout time and recovery steps.</li></ol>
<h2>Avoid</h2>
<p>Do not run one path or treat the stream as one-shot; a dropout kills more than soft image quality.</p>
<h2>Check</h2>
<ul><li>Uplink is at least 1.5 times the target bitrate and the margin is recorded.</li><li>When the primary drops, the hotspot backup and local recording still run.</li><li>The rehearsal log shows the dropout time, cause, and recovery duration.</li></ul>
