---
id: animation.3d.layout.en
site: animation
type: article
lang: en
translation_key: animation.3d.layout
translation_status: reviewed
title: "Layout: Camera and Asset Handoff"
summary: "Layout locks camera, scale, and asset versions before animation. A vague handoff makes animators guess."
slug: layout
aliases: [layout]
canonical_site: animation
canonical_path: /en/3d/layout/
status: published
diagram: /images/diagrams/en/layout.svg
diagram_alt: "Layout: Camera and Asset Handoff three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Layout locks camera, scale, and asset versions before animation. A vague handoff makes animators guess.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/layout.svg" alt="Layout: Camera and Asset Handoff three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Lock three things before handoff: camera, character scale, and asset version. Put the version in the file header and animate to the layout.</p>
<h2>Do this</h2>
<p>Layout locks camera, proportion, and asset version before handoff; unclear handoff makes animators guess.</p><ol><li>Lock three things: camera, character scale, asset version.</li><li>Write the version number in the file header.</li><li>Animate to the layout without changing the camera.</li></ol>
<h2>Avoid</h2>
<p>Do not leave the camera live in layout; changing it after animation starts is rework.</p>
<h2>Check</h2>
<ul><li>Camera, character scale, and asset version are locked and versioned.</li><li>The file header shows version and dependencies so animators do not guess.</li><li>Animation does not change the camera and the final shot matches layout.</li></ul>
