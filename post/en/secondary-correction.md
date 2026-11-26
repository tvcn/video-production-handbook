---
id: post.color.secondary-correction.en
site: post
type: article
lang: en
translation_key: post.color.secondary-correction
translation_status: reviewed
title: 'Secondary Correction: Change One Area'
summary: 'Secondary correction changes one area: skin, sky, wardrobe. More areas,
  more fake.'
slug: secondary-correction
aliases:
- secondary-correction
canonical_site: post
canonical_path: /en/article/secondary-correction/
status: published
diagram: /images/diagrams/en/secondary-correction.svg
diagram_alt: 'Structure diagram for Secondary Correction: Change One Area.'
diagram_caption: 'Watch “Choose one region: face or sky.” and “Feather the qualifier
  10 to 20 pixels and”; judge whether removing one shot makes the scene faster rather
  than muddier.'
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.sound.sound, post.editing.sound-bridge, shoot.camera.composition]
source_kind: sourced
sources:
- S30
- S24
---
<p>Use masks, HSL or qualifiers to move one range: sky, skin, clothing or background. Primary first, secondary second; without a primary, secondary locks the cast in.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/secondary-correction.svg" alt="Structure diagram for Secondary Correction: Change One Area.">
  <figcaption>Watch “Choose one region: face or sky.” and “Feather the qualifier 10 to 20 pixels and”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Secondary only changes the selected area</h2><p>One node, one purpose, named clearly. With too many nodes, disable all and re-enable one by one to find what actually works.</p><h2 id="section-2">Limits</h2><p>Secondary is not a local filter. Feather the edge and track motion; hard edges and drifting masks read as fake immediately.</p></section><section><h2 id="section-3">On set</h2><p>Pick one area: face or sky. Feather the qualifier 10 to 20 pixels, keep the change under five percent, and toggle it off to check.</p></section><section><h2 id="section-4">Do this</h2><p>Secondary correction changes one region: face, sky, or clothing. The more regions, the faker it looks.</p><ol><li>Choose one region: face or sky.</li><li>Feather the qualifier 10 to 20 pixels and keep the change under five percent.</li><li>Toggle the node and check for halo or color patch at the edge.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not change five regions at once; every edge leaves a trace.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> Only one region moved and neighboring colors are untouched.</li><li><strong>2.</strong> Feathering looks natural with no halo, jagged edge, or patch.</li><li><strong>3.</strong> With the node off, the audience cannot tell which area was isolated.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“Only one region moved and neighboring colors a…”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“Feathering looks natural with no halo, jagged…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not change five regions at once; every edge leaves a trace.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Choose one region: face or sky.”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>Only one region moved and neighboring colors are untouched.</li><li>Feathering looks natural with no halo, jagged edge, or patch.</li><li>With the node off, the audience cannot tell which area was isolated.</li></ul>

<!-- SOURCES_START -->
## References and further reading

- [S30] [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Secondary correction changes one area: skin, sky, wardrobe. ”) against Official entry for editing, grading, Fusion and delivery; not a substitute for an on-set test.
- [S24] [ACESCentral: ACES](https://acescentral.com/) — Accessed 2026-11-27. Used to check the terminology and public context in the opening paragraph (“Secondary correction changes one area: skin, sky, wardrobe. ”) against ACES color encoding, ACEScg and delivery/archive workflows; not a substitute for an on-set test.
<!-- SOURCES_END -->

