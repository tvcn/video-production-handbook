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
authors: ["TVCN Animation Desk"]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
sources: [S12, S28, S34]
test_context: "Review setup: Windows 11; public Blender 4.x / After Effects 2025 workflows; not every version behaves the same."
known_failures: "Known failures: plugin/version gaps break rigs or renders; font and asset licenses need separate checks."
verified: 2026-11-22
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
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S12]</span> Britannica: Animation</li><li><span class="mono">[S28]</span> Netflix Partner Help</li><li><span class="mono">[S34]</span> Adobe Premiere Pro Guide</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
