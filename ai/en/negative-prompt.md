---
id: ai.generation.negative-prompt.en
site: ai
type: article
lang: en
translation_key: ai.generation.negative-prompt
translation_status: reviewed
title: "Negative Prompt: Remove Before You Add"
summary: "Remove what ruins the frame first: flicker, extra fingers, garbled text, face morphing."
slug: negative-prompt
aliases: [negative-prompt]
canonical_site: ai
canonical_path: /en/generation/negative-prompt/
status: published
diagram: /images/diagrams/en/negative-prompt.svg
diagram_alt: "Negative Prompt: Remove Before You Add three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>Remove what ruins the frame first: flicker, extra fingers, garbled text, face morphing.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/negative-prompt.svg" alt="Negative Prompt: Remove Before You Add three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>List four categories: flicker, extra fingers, garbled text, warped faces. One negative term per category; do not stack fifty.</p>
<h2>Do this</h2>
<p>Negative prompts remove what breaks the image first: flicker, extra fingers, garbled text, face warping.</p><ol><li>List four classes: flicker, fingers, text, face.</li><li>Write one negative term per class, not fifty.</li><li>Run three times and confirm the term actually reduces that problem.</li></ol>
<h2>Avoid</h2>
<p>Do not stack a long negative list; conflicting constraints make the model less stable.</p>
<h2>Check</h2>
<ul><li>Negative terms cover four problem classes and each maps to a visible error.</li><li>The problem visibly decreases across three outputs, not just in your head.</li><li>Remove one term and the problem returns, proving it worked.</li></ul>
