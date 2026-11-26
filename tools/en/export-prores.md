---
id: tools.tutorial.export-prores.en
site: tools
type: article
lang: en
translation_key: tools.tutorial.export-prores
translation_status: reviewed
title: 'ProRes Export: Archive and Delivery'
summary: ProRes is for archive and regrading, not direct upload everywhere; big files,
  but editable.
slug: export-prores
aliases:
- export-prores
canonical_site: tools
canonical_path: /en/article/export-prores/
status: published
diagram: /images/diagrams/en/export-prores.svg
diagram_alt: 'Structure diagram for ProRes Export: Archive and Delivery.'
diagram_caption: Watch “Archive in ProRes 422 HQ.” and “Deliver in 422.”; judge whether
  the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [tools.tutorial.exposure-check, tools.capability.field-monitor, shoot.camera.composition]
verified: 2026-11-23
source_kind: sourced
sources:
- S65
- S29
- S35
---
<p>ProRes is for archive and regrading, not direct upload to every platform; files are large but re-editable.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/export-prores.svg" alt="Structure diagram for ProRes Export: Archive and Delivery.">
  <figcaption>Watch “Archive in ProRes 422 HQ.” and “Deliver in 422.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">On set</h2><p>Archive in ProRes 422 HQ and deliver 422. Do not upload ProRes to platforms; the files are too large.</p></section><section><h2 id="section-2">Do this</h2><ol><li>Archive in ProRes 422 HQ.</li><li>Deliver in 422.</li><li>Do not upload ProRes to platforms; the file is too large.</li></ol></section><section><h2 id="section-3">Avoid</h2><p>Do not treat ProRes as a platform delivery format; it gets compressed back to H.264 anyway.</p></section><section><h2 id="section-4">Three causes</h2><p>For “ProRes Export: Archive and Delivery”, check three directions first. Change one variable, record a 30-second comparison, and see which link the change follows.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Cause</th><th>Signal on set</th><th>Five-minute test</th></tr></thead><tbody><tr><td>Wrong profile</td><td>Using ProRes 422 LT as a master leaves no room for grading</td><td>Archive with 422 HQ or 4444</td></tr><tr><td>Wrong colour space</td><td>Mislabeled Log/Rec.709 shifts colour downstream</td><td>Follow the project colour pipeline</td></tr><tr><td>Not enough storage</td><td>ProRes files are large and the write fails halfway</td><td>Reserve twice the space and verify</td></tr></tbody></table></div></section><section><h2 id="section-5">On-set diagnosis</h2><ol><li>Decide whether the file is an archive, a grading intermediate or a web deliverable.</li><li>Use MediaInfo to check profile, colour tags and audio channels.</li><li>Import into the target NLE and confirm no transcode and no colour shift.</li></ol></section><section><h2 id="section-6">Fix</h2><p>ProRes is an intermediate/archive format, not a web delivery format. Decide its place in the pipeline before choosing a profile.</p><ol><li>Archive/grading: ProRes 422 HQ; alpha or maximum: 4444.</li><li>Proxy/offline: ProRes Proxy or 422 LT; never use them as the final master.</li><li>Keep source frame rate, colour space and audio channels; do not change them here.</li><li>Checksum the export to confirm the file is complete.</li></ol></section><section><h2 id="section-7">Failure cases</h2><p>With “ProRes Export: Archive and Delivery”, these three moves make it worse. Pick one replacement action and do not change three variables at once.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Failure</th><th>Why it gets worse</th><th>Replace with</th></tr></thead><tbody><tr><td>Upload ProRes to a platform</td><td>The file is huge and gets rejected or transcoded</td><td>Make a separate H.264 deliverable</td></tr><tr><td>Use LT as master</td><td>There is too little room for grading and shadows break</td><td>Use HQ for the master</td></tr><tr><td>Ignore audio</td><td>Wrong audio channels are discovered in post</td><td>Check before export</td></tr></tbody></table></div></section><section><h2 id="section-8">Acceptance table</h2><p>Acceptance is not “it feels better”; all four must be identifiable, playable and logged.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Log</th></tr></thead><tbody><tr><td>Profile</td><td>Matches the pipeline position</td><td>MediaInfo</td></tr><tr><td>Colour</td><td>Tags match the project</td><td>Import into NLE</td></tr><tr><td>Integrity</td><td>Checksum matches and the last frame decodes</td><td>Verify</td></tr><tr><td>Audio</td><td>Channels and sample rate are correct</td><td>Listen separately</td></tr></tbody></table></div></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> Archive is ProRes 422 HQ and regradable.</li><li><strong>2.</strong> Client delivery is 422 within the contracted size.</li><li><strong>3.</strong> A separate H.264 upload exists; ProRes is not uploaded.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“Archive is ProRes 422 HQ and regradable”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“Client delivery is 422 within the contracted s…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not treat ProRes as a platform delivery format; it gets compressed back to H.264 anyway.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Run a 60-second test with the gear you already own, measuring only “Archive in ProRes 422 HQ.”. Record two numbers: what you need and what the gear actually gives.</p></section>
<h2>Check</h2><ul><li>Archive is ProRes 422 HQ and regradable.</li><li>Client delivery is 422 within the contracted size.</li><li>A separate H.264 upload exists; ProRes is not uploaded.</li></ul>

<section><h2>Boundary</h2><p>This page only covers “ProRes Export: Archive and Delivery”; it does not replace Exposure Check: Waveform, Zebra, False Color, Field Monitor: Brightness, Scopes, LUT, Composition: Tell the Eye Where to Look. When the problem belongs to one of those pages, use that page instead of adding more parameters here.</p></section>
<!-- SOURCES_START -->
## References and further reading

- [S65] [ITU-T H.264](https://www.itu.int/rec/T-REC-H.264/en) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “On set” section against H.264 codec standard, not platform upload rules; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S29] [YouTube: Upload Encoding Specs](https://support.google.com/youtube/answer/1722171) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Do this” section against YouTube upload encoding recommendations, not creative standards; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

