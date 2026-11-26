---
id: animation.3d.rigging.en
site: animation
type: article
lang: en
translation_key: animation.3d.rigging
translation_status: reviewed
title: 'Rigging: Make the Joints Turn'
summary: Rigging makes joints turn correctly before skin looks good; if the joint
  fails, weights cannot save it.
slug: rigging
aliases:
- rigging
canonical_site: animation
canonical_path: /en/article/rigging/
status: published
diagram: /images/diagrams/en/rigging.svg
diagram_alt: 'Structure diagram for Rigging: Make the Joints Turn.'
diagram_caption: Watch “Rotate shoulder, elbow, and knee, ten frames each.” and “If
  the mesh collapses, fix weights before adding”; judge whether the speed split between
  foreground, midground and background reads in one move.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.2d.run-cycle, animation.stop-motion.stop-motion, formats.documentary.documentary-template]
sources:
- S62
- S59
test_context: 'Review setup: Windows 11; public Blender 4.x / After Effects 2025 workflows;
  not every version behaves the same.'
known_failures: 'Known failures: plugin/version gaps break rigs or renders; font and
  asset licenses need separate checks.'
verified: 2026-11-22
source_kind: sourced
---
<p>A rig must first do three things: elbows and knees bend one way, shoulders lift, head turns. Limit each joint and test weights before adding dozens of controls.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/rigging.svg" alt="Structure diagram for Rigging: Make the Joints Turn.">
  <figcaption>Watch “Rotate shoulder, elbow, and knee, ten frames each.” and “If the mesh collapses, fix weights before adding”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">The joint turns, the weights do not tear</h2><p>Test extreme poses: arms overhead, deep squat, turn. Check armpits, knees and hips for tearing. Fix weights first, not with corrective shapes.</p><h2 id="section-2">Limits</h2><p>Complexity is not professionalism. A simple skeleton that survives the shots beats a feature-rich rig that breaks every time.</p></section><section><h2 id="section-3">On set</h2><p>Rotate shoulder, elbow, and knee for ten frames each. If the mesh collapses, fix weights before adding bones.</p></section><section><h2 id="section-4">Do this</h2><p>Rigging makes joints rotate correctly before skin deforms nicely; if it cannot turn, weights do not matter.</p><ol><li>Rotate shoulder, elbow, and knee, ten frames each.</li><li>If the mesh collapses, fix weights before adding bones.</li><li>Only animate after all three joints reach their limits.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not add bones to fix collapse; wrong weights get messier with more bones.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> Shoulder, elbow, and knee reach their limits without mesh collapse.</li><li><strong>2.</strong> Collapse was fixed with weights, not covered by extra bones.</li><li><strong>3.</strong> Ten-frame rotation playback shows no tearing or pinching.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“Shoulder, elbow, and knee reach their limits w…”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“Collapse was fixed with weights, not covered b…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not add bones to fix collapse; wrong weights get messier with more bones.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “If the mesh collapses, fix weights before adding”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>Shoulder, elbow, and knee reach their limits without mesh collapse.</li><li>Collapse was fixed with weights, not covered by extra bones.</li><li>Ten-frame rotation playback shows no tearing or pinching.</li></ul>

<!-- SOURCES_START -->
## References and further reading

- [S62] [Blender: Official Manual](https://docs.blender.org/manual/en/latest/) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “The joint turns, the weights do not tear” section against Blender manual, not an industry pipeline standard; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S59] [Adobe: After Effects Guide](https://helpx.adobe.com/after-effects/user-guide.html) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Limits” section against official After Effects guide, not a verdict on compositing aesthetics; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

