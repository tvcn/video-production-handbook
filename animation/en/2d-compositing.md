---
id: animation.2d.2d-compositing.en
site: animation
type: article
lang: en
translation_key: animation.2d.2d-compositing
translation_status: reviewed
title: '2D Compositing: Separate Background, Character, Light'
summary: Separate background, character, and light. Flattened layers force a full redraw for one change.
slug: 2d-compositing
aliases:
- 2d-compositing
canonical_site: animation
canonical_path: /en/article/2d-compositing/
status: published
diagram: /images/diagrams/en/2d-compositing.svg
diagram_alt: 'Structure diagram for 2D Compositing: Separate Background, Character, Light.'
diagram_caption: 'Watch “Use four layers: background, character, foreground, light effect.” and “Grade each layer separately and keep shadows off”; judge whether the speed split between foreground, midground and background reads in one move.'
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.3d.3d-pipeline, animation.pipeline.animatic-pipeline, formats.documentary.documentary-template]
source_kind: sourced
sources:
- S63
- S62
- S59

---
<p>The giveaway is inconsistent line weight and color. Unify stroke width, anti-aliasing and value range before lighting; adjust each layer separately, not with a global filter.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/2d-compositing.svg" alt="Structure diagram for 2D Compositing: Separate Background, Character, Light.">
  <figcaption>Watch “Use four layers: background, character, foreground, light effect.” and “Grade each layer separately and keep shadows off”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">2D compositing aligns line and color first</h2><p>Check with a comparison frame: foreground and background blacks and whites must match; if not, it looks pasted on.</p><h2 id="section-2">Limits</h2><p>Compositing is not adding effects. No amount of effects fixes misaligned lines; align the base layers first.</p><h2 id="section-3">2D compositing: fix edges, then color, then light</h2>
<p>Compositing problems are usually order problems, not “not enough effect.” Color before edge work magnifies edge fringes. Light before edge work covers seams. The order is: clean plate → edge → color match → light → output.</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>Step</th><th>Check</th><th>Failure signal</th></tr></thead><tbody>
<tr><td>Edge</td><td>Inspect at 1:1 pixels</td><td>White/black fringe, jaggies</td></tr>
<tr><td>Color</td><td>Skin and sky within one scene</td><td>Foreground warmer or greener than background</td></tr>
<tr><td>Light</td><td>Light direction matches</td><td>Glow passes through an occluder</td></tr>
<tr><td>Output</td><td>Review at each delivery size</td><td>Edge vanishes small, seam shows large</td></tr>
</tbody></table></div>
<h3>Project-level checks</h3>
<ol><li>Toggle every element and make a list. One missing shadow or contact shadow makes the layer float.</li><li>Use the smallest edge setting, several light passes. One maxed-out pass eats detail.</li><li>Match color on neutral gray first, then skin. Eyes alone drift on a colored background.</li><li>Put the light pass on top but mask it behind foreground objects; otherwise light goes through walls.</li></ol>
<p>Before delivery, ask someone else to watch ten seconds and answer only “what floats?” After staring for hours, you stop seeing seams.</p></section><section><h2 id="section-4">On set</h2><p>Use four layers: background, character, foreground, and light. Grade each separately and keep shadows off the character layer.</p></section><section><h2 id="section-5">Do this</h2><p>2D compositing separates background, character, foreground, and light; one flattened image means redrawing everything for one change.</p><ol><li>Use four layers: background, character, foreground, light effect.</li><li>Grade each layer separately and keep shadows off the character layer.</li><li>Composite position first, then light and shadow.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not draw everything on one layer; one change forces a full redraw.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> Background, character, foreground, and light are separate layers with clear structure.</li><li><strong>2.</strong> Shadows live on their own layer, not baked into the character.</li><li><strong>3.</strong> Changing an action moves only the character layer; background and light stay.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“Background, character, foreground, and light a…”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“Shadows live on their own layer, not baked int…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not draw everything on one layer; one change forces a full redraw.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Grade each layer separately and keep shadows off”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>Background, character, foreground, and light are separate layers with clear structure.</li><li>Shadows live on their own layer, not baked into the character.</li><li>Changing an action moves only the character layer; background and light stay.</li></ul>

<!-- SOURCES_START -->
## References and further reading

- [S63] [Toon Boom: Documentation](https://docs.toonboom.com/) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “2D compositing aligns line and color first” section against Toon Boom documentation, not an industry pipeline standard; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S62] [Blender: Official Manual](https://docs.blender.org/manual/en/latest/) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “2D compositing: fix edges, then color, then light” section against Blender manual, not an industry pipeline standard; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S59] [Adobe: After Effects Guide](https://helpx.adobe.com/after-effects/user-guide.html) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Limits” section against official After Effects guide, not a verdict on compositing aesthetics; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

