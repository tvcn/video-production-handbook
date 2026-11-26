---
id: post.color.primary-correction.en
site: post
type: article
lang: en
translation_key: post.color.primary-correction
translation_status: reviewed
title: 'Primary Correction: Exposure and White Balance'
summary: Primary correction fixes exposure and white balance first. Do not hide technical
  problems under a look.
slug: primary-correction
aliases:
- primary-correction
canonical_site: post
canonical_path: /en/article/primary-correction/
status: published
diagram: /images/diagrams/en/primary-correction.svg
diagram_alt: 'Structure diagram for Primary Correction: Exposure and White Balance.'
diagram_caption: Watch “Shoot a gray or color chart; set black” and “Match every shot
  in the scene for exposure”; judge whether removing one shot makes the scene faster
  rather than muddier.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.assets.project-structure, post.assets.proxy-cache, shoot.camera.composition]
depth: deep
deep_minutes: 6
sources:
- S24
- S27
- S28
- S30
- S34
test_context: 'Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci
  Resolve 20 and Premiere Pro 2025; results vary by machine.'
known_failures: 'Known failures: older-version timelines break; camera Logs need remapping;
  lost proxies require relinking.'
verified: 2026-11-22
source_kind: sourced
---
<p>Primary correction only unifies exposure, white balance and contrast: align black, white and skin on every shot before discussing a look. Use scopes, not guesswork in a dark room.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/primary-correction.svg" alt="Structure diagram for Primary Correction: Exposure and White Balance.">
  <figcaption>Watch “Shoot a gray or color chart; set black” and “Match every shot in the scene for exposure”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Bring every shot to the same start line</h2><p>Order: normalize exposure, normalize white balance, normalize contrast, then check shot-to-shot jumps. If one step is skipped, the secondary grade locks the cast in.</p><h2 id="section-2">Limits</h2><p>Primary is not “make every shot equally bright.” Different shot sizes and lighting may differ; unify the reference, not the emotion.</p></section><section><h2 id="section-3">On set</h2><p>Shoot a grey or color card first: set black to 0 to 5 and white below 100. Match every shot in the scene, then check the skin line.</p></section><section><h2 id="section-4">Do this</h2><p>Primary correction fixes exposure and white balance before style.</p><ol><li>Shoot a gray or color chart; set black to 0 to 5 and white below 100.</li><li>Match every shot in the scene for exposure and white balance, then check the skin line.</li><li>Add contrast and style only after the technical problems are gone.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not use a LUT to hide technical problems; it makes them look prettier.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>removing one shot makes the scene faster, not muddier</li><li>skin, highlights and blacks sit inside scope limits</li><li>loudness, subtitles and file specs pass one delivery check</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>cuts follow the music, not the action</li><li>style before unity: shots jump in color</li><li>loudness and subtitles are checked at the very end</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Shoot a gray or color chart; set black”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>Black and white levels match across the scene and cuts do not jump.</li><li>Skin sits on the same vector line with no green or red drift between shots.</li><li>Turn off the style LUT and the image still holds technically.</li></ul>

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 6 minutes.</strong> Primary correction does three things: match exposure, unify white balance, restore contrast. Do not build a look here.</p>
### Match first, grade later
<p>Choose the most accurate shot in the scene as reference and bring the others to it. Read the waveform, not your eye; the eye is fooled by neighboring shots.</p><p>Grade interior and exterior separately; do not pull the window to the same brightness as the room. The audience knows outside is brighter, and flattening it looks false.</p>
### White balance on neutral gray
<p>A white wall carries a cast; a gray card is truer. Without one, use white paper but do not overexpose it; clipped paper is no longer white.</p><p>Under mixed light there is no absolute correct. Choose one dominant source and let other colors remain. Pull everything to white and the room dies.</p>
### Do not crush the contrast
<p>Lifting blacks makes them milky; crushing them loses detail. Read the scope before deciding; black is not a grade contest.</p><p>Put the LUT after primary. Do not use a LUT to hide exposure errors; if primary is wrong, every later node patches the wrong image.</p>
### The order of shot matching
<p>Exposure first, white balance second, contrast third, skin last. Reverse the order and every adjustment undoes the one before.</p><p>After a scene, play three shots before moving on and confirm there is no jump.</p>
### Skin and memory colors
<p>Sky, grass, and skin are memory colors; the audience notices a small shift. Protect skin before sky.</p><p>Do not grade every face to the same brightness. Different people have different skin, and unifying it looks false.</p>
### Ten primary-correction checks
<ul><li>Choose one reference shot per scene</li><li>Match exposure first</li><li>Then white balance</li><li>Then skin tone</li><li>Then black level</li><li>Then highlights</li><li>Keep ambient color under mixed light</li><li>Place the LUT after primary</li><li>Check on the scopes</li><li>Play the whole scene back</li></ul><p>Primary correction is not about looking good; it is about making the seams between shots disappear.</p>
### When you have five minutes
<ul><li>Choose one reference per scene</li><li>Match exposure</li><li>Then white balance</li><li>Then skin</li><li>Check black and highlight</li><li>Place the LUT after primary</li></ul><p>Primary correction is the foundation for any look; if it is crooked, every later grade looks false. Make the faces in one scene look like the same person before you talk about style. The face must stay the same person across the scene, not two color temperatures.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S24] [ACES Color Management](https://www.oscars.org/science-technology/aces) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Primary correction fixes exposure and white balance first. D”) against Official ACES color pipeline documentation; not a substitute for an on-set test.
- [S27] [EBU R128 Loudness](https://tech.ebu.ch/publications/r128) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Primary correction fixes exposure and white balance first. D”) against Broadcast loudness targets, true peak and measurement; not a substitute for an on-set test.
- [S28] [Netflix Partner Help](https://partnerhelp.netflixstudios.com/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Primary correction fixes exposure and white balance first. D”) against Public entry for delivery specs, HDR/SDR and QC; not a substitute for an on-set test.
- [S30] [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Primary correction fixes exposure and white balance first. D”) against Official entry for editing, grading, Fusion and delivery; not a substitute for an on-set test.
- [S34] [Adobe Premiere Pro Guide](https://helpx.adobe.com/premiere-pro/user-guide.html) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Primary correction fixes exposure and white balance first. D”) against Official docs for editing, proxies, color and export; not a substitute for an on-set test.
<!-- SOURCES_END -->

