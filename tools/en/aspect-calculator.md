---
id: tools.calculator.aspect-calculator.en
site: tools
type: calculator
lang: en
translation_key: tools.calculator.aspect-calculator
translation_status: reviewed
title: 'Aspect Ratio Calculator: Crop and Safe Area'
summary: Calculate effective pixels after crop, then safe area; vertical is not a
  horizontal crop.
slug: aspect-calculator
aliases:
- aspect-calculator
canonical_site: tools
canonical_path: /en/article/aspect-calculator/
status: published
diagram: /images/diagrams/en/aspect-calculator.svg
diagram_alt: 'Structure diagram for Aspect Ratio Calculator: Crop and Safe Area.'
diagram_caption: Watch “4K 16:9 cropped to 9:16 leaves about 1215×2160.” and “Confirm
  the pixel count is enough.”; judge whether the spec maps to one concrete shooting
  problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.capability.audio-interface, tools.guide.audio-noise-fix, shoot.camera.composition]
source_kind: experience
---
<p>Aspect ratio = width ÷ height . Cropping 16:9 to 9:16 keeps width = original height × 9 ÷ 16; a 3840×2160 frame becomes 1215×2160, losing about 1312 pixels on each side.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/aspect-calculator.svg" alt="Structure diagram for Aspect Ratio Calculator: Crop and Safe Area.">
  <figcaption>Watch “4K 16:9 cropped to 9:16 leaves about 1215×2160.” and “Confirm the pixel count is enough.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Formula and safe area</h2><p>Aspect ratio = <strong>width ÷ height</strong>. Cropping 16:9 to 9:16 keeps width = original height × 9 ÷ 16; a 3840×2160 frame becomes 1215×2160, losing about 1312 pixels on each side.</p><h2 id="section-2">Three common conversions</h2><ul><li>16:9 → 1:1: keep 2160×2160, lose 840 pixels each side.</li><li>16:9 → 4:5: keep 1728×2160, lose 1056 each side.</li><li>When shooting 9:16, keep the subject inside the central 1080-wide safe area.</li></ul><h2 id="section-3">Limits</h2><p>A crop is not a recomposition; action and subtitles must stay inside the safe area. Platforms crop again, so check the platform preview before delivery.</p></section><section><h2 id="section-4">On set</h2><p>4K 16:9 cropped to 9:16 leaves about 1215×2160. Confirm the pixels are enough and redraw safe areas per platform.</p></section><section><h2 id="section-5">Do this</h2><p>An aspect-ratio calculator first computes effective pixels after crop, then the safe area; vertical is not just cropping the sides.</p><ol><li>4K 16:9 cropped to 9:16 leaves about 1215×2160.</li><li>Confirm the pixel count is enough.</li><li>Redraw the safe area for the platform.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not crop landscape into vertical blindly; effective pixels halve and close-ups soften.</p></section><section class="calc-widget" data-calculator="aspect-calculator">
<h2 id="section-7">Aspect-ratio crop calculator</h2>
<p class="calc-lede">Finds the largest crop at the target ratio and reports kept pixels and crop percentage.</p>
<div class="calc-grid"><label class="calc-field"><span>Source width (px)</span><input type="number" inputmode="decimal" data-calc="width" data-default="3840" value="3840" step="1" min="1"></label><label class="calc-field"><span>Source height (px)</span><input type="number" inputmode="decimal" data-calc="height" data-default="2160" value="2160" step="1" min="1"></label><label class="calc-field"><span>Target ratio</span><select data-calc="ratio" data-default="9:16"><option value="1:1">1:1 square</option><option value="4:5">4:5 vertical</option><option value="9:16" selected>9:16 full screen</option><option value="16:9">16:9 horizontal</option><option value="2.35:1">2.35:1 widescreen</option></select></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">Crop —</strong><span data-out="detail">Protect the subject first, then trim edges; do not center-crop blindly.</span></div>
<div class="calc-actions"><button type="button" data-reset>Reset defaults</button></div>
<p class="calc-formula">Compare source and target ratios: if wider, crop width; if taller, crop height. Keep the other axis.</p>
<noscript><p class="calc-noscript">With JavaScript off: 3840×2160 to 9:16 keeps 1215×2160.</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><p><strong>Boundary</strong></p><p>It does not replace an on-set reading. The number is a starting point; the monitor, scope or actual recording decides.</p></section><section><h2>Alternative</h2><p>If “4K 16:9 cropped to 9:16 leaves about 1215×2160.” is not the main problem, start with the basic move behind “Confirm the pixel count is enough.”. Upgrade only after both hold.</p></section><section><h2>60-second test</h2><p>Run a 60-second test with the gear you own, focused on “4K 16:9 cropped to 9:16 leaves about 1215×2160.”, and record one number. If the number does not change, do not add budget.</p></section>
<h2>Check</h2><ul><li>Cropped effective pixels are numeric, about 1215×2160.</li><li>Pixels meet delivery needs without upscaling.</li><li>The safe area is redrawn for vertical platforms, not reused from landscape.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note: this page draws on 3 gear trial and playback reviews under the listed model and firmware, once indoors and once outdoors; it discusses “Aspect Ratio Calculator: Crop and Safe Area”; no external laboratory test was run, and the conclusion may not transfer when conditions change.
<!-- SOURCES_END -->

