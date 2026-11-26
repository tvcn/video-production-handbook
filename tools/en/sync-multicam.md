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
review_due: '2027-02-26'
related: [tools.test.test-protocols, tools.capability.timecode, shoot.camera.composition]
source_kind: sourced
sources:
- S23
- S67
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
<p>Acceptance: all cameras film a stopwatch, pause on the same frame; readings should match. If not, return to timecode or frame rate.</p></section><section><h2 id="section-4">On set</h2><p>Sync timecode and clap once more. Build a multicam clip and switch using the camera map.</p></section><section><h2 id="section-5">Do this</h2><p>Multicam sync uses timecode first and a clap as backup; with both, the edit dares to cut.</p><ol><li>Sync timecode, then clap once more.</li><li>Build a multicam clip in the edit.</li><li>Switch by the camera map, not memory.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not rely on timecode alone; one camera off-code throws the whole multicam group.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> All cameras share timecode with a clap backup.</li><li><strong>2.</strong> A multicam clip exists with the correct camera count.</li><li><strong>3.</strong> Switching follows the camera map and every shot&#x27;s source is nameable.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“All cameras share timecode with a clap backup”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“A multicam clip exists with the correct camera…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not rely on timecode alone; one camera off-code throws the whole multicam group.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Run a 60-second test with the gear you already own, measuring only “Sync timecode, then clap once more.”. Record two numbers: what you need and what the gear actually gives.</p></section>
<h2>Check</h2><ul><li>All cameras share timecode with a clap backup.</li><li>A multicam clip exists with the correct camera count.</li><li>Switching follows the camera map and every shot's source is nameable.</li></ul>

<!-- SOURCES_START -->
## References and further reading

- [S23] [SMPTE Standards](https://www.smpte.org/standards) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Sync timecode first, clap as backup; with both, the edit can”) against Entry point for timecode, color, cinema and signal-chain standards; not a substitute for an on-set test.
- [S67] [IETF: RFC 8216: HTTP Live Streaming](https://datatracker.ietf.org/doc/html/rfc8216) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Sync timecode first, clap as backup; with both, the edit can”) against HLS segments, playlists and playback; not a substitute for an on-set test.
<!-- SOURCES_END -->

