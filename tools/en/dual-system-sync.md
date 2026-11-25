---
id: tools.tutorial.dual-system-sync.en
site: tools
type: article
lang: en
translation_key: tools.tutorial.dual-system-sync
translation_status: reviewed
title: 'Dual-System Sync: Clap and Timecode'
summary: Clap first, then timecode; when both match, post does not have to listen
  to every take.
slug: dual-system-sync
aliases:
- dual-system-sync
canonical_site: tools
canonical_path: /en/article/dual-system-sync/
status: published
diagram: /images/diagrams/en/dual-system-sync.svg
diagram_alt: 'Structure diagram for Dual-System Sync: Clap and Timecode.'
diagram_caption: Watch “Clap three times while the recorder runs.” and “Sync by waveform,
  then by timecode.”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.capability.timecode.en
- tools.tutorial.sync-multicam.en
- tools.guide.buy-audio-field.en
verified: 2026-11-23
source_kind: experience
---

<p>Dual-system sync claps first, then checks timecode; both must align before post stops listening shot by shot.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/dual-system-sync.svg" alt="Structure diagram for Dual-System Sync: Clap and Timecode.">
  <figcaption>Watch “Clap three times while the recorder runs.” and “Sync by waveform, then by timecode.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">On set</h2><p>Clap three times and record it on the recorder. Sync by waveform, then timecode, and keep drift under one frame.</p></section><section><h2 id="section-2">Do this</h2><ol><li>Clap three times while the recorder runs.</li><li>Sync by waveform, then by timecode.</li><li>Pass only under one frame of drift.</li></ol></section><section><h2 id="section-3">Avoid</h2><p>Do not clap only once; if it misses, there is no second reference.</p></section><section><h2 id="section-4">Three causes</h2><p>For “Dual-System Sync: Clap and Timecode”, check three directions first. Change one variable, record a 30-second comparison, and see which link the change follows.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Cause</th><th>Signal on set</th><th>Five-minute test</th></tr></thead><tbody><tr><td>No clap</td><td>Camera and recorder share no marker, so sync is a guess</td><td>Clap before rolling; capture it in picture and sound</td></tr><tr><td>Timecode not synced</td><td>Wrong jam or frame rate makes drift grow</td><td>Jam once before the shoot</td></tr><tr><td>Wrong sample rate</td><td>48kHz and 44.1kHz mixed together change pitch</td><td>Use 48kHz throughout</td></tr></tbody></table></div></section><section><h2 id="section-5">On-set diagnosis</h2><ol><li>Align the clap in the NLE and check whether the waveform peak meets the picture.</li><li>Check frame rate and sample rate before aligning; unify first.</li><li>Inspect the last section for drift; drift means timecode or clock trouble.</li></ol></section><section><h2 id="section-6">Fix</h2><p>Dual-system sync does not rely on ears; it relies on a shared marker. A clap is the cheapest timecode; a timecode box is the steadier version.</p><ol><li>Clap for three seconds before every take and keep it in picture and sound.</li><li>When using timecode, jam before the shoot and check again at wrap.</li><li>Use 48kHz/24-bit and record a camera reference track.</li><li>After syncing, check the whole take, especially the last section.</li></ol></section><section><h2 id="section-7">Failure cases</h2><p>With “Dual-System Sync: Clap and Timecode”, these three moves make it worse. Pick one replacement action and do not change three variables at once.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Failure</th><th>Why it gets worse</th><th>Replace with</th></tr></thead><tbody><tr><td>Align by ear</td><td>Two or three frames off reads as bad lip-sync</td><td>Clap/timecode</td></tr><tr><td>Check only the start</td><td>The head syncs and the tail drifts</td><td>Check the end</td></tr><tr><td>Ignore sample rate</td><td>Pitch rises or falls</td><td>Use 48kHz</td></tr></tbody></table></div></section><section><h2 id="section-8">Acceptance table</h2><p>Acceptance is not “it feels better”; all four must be identifiable, playable and logged.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Log</th></tr></thead><tbody><tr><td>Clap</td><td>Every take has a shared marker</td><td>Footage check</td></tr><tr><td>Timecode</td><td>Start/end within one frame</td><td>Timecode readout</td></tr><tr><td>Sample rate</td><td>All 48kHz/24-bit</td><td>MediaInfo</td></tr><tr><td>Full length</td><td>The last section remains in sync</td><td>Play the end</td></tr></tbody></table></div></section><section><h2 id="section-9">One line for the set</h2><p>No clap means no evidence; no timecode means no certainty.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>every spec maps to one concrete shooting problem</li><li>weight, power and connections hold on a real rig</li><li>a 60-second test leaves one comparable number</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>specs without connections, power or weight</li><li>batteries, storage or body do not match after purchase</li><li>no 60-second test, so the problem arrives on the shoot</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Run a 60-second test with the gear you already own, measuring only “Clap three times while the recorder runs.”. Record two numbers: what you need and what the gear actually gives.</p></section>
<h2>Check</h2><ul><li>Three claps are recorded by both camera and recorder.</li><li>Waveform and timecode alignment are both performed.</li><li>The two tracks drift under one frame.</li></ul>
