---
id: main.method.method-ai-consistency.en
site: main
type: template
lang: en
translation_key: main.method.method-ai-consistency
translation_status: reviewed
title: AI Characters Drift
summary: Build a character sheet and carry one reference into every shot.
slug: method-ai-consistency
aliases:
- method-ai-consistency
canonical_site: main
canonical_path: /en/article/method-ai-consistency/
status: published
diagram: /images/diagrams/en/method-ai-consistency.svg
diagram_alt: Structure diagram for AI Characters Drift.
diagram_caption: 'Watch “Lock ten traits: age, hair, face shape, brows,” and “Generate
  front, side, and back views; choose one”; judge whether the symptom can be restated
  as one observable sentence.'
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Editorial
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [main.method.method-ai-rights, main.method.method-ai-uncanny, context.history.16mm]
sources:
- S19
- S20
- S04
source_kind: sourced
---
<p>Generate front, profile and looking-down views and compare them in one image. If cheekbones, nose bridge, hairline and wardrobe do not align, do not start batch generation. Fix the references, then the prompt. When not to force it For long dialogue, complex expressions or sharing the frame with a real actor, shoot a live reference first and use generation for wides and inserts. Do not hide drift with “we&#x27;ll match it in post.”</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/method-ai-consistency.svg" alt="Structure diagram for AI Characters Drift.">
  <figcaption>Watch “Lock ten traits: age, hair, face shape, brows,” and “Generate front, side, and back views; choose one”; judge whether the symptom can be restated as one observable sentence.</figcaption>
</figure>
<!-- DIAGRAM_END -->


<section><h2 id="section-1">Lock four things</h2>
<ul><li><strong>Face:</strong> one front, one profile and one three-quarter reference; fix hair and brow shape. Do not rely on a text description each time.</li><li><strong>Wardrobe:</strong> material, color, collar and buttons in the character sheet; do not switch to a near-match color in the same scene.</li><li><strong>Light:</strong> key direction, color temperature and softness in the shot card; change the light before changing the face.</li><li><strong>Lens:</strong> focal length and shot size change the face. The same character on a wide and a tele looks like two people; lock the lens first.</li></ul>
<h2 id="section-2">Three-angle test</h2>
<p>Generate front, profile and looking-down views and compare them in one image. If cheekbones, nose bridge, hairline and wardrobe do not align, do not start batch generation. Fix the references, then the prompt.</p>
<h2 id="section-3">When not to force it</h2>
<p>For long dialogue, complex expressions or sharing the frame with a real actor, shoot a live reference first and use generation for wides and inserts. Do not hide drift with “we'll match it in post.”</p></section><section><h2 id="section-4">On set</h2><p>Use a character sheet, three views, and one reference. Compare face, wardrobe, and hair shot by shot.</p></section><section><h2 id="section-5">Do this</h2><p>AI character drift: build a character sheet and three views, then carry the same reference into every shot.</p><ol><li>Lock ten traits: age, hair, face shape, brows, nose, wardrobe, shoes, accessories, build, skin tone.</li><li>Generate front, side, and back views; choose one as the master.</li><li>Every shot carries the same reference and the same description; change only action and camera.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not rewrite the adjectives for every shot; each one grows a different person.</p></section><section><h2 id="section-7">Boundary</h2><p>This page only covers “AI Characters Drift”; it does not replace AI Rights Are Unclear, AI Looks Uncanny, 16mm: Cinema Left the Theater. When the problem belongs to one of those pages, use that page instead of adding more parameters here.</p></section><section><h2 id="section-8">Alternative</h2><p>If “Lock ten traits: age, hair, face shape, brows, nose, wardrobe, shoes, accessories, build, skin tone” is not the main problem, start with “Generate front, side, and back views; choose one as the master”; only upgrade after both hold.</p></section><section><h2 id="section-9">60-second test</h2><p>Run one 60-second test against check 1: Ten traits are locked and one three-view master is chosen. If check 2 (Every shot carries the same reference and the same description) does not change, do not add gear or budget.</p></section>
<h2 id="section-12">Check</h2><ul><li>Ten traits are locked and one three-view master is chosen.</li><li>Every shot carries the same reference and the same description.</li><li>Only action and camera change; the adjectives are not rewritten.</li></ul>


> Intent split: this page covers the practical details of “AI Characters Drift”; start with <a href="https://tools.tvcn.org/article/deep-ai-toolchain/">AI toolchain: generation, voice, render</a> for the cluster-level judgement, then return here.

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## References and further reading

- [S19] [Generative Adversarial Nets (2014)](https://arxiv.org/abs/1406.2661) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Lock four things” section against the original GAN paper, not a product review; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S20] [Denoising Diffusion Probabilistic Models (2020)](https://arxiv.org/abs/2006.11239) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Lock four things” section against the original DDPM paper, not a product review; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S04] [CAC: Interim Measures for Generative AI Services](https://www.cac.gov.cn/2023-07/13/c_1690898327029107.htm) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Three failures” section against China's generative-AI service rules, not technical implementation; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

