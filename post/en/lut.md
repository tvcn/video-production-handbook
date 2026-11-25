---
id: post.color.lut.en
site: post
type: article
lang: en
translation_key: post.color.lut
translation_status: reviewed
title: 'LUT: A Starting Point, Not a Finish'
summary: A LUT is a start, not a finish. Return to primary correction and check blacks
  and highlights.
slug: lut
aliases:
- lut
canonical_site: post
canonical_path: /en/article/lut/
status: published
diagram: /images/diagrams/en/lut.svg
diagram_alt: 'Structure diagram for LUT: A Starting Point, Not a Finish.'
diagram_caption: Watch “Balance exposure and white balance before the LUT.” and “Check
  whether blacks lifted or highlights picked up”; judge whether removing one shot
  makes the scene faster rather than muddier.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.color.hdr.en
- post.color.scopes.en
- post.color.secondary-correction.en
source_kind: experience
---

<p>A LUT is a starting point, not a finish. After applying it, return to primary correction for blacks and highlights.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/lut.svg" alt="Structure diagram for LUT: A Starting Point, Not a Finish.">
  <figcaption>Watch “Balance exposure and white balance before the LUT.” and “Check whether blacks lifted or highlights picked up”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">On set</h2><p>Balance exposure and white balance before the LUT. After applying it, check for lifted blacks and stained highlights, then return to primary.</p></section><section><h2 id="section-2">Do this</h2><ol><li>Balance exposure and white balance before the LUT.</li><li>Check whether blacks lifted or highlights picked up a cast.</li><li>Fix in primary and then decide how much LUT strength to keep.</li></ol></section><section><h2 id="section-3">Avoid</h2><p>Do not use a LUT as a repair; it only tints the problem one color.</p></section><section><h2 id="section-4">Kinds of LUT</h2><p>Separate three kinds: technical LUT (Log→Rec.709, colour-space conversion), creative LUT (a look) and calibration LUT (monitor or printer). A technical LUT belongs at the front of colour management; a creative LUT comes after the primary grade. Do not stack all three in one node.</p><p>Confirm the LUT’s input colour space and cube size. Put a Rec.709 LUT on Log footage and black level and highlights will be wrong.</p></section><section><h2 id="section-5">Node order</h2><ol><li>Convert to the working colour space first; do not apply a creative LUT to camera-native Log.</li><li>Do the primary grade: exposure, white balance and black level. Bring the plate back to neutral.</li><li>Apply the LUT at controlled strength; then fix black level, highlights and skin with curves or wheels.</li><li>Finish with output transform and legalisation; check the waveform and scopes.</li></ol></section><section><h2 id="section-6">LUT misuse</h2><ol><li>Using a LUT to fix exposure: on a blown plate it only tints the highlight; detail does not return.</li><li>Running the LUT at 100%: blacks lift and skin turns orange. Drop to 50–70% and see if it still works.</li><li>Applying one LUT across lenses without matching: each lens has its own cast. Match first.</li><li>Treating a creative LUT as a technical transform: the colour space is wrong, so everything after is wrong.</li></ol></section><section><h2 id="section-7">Grade acceptance log</h2><ul><li>Before the LUT: exposure is correct and white balance neutral; black level neither lifts nor crushes on the waveform.</li><li>After the LUT: highlights are not visibly tinted and skin has not gone uniformly orange or green.</li><li>At 50% LUT strength the image still holds; that proves the base grade is right.</li><li>Log LUT name, input colour space, strength and node order; check once in Rec.709 before delivery.</li></ul></section><section><h2 id="section-8">Grade log</h2><p>Log LUT name, input colour space, strength, node position, output transform and viewing standard. Watch the whole timeline in Rec.709 before delivery, not a single frame.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>removing one shot makes the scene faster, not muddier</li><li>skin, highlights and blacks sit inside scope limits</li><li>loudness, subtitles and file specs pass one delivery check</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>cuts follow the music, not the action</li><li>style before unity: shots jump in color</li><li>loudness and subtitles are checked at the very end</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Balance exposure and white balance before the LUT.”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>The footage is correctly exposed and neutral before the LUT.</li><li>After the LUT, blacks are not lifted and highlights show no obvious cast.</li><li>Lower the LUT strength and the image still returns to a deliverable state.</li></ul>
