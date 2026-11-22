---
id: post.color.color-management.en
site: post
type: article
lang: en
translation_key: post.color.color-management
translation_status: reviewed
title: "Color Management: Input, Timeline, Output"
summary: "Set input, timeline, and output color spaces before monitors and LUTs."
slug: color-management
aliases: [color-management]
canonical_site: post
canonical_path: /en/color/color-management/
status: published
diagram: /images/diagrams/en/color-management.svg
diagram_alt: "Color Management: Input, Timeline, Output three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Set input, timeline, and output color spaces before monitors and LUTs.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/color-management.svg" alt="Color Management: Input, Timeline, Output three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Confirm whether the footage is S-Log3, HLG, or Rec.709, set the timeline input to match, output Rec.709 2.4, and monitor through a calibration LUT.</p>
<h2>Do this</h2>
<p>Color management fixes input, timeline, and output before monitoring or LUTs.</p><ol><li>Identify the footage: S-Log3, HLG, or Rec.709.</li><li>Set the matching timeline input and output Rec.709 2.4.</li><li>Monitor through a calibration LUT and check once with it off before delivery.</li></ol>
<h2>Avoid</h2>
<p>Do not use the wrong input LUT; once color is wrong, every later match is fake.</p>
<h2>Check</h2>
<ul><li>Timeline input matches the footage format; Log is not treated as Rec.709.</li><li>Output space matches the platform and scopes read correctly.</li><li>Turn off the monitor LUT and black or highlight levels do not jump.</li></ul>
