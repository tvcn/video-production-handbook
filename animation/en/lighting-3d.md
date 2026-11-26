---
id: animation.3d.lighting-3d.en
site: animation
type: article
lang: en
translation_key: animation.3d.lighting-3d
translation_status: reviewed
title: '3D Lighting: Three Points and HDRI'
summary: Use key, fill, and rim to build structure, then HDRI for environment. Reverse
  the order and space flattens.
slug: lighting-3d
aliases:
- lighting-3d
canonical_site: animation
canonical_path: /en/article/lighting-3d/
status: published
diagram: /images/diagrams/en/lighting-3d.svg
diagram_alt: 'Structure diagram for 3D Lighting: Three Points and HDRI.'
diagram_caption: Watch “Turn off HDRI and shape with the key” and “Add fill and rim.”;
  judge whether the speed split between foreground, midground and background reads
  in one move.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.2d.loop-cycle, animation.3d.materials, formats.documentary.documentary-template]
source_kind: sourced
sources:
- S62
- S59
---
<p>3D lighting is not filling a scene with light. Set one key direction so shadows explain space; use ambient and fill to control contrast. Even a realistic material looks like a texture map when the key is wrong.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/lighting-3d.svg" alt="Structure diagram for 3D Lighting: Three Points and HDRI.">
  <figcaption>Watch “Turn off HDRI and shape with the key” and “Add fill and rim.”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">3D lighting starts with key direction, then materials</h2><p>For every added light, name the real source it replaces; if none, delete it. Keep light layers separable for comparison.</p><h2 id="section-2">Limits</h2><p>HDRI is not universal. Interiors, night and hard directional light need manual lamps; an environment map alone goes flat and shadows scatter.</p><h2 id="section-3">3D lighting: key light first, atmosphere later</h2>
<p>The most common 3D lighting mistake is adding atmosphere before the key. Volumetrics, glow and depth of field erase direction. The order is key → fill → rim → environment → atmosphere.</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>Layer</th><th>Role</th><th>Check</th></tr></thead><tbody>
<tr><td>Key</td><td>Sets time and direction</td><td>Do shadows fall one way?</td></tr>
<tr><td>Fill</td><td>Controls contrast</td><td>Shadow detail without milkiness</td></tr>
<tr><td>Rim</td><td>Separates subject from background</td><td>Edges not blown</td></tr>
<tr><td>Environment</td><td>Reflection and sky</td><td>HDRI matches the set</td></tr>
</tbody></table></div>
<h3>Project-level checks</h3>
<ol><li>Turn off all atmosphere and judge the silhouette on key light alone. If the silhouette fails, atmosphere cannot save it.</li><li>Use one lighting rig across shots; record why a shot needs a special light.</li><li>Render reflection and refraction as a separate pass so post can adjust. Baking them into beauty locks them.</li><li>Check 10% gray and skin, not “brightness”; expose for the midtones.</li></ol>
<p>If render time runs short, cut atmosphere passes before key-light samples. Key noise ruins the whole shot.</p></section><section><h2 id="section-4">On set</h2><p>Turn off the HDRI and shape the form with the key only. Add fill and rim, then bring the HDRI back to 20 or 30 percent for environment.</p></section><section><h2 id="section-5">Do this</h2><p>3D lighting builds structure with key, fill, and rim before HDRI; reversing the order flattens space.</p><ol><li>Turn off HDRI and shape with the key only.</li><li>Add fill and rim.</li><li>Bring HDRI in at 20 to 30 percent to fill the environment.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not start with HDRI; environment light hides the form.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> With HDRI off, the key already defines form.</li><li><strong>2.</strong> Fill and rim do their jobs without flattening the key.</li><li><strong>3.</strong> HDRI stays at 20 to 30 percent and does not take over.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“With HDRI off, the key already defines form”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“Fill and rim do their jobs without flattening…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not start with HDRI; environment light hides the form.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Add fill and rim.”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>With HDRI off, the key already defines form.</li><li>Fill and rim do their jobs without flattening the key.</li><li>HDRI stays at 20 to 30 percent and does not take over.</li></ul>

<!-- SOURCES_START -->
## References and further reading

- [S62] [Blender Foundation: Blender Manual](https://docs.blender.org/manual/en/latest/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Use key, fill, and rim to build structure, then HDRI for env”) against Modelling, rigging, animation and rendering; not a substitute for an on-set test.
- [S59] [Adobe: After Effects User Guide](https://helpx.adobe.com/after-effects/user-guide.html) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Use key, fill, and rim to build structure, then HDRI for env”) against Compositing, keyframes, tracking and export; not a substitute for an on-set test.
<!-- SOURCES_END -->

