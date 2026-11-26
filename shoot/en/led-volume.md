---
id: shoot.virtual-production.led-volume.en
site: shoot
type: article
lang: en
translation_key: shoot.virtual-production.led-volume
translation_status: reviewed
title: 'LED Volume: Track First, Light Second'
summary: In LED volume work, lock tracking before lighting. If tracking drifts, no
  background will stick.
slug: led-volume
aliases:
- led-volume
canonical_site: shoot
canonical_path: /en/article/led-volume/
status: published
diagram: /images/diagrams/en/led-volume.svg
diagram_alt: 'Structure diagram for LED Volume: Track First, Light Second.'
diagram_caption: Watch “Shoot a pan and a push-in to check” and “Match the on-set
  light direction to the background”; judge whether highlights, skin and sound survive
  together.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Shoot Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [shoot.camera.lens-distance, shoot.lighting.lighting-style, post.color.color]
source_kind: sourced
sources:
- S31
- S52
- S52
---
<p>LED volume work starts with tracking, then light. If tracking drifts, a beautiful background will not stick.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/led-volume.svg" alt="Structure diagram for LED Volume: Track First, Light Second.">
  <figcaption>Watch “Shoot a pan and a push-in to check” and “Match the on-set light direction to the background”; judge whether highlights, skin and sound survive together.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">On set</h2><p>Shoot a pan and a push-in first and check background tracking. Match set light to the background direction, then grade.</p></section><section><h2 id="section-2">Do this</h2><ol><li>Shoot a pan and a push-in to check background tracking and latency.</li><li>Match the on-set light direction to the background source before brightness.</li><li>Grade last and confirm no scan lines, drift, or color shift in the background.</li></ol></section><section><h2 id="section-3">Avoid</h2><p>Do not build the pretty background first; if tracking drifts, all of it is wasted.</p></section><section><h2 id="section-4">Boot order and tracking</h2><p>Match the LED wall refresh to the camera shutter before judging the image. At 24p/25p, 1/50 or 1/60 is common. If scan lines appear, change shutter or wall refresh first, not the grade.</p><ol><li>Run a pan, a push-in and a half-circle around the subject with a tracking chart; watch the background edge for lag.</li><li>Put tracking latency, genlock and lens-distortion calibration on the boot checklist. Recalibrate after a lens change.</li><li>Shoot a test with no subject, only wall and floor, to confirm perspective and horizon.</li></ol></section><section><h2 id="section-5">Wall light and colour temperature</h2><p>The wall is background, not key light. Keep the key on the front side; run the wall 1–2 stops below the key so green/blue bounce does not tint the face.</p><p>Put wall and practicals on the same side of 5600K or 3200K; do not mix warm and cool. Keep the actor at least 1.5m from the wall to reduce spill and moiré.</p></section><section><h2 id="section-6">Virtual-production failures</h2><ol><li>Tracking drift: the background looks like a sticker and slips when the actor moves. Recalibrate; do not fix it with post tracking.</li><li>Scan lines or moiré: shutter and refresh disagree. Change shutter or shooting distance.</li><li>Wall bounce: the face turns green. Lower wall brightness; add negative fill or a black flag.</li><li>Wrong perspective: horizon and floor do not meet. Adjust camera height and lens; do not stretch the background.</li></ol></section><section><h2 id="section-7">Tracking acceptance log</h2><ul><li>Ten-second pan and push-in: no lag, drift or frame jump at the background edge.</li><li>Actor at 1.5m from the wall: no visible green/blue spill on the face.</li><li>No scan lines or moiré at delivery size; artefacts visible only at 100% are not a failure.</li><li>Log refresh rate, shutter, lens, tracking software version and calibration date.</li></ul></section><section><h2 id="section-8">Boot log</h2><p>Log wall refresh, shutter, genlock state, tracking software version, lens-distortion calibration date and actor distance. If any one changes, retest tracking and colour; do not reuse the previous setup.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> The background does not lag or drift during the pan and push-in.</li><li><strong>2.</strong> Light direction on the subject matches the source inside the background.</li><li><strong>3.</strong> At delivery size there are no scan lines, moire, or obvious color shift.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“The background does not lag or drift during th…”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“Light direction on the subject matches the sou…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not build the pretty background first; if tracking drifts, all of it is wasted.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Shoot three 10-second takes by the same window, changing only “Shoot a pan and a push-in to check”. Compare highlights, skin and background; keep the one that is editable.</p></section>
<h2>Check</h2><ul><li>The background does not lag or drift during the pan and push-in.</li><li>Light direction on the subject matches the source inside the background.</li><li>At delivery size there are no scan lines, moire, or obvious color shift.</li></ul>

<section><h2>Boundary</h2><p>This page only covers “LED Volume: Track First, Light Second”; it does not replace Focal Length: Decide How Close the Audience Stands, Lighting Style: Soft, Hard, Natural, Color: Match First, Style Second. When the problem belongs to one of those pages, use that page instead of adding more parameters here.</p></section>
<!-- SOURCES_START -->
## References and further reading

- [S31] [ARRI: Cine Systems](https://www.arri.com/en/cine-systems) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Wall light and colour temperature” section against ARRI camera, lens and lighting documentation, not a general shooting tutorial; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S52] [ARRI: ALEXA 35](https://www.arri.com/en/camera-systems/cameras/legacy-camera-systems/alexa-35) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “On set” section against ALEXA 35 official specs, not independent testing; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

