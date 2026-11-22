---
id: animation.stop-motion.stop-motion.en
site: animation
type: article
lang: en
translation_key: animation.stop-motion.stop-motion
translation_status: reviewed
translation_reviewed: 2026-11-21
title: "Stop Motion: One Frame at a Time"
summary: "Stop motion is a test of stability: lock the camera, lock the light, move the puppet a little each frame. Two seconds in a day is normal. You are not slow."
slug: stop-motion
aliases: [stop-motion]
canonical_site: animation
canonical_path: /en/stop-motion/stop-motion/
status: published
difficulty: beginner
stage: animate
format: short-film
tools: []
authors: ["TVCN Animation Desk"]
reviewers: [technical-reviewer]
cover: /images/animation/stop-motion.webp
diagram: /images/diagrams/en/stop-motion.png
diagram_alt: "Stop motion: lock camera, light, and hand"
diagram_caption: "The hard part is not movement but stability. Lock the camera and light, change one thing per frame. Two seconds a day is normal."
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related: []
depth: deep
deep_minutes: 7
sources: [S12, S28, S34]
test_context: "Review setup: Windows 11; public Blender 4.x / After Effects 2025 workflows; not every version behaves the same."
known_failures: "Known failures: plugin/version gaps break rigs or renders; font and asset licenses need separate checks."
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
## Diagram

<figure>
  <img src="/images/diagrams/en/stop-motion.png" alt="Stop motion: lock camera, light, and hand">
  <figcaption>The hard part is not movement but stability. Lock the camera and light, change one thing per frame. Two seconds a day is normal.</figcaption>
</figure>
<!-- DIAGRAM_END -->

The barrier in stop motion is not gear; it is stability. Lock the camera, lock the light, move the puppet a little each frame.

## Lock the camera

Tripod, remote shutter, manual exposure, manual white balance. Any automatic mode will flicker across hundreds of frames. If the camera moves a millimeter, the action jumps.

Tape down the tripod position and focal length. Do not touch the camera until the shot is finished.

## Shoot it twice

Twelve fps is a common stop-motion rate; fast action can use twenty-four. Shoot a test pass to confirm direction and distance, then shoot the real pass.

Use onion skin for the previous frame, but do not rely on it alone. Watch the whole sequence every few frames, or you will get “every frame right, the whole wrong.”

## Light and motion

Use continuous, flicker-free light. Avoid cheap LEDs with PWM flicker; test with a phone video before shooting. Move the puppet a little each frame: two millimeters for a step, three degrees for a turn. More frames are cheaper than a jump.

## Three checks

- Camera, exposure, and white balance are manual and locked.
- There is a twelve-fps test pass.
- The puppet moves only a small amount each frame.

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 7 minutes.</strong> Stop motion is not shooting frame by frame. It is calculating how much each frame moves, then keeping light and rig still.</p>
### Count frames first
<p>At twelve frames per second, one second needs twelve moves; a three-second action is thirty-six. Count total frames before shooting, or discover the shortage halfway.</p><p>Measure movement in millimeters per frame. Too much jumps; too little sticks. Mark the rig rail with a ruler, not a feeling.</p>
### Lock light and rig
<p>Sandbag and tape every lamp; mark a position line. If someone bumps a light mid-shot, the whole section flickers. Use a cable release or software, not a finger.</p><p>Leave frame before touching the puppet; if a hand must enter, use a stand-in or a long tool. Change one joint, shoot one frame. Do not change three at once.</p>
### Set and post
<p>Build a set that survives repeated touching: walls fixed, floor flat, props weighted. Use cloth that does not spring back and hair material that holds shape.</p><p>In post, fix flicker first, then add motion blur. Do not hide on-set light flicker with a plugin. Sound can be built later, but footsteps and contacts must land on the frame.</p>
### Five-minute drill: twelve frames, one action
<p>Move an object ten centimeters in twelve frames. Mark the ruler each frame and play it as one second. Does it slide, jump, or move at constant speed?</p><p>Shoot a second version: less movement in the first two frames, more in the last two. Compare weight. Keep the ruler chart for next time.</p>
### When stop motion is done
<p>No light flicker, no rig shake, no foot slide, no hand in frame; every contact has a sound on frame; total frames are within two of the plan. All five pass.</p><p>If it flickers, check the lamp and shutter before post stabilization. If it sticks, check movement per frame before motion blur.</p>
### Ten stop-motion checks
<ul><li>Total frames counted first</li><li>Twelve fps, measured on a ruler</li><li>Movement in millimeters per frame</li><li>Lamps sandbagged and taped</li><li>Cable release or software</li><li>Hands out of frame before touching</li><li>One joint changed at a time</li><li>Walls and floor fixed</li><li>Flicker fixed before motion blur</li><li>Footsteps and contacts on frame</li></ul><p>Stop-motion realism is not puppet detail. It is the same movement per frame and the same light position every frame.</p>
<!-- DEEP_DIVE_END -->
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S12]</span> Britannica: Animation</li><li><span class="mono">[S28]</span> Netflix Partner Help</li><li><span class="mono">[S34]</span> Adobe Premiere Pro Guide</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
