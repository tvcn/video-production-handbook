---
id: post.vfx.cg-integration.en
site: post
type: article
lang: en
translation_key: post.vfx.cg-integration
translation_status: reviewed
title: 'CG Integration: Match Light, Shadow, Atmosphere'
summary: CG integration matches light direction, shadow softness, and atmosphere before
  detail.
slug: cg-integration
aliases:
- cg-integration
canonical_site: post
canonical_path: /en/article/cg-integration/
status: published
diagram: /images/diagrams/en/cg-integration.svg
diagram_alt: 'Structure diagram for CG Integration: Match Light, Shadow, Atmosphere.'
diagram_caption: Watch “Match the key direction so CG and live” and “Match shadow
  softness and atmospheric haze to set”; judge whether removing one shot makes the
  scene faster rather than muddier.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.vfx.cleanup.en
- post.vfx.rotoscoping.en
- post.accessibility.sdh.en
source_kind: experience
---

<p>CG-live integration fails at light direction and lens distortion. Record the live key position, color temperature, focal length and aperture, then render CG with the same set. Color can be graded; light position cannot.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/cg-integration.svg" alt="Structure diagram for CG Integration: Match Light, Shadow, Atmosphere.">
  <figcaption>Watch “Match the key direction so CG and live” and “Match shadow softness and atmospheric haze to set”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Share light and lens before color</h2><p>Compare a gray ball and chart before comp; match CG reflection, shadow and grain to the plate.</p><h2 id="section-2">Limits</h2><p>CG cannot save a bad plate. Wrong motion blur or perspective makes effects look worse; shoot it right first.</p></section><section><h2 id="section-3">On set</h2><p>Match three things first: key direction, shadow softness, and atmospheric haze. Then grain and lens distortion; detail comes last.</p></section><section><h2 id="section-4">Do this</h2><p>CG integration matches light direction, shadow softness, and haze before detail.</p><ol><li>Match the key direction so CG and live plate receive the same light.</li><li>Match shadow softness and atmospheric haze to set depth.</li><li>Match grain and lens distortion last, then add detail.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not start with detail; if light and shadow are wrong, more detail looks faker.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>removing one shot makes the scene faster, not muddier</li><li>skin, highlights and blacks sit inside scope limits</li><li>loudness, subtitles and file specs pass one delivery check</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>cuts follow the music, not the action</li><li>style before unity: shots jump in color</li><li>loudness and subtitles are checked at the very end</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Match the key direction so CG and live”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>CG and plate share the key direction and shadows fall on the same side.</li><li>Shadow softness and haze match so the layers do not look pasted.</li><li>Grain and distortion align and the CG boundary disappears at delivery size.</li></ul>
