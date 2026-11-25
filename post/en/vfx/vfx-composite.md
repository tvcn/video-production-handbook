---
id: post.vfx.vfx-composite.en
site: post
type: article
lang: en
translation_key: post.vfx.vfx-composite
translation_status: reviewed
translation_reviewed: 2026-11-21
title: "Compositing: Make Both Layers Believe the Same Light"
summary: A clean key is not a composite. Match direction, softness, color temperature, and contact shadow before touching the edge.
slug: vfx-composite
aliases: [vfx-composite, compositing, keying]
canonical_site: post
canonical_path: /en/article/vfx-composite/
status: published
difficulty: intermediate
stage: post
format: short-film
tools: []
authors: ["TVCN Post Desk"]
reviewers: [technical-reviewer]
cover: /images/post/vfx-composite.webp
diagram: /images/diagrams/en/vfx-composite.png
diagram_alt: "Match four things before the edge"
diagram_caption: "Wrong direction or softness makes a clean edge look pasted. Test ten seconds before the full shot."
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related: [post.vfx.cg-integration.en, post.color.color.en, post.editing.sound-bridge.en]
---

<!-- DIAGRAM_START -->
## Diagram

<figure>
  <img src="/images/diagrams/en/vfx-composite.png" alt="Match four things before the edge">
  <figcaption>Wrong direction or softness makes a clean edge look pasted. Test ten seconds before the full shot.</figcaption>
</figure>
<!-- DIAGRAM_END -->

Drop the foreground in and turn off edge checking for a minute. See where the key comes from, where the shadow falls, and whether the background is hard sun or overcast. If the direction is wrong, a perfect edge still looks like a sticker.

Then match softness and color temperature. Window light is soft; noon sun is hard; a warm room pushes skin toward orange. Put both layers in the same light before discussing the edge.

## Contact shadow saves more than the edge

If a person stands on a floor, the area under the feet needs to go darker. If a hand rests on a table, the table needs a small shadow. Without contact, the subject floats. Follow the key direction; do not paint a black ring around everything.

Reflective surfaces also need a little bounce: a table throws shirt color up to the chin, glass throws window light onto a cheek. It does not need much. Direction is enough.

## Grain, flare, and lens share the room

A clean foreground over a grainy background gives itself away. Add grain in the same direction, then a little highlight bloom and slight dispersion so the edge belongs to the same lens. A hard key edge is often not a mask problem; the light and grain do not match.

Do a ten-second test: one turn, one occlusion, one highlight pass. If ten seconds hold, comp the shot. Finding the problem after the full shot costs days.

## Checks

- You can name the key direction in both layers, and they agree.
- Feet and hands have contact shadows; the subject does not float.
- The ten-second test has no obvious sticker edge.
