---
id: animation.motion-graphics.mg-typography.en
site: animation
type: article
lang: en
translation_key: animation.motion-graphics.mg-typography
translation_status: reviewed
title: 'Motion Typography: Read, Then Move'
summary: Type must read at rest before it moves; reading while moving cuts comprehension
  in half.
slug: mg-typography
aliases:
- mg-typography
canonical_site: animation
canonical_path: /en/article/mg-typography/
status: published
diagram: /images/diagrams/en/mg-typography.svg
diagram_alt: 'Structure diagram for Motion Typography: Read, Then Move.'
diagram_caption: Watch “Make a static version and check it at” and “Animate a six-frame
  entrance using only position and”; judge whether the speed split between foreground,
  midground and background reads in one move.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Animation Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.3d.rigging.en
- context.law.music-license.en
- formats.fashion.fashion-beauty-video-template.en
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

<p>The usual mistake is every letter flying, spinning and morphing while nobody finishes reading. Give the line enough hold time, then animate the entrance: under 0.3 seconds in, at least 1.5 seconds hold.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/mg-typography.svg" alt="Structure diagram for Motion Typography: Read, Then Move.">
  <figcaption>Watch “Make a static version and check it at” and “Animate a six-frame entrance using only position and”; judge whether the speed split between foreground, midground and background reads in one move.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Type animation is readable before beautiful</h2><p>One move per line: fade, rise or mask, not three at once.</p><h2 id="section-2">Limits</h2><p>Type is not decoration. Readability first: contrast, size, leading. Use display faces for titles, not long sentences.</p><h2 id="section-3">MG typography: grid first, animation second</h2>
<p>Type animation looks messy not because of the animation, but because there is no grid. Set baseline, tracking and safe area first, then move the type. Without a grid, more motion means more mess.</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>Define first</th><th>Value</th><th>Purpose</th></tr></thead><tbody>
<tr><td>Baseline grid</td><td>Divide frame height into 8–12 rows</td><td>Align multiple lines</td></tr>
<tr><td>Tracking</td><td>Chinese 0, English -2% to +2%</td><td>Avoid loose or cramped lines</td></tr>
<tr><td>Safe area</td><td>12% top and bottom on vertical</td><td>Platform UI does not cover text</td></tr>
<tr><td>Weights</td><td>Two maximum</td><td>Clear hierarchy</td></tr>
</tbody></table></div>
<h3>Project-level checks</h3>
<ol><li>Check the font license for commercial use. Display and body fonts are licensed separately; “downloadable” is not “usable.”</li><li>Use two or three motions only: position, mask, weight change. Do not fly every letter.</li><li>In mixed Chinese/English, set English at 80–90% of the Chinese size on the same baseline.</li><li>Review at phone size; minimum type is 24px at 1080 width.</li></ol>
<p>If the client asks for “all the type to move,” cut a five-second sample first. Too much motion eats the message.</p></section><section><h2 id="section-4">On set</h2><p>Make a still version that reads at phone width. Then animate six frames of entrance using position and opacity only; do not rotate, scale, and glow at once.</p></section><section><h2 id="section-5">Do this</h2><p>Motion typography must read at rest before it moves; reading while moving cuts speed in half.</p><ol><li>Make a static version and check it at phone width.</li><li>Animate a six-frame entrance using only position and opacity.</li><li>Do not add rotation, scale, and glow at once; protect the information.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not use white flashes and pushes as universal transitions; unreadable type wastes the motion.</p></section><aside class="regional-note"><p><strong>Regional note for US / UK / EU readers</strong></p><p>This English page keeps mainland-China examples where they are part of the method. Read platform names as examples, not as the only market: Douyin ↔ TikTok/Reels, Bilibili ↔ YouTube, Xiaohongshu ↔ Instagram/Pinterest; RMB figures are not converted here. Contracts, tax, insurance and consent rules differ by market; use the local currency and local counsel before signing or invoicing.</p></aside><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>the speed split between foreground, midground and background reads in one pan</li><li>a 0.5-second action still carries weight or anticipation</li><li>turn off any layer and the space still holds</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>more layers, same speed: the space stays flat</li><li>anticipation without follow-through: the weight is only half done</li><li>rendering before assets are locked: rework starts at the compositor</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Draw three keys at 24 fps, change only “Animate a six-frame entrance using only position and”, and export two seconds. If the weight still does not read, add anticipation before adding blur.</p></section>
<h2>Check</h2><ul><li>The static version reads at phone width and the longest line stays in frame.</li><li>The entrance moves only position and opacity, not rotation and scale together.</li><li>Muted playback still communicates the order of information.</li></ul>
<!-- SOURCES_START -->
