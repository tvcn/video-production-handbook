---
id: animation.3d.3d-pipeline.en
site: animation
type: article
lang: en
translation_key: animation.3d.3d-pipeline
translation_status: reviewed
translation_reviewed: 2026-11-21
title: "The 3D Pipeline: Blockout to Render"
summary: "3D does not start with animation after modeling. Blockout sets timing, then layout, animation, lighting, and render, each step reversible."
slug: 3d-pipeline
aliases: [3d pipeline, 3D animation, blockout]
canonical_site: animation
canonical_path: /en/article/3d-pipeline/
status: published
difficulty: advanced
stage: animation
format: 3d
tools: [lookdev, t2v, vfx]
authors: ["TVCN Animation Desk"]
reviewers: [technical-reviewer]
cover: /images/animation/3d-pipeline.webp
diagram: /images/diagrams/en/3d-pipeline.png
diagram_alt: "The 3D pipeline: six gates, rising cost"
diagram_caption: "Moving a character in blockout costs almost nothing. Changing it after render burns the whole crew’s time."
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related: [animation.principles.animation-principles.en, context.law.invoice-tax-cross-border.en, formats.fashion.fashion-beauty-video-breakdown.en]
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
  <img src="/images/diagrams/en/3d-pipeline.png" alt="The 3D pipeline: six gates, rising cost">
  <figcaption>Moving a character in blockout costs almost nothing. Changing it after render burns the whole crew’s time.</figcaption>
</figure>
<!-- DIAGRAM_END -->

## Blockout sets timing

Use simple cubes and spheres to lay out timing and camera. No modeling or texturing yet; only answer when things happen and where the camera is.

Do not move on until blockout works. If the rhythm is wrong here, detail makes it harder to fix later.

## Layout locks the camera before animation

Layout sets framing, focal length, and camera path. If the camera is not locked, animators perform inside the wrong frame and everything gets redone.

Make a playblast with no detail and confirm the cut points. Once shot length is fixed, allocate animation time.

## Lighting and render are separate checks

Lighting checks separation: subject, background, environment. Render checks output: noise, samples, passes, and compositing.

Do not treat “fix it in render” as a workflow. Preview lighting at low samples to confirm mood; only then raise samples.

## Three checks

- Blockout timing and cut points are approved.
- Cameras are locked before animation starts.
- Lighting preview and final render are reviewed separately.

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 7 minutes.</strong> The 3D pipeline is not a software menu. It is a chain where every step can go back one step; skip blockout and you rebuild structure forever.</p>
### Blockout before modeling
<p>Block with boxes and cylinders for proportion, camera, and blocking. Confirm what the shot can see before modeling detail. If the blockout fails, more detail is more waste.</p><p>Put the camera in the scene first and check composition at the real focal length. Do not model first and look for a camera later; by then it cannot change.</p>
### Rig and animation handoff
<p>Set joint count and naming before rigging. Animators need a rig that bends, turns, and carries weight, not a pile of controls. Record a test action at handoff.</p><p>Animate on the low model first to confirm timing and center of gravity, then move to high. Animating heavy geometry slows both the viewport and your judgment.</p>
### Lighting, render, and rollback
<p>Light the gray model first to confirm the key direction. Do not load full materials at the start; read the value structure first. Render low resolution and low samples to confirm motion and composition.</p><p>Save a version at every stage with date and content in the name. Rolling back is part of the pipeline, not a failure. Without versions, rollback means redo.</p>
### Five-minute drill: one shot through the pipeline
<p>Take a simple scene through blockout, low model, rig test, low-model animation, gray lighting, low-res render. Ten minutes per step; no detail chasing.</p><p>Save a version each step, then roll back to the blockout and check the camera. If it moved, you changed structure later without admitting it.</p>
### When a 3D shot is done
<p>From blockout to final render: the camera did not secretly move, proportions held, the rig did not break, light direction matches, and the low-res test and final share composition. All five pass.</p><p>If the final composition differs from the blockout, roll back and check. Do not hide it with a post crop. The expensive 3D problems are decisions changed late.</p>
### Ten 3D pipeline checks
<ul><li>Blockout before modeling</li><li>Boxes and cylinders in blockout</li><li>Camera placed first</li><li>Composition at real focal length</li><li>Joints and naming before rig</li><li>Test action recorded at handoff</li><li>Animation on low model</li><li>Gray-model lighting first</li><li>Low-res, low-sample test render</li><li>Version saved at every stage</li></ul><p>The way to save time in 3D is not skipping a step. It is making every step able to go back one.</p>
<!-- DEEP_DIVE_END -->
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S12]</span> Britannica: Animation</li><li><span class="mono">[S28]</span> Netflix Partner Help</li><li><span class="mono">[S34]</span> Adobe Premiere Pro Guide</li></ul>
<p><a href="../../about/">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
