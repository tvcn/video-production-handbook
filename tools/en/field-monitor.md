---
id: tools.capability.field-monitor.en
site: tools
type: tool
lang: en
translation_key: tools.capability.field-monitor
translation_status: reviewed
title: 'Field Monitor: Brightness, Scopes, LUT'
summary: A field monitor needs brightness, scopes, and LUT support; a pretty screen
  does not mean correct footage.
slug: field-monitor
aliases:
- field-monitor
canonical_site: tools
canonical_path: /en/article/field-monitor/
status: published
diagram: /images/diagrams/en/field-monitor.svg
diagram_alt: 'Structure diagram for Field Monitor: Brightness, Scopes, LUT.'
diagram_caption: Watch “Set 800 nits outdoors and load the LUT.” and “Shoot a gray
  card.”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.capability.field-recorder, tools.workflow.first-shoot-day, shoot.camera.composition]
source_kind: experience
---
<p>If the delivery only needs the camera screen, do not add a monitor for “professional look.” It adds weight, cables and another power failure point.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/field-monitor.svg" alt="Structure diagram for Field Monitor: Brightness, Scopes, LUT.">
  <figcaption>Watch “Set 800 nits outdoors and load the LUT.” and “Shoot a gray card.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">What to compare first</h2><ul><li><strong>Brightness:</strong> ask whether it is readable outdoors before resolution; 500–1000 nits is the divide, and a hood is still needed.</li><li><strong>LUT and scopes:</strong> can it load a monitoring LUT and show waveform, zebra or false color? Do not judge by “pretty color” alone.</li><li><strong>Latency and power:</strong> check HDMI/SDI delay, battery type and hot-swap support; losing monitoring is more common than losing recording.</li></ul><h2 id="section-2">When not to use it</h2><h2 id="section-3">On-set monitor: brightness, waveform, LUT — three checks</h2>
<p>A monitor is not “brighter is better.” Set it to standard brightness first, then judge waveform and LUT. Otherwise you are grading the monitor, not the image.</p>
<ol><li>Brightness: use a built-in grayscale or hood; set it so 5% and 10% black are distinct. “Looks comfortable” is not a setting.</li><li>Waveform: use it for midtones. When monitor and waveform disagree, trust the waveform.</li><li>LUT: use the on-set LUT for style, not exposure. Judge exposure on the log waveform.</li></ol>
<p>Acceptance: play the same clip on the monitor and the computer; brightness and skin should not differ a stop. If they do, calibrate the monitor.</p></section><section><h2 id="section-4">On set</h2><p>Set the monitor to 800 nits outdoors and load the LUT. Shoot a grey card and compare the waveform and skin with the monitor.</p></section><section><h2 id="section-5">Do this</h2><p>A field monitor is judged by brightness, waveform, and LUT; a pretty screen does not mean correct footage.</p><ol><li>Set 800 nits outdoors and load the LUT.</li><li>Shoot a gray card.</li><li>Check waveform and skin against the monitor.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not trust a pretty monitor image; without waveform, brightness and color can lie.</p></section>
<h2>Check</h2><ul><li>Outdoor brightness reaches 800 nits and stays readable.</li><li>The LUT is loaded and the gray card has a waveform reading.</li><li>Skin judgment matches waveform, not eye alone.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note: this page draws on 6 gear trial and playback reviews under the listed model and firmware, once indoors and once outdoors; it discusses “Field Monitor: Brightness, Scopes, LUT”; no external laboratory test was run, and the conclusion may not transfer when conditions change.
<!-- SOURCES_END -->

