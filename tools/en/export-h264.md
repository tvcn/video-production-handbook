---
id: tools.tutorial.export-h264.en
site: tools
type: article
lang: en
translation_key: tools.tutorial.export-h264
translation_status: reviewed
title: 'H.264 Export: Bitrate and Compatibility'
summary: Set platform and bitrate before two-pass encoding; low bitrate destroys motion
  first.
slug: export-h264
aliases:
- export-h264
canonical_site: tools
canonical_path: /en/article/export-h264/
status: published
diagram: /images/diagrams/en/export-h264.svg
diagram_alt: 'Structure diagram for H.264 Export: Bitrate and Compatibility.'
diagram_caption: Watch “1080p at 10 to 16 Mbps, 4K at” and “Use two-pass encoding.”;
  judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.tutorial.export-prores.en
- tools.delivery.delivery-specs.en
- tools.guide.export-fail-fix.en
verified: 2026-11-23
source_kind: experience
---

<p>H.264 export fixes platform and bitrate first, then two-pass encoding; low bitrate destroys motion first.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/export-h264.svg" alt="Structure diagram for H.264 Export: Bitrate and Compatibility.">
  <figcaption>Watch “1080p at 10 to 16 Mbps, 4K at” and “Use two-pass encoding.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">On set</h2><p>Use 10 to 16 Mbps for 1080p and 35 to 45 Mbps for 4K. Two-pass encode, AAC audio at 192 kbps.</p></section><section><h2 id="section-2">Do this</h2><ol><li>1080p at 10 to 16 Mbps, 4K at 35 to 45 Mbps.</li><li>Use two-pass encoding.</li><li>Audio AAC at 192 kbps.</li></ol></section><section><h2 id="section-3">Avoid</h2><p>Do not upload 4K at 5 Mbps; any motion turns into blocks.</p></section><section><h2 id="section-4">Three causes</h2><p>For “H.264 Export: Bitrate and Compatibility”, check three directions first. Change one variable, record a 30-second comparison, and see which link the change follows.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Cause</th><th>Signal on set</th><th>Five-minute test</th></tr></thead><tbody><tr><td>Bitrate too low</td><td>Motion and large detail block up, and platform recompression makes it worse</td><td>Test 12/20/35Mbps on a two-second high-motion clip</td></tr><tr><td>Incompatible parameters</td><td>Colour, frame rate, pixel aspect and platform spec disagree</td><td>Check MediaInfo against the delivery spec</td></tr><tr><td>Audio out of spec</td><td>Wrong sample rate, channels or bitrate causes silence or distortion</td><td>Inspect the audio track separately</td></tr></tbody></table></div></section><section><h2 id="section-5">On-set diagnosis</h2><ol><li>Use MediaInfo to read codec, profile, level, bitrate, colour tags and audio parameters.</li><li>Upload a thirty-second test to the target platform and check clarity and colour.</li><li>Compare the same frame in source and export for unintended crop or stretch.</li></ol></section><section><h2 id="section-6">Fix</h2><p>H.264 is not about the smallest file; it is about correct playback on the target platform. Set the delivery spec first, then choose bitrate and profile.</p><ol><li>For web delivery use H.264 High Profile, 4:2:0 8-bit, AAC 48kHz.</li><li>Use 12–20Mbps for 1080p and 35–60Mbps for 4K; go higher for heavy motion.</li><li>Use two-pass or VBV limits so peaks do not blow the budget.</li><li>After export, check first frame, last frame, audio sync and platform playback.</li></ol></section><section><h2 id="section-7">Failure cases</h2><p>With “H.264 Export: Bitrate and Compatibility”, these three moves make it worse. Pick one replacement action and do not change three variables at once.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Failure</th><th>Why it gets worse</th><th>Replace with</th></tr></thead><tbody><tr><td>Watch file size only</td><td>The file is small and the detail and audio are broken</td><td>Test against platform spec</td></tr><tr><td>Deliver 4:4:4</td><td>The platform does not support it and recompresses or rejects</td><td>Deliver 4:2:0</td></tr><tr><td>Ignore colour tags</td><td>Colour looks grey or oversaturated on the platform</td><td>Write correct matrix/primaries</td></tr></tbody></table></div></section><section><h2 id="section-8">Acceptance table</h2><p>Acceptance is not “it feels better”; all four must be identifiable, playable and logged.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Log</th></tr></thead><tbody><tr><td>Codec</td><td>H.264 High with a matching level</td><td>MediaInfo</td></tr><tr><td>Bitrate</td><td>No blocking in high motion</td><td>Thirty-second upload</td></tr><tr><td>Audio</td><td>AAC 48kHz, correct channels, no clipping</td><td>Listen separately</td></tr><tr><td>Colour</td><td>Platform playback matches the source</td><td>Compare with source</td></tr></tbody></table></div></section><figure class="article-audio"><audio controls preload="none" src="../../../assets/audio/en/tool-export-h264.en.mp3"></audio><figcaption>20-second audio demo: one check point and the most common failure. Transcript and steps are in the article.</figcaption></figure><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>every spec maps to one concrete shooting problem</li><li>weight, power and connections hold on a real rig</li><li>a 60-second test leaves one comparable number</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>specs without connections, power or weight</li><li>batteries, storage or body do not match after purchase</li><li>no 60-second test, so the problem arrives on the shoot</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Run a 60-second test with the gear you already own, measuring only “1080p at 10 to 16 Mbps, 4K at”. Record two numbers: what you need and what the gear actually gives.</p></section>
<h2>Check</h2><ul><li>Resolution and bitrate sit in the recommended range.</li><li>Encoding is two-pass, not single-pass rushed.</li><li>Audio is AAC 192 kbps and stays in sync.</li></ul>
