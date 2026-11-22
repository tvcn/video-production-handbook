---
id: ai.generation.motion-control.en
site: ai
type: article
lang: en
translation_key: ai.generation.motion-control
translation_status: reviewed
title: "Motion Control: Give the Camera a Route"
summary: "Give the camera a route: where it starts, what it passes, where it stops. 'Camera moves' says nothing."
slug: motion-control
aliases: [motion-control]
canonical_site: ai
canonical_path: /en/generation/motion-control/
status: published
diagram: /images/diagrams/en/motion-control.svg
diagram_alt: "Motion Control: Give the Camera a Route three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Give the camera a route: where it starts, what it passes, where it stops. "Camera moves" says nothing.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/motion-control.svg" alt="Motion Control: Give the Camera a Route three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Write the camera path: push from the door to one meter from the table, hold two seconds. Use a reference video or keyframes; do not just say orbit.</p>
<h2>Do this</h2>
<p>Motion control starts with a camera path: where it starts, what it passes, where it stops. “Camera moves” says nothing.</p><ol><li>Write the path: push from the door to one meter from the table, hold two seconds.</li><li>Control with a reference video or keyframes, not just “orbit.”</li><li>Run three times to confirm the path repeats before changing a variable.</li></ol>
<h2>Avoid</h2>
<p>Do not write only “orbit” or “push”; without start and stop, the model wanders.</p>
<h2>Check</h2>
<ul><li>The prompt states start, path, and stop and can be drawn as a line.</li><li>All three outputs reach the same endpoint without changing direction mid-shot.</li><li>When speed or lens changes, the path itself still repeats.</li></ul>
