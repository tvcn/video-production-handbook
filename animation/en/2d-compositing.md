---
id: animation.2d.2d-compositing.en
site: animation
type: article
lang: en
translation_key: animation.2d.2d-compositing
translation_status: reviewed
title: "2D Compositing: Separate Background, Character, Light"
summary: "Separate background, character, and light. Flattened layers force a full redraw for one change."
slug: 2d-compositing
aliases: [2d-compositing]
canonical_site: animation
canonical_path: /en/2d/2d-compositing/
status: published
diagram: /images/diagrams/en/2d-compositing.svg
diagram_alt: "2D Compositing: Separate Background, Character, Light three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Separate background, character, and light. Flattened layers force a full redraw for one change.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/2d-compositing.svg" alt="2D Compositing: Separate Background, Character, Light three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Use four layers: background, character, foreground, and light. Grade each separately and keep shadows off the character layer.</p>
<h2>Do this</h2>
<p>2D compositing separates background, character, foreground, and light; one flattened image means redrawing everything for one change.</p><ol><li>Use four layers: background, character, foreground, light effect.</li><li>Grade each layer separately and keep shadows off the character layer.</li><li>Composite position first, then light and shadow.</li></ol>
<h2>Avoid</h2>
<p>Do not draw everything on one layer; one change forces a full redraw.</p>
<h2>Check</h2>
<ul><li>Background, character, foreground, and light are separate layers with clear structure.</li><li>Shadows live on their own layer, not baked into the character.</li><li>Changing an action moves only the character layer; background and light stay.</li></ul>
