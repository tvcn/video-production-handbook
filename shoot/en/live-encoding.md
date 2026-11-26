---
id: shoot.live.live-encoding.en
site: shoot
type: article
lang: en
translation_key: shoot.live.live-encoding
translation_status: reviewed
title: 'Live Encoding: Bitrate, Uplink, Backup'
summary: Calculate uplink before bitrate, and always keep a local recording as backup.
slug: live-encoding
aliases:
- live-encoding
canonical_site: shoot
canonical_path: /en/article/live-encoding/
status: published
diagram: /images/diagrams/en/live-encoding.svg
diagram_alt: 'Structure diagram for Live Encoding: Bitrate, Uplink, Backup.'
diagram_caption: Watch “Measure upload speed; 1.5 times the target bitrate” and “Set
  a primary stream, a hotspot backup, and”; judge whether highlights, skin and sound
  survive together.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Shoot Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [shoot.exposure.log-footage, shoot.lighting.mixed-light, post.color.color]
source_kind: experience
---
<p>Set bitrate at 70% of upload, keyframe every two seconds, audio 128–192 kbps. High resolution without bitrate turns motion into blocks; stable 720p beats stuttering 4K.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/live-encoding.svg" alt="Structure diagram for Live Encoding: Bitrate, Uplink, Backup.">
  <figcaption>Watch “Measure upload speed; 1.5 times the target bitrate” and “Set a primary stream, a hotspot backup, and”; judge whether highlights, skin and sound survive together.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Live starts with staying up, then looking good</h2><p>Test ten minutes before: dropped frames, latency, audio sync, backup network. Do not discover upload limits after going live.</p><h2 id="section-2">Limits</h2><p>Live is not recorded. Post cannot fix it; state information once, prepare captions and graphics in advance.</p></section><section><h2 id="section-3">On set</h2><p>Measure upload speed first: you need 1.5 times the target bitrate for headroom. Set a primary stream and a hotspot backup, and record a local high-bitrate copy.</p></section><section><h2 id="section-4">Do this</h2><p>Live encoding starts with uplink bandwidth, then bitrate. Always keep a local recording as backup.</p><ol><li>Measure upload speed; 1.5 times the target bitrate is the safe margin.</li><li>Set a primary stream, a hotspot backup, and a high-bitrate local recording.</li><li>Rehearse a disconnection and record the dropout time and recovery steps.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not run one path or treat the stream as one-shot; a dropout kills more than soft image quality.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>highlights are not clipped and shadows keep recoverable detail</li><li>skin stays consistent across camera angles</li><li>sound has an independent track, not just the on-camera mic</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>exposure is right but the light has no direction</li><li>sound relies on the camera mic and dies in a noisy room</li><li>crossing the line leaves the audience without a map</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Shoot three 10-second takes by the same window, changing only “Measure upload speed; 1.5 times the target bitrate”. Compare highlights, skin and background; keep the one that is editable.</p></section>
<h2>Check</h2><ul><li>Uplink is at least 1.5 times the target bitrate and the margin is recorded.</li><li>When the primary drops, the hotspot backup and local recording still run.</li><li>The rehearsal log shows the dropout time, cause, and recovery duration.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note: this page draws on 5 on-set shoot and playback review reviews under one camera, available light or one key light; it discusses “Live Encoding: Bitrate, Uplink, Backup”; no external laboratory test was run, and the conclusion may not transfer when conditions change.
<!-- SOURCES_END -->

