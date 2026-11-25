---
id: post.vfx.tracking.en
site: post
type: article
lang: en
translation_key: post.vfx.tracking
translation_status: reviewed
title: 'Tracking: Put the Point on Something Real'
summary: Put tracking points on real, textured, unoccluded surfaces; a flat wall will
  drift.
slug: tracking
aliases:
- tracking
canonical_site: post
canonical_path: /en/article/tracking/
status: published
diagram: /images/diagrams/en/tracking.svg
diagram_alt: 'Structure diagram for Tracking: Put the Point on Something Real.'
diagram_caption: 'Watch “Place three points: a textured corner, a high-contrast” and
  “Switch to manual keys when a point is”; judge whether removing one shot makes the
  scene faster rather than muddier.'
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.vfx.rotoscoping.en
- post.vfx.keying.en
- post.vfx.cleanup.en
source_kind: experience
---

<p>Tracking points belong on real, textured, unobstructed surfaces; a flat wall will drift.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/tracking.svg" alt="Structure diagram for Tracking: Put the Point on Something Real.">
  <figcaption>Watch “Place three points: a textured corner, a high-contrast” and “Switch to manual keys when a point is”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">On set</h2><p>Place three tracking points: a textured corner, a high-contrast mark, and a backup. If one gets blocked, switch to manual keyframes.</p></section><section><h2 id="section-2">Do this</h2><ol><li>Place three points: a textured corner, a high-contrast mark, and a backup.</li><li>Switch to manual keys when a point is occluded.</li><li>Play the whole shot and check for drift or sliding.</li></ol></section><section><h2 id="section-3">Avoid</h2><p>Do not put points on a flat wall or mirror; the tracker has nothing to grab.</p></section><section><h2 id="section-4">How to choose points</h2><p>Choose textured, high-contrast, non-repeating features: a wall corner, label, screw or floor pattern. Do not put points on a flat wall, a mirror, a fast-moving hand or an ear that hair will cover.</p><p>Use at least three points for planar tracking and six at different depths for 3D. More is not better; a point that survives occlusion is.</p></section><section><h2 id="section-5">Solve order</h2><ol><li>Set origin and scale before solving. Do not change lens distortion while solving.</li><li>Solve translation/rotation/scale first, then perspective. If the error is large, go back to manual keys.</li><li>Check reprojection: stick a test grid to the plate; the edge must not slide.</li></ol><p>For motion-blurred shots, compensate or key manually first. Do not make the tracker guess.</p></section><section><h2 id="section-6">Tracking failures</h2><ol><li>Flat wall: no texture, so the tracker drifts. Add temporary marks or key manually.</li><li>Reflective or transparent surface: the point moves and the solve scales. Move to nearby real texture.</li><li>Rolling shutter: fast pans warp the plate. Undistort first or change the lens.</li><li>Occlusion: points disappear and do not recover. Place backup points and switch to manual keys.</li></ol></section><section><h2 id="section-7">Solve acceptance log</h2><ul><li>Reprojection error at delivery size is 1–2px or less; no slide at 200%.</li><li>Play the full shot: no scale drift, foot slide or sudden point jump.</li><li>Occlusion sections have manual keys and no hard transition.</li><li>Log tracking software, version, lens, focal length, solve error and manual key count.</li></ul></section><section><h2 id="section-8">Solve log</h2><p>Log lens, focal length, tracking software version, solve error, manual key count and occlusion sections. When the error grows, check these fields before re-solving the whole shot.</p></section><section><h2 id="section-9">Check before re-solving</h2><p>Check lens-distortion calibration and focal length first, then whether points were occluded. Do not re-solve the whole shot immediately. Save the previous solve so you can roll back.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>removing one shot makes the scene faster, not muddier</li><li>skin, highlights and blacks sit inside scope limits</li><li>loudness, subtitles and file specs pass one delivery check</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>cuts follow the music, not the action</li><li>style before unity: shots jump in color</li><li>loudness and subtitles are checked at the very end</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Place three points: a textured corner, a high-contrast”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>At least two of three points stay visible and textured through the shot.</li><li>When occlusion happens, manual keys take over with no hard jump.</li><li>On full playback the tracked surface shows no slide or scale drift.</li></ul>
