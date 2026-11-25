---
id: animation.stop-motion.armature.en
site: animation
type: article
lang: en
translation_key: animation.stop-motion.armature
translation_status: reviewed
title: 'Armature: It Must Stand Before It Acts'
summary: A stop-motion puppet must stand, walk, and repeat before acting. A soft armature
  collapses in ten frames.
slug: armature
aliases:
- armature
canonical_site: animation
canonical_path: /en/article/armature/
status: published
diagram: /images/diagrams/en/armature.svg
diagram_alt: 'Structure diagram for Armature: It Must Stand Before It Acts.'
diagram_caption: Watch “Stand the puppet for ten seconds without wobble.” and “Walk
  three steps without collapse.”; judge whether the speed split between foreground,
  midground and background reads in one move.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.stop-motion.stop-motion-set.en
- animation.stop-motion.stop-motion-motion-blur.en
- animation.3d.layout.en
source_kind: experience
---

<p>Test three moves: standing without wobble, raising an arm without sag, sitting without collapse. Use a metal armature with silicone pads and enlarge the feet; do not start with fingers before the center of gravity and knees are stable.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/armature.svg" alt="Structure diagram for Armature: It Must Stand Before It Acts.">
  <figcaption>Watch “Stand the puppet for ten seconds without wobble.” and “Walk three steps without collapse.”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">The armature must stand before it performs</h2><p>Before touching the puppet each frame, ask whether it will fall; shoot a test and check the pivot frame by frame.</p><h2 id="section-2">Limits</h2><p>Harder is not better. Too rigid looks robotic; leave softness where it bends and stiffness where it carries weight.</p><h2 id="section-3">Rigging: run extreme-pose tests before animation</h2>
<p>A rig is not done when bones are connected. Problems appear when an animator pulls: elbow collapse, knee inversion, shoulder intersections. Before handoff, run extreme-pose tests; do not start animation until they pass.</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>Test</th><th>Pose</th><th>Pass condition</th></tr></thead><tbody>
<tr><td>Shoulder</td><td>Arm raised 180°</td><td>No armpit collapse, no cloth intersection</td></tr>
<tr><td>Elbow</td><td>Bend 140°</td><td>Volume holds, no candy-wrapper twist</td></tr>
<tr><td>Knee</td><td>Deep squat + reverse</td><td>No inversion, feet do not slide</td></tr>
<tr><td>Spine</td><td>Twist + side bend</td><td>Chest and pelvis transition smoothly</td></tr>
</tbody></table></div>
<h3>Project-level checks</h3>
<ol><li>Standardize controller names: left/right, FK/IK, mirror rules on one page. Animators should not guess.</li><li>Lock axes that should not move and hide unused controls. A rig that can be bumped will be bumped.</li><li>Save a screenshot of every extreme pose as the rig acceptance record. “It works” is not evidence.</li><li>Weight joints before muscles; a full-body weight pass hides problems inside other problems.</li></ol>
<p>If the schedule is under three days, do not build film-level facial rigging. Use simplified facial controls and spend the time on performance and rendering.</p></section><section><h2 id="section-4">On set</h2><p>Make the puppet stand for ten seconds without wobble, then walk three steps without collapsing. Use a metal armature and weight the feet.</p></section><section><h2 id="section-5">Do this</h2><p>A stop-motion puppet must stand, walk, and repeat before performance; a soft armature collapses in ten frames.</p><ol><li>Stand the puppet for ten seconds without wobble.</li><li>Walk three steps without collapse.</li><li>Use a metal armature and add weight to the feet.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not let the armature stay soft; it collapses within ten frames.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Walk three steps without collapse.”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>The puppet stands ten seconds without wobble and the feet are weighted.</li><li>Three steps hold without collapse or sudden joint lock.</li><li>Ten frames of one pose show no positional drift.</li></ul>
