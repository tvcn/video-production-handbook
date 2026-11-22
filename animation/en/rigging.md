---
id: animation.3d.rigging.en
site: animation
type: article
lang: en
translation_key: animation.3d.rigging
translation_status: reviewed
title: "Rigging: Make the Joints Turn"
summary: "Rigging makes joints turn correctly before skin looks good; if the joint fails, weights cannot save it."
slug: rigging
aliases: [rigging]
canonical_site: animation
canonical_path: /en/3d/rigging/
status: published
diagram: /images/diagrams/en/rigging.svg
diagram_alt: "Rigging: Make the Joints Turn three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Rigging makes joints turn correctly before skin looks good; if the joint fails, weights cannot save it.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/rigging.svg" alt="Rigging: Make the Joints Turn three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Rotate shoulder, elbow, and knee for ten frames each. If the mesh collapses, fix weights before adding bones.</p>
<h2>Do this</h2>
<p>Rigging makes joints rotate correctly before skin deforms nicely; if it cannot turn, weights do not matter.</p><ol><li>Rotate shoulder, elbow, and knee, ten frames each.</li><li>If the mesh collapses, fix weights before adding bones.</li><li>Only animate after all three joints reach their limits.</li></ol>
<h2>Avoid</h2>
<p>Do not add bones to fix collapse; wrong weights get messier with more bones.</p>
<h2>Check</h2>
<ul><li>Shoulder, elbow, and knee reach their limits without mesh collapse.</li><li>Collapse was fixed with weights, not covered by extra bones.</li><li>Ten-frame rotation playback shows no tearing or pinching.</li></ul>
