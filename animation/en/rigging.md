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
deep_minutes: 8
depth: deep
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

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 8 minutes.</strong> This section does not repeat the method above. It adds three things: two conditions, a counterexample and a reusable model, so you can decide when to change the method.</p>
### Condition A: simple character, few controls
<p>A simple character does not need a full facial rig; do four body points first: centre of gravity, feet, hands and head. The centre decides which way the body falls, feet decide contact, hands decide grip, head decides looking. With four points moving, the character can play most shots.</p><p>Fewer controls make animators more willing to use them. Give every control a clear name and colour, not the default; default names mean nothing at handoff. Even a simple rig gets a limit test: rotate every joint to maximum and check for intersections.</p>
### Condition B: complex character or face
<p>A complex character layers controls: body, fingers, face, cloth and props each on a layer; do not crowd every control into one panel. Animators need fast finding, not total visibility. Expose five to eight common controls per layer and hide the rest in a secondary panel.</p><p>Facial rigging starts with an expression range sheet: what this character can and cannot do; what it cannot do is solved by animation, texture or camera, not forced into the rig. A rig is not better when it has more; it is better when it is more predictable.</p>
### Counterexample: every control on one layer
<p>Every control sits on one panel: thirty fingers, sixty face, twenty body. The animator spends minutes finding one finger; after three days they use the face instead of the fingers, and the character forgets how to hold things.</p><p>The fix is not deleting controls; group them: common, secondary, debug; the common group holds eight. Grouping is not convenience; it puts attention on performance instead of button hunting.</p>
### Reusable model
<p><strong>Control map → limit test → naming → handoff.</strong> Draw the map, run the limit test, standardise names, write the handoff note. With all four, the rig is an asset, not one person's memory.</p><p>At handoff, have another animator do three actions without the note: grab, walk, look. If they cannot, the rig or naming has a problem. A rig is not for you; it is for the next person.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S62] [Blender: Official Manual](https://docs.blender.org/manual/en/latest/) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “The joint turns, the weights do not tear” section against Blender manual, not an industry pipeline standard; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S59] [Adobe: After Effects Guide](https://helpx.adobe.com/after-effects/user-guide.html) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Limits” section against official After Effects guide, not a verdict on compositing aesthetics; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

