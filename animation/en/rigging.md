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
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.stop-motion.stop-motion.en
- context.literacy.platform-rules.en
- formats.food.food-video-breakdown.en
sources:
- S12
- S28
- S34
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
<section><h2 id="section-1">The joint turns, the weights do not tear</h2><p>Test extreme poses: arms overhead, deep squat, turn. Check armpits, knees and hips for tearing. Fix weights first, not with corrective shapes.</p><h2 id="section-2">Limits</h2><p>Complexity is not professionalism. A simple skeleton that survives the shots beats a feature-rich rig that breaks every time.</p></section><section><h2 id="section-3">On set</h2><p>Rotate shoulder, elbow, and knee for ten frames each. If the mesh collapses, fix weights before adding bones.</p></section><section><h2 id="section-4">Do this</h2><p>Rigging makes joints rotate correctly before skin deforms nicely; if it cannot turn, weights do not matter.</p><ol><li>Rotate shoulder, elbow, and knee, ten frames each.</li><li>If the mesh collapses, fix weights before adding bones.</li><li>Only animate after all three joints reach their limits.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not add bones to fix collapse; wrong weights get messier with more bones.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “If the mesh collapses, fix weights before adding”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>Shoulder, elbow, and knee reach their limits without mesh collapse.</li><li>Collapse was fixed with weights, not covered by extra bones.</li><li>Ten-frame rotation playback shows no tearing or pinching.</li></ul>
<!-- SOURCES_START -->
