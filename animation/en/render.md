---
id: animation.3d.render.en
site: animation
type: article
lang: en
translation_key: animation.3d.render
translation_status: reviewed
title: "Render: Samples and Noise"
summary: "Samples and noise come before resolution; unresolved noise at 4K is just bigger dirt."
slug: render
aliases: [render]
canonical_site: animation
canonical_path: /en/3d/render/
status: published
diagram: /images/diagrams/en/render.svg
diagram_alt: "Render: Samples and Noise three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Samples and noise come before resolution; unresolved noise at 4K is just bigger dirt.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/render.svg" alt="Render: Samples and Noise three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Render at 50 percent resolution with low samples to see where noise lives. Raise light and material samples separately; do not just raise the total.</p>
<h2>Do this</h2>
<p>Rendering checks samples and noise before resolution; unresolved noise at 4K is just bigger dirt.</p><ol><li>Render at 50 percent resolution and low samples to see noise distribution.</li><li>Adjust light samples and material samples separately.</li><li>Do not only raise total samples; find which source causes the noise.</li></ol>
<h2>Avoid</h2>
<p>Do not brute-force noise with total samples; without the source, render time burns.</p>
<h2>Check</h2>
<ul><li>A 50 percent low-sample pass shows whether noise comes from light or material.</li><li>Light and material samples were adjusted separately.</li><li>Final noise is traced to a specific source, not brute-forced.</li></ul>
