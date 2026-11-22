---
id: post.color.primary-correction.en
site: post
type: article
lang: en
translation_key: post.color.primary-correction
translation_status: reviewed
title: "Primary Correction: Exposure and White Balance"
summary: "Primary correction fixes exposure and white balance first. Do not hide technical problems under a look."
slug: primary-correction
aliases: [primary-correction]
canonical_site: post
canonical_path: /en/color/primary-correction/
status: published
diagram: /images/diagrams/en/primary-correction.svg
diagram_alt: "Primary Correction: Exposure and White Balance three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: ["TVCN Post Desk"]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
depth: deep
deep_minutes: 6
sources: [S24, S27, S28, S30, S34, S35]
test_context: "Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci Resolve 20 and Premiere Pro 2025; results vary by machine."
known_failures: "Known failures: older-version timelines break; camera Logs need remapping; lost proxies require relinking."
verified: 2026-11-22
---

<p>Primary correction fixes exposure and white balance first. Do not hide technical problems under a look.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/primary-correction.svg" alt="Primary Correction: Exposure and White Balance three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Shoot a grey or color card first: set black to 0 to 5 and white below 100. Match every shot in the scene, then check the skin line.</p>
<h2>Do this</h2>
<p>Primary correction fixes exposure and white balance before style.</p><ol><li>Shoot a gray or color chart; set black to 0 to 5 and white below 100.</li><li>Match every shot in the scene for exposure and white balance, then check the skin line.</li><li>Add contrast and style only after the technical problems are gone.</li></ol>
<h2>Avoid</h2>
<p>Do not use a LUT to hide technical problems; it makes them look prettier.</p>
<h2>Check</h2>
<ul><li>Black and white levels match across the scene and cuts do not jump.</li><li>Skin sits on the same vector line with no green or red drift between shots.</li><li>Turn off the style LUT and the image still holds technically.</li></ul>

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
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S24]</span> ACES Color Management</li><li><span class="mono">[S27]</span> EBU R128 Loudness</li><li><span class="mono">[S28]</span> Netflix Partner Help</li><li><span class="mono">[S30]</span> DaVinci Resolve</li><li><span class="mono">[S34]</span> Adobe Premiere Pro Guide</li><li><span class="mono">[S35]</span> Avid Resource Center</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
