---
id: tools.tutorial.export-h264.en
site: tools
type: article
lang: en
translation_key: tools.tutorial.export-h264
translation_status: reviewed
title: "H.264 Export: Bitrate and Compatibility"
summary: "Set platform and bitrate before two-pass encoding; low bitrate destroys motion first."
slug: export-h264
aliases: [export-h264]
canonical_site: tools
canonical_path: /en/tutorial/export-h264/
status: published
diagram: /images/diagrams/en/export-h264.svg
diagram_alt: "H.264 Export: Bitrate and Compatibility three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Set platform and bitrate before two-pass encoding; low bitrate destroys motion first.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/export-h264.svg" alt="H.264 Export: Bitrate and Compatibility three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Use 10 to 16 Mbps for 1080p and 35 to 45 Mbps for 4K. Two-pass encode, AAC audio at 192 kbps.</p>
<h2>Do this</h2>
<p>H.264 export fixes platform and bitrate first, then two-pass encoding; low bitrate destroys motion first.</p><ol><li>1080p at 10 to 16 Mbps, 4K at 35 to 45 Mbps.</li><li>Use two-pass encoding.</li><li>Audio AAC at 192 kbps.</li></ol>
<h2>Avoid</h2>
<p>Do not upload 4K at 5 Mbps; any motion turns into blocks.</p>
<h2>Check</h2>
<ul><li>Resolution and bitrate sit in the recommended range.</li><li>Encoding is two-pass, not single-pass rushed.</li><li>Audio is AAC 192 kbps and stays in sync.</li></ul>
