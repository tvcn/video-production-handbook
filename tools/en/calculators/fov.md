---
id: tools.calculators.fov.en
site: tools
type: calculator
lang: en
translation_key: tools.calculators.fov
translation_status: reviewed
translation_reviewed: 2026-11-21
title: 'Lens Field-of-View Calculator: Focal Length, Sensor, and Horizontal Angle'
summary: Enter sensor width and focal length to estimate horizontal field of view, and decide whether a lens is wide enough for a room, a landscape, or a close-up.
slug: fov
canonical_site: tools
canonical_path: /en/article/fov/
status: published
difficulty: beginner
stage: prep
format: all
tools:
- camera
- lens
authors:
- TVCN Tools Desk
reviewers:
- technical-reviewer
diagram: /images/diagrams/en/fov.svg
diagram_alt: 'Field of view: frame and focal length together'
diagram_caption: 'Same focal length: a smaller frame is a narrower view. Narrower is not a zoom.'
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related:
- main.paths.first-film
- tools.calculator.dof-calculator.en
- tools.guide.rent-camera.en
---

<!-- DIAGRAM_START -->
## Diagram

<figure>
  <img src="/images/diagrams/en/fov.svg" alt="Field of view: frame and focal length together">
  <figcaption>Same focal length: a smaller frame is a narrower view. Narrower is not a zoom.</figcaption>
</figure>
<!-- DIAGRAM_END -->

## What this calculator solves

“Is a 24mm wide enough indoors?” “Will an 85mm feel too tight for a person?” Do not guess. Estimate the horizontal angle first.

## Formula

\[
\theta = 2 \times \arctan\left(\frac{w}{2f}\right)
\]

Where \(w\) is sensor width, \(f\) is focal length, and \(\theta\) is the horizontal field of view.

## Common sensor widths

- Full frame: 36mm
- APS-C: 23.5mm
- M4/3: 17.3mm

## How to use it

1. Choose the sensor width.
2. Enter the focal length.
3. Read the horizontal angle.
4. If the angle is too narrow for the space, go wider; if faces distort, go longer.

## Three checks

- You can explain what wide and long lenses change, beyond “zoom.”
- You know the same focal length gives a different angle on different sensor sizes.
- You can use the angle to estimate camera distance.

## Boundary

This is horizontal field of view. It does not include distortion, focus breathing, or real-world lens marking error. Cinema lenses should be measured on set.

## Practice

Take a 24mm and a 50mm lens into the same room, from the same tripod position. Calculate each horizontal angle first, then compare the frames: how much wall does the 24mm hold, and how much larger is the person at 50mm? If you can explain why a wider angle is not the same as a bigger subject, you have used this page.
